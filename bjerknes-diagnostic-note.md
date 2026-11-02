# ENSO Structure Diagnostics: Node, Gradient, and Downstream Risk
## Bjerknes Diagnostic Lab — portfolio note

**Purpose.** This note summarises an idealized computational diagnostic of El Niño–Southern Oscillation (ENSO) regime structure. It isolates spatial and temporal features that standard single-index descriptions tend to collapse, shows how those features control teleconnection strength, and illustrates how a classification error would propagate through an idealized catastrophe-risk chain. The work is fully reproducible; the notebooks, physics modules, tests, and figures live in the linked laboratory.

The central claim is simple and, for risk work, consequential: the relevant property of an ENSO state is the spatial structure of the sea-surface temperature (SST) anomaly relative to the Pacific’s maintained cold baseline, not the magnitude of the anomaly alone. Structure beats magnitude.

### 1. Why this matters for catastrophe risk

Operational ENSO monitoring and many catastrophe-model climate drivers reduce the equatorial Pacific to a single number—most commonly the Niño-3.4 / Oceanic Niño Index SST anomaly, with the Southern Oscillation Index as a secondary pressure-based measure. That reduction is useful for classification and communication. It is less useful when the downstream hazard depends on where the pressure see-saw is pivoting and how steep the meridional SST gradient is.

Bjerknes (1969) described the equatorial Pacific pressure see-saw and its teleconnections. The laboratory returns to that description with a deliberately narrow diagnostic question: can we separate two quantities that a single index conflates?

- the **zero isallobar** (the temporal node at which pressure has stopped changing), and  
- the **gradient maximum** (the spatial peak of the east–west pressure gradient).

Their coincidence is not guaranteed. When a basin-wide offset is present, the node can disappear entirely or be displaced. The same offset also removes or weakens the meridional SST gradient that drives the Hadley overturning and the subtropical jet. In both cases the diagnosed regime changes, and with it the expected pattern of mid-latitude and tropical impacts.

For a catastrophe modeller or risk consultant the practical implication is straightforward. An index that registers “strong El Niño” can still correspond to structurally different states. One of those states (a pure see-saw with a sharp gradient) produces a vigorous teleconnection; another (a warm, nearly uniform basin) produces almost none. Treating them as interchangeable introduces a structural error whose downstream effect on hazard and loss can be large even when the headline SST anomaly looks similar. The laboratory makes that distinction explicit and traceable.

### 2. The two-axis diagnostic

The study examines one A/B/C/D regime taxonomy along two perpendicular axes.

**Zonal (Walker) axis.**  
Notebook 01 diagnoses Bjerknes’s equatorial see-saw along longitude. It asks whether the coincidence of the zero isallobar and the gradient maximum—observed by Bjerknes in the cold Januaries of the 1960s—is structural or regime-dependent. Four regimes are classified by a basin-wide-offset parameter:

- **A** — pure see-saw: node lies on the gradient maximum;  
- **B** — basin-wide offset erases the node entirely;  
- **C** — node displaced east;  
- **D** — node displaced west.

The model also reproduces the vertical closure of the Walker cell: the zonal pressure gradient reverses sign with height, “scissoring” the isobaric surfaces (the feature illustrated in Bjerknes’s own Figure 8).

**Meridional (Hadley-to-jet) axis.**  
Notebook 02 examines the downstream teleconnection along latitude. For each regime it constructs the same three-panel anatomy—equator-to-pole SST forcing, pressure anomaly plus Hadley overturning, upper-tropospheric jet—so the four cases can be read as variations on one structure. The central result is that teleconnection strength tracks the meridional SST gradient, not SST magnitude. The warmest of the four states produces the weakest jet.

**Shared taxonomy and the keystone.**  
The correspondence between the two axes is exact for regimes A and B. Regime B is the shared keystone: on the zonal axis the basin-wide offset erases the node; on the meridional axis the same uniform-warm state removes the gradient that drives the jet. Structure disappears on both axes simultaneously. Regimes C and D carry the “node displaced east/west” label across both notebooks; on the meridional axis they are realized as cold La Niña states because a warm-versus-cold contrast is required to trace the teleconnection. The two notebooks are therefore perpendicular views of one taxonomy, not identical scenarios.

The geographic foundation is the Pacific’s extensive equatorial cold tongue, actively maintained by upwelling, westward cold-water advection, and air–sea coupling. Anomalies sit relative to that baseline and thereby acquire spatial structure. Without the baseline, a warm basin can be nearly uniform (Scenario B). The diagnostics assume the cold-water structure exists and show what happens when anomalies are placed on top of it.

### 3. Error-propagation illustration

Part 1 includes an idealized catastrophe-risk chain that traces the consequence of a node-classification error. The figures are order-of-magnitude illustrations of how an error propagates and compounds; they are not derived loss estimates and are not calibrated to any portfolio or event set.

The exercise is nevertheless useful as a sensitivity demonstration. Once the diagnostic has mis-placed or erased the node, the regime label changes. That change alters the prescribed teleconnection pattern, which in turn alters the downstream hazard fields fed into the simplified risk chain. The point is not to produce a number that could be inserted into a pricing model; it is to make the propagation path visible and to show that the size of the final difference is not a small perturbation around a single “ENSO on” state.

### 4. Scope and limitations

Both notebooks are idealized diagnostics, not general circulation models or calibrated forecast systems. The fields are prescribed analytic forms chosen for pedagogical clarity; they are not solutions of the primitive equations. Magnitudes (for example pressure anomalies) are illustrative.

The work therefore claims mechanistic transparency and a legible account of one causal chain. It does not claim predictive skill, quantitative loss ratios, or operational index replacement. Part 3 of the laboratory—data processing for a Southeast Asia drought analysis linked to the 1997–98 analog and a forthcoming 2026–27 outlook—is still in progress and depends on license-gated forecast data. The core diagnostic claims of Parts 1 and 2 do not rely on it.

These limitations are stated explicitly in the laboratory and are restated here because they are part of the professional signal: the analysis knows what it is and what it is not.

### 5. Reproducibility and artifacts

The laboratory is self-contained and executable.

- Notebooks 01 (zonal node-versus-gradient diagnostic) and 02 (meridional jet teleconnection atlas) run top-to-bottom in a fresh environment built from the pinned requirements.  
- Physics modules (`bjerknes_physics.py`, `teleconnection_physics.py`) implement the field generators and diagnostic functions; both are covered by claim-level test suites.  
- Figures include the four-regime meridional atlas (identical three-panel anatomy for A–D) and the vertical scissoring closure of the Walker cell.  
- A short README states the taxonomy correspondence, the structure-versus-magnitude argument, and the idealized scope.

Repository: https://github.com/shunchantsai/Bjerknes-Diagnostic-Lab  

The notebooks themselves remain the primary evidence. This note is only a map of the argument and an indication of why the distinction it draws is relevant to catastrophe-risk work.