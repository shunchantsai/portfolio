# Cascading Failure on the Bhote Koshi: A Catastrophe-Risk Case Study of the 2026 Rasuwa Flood

---

## Executive Summary

On 26 August 2026 a large, rapid slope failure near the Nepal–China border sent rock, ice and sediment into the Lhende Khola and the Bhote Koshi–Trishuli system. The resulting debris flood reached the Rasuwagadhi border area within minutes and propagated downstream through a corridor of settlements, roads and hydropower infrastructure. Gauge records further down the Trishuli show water-level rises of approximately nine metres at Galchhi and seven metres at Malekhu within about thirty minutes. The physical cascade is not in serious dispute.

The research question is: what would an insurer, reinsurer, or public risk-finance institution need to understand about the catastrophe risk exposed by the August 2026 Nepal–China border flood-debris cascade?

The central problem is not simply estimating how much damage occurred. It is establishing which physical processes produced the loss, what assets were exposed, how much damage can be attributed to the event, and which portion of that loss was transferred to insurers and reinsurers — when key links in the hazard chain remain unresolved and the available numbers come from different scopes, dates and valuation bases.

This case study reconstructs the event under an explicit uncertainty framework. Claims are tagged CONFIRMED, REPORTED or HYPOTHESIS. The initiating failure, entry of material into the drainage network, and rapid downstream propagation are strongly supported by seismic, hydrological and situational evidence. Post-event satellite imagery from independent analyses identifies two newly formed water bodies interpreted as barrier lakes; the mapping is preliminary and not field-validated. The hypothesis that a temporary upstream dam formed and breached *during* the main cascade is retained as open: institutional and scientific interpretations have invoked temporary blockage, but the existence, location, duration and breach dynamics of such an impoundment have not been established to the evidentiary standard adopted here. Volume estimates and the precise source peak are likewise left unresolved rather than forced into a single narrative.

An illustrative exposure–vulnerability–loss chain is then run to demonstrate the arithmetic of catastrophe modelling. The exposure table is synthetic and incomplete by design; the vulnerability functions are literature-informed placeholders, not Nepal-calibrated curves. The resulting ground-up loss is a model output for the included assets only. It is not an estimate of actual event loss. External benchmarks — Copernicus EMSR927 grading for two small areas of interest, RAPIDA building-damage figures, national aggregate loss estimates, and dated insurance claims snapshots — are kept visible and separate. They are not used as calibration targets. Disagreement between model output and reported totals is treated as information, not as a reason to retune assumptions.

The available evidence indicates a substantial *potential* protection gap. National damage and reconstruction estimates substantially exceed the losses visible in available insurance claims snapshots. Those figures, however, differ in reporting date, geographical coverage, valuation basis and eligible loss categories; they cannot be treated as a direct measure of the uninsured share of total economic loss. Hydropower and corridor infrastructure concentrate both physical exposure and formal risk transfer, while a large share of household and informal losses sits outside the insured perimeter. The analysis does not apply policy limits, deductibles or reinsurance structures; those steps remain the natural next extension.

The resulting case study demonstrates how hazard evidence, exposure assumptions, vulnerability functions and insurance information can be assembled into a transparent risk assessment, while identifying the limitations that must be resolved before the results can support underwriting or portfolio decisions. Rapid-mapping products such as Copernicus EMSR927 optimise for standardised damage grading under time pressure. A catastrophe-risk case study optimises for transparent assumptions, status discipline, and the questions a risk analyst must still ask when the hazard chain is only partly resolved.

---

## 1. The Event and the Hazard Chain

### 1.1 Event overview

At 08:37 Nepal Time on 26 August 2026, a large, rapid slope failure near the Nepal–China border sent rock, ice and sediment into the Lhende Khola and the Bhote Koshi–Trishuli river system. Seismic signals recorded by the USGS registered the event; subsequent technical work placed the failure in the high Langtang Himal. The resulting debris flood reached the Rasuwagadhi border area within minutes — on the order of three to seven minutes over roughly twenty kilometres, according to timeline reconstructions anchored to seismic time, border CCTV and gauge behaviour — before propagating downstream through the corridor. At Galchhi, the Trishuli gauge recorded a water-level rise of approximately nine metres within about thirty minutes; at Malekhu, the rise was approximately seven metres over a similar period. A second seismic signal later the same morning has also been attributed to slope instability.

The initiating failure and the entry of material into the drainage network are **CONFIRMED**. Rapid downstream propagation and the gauge response are **strongly supported** by hydrological monitoring and multiple independent situational sources. The precise mechanism responsible for every segment of the flood hydrograph is **not uniformly confirmed**.

The cascading sequence, with confirmed and hypothesised elements distinguished, is shown below.

![Hazard-chain diagram](https://raw.githubusercontent.com/shunchantsai/nepal-flood-cat-case-study/master/01_event_reconstruction/hazard_chain.jpg)

*Source: [hazard-chain diagram](https://github.com/shunchantsai/nepal-flood-cat-case-study/blob/master/01_event_reconstruction/hazard_chain.jpg) in the nepal-flood-cat-case-study repository.*

The 2021 Chamoli rock-ice avalanche (Shugar et al. 2021), the 2016 Bhote Koshi GLOF (Cook et al. 2018) and the 2021 Melamchi debris flood are high-mountain analogues for rapid, infrastructure-damaging flows in steep valleys. None is evidence for the mechanism or intensity of the 26 August 2026 event, and none is used as a calibration source.

### 1.2 Source location and volume

Two peaks sit roughly four kilometres apart in the same massif: Langtang Lirung (7,234 m) and Tsangbu Ri (also called Kimshung, 6,781 m). The USGS event page places the signal near Langtang Lirung without specifying flank or elevation. An EarthArXiv preprint argues for failure on the northern flank of Langtang Lirung. Adhikari, Subedi et al. (*Seismica*, October 2026) place a rock fall with some ice, on the order of 100 million cubic metres, on the north flank of Tsangbu Ri, with a relocated seismic point argued to be consistent with a scarp visible on post-event imagery. The accounts have not been reconciled. The volume, ice content and Tsangbu Ri flank attribution appear only in the *Seismica* paper; the northern-flank Langtang Lirung claim appears only in the preprint. Neither is a shared finding. The source area and corridor are shown in the event location map (`01_event_reconstruction/maps/`).

The source area and corridor are shown below.

![Event location map](https://raw.githubusercontent.com/shunchantsai/nepal-flood-cat-case-study/master/01_event_reconstruction/maps/event_location.png)

*Source: [event location map](https://github.com/shunchantsai/nepal-flood-cat-case-study/blob/master/01_event_reconstruction/maps/event_location.png) in the nepal-flood-cat-case-study repository.*

A seismic source location and a visible detachment scarp are not necessarily the same geographical point. Without published relocation uncertainty and the actual spatial separation between the seismic solution and the scarp, the cross-check cannot be weighed quantitatively here. For downstream risk analysis the distinction between the two peaks is secondary: both locations feed the same drainage. For forensic hazard reconstruction it remains open and is carried as **REPORTED**.

Published volume estimates diverge and are left unresolved. The *Seismica* paper reports approximately 100 million cubic metres. Park (EarthArXiv, September 2026) reconstructs a moving volume of 27 (18–35) × 10⁶ m³ with an ice fraction of 0.1–0.3 and presents a reconstruction in which a rock–ice avalanche, without requiring stored water or a temporary dam breach, can reproduce the observed timing and gauge response. That analysis is a non-peer-reviewed preprint.

These figures should not automatically be treated as measurements of the same quantity. Detached source volume, mobilised avalanche volume, and deposit volume (including entrained material) can differ substantially; ice content and bulk-density assumptions also affect comparison. Until definitions, spatial boundaries and treatment of entrainment are reconciled, the numerical difference cannot be interpreted simply as disagreement about the size of the event. No single figure is adopted here. Treating volume as settled would propagate false precision into any subsequent intensity or loss calculation.

### 1.3 Secondary hazards and the temporary blockage hypothesis

Post-event satellite imagery from independent analyses identifies two newly formed water bodies interpreted as barrier lakes. UNOSAT’s product *Satellite-Detected Newly Formed Barrier Lakes Following an Ice-Rock Avalanche in Rasuwa District, Nepal, as of 28 August 2026* (Cartosat-3) maps these features. Complementary analysis by India’s National Remote Sensing Centre using the same Cartosat-3 pass and pre-event PlanetScope imagery reports two impoundments of approximately 19 ha and 11 ha. Chinese authorities and Nepal’s NDRRMA also recorded and monitored barrier lakes in the corridor. The mapping is preliminary and not field-validated. Presence of the water bodies is well supported by remote sensing; depth, volume, stability and exact formation timing are not. These post-event lakes are treated as a **satellite-detected secondary hazard**, distinct from any temporary impoundment during the main cascade.

The hypothesis that failed material temporarily impounded a reach (commonly framed as the Lhende Khola or an adjacent channel) and that a subsequent breach amplified the main flood wave remains **HYPOTHESIS**. Temporary blockage and breach have appeared in published scientific and institutional interpretations, including early reconstructions that invoked natural-dam failure as part of the sequence. ICIMOD identified the possibility as a priority line of investigation. Later secondary accounts described barrier-lake formation and breach in more definite terms, including specific travel-time claims.

An institution can publish an expert interpretation; that interpretation can be scientifically plausible; it does not automatically mean that the temporary dam and its breach have been independently demonstrated through field evidence or a sufficiently resolved reconstruction. The existence, location, duration and breach dynamics of a temporary impoundment *during* the 26 August cascade have not been established to the evidentiary standard adopted here. The hypothesis is therefore retained rather than treated as a confirmed link in the hazard chain. Post-event barrier lakes must not be conflated with that unresolved upstream question.

### 1.4 Implications for hazard reconstruction

For emergency response, the difference between a pure rock–ice avalanche and a cascade that included a temporary dam may be secondary once the wave has already passed. For catastrophe-risk analysis the difference is material. An amplifying breach changes the shape and timing of the hydrograph, peak intensity at downstream assets, and the credibility of any scenario set built from the event.

The temporary-dam question potentially affects:

1. **Hazard intensity** — peak discharge, flow depth, velocity and sediment concentration  
2. **Spatial footprint** — which downstream locations are affected and to what degree  
3. **Temporal characteristics** — arrival time, duration and shape of the flood wave  
4. **Vulnerability response** — how different infrastructure and building types experience the resulting physical conditions  
5. **Financial loss** — the resulting damage estimates and the uncertainty around them  

Treating a hypothesis as settled would understate epistemic uncertainty at the base of the modelling chain. Keeping the status explicit preserves the option to update the narrative when primary evidence arrives, without having to unwind a premature consensus. The same discipline applies to volume and source-peak ambiguity: unresolved inputs are carried as unresolved, not averaged or silently preferred.

### 1.5 Implications for catastrophe-risk modelling

The unresolved elements of the hazard chain are not merely geological uncertainties. They affect the assumptions used to translate the event into financial loss.

A larger or smaller mobilised volume, different ice content, or the presence of a temporary impoundment could produce materially different flow characteristics. Those differences influence the spatial distribution and intensity of flooding, and therefore the depth and velocity experienced by exposed assets. In a fully developed catastrophe model, these variables would inform alternative hazard scenarios, which would then be intersected with an exposure inventory and passed through appropriate vulnerability functions. Financial terms would subsequently determine insured and retained losses.

This case study does not have sufficient hydraulic or asset-level data to quantify those alternatives reliably. Instead, it identifies where the uncertainties enter the modelling chain and distinguishes the illustrative calculations that follow from estimates of actual event loss. Until the mechanism is better constrained, the appropriate response is to retain alternative hazard scenarios rather than select one interpretation and treat its outputs as definitive.

---

## 2. Why This Corridor Concentrates Risk

The Bhote Koshi–Trishuli corridor is not merely the path taken by the debris flood. It is a concentration of physical exposure, critical infrastructure and assets with potentially significant insurance and reinsurance implications. Its terrain, cross-border setting and linear infrastructure network help explain why a single high-altitude failure produced impacts across multiple settlements and economic sectors. They also provide the geographical context for the exposure, vulnerability and insurance analysis that follows.

### 2.1 Terrain, confinement and flow concentration

In its upper reaches and other tightly constrained valley sections, the corridor is narrow and steep. Material entering the Lhende Khola and Bhote Koshi therefore has limited opportunity to spread laterally across a broad floodplain. The steep channel gradient may support rapid downstream propagation, while confinement can concentrate the flow through settlements and infrastructure nodes.

Timeline reconstructions imply high average propagation speeds over the first tens of kilometres — on the order of twenty kilometres in roughly three to seven minutes between the seismic signal and impact near the border. An average travel time between two points is not the same as the velocity of the moving debris or water at every location along the reach, and it is sensitive to uncertainty in start time and first observed impact.

More importantly, steepness and confinement do not by themselves establish that peak discharge, depth and velocity remained high at any particular downstream cluster of assets. Actual behaviour also depends on channel geometry, entrainment, deposition, flow resistance, temporary obstructions, tributary inflows and the evolving mixture of water and sediment. Discharge, depth and velocity are not interchangeable intensity measures. For catastrophe modelling, the terrain provides a strong basis for identifying locations where flow may be concentrated, but it is not a substitute for estimating local hazard intensity. That would require hydraulic reconstruction.

### 2.2 Cross-border setting and warning asymmetry

The initiating failure and the first tens of kilometres of the pathway sit on or across the Nepal–China border. Upstream monitoring, imagery and institutional response are therefore split across two systems. In this event, the seismic signal at 08:37 was followed within minutes by impact at the Rasuwagadhi border area. Gauges in the upper Nepali reach ceased transmission as the wave arrived. Nepal’s Department of Hydrology and Meteorology issued a high-alert bulletin at 09:15 and dispatched SMS alerts to approximately 679,000 recipients at 09:16 — after the surge had entered the Bhote Koshi and the uppermost settlements had been hit. The dispatch figures establish the scale and timing of the alert operation, not the number of people who received or acted on the warning, and they do not by themselves demonstrate geographical targeting, delivery rates or behavioural effectiveness further downstream.

The result was a pronounced warning asymmetry. Communities closest to the cross-border source had little or no practical warning time, while the national warning system issued alerts that could, in principle, reach some downstream communities after the surge had already entered Nepal. Warning lead time therefore varied substantially along the corridor. For risk analysis this is a spatially differentiated **consequence modifier**, not a uniform characteristic of every exposed asset and not a parameter of a building’s physical vulnerability function. Warning time may affect evacuation, human safety, emergency response, contents and movable-property outcomes, business interruption and recovery; it does not rewrite a depth–damage relationship. Assets at the border and in the first corridor settlements faced a near-zero practical warning window for this class of cascade; assets further downstream did not face the same condition.

### 2.3 Infrastructure, settlement and asset concentration

Roads, bridges, border facilities and hydropower works are aligned along the same narrow valley floor that carries the flood. The Rasuwagadhi crossing, the Syabrubesi–Timure settlements, multiple hydropower intakes, powerhouses and tunnels, and successive road and bridge links form a linear accumulation of high-value and high-criticality assets.

Copernicus EMSR927 grading for the two small areas of interest (AOI01 Syapru Besi, 346 ha; AOI02 Timure, 297 ha) recorded 237 ha of mass movement, graded 864 building points, and classified as destroyed the Langtang Khola 20 MW powerhouse, the Rasuwagadhi hydropower dam, six bridges and approximately 9.5 km of primary road (including a section of the Pasang Lhamu Highway). These are rapid image-based damage classifications, not engineering inspections or estimates of replacement cost. The AOIs are not the full corridor, but they illustrate the density of exposure where the valley is tightest.

Hydropower deserves separate emphasis. Public reporting in the days after the event described shutdowns across multiple projects and combined affected capacity on the order of several hundred megawatts, alongside substantial numbers of workers unaccounted for at several sites. Hydropower assets concentrate replacement value, potential business-interruption exposure and, where covered, formal risk transfer. They also concentrate people. Corridor risk is therefore not only residential and transport risk; it is energy-infrastructure and workforce risk stacked on the same channel. A single event can affect multiple asset classes and several components of the same infrastructure network simultaneously — for example where damage to a bridge or access road interrupts repair or operation of a powerhouse that is itself only partially damaged.

### 2.4 Satellite mapping: regional footprint and limitations

Independent satellite products provide order-of-magnitude spatial context. They are not used as model inputs or calibration targets. Detailed Copernicus grading for the two AOIs is set out in Section 2.3; the comparison below places that assessment alongside broader UNOSAT product framings.

| Product | Spatial finding | Interpretation |
|---|---|---|
| UNOSAT, 28 Aug 2026 (FL20260826NPL product framing) | ~37 km² affected; ~120 km of potentially affected roads; ~5,000 buildings exposed to or near affected areas | Preliminary regional context; not field-validated |
| UNOSAT, district-level framing (FL20260826NPL) | ~30 km² affected (~20 km² Rasuwa, ~10 km² Nuwakot); population exposure reported in the low thousands depending on product | Separate product framing; not directly interchangeable with the row above |
| Copernicus EMSR927, first release (AOI01–02) | Mass-movement delineation and building/facility/transport grading within two limited AOIs (see §2.3) | Higher-resolution image-based damage grading; not field-validated |

These products measure different things over different footprints. “Buildings exposed to or near affected areas” is not the same as buildings intersecting a mapped hazard polygon, and is not the same as buildings damaged or destroyed. Population estimates vary by product and, in the Copernicus case, across the population grids used; Copernicus itself rated the reliability of its affected-population estimate as poor. Mapped extent is related to, but not identical with, a hydraulic flood footprint: UNOSAT categories include mudflow/rockflow and flood-affected areas; Copernicus separately delineates mass movement and grades damage.

Satellite assessments indicate that the affected area extends across multiple districts and includes settlements, transport links and energy infrastructure. Although preliminary and incomplete, these products establish the regional scale of the impact and provide independent spatial context for the exposure analysis. They must not be blended with national loss aggregates or claims snapshots that use different scopes and dates. Dataset metadata that attribute the event to a glacial lake outburst flood are not adopted here as a resolved mechanism; Section 1 leaves key links in the hazard chain open.

### 2.5 Implications for catastrophe-risk modelling

Corridor concentration has implications at several stages of the loss calculation.

**Physical concentration.** Steep, confined terrain and a relatively narrow channel influence where hazard intensity *may* be concentrated. That is a basis for prioritising locations in a hazard footprint, not a measured intensity field.

**Exposure concentration.** Buildings, roads, bridges, hydropower facilities and other assets are aligned along the same constrained corridor, often in close spatial proximity. Damage to one part of the network may affect the operation or accessibility of another. The exposure inventory must identify not only buildings but also transport and energy infrastructure, including relationships between connected assets. This also creates a potential **accumulation** problem: a single event can damage multiple assets within the same portfolio and disrupt connected infrastructure, so losses cannot necessarily be understood by assessing each asset in isolation. The evidence here establishes the geographical conditions for accumulation and interdependency; it does not quantify their financial magnitude.

**Vulnerability and financial concentration.** A residential building, a bridge, a powerhouse and a tunnel do not share the same damage mechanisms, repair times, replacement values or insurance arrangements. Their physical vulnerability and financial treatment must therefore be differentiated. **Asset replacement value, insured value and recoverable insurance loss are separate quantities**; the last depends on policy coverage, limits, deductibles, exclusions and applicable terms.

The available evidence establishes the importance of these asset classes and their spatial concentration. It does not provide sufficient information to quantify all of these loss components. Uncertainty in the hazard chain therefore maps onto a small set of high-consequence locations rather than being diluted across a diffuse portfolio — which is precisely why transparent status tagging and the refusal to force calibration matter in the sections that follow.

---

## Section 3. Exposure, Vulnerability, and Illustrative Loss

Sections 1 and 2 establish what is known and unknown about the hazard and why consequences concentrated along the corridor. This section turns to the modelling chain: how exposure is represented, how intensity is translated into damage, what the illustrative loss figure is, and how external damage and claims numbers are treated. Model output, graded or reported damage, national economic estimates and insurance claims are kept in separate categories. They are not forced into agreement.

### 3.1 Nature of the exposure table

The exposure inventory is synthetic and incomplete by design. It contains a small number of representative assets with estimated locations and replacement values. Its purpose is to demonstrate the exposure → vulnerability → loss arithmetic transparently, not to reproduce the corridor’s actual asset stock.

Limitations follow from that design:

- The table is not a real client submission and is not statistically representative of affected properties.
- Coordinates are present, but the loss calculation does not intersect assets with a hazard surface. Flood depths are assigned manually to each row.
- Losses apply only to the included assets and modelled mechanisms. They must not be extrapolated to corridor or national totals without a defensible inventory and scaling methodology that this project does not provide.

In production, exposure work would begin with completeness and consistency checks: missing or inconsistent occupancy and construction fields; replacement values in mixed currencies or valuation years; coordinates outside the study area; duplicate records; missing or inappropriate vulnerability classifications; and consistency between asset type and the assigned vulnerability function. The illustrative table stops short of that workflow so that every assumption in the loss calculation remains visible. What it demonstrates is structure; what it does not demonstrate is a validated portfolio inventory.

### 3.2 Vulnerability functions

Hazard intensity is translated into physical damage through simplified, literature-informed depth–damage functions. The implementation is informed by the global flood depth–damage framework of Huizinga, de Moel and Szewczyk (2017), but the curves used here are **linear placeholders**, not the published JRC functions reproduced without modification, and they are not calibrated to Nepali construction types, local damage observations or this event.

**Implemented form.** For each asset \(i\):

$$
D_i = \min(1, s_{t(i)} \cdot h_i)
$$

$$
L_i = R_i \cdot D_i
$$

where \(h_i\) is assigned flood depth (m), \(R_i\) is replacement value (USD), \(D_i\) is the damage ratio, \(L_i\) is direct physical ground-up loss, and \(s_{t(i)}\) is an asset-type slope:

| Asset type   | Illustrative slope \(s\) (per metre depth) |
| ------------ | ------------------------------------------ |
| Residential  | 0.15                                       |
| Commercial   | 0.10                                       |
| Bridge       | 0.20                                       |
| Hydropower   | 0.25                                       |
| Road segment | 0.30                                       |

Damage ratios are bounded in \([0, 1]\). Unrecognised asset types, missing depths or negative depths yield NaN and are excluded from the total rather than treated as zero. Loss under these direct-damage assumptions cannot exceed replacement value. The calculation is fully reproducible from the exposure table and the function defined in `02_exposure_vulnerability/vulnerability_functions.py`.

**Worked example.** Asset A0005 (hydropower):

\( R = 50{,}000{,}000 \) USD, \( h = 2.5\,\mathrm{m} \), \( s = 0.25 \).

$$
D = \min(1,\ 0.25 \times 2.5) = 0.625
$$

$$
L = 50{,}000{,}000 \times 0.625 = 31{,}250{,}000 \text{ USD}
$$

**Limitations of different kinds.**

A single linear depth–damage relationship does not capture thresholds or strongly nonlinear damage. Depth alone does not represent velocity, sediment concentration, boulder impact or scour. Parameters are not fitted to Nepali construction or observed damage from this event.

These omissions matter because the event was a high-velocity debris flood, not a clear-water inundation. Empirical and experimental work on debris flows and debris floods shows that damage to buildings and infrastructure is driven by the interaction of depth with velocity, sediment concentration, boulder impact and scour rather than by hydrostatic depth alone (Jakob & Hungr 2005; Fuchs et al. 2007; Totschnig et al. 2011). The 2021 Chamoli event provides a recent high-mountain analogue for the mechanism class; the inference that the resulting infrastructure damage is inconsistent with clear-water depth-damage assumptions is drawn here and is not a direct claim of the Chamoli study (Shugar et al. 2021). It is not used as evidence for the 26 August 2026 event. Linear depth-only functions calibrated primarily on clear-water flooding therefore systematically under-represent the dominant loading mechanisms for this event type. Those mechanisms are identified, not modelled.

| Processes not represented             | Potential damage relevance                 | Uncertainty type            |
| ------------------------------------- | ------------------------------------------ | --------------------------- |
| Sediment concentration and deposition | Burial, inundation, sediment loading       | Epistemic (process form)    |
| Boulder transport and impact          | Localised structural failure               | Epistemic + aleatory        |
| Channel erosion and scour             | Foundation undermining, bridge failure     | Epistemic (parameter)       |
| Flow velocity and momentum            | Structural loading                         | Epistemic (hazard variable) |
| Debris blockage                       | Local water-level increase, flow diversion | Aleatory + epistemic        |

A depth-only linear function is therefore a weak representation of damage to bridges, hydropower works and other infrastructure in a debris flood. The residual uncertainty is predominantly epistemic: it stems from incomplete process representation and uncalibrated parameters rather than from random variation around a well-specified function.

### 3.3 Ground-up loss result and what it represents

Applying the functions to the illustrative exposure table produces a ground-up loss of approximately **US$33.3 million** under the stated assumptions (Section 3; reproducible from vulnerability_functions.py). That figure is a deterministic model output for the included synthetic assets. The result is dominated by a single large hydropower asset in the synthetic table; the concentration is a feature of the illustrative exposure design, not a finding about the actual corridor portfolio. It is **direct physical damage** only. Business interruption and other indirect economic consequences are not included. No policy limits, deductibles, sub-limits, exclusions or reinsurance structures are applied, so insured loss and net retained loss are not calculated.

The result answers a narrow question: given this exposure table, these assigned depths and these vulnerability functions, what damage value does the arithmetic produce? It does not estimate how much of the real event’s loss was incurred, insured, recoverable or retained. Asset-level losses sum to the reported total (invalid rows excluded); the calculation is reproducible from the stated inputs and code.

### 3.4 External benchmarks kept separate

Several external figures are retained as **independent reference points** for the event’s reported physical, economic and insurance impacts. They provide context for interpreting the illustrative model output. They are **not directly comparable** with it and are **not used as calibration targets**.

**Exhibit 1. External benchmarks kept separate from the illustrative model output**  

| Benchmark | Approximate figure | What it measures | What it does not measure |
|-----------|--------------------|------------------|--------------------------|
| Illustrative model (Section 3) | ~US$33.3 million | Deterministic ground-up loss on included synthetic assets | Corridor or national loss; insured loss |
| Copernicus EMSR927 (AOI01–02) | 864 building points graded; named facilities and transport links graded destroyed | Image-based damage classification in two small AOIs | Corridor-wide loss; replacement cost; insured loss |
| UNDP RAPIDA (via OCHA Sitrep No. 6, 3 Sept 2026) | ~US$158.6 million potential building damage (±30%) | Potential building-damage estimate for the assessment scope | Total disaster loss; verified repair costs; model ground-up loss |
| National loss estimate (NDRRMA, 4 Sept 2026) | ~US$2.56 billion (NPR 387.5 billion) | Preliminary official estimate of property, housing and infrastructure loss | Fully documented methodology; insured loss; model output |
| RDNA total effects | ~US$2.7 billion (NDRRMA/NPC RDNA, September 2026)| Physical damage + economic losses | Reconstruction needs; insured loss |
| RDNA reconstruction needs | ~US$4.7–4.8 billion (NDRRMA/NPC RDNA, September 2026)| Longer-term recovery and reconstruction needs | Interchangeable with the loss estimate; insured loss |
| NIA claims, ~31 Aug 2026 | ~US$171 million (NPR 25.87 billion); 583 policies | Claims filed/reported at that date | Ultimate paid loss; total economic damage |
| NIA claims, ~29 Sept 2026 | ~US$139 million (NPR 20.98 billion); 2,180 policies | Later reporting point (not blended with August) | Same as above |

*Sources: Section 3 model output; Copernicus EMS EMSR927 grading products (27 August 2026); OCHA Rasuwa Flood Situation Report No. 6 (3 September 2026); NDRRMA statement reported by Reuters (4 September 2026); NDRRMA/NPC Rapid Damage and Needs Assessment (September 2026); NIA claims snapshot ~31 August 2026 (as reported early September 2026); NIA claims snapshot ~29 September 2026 (as reported late September 2026); NIA figures as of 16 October 2026 (Banjade 2026) for the paid/unpaid split shown in Section 4.2.*

The ~US$2.56 billion figure originates from an official statement by **Dharma Raj Upreti**, Chief Executive of the **National Disaster Risk Reduction and Management Authority (NDRRMA)** (NDRRMA / Reuters, 4 September 2026), given to Reuters on 4 September 2026. He reported that property, housing and infrastructure losses were estimated at **at least NPR 387.5 billion** (US$2.56 billion at the then-prevailing exchange rate), calculated in coordination with relevant agencies, with a more detailed assessment to follow.

The subsequent **Rapid Damage and Needs Assessment (RDNA) – Rasuwa-Bhotekoshi Flood 2026** (published by NDRRMA with the National Planning Commission in September 2026) refined the picture: total effects (physical damage + economic losses) of approximately US$2.7 billion and longer-term recovery/reconstruction needs of approximately US$4.7–4.8 billion. The two quantities are distinct and must not be treated as interchangeable.

Building damage is not total disaster loss. Filed or reported claims are not ultimate paid insurance losses. Satellite exposure counts (buildings exposed to or near affected areas, population, road length) are independent spatial context, not loss estimates and not inputs to the illustrative calculation.

### 3.5 Explicit refusal to force calibration

The gap between the illustrative ground-up result (~US$33 million) and the national aggregate (~US$2.56 billion), or between the model output and RAPIDA’s potential building-damage estimate, is expected. The scopes differ. Vulnerability curves should not be retuned, and the exposure table should not be inflated, merely to force the illustrative output to match an external total.

Agreement between a model and a benchmark is informative only when four foundations are aligned: (1) exposure coverage and completeness, (2) hazard intensity representation (including process type), (3) vulnerability basis (functional form and calibration), and (4) loss definition (direct physical vs total economic, ground-up vs insured). Where they are not aligned, the discrepancy is information about scope mismatch, not a reason to overwrite assumptions.

In this case the four foundations are deliberately unaligned. The exposure table is synthetic and partial (epistemic incompleteness). The hazard is represented by manually assigned depth only, omitting velocity, sediment and impact processes that dominate debris-flood damage (epistemic process omission). The vulnerability functions are uncalibrated linear placeholders (epistemic parameter uncertainty). The loss definition is restricted to direct physical ground-up loss on the included assets. Under these conditions, forcing numerical agreement would conceal rather than reduce uncertainty.

A meaningful reconciliation would first require aligning those four foundations and only then investigating residual differences through exposure completeness, hazard intensity, vulnerability assumptions and financial treatment. This case study does not attempt that reconciliation because the underlying data are insufficient. 

---

## 4. Insurance, Claims, and the Protection Gap

Sections 1–3 reconstruct the hazard chain, examine the concentration of exposed infrastructure along the affected corridor, and demonstrate an illustrative exposure–vulnerability–loss calculation. This section examines how the resulting losses interact with Nepal’s insurance market and wider disaster-financing arrangements.

The central distinction is between **economic loss, insured loss, claims submitted, claims paid and the funding required for recovery**. These are related, but they are not equivalent. The available figures provide evidence of the scale of the insurance response and the wider financing challenge; they do not, by themselves, establish a definitive event-wide protection-gap estimate.

### 4.1 Insurance exposure: hydropower and infrastructure

The flood affected a corridor in which hydropower generation, transmission infrastructure, roads and bridges are economically important and geographically concentrated. This creates a particular challenge for insurers: multiple assets and projects can be exposed to the same event, while damage to one part of the corridor can disrupt the operation of others.

The Nepal Insurance Authority (NIA) report *Hydropower Insurance in Nepal: Assessment of Trends, Challenges, and Opportunities for Reform* provides useful context for the sector's existing insurance arrangements. Its findings point to significant underwriting and claims-management pressures in hydropower insurance.

The report identifies several issues:

* **Claims experience is volatile.** The reported hydropower claim ratio varied substantially between financial years, reflecting the influence of large losses and the relatively concentrated nature of the portfolio.
* **Underwriting performance is under pressure.** Using the report's figures and an assumed 5% expense ratio, the estimated average gross combined ratio is approximately 146%, while the estimated net combined ratio is approximately 108%. The report excludes FY2077/78 from this calculation because it includes pre-MTR data and notes that FY2081/82 contains only nine months of data.
* **Claims can take a long time to settle.** The report identifies a median settlement time of approximately 298 days in its sample of 121 paid claims, increasing to 372 days for Engineering All Risks (EAR) claims.
* **Claims assessment is an operational bottleneck.** The report identifies the survey and assessment process as a significant contributor to delays.

These findings should be interpreted as evidence of structural pressures in the hydropower insurance market, not as a direct measurement of the financial performance of insurers following the August 2026 flood. The combined ratios are derived estimates, not independently calculated market-wide results, and the claims-settlement sample is not necessarily representative of all claims.

The report also describes the use of different reinsurance arrangements. Its reported distribution includes treaty and facultative arrangements (62%), proportional or treaty arrangements (21%), facultative arrangements (16%), and a small residual category involving combined arrangements. These figures describe the reported arrangement categories; they should not be interpreted as the proportion of premiums ceded, losses recovered, or available reinsurance capacity.

Taken together, the findings indicate that the flood struck a sector already facing questions about underwriting sustainability, claims administration and the availability of reinsurance for large infrastructure risks.

**Source:** Nepal Insurance Authority, *Hydropower Insurance in Nepal: Assessment of Trends, Challenges, and Opportunities for Reform* (2026).

### 4.2 Insurance claims following the August 2026 flood

The NIA's reported claims figures provide an indication of the scale of the insurance response, although they remain provisional and subject to adjustment as loss assessments progress.

By 16 October 2026, insurers had reported approximately **NPR 20.9 billion in claims**, against which **NPR 821.39 million had been paid**. The paid amount was therefore approximately **3.9% of the reported claims total** at that reporting date.

The reported claims were distributed across several insurance classes:

**Exhibit 2. NIA claims by insurance class, as of 16 October 2026**  

| Insurance class | Claims reported | Reported claim value (NPR) |
|-----------------|-----------------|----------------------------|
| Property | 576 | 9.56 billion |
| Engineering and contractor | 174 | 4.40 billion |
| Motor | 1,067 | 2.85 billion |
| Transit | 105 | 2.34 billion |
| Other | 556 | 1.51 billion |
| Health | 53 | 246.3 million |
| **Total** | **~2,531** | **~20.9 billion** |

*Source: Nepal Insurance Authority figures as of 16 October 2026, reported in Yagya Banjade, “Insurers have paid just 4 percent of Bhotekoshi flood claims,” The Kathmandu Post, 28 October 2026. Paid amount at that date: NPR 821.39 million (~3.9% of reported claims).*

Property insurance accounted for the largest reported claim value, while motor insurance generated the largest number of claims. Engineering and contractor insurance also represented a substantial share of the reported value, reflecting the importance of infrastructure and construction-related risks in the affected area.

The payment position varied by class. Reported payments included approximately NPR 238.9 million for transit claims, NPR 236.6 million for motor claims, NPR 174 million for engineering and contractor claims, NPR 162.8 million for property claims and NPR 8.9 million for other claims.

The low proportion paid by 16 October should not automatically be interpreted as the final proportion of insured losses that will be recovered. The event had occurred less than two months earlier, and large infrastructure claims require access to damaged sites, technical assessment, documentation, coverage review and, in some cases, reinsurance coordination. The figures are a dated snapshot of claims processing, not a final settlement ratio.

The claims total also changed substantially during the reporting process. Preliminary estimates reached NPR 25.87 billion within several days of the disaster, before falling to approximately NPR 15–16 billion as assessments began and subsequently increasing to NPR 20.9 billion as further claims were submitted. This illustrates why claims figures must be accompanied by their reporting dates and status rather than presented as a single fixed estimate.

**Source:** Yagya Banjade, “Insurers have paid just 4 percent of Bhotekoshi flood claims,” *The Kathmandu Post*, 28 October 2026, reporting NIA figures as of 16 October 2026.

### 4.3 Modelled loss and reported disaster effects: different measures

The illustrative model in Section 3 produces approximately **US$33.3 million in ground-up loss** under its current exposure, hazard and vulnerability assumptions. This figure applies only to the synthetic assets included in the model. It is not an estimate of total losses from the flood, nor is it a measure of insured losses.

For comparison, the Government of Nepal's September 2026 Rapid Damage and Needs Assessment (RDNA) estimates:

* **US$1.812 billion** in physical damage;
* **US$883 million** in economic losses;
* **US$2.695 billion** in total disaster effects; and
* **US$4.775 billion** in total recovery and reconstruction needs.

The distinction between these figures matters. Physical damage refers to damage to assets; economic losses capture the effects of disrupted economic activity and services. Total disaster effects combine these two categories. Recovery and reconstruction needs are higher because they include the resources required to restore and rebuild, including measures intended to improve resilience.

The US$33.3 million model output and the RDNA's US$2.695 billion estimate therefore have fundamentally different scopes. The former is a calculation for a small illustrative portfolio; the latter is a national, multi-sector assessment. Their difference is expected and does not indicate that the illustrative model has identified a particular proportion of the disaster's total loss.

The model should not be recalibrated simply to force its output to match the RDNA. Doing so would obscure the limitations of the synthetic exposure inventory and simplified vulnerability functions rather than improve the credibility of the analysis.

**Source:** Government of Nepal, *Rapid Damage and Needs Assessment: Rasuwa-Bhotekoshi Flood 2026* (September 2026). The RDNA figures are also summarised in the Ministry of Foreign Affairs' press briefing of 11 September 2026.

### 4.4 The protection-gap question

The reported insurance claims total of NPR 20.9 billion can be placed alongside the wider disaster estimates to illustrate the relative scale of the insurance response.

However, a simple ratio between claims and total disaster effects is **not an insured-loss ratio**. The numerator is a provisional total of claims submitted to insurers; the denominator includes physical damage and economic losses across sectors, including assets and activities that may not be insurable or insured. The two figures also differ in assessment methodology, coverage and reporting status.

Similarly, comparing claims with reconstruction needs does not establish the amount of the protection gap. Reconstruction needs include costs associated with rebuilding and improving resilience, while insurance claims relate to losses submitted under specific policies and coverage conditions.

The comparison is nevertheless informative as a measure of scale:

* Reported claims of NPR 20.9 billion are approximately **5.1% of the RDNA's NPR 408.3 billion in total disaster effects**.
* The same claims total is approximately **2.9% of the RDNA's NPR 723.3 billion in recovery and reconstruction needs**.

These percentages should be read only as scale comparisons. They do not show that insurance covers 5.1% of disaster losses or that the remaining 97.1% of reconstruction needs are uninsured. A defensible protection-gap estimate would require a consistent assessment of eligible insurable losses, actual policy coverage, insured asset values, deductibles, limits, exclusions, accepted claims and final insurer payments.

The protection gap is also not limited to the difference between insured and uninsured physical damage. It includes the financial consequences of business interruption, loss of livelihoods, damage to public infrastructure, disruption to essential services and reconstruction costs that fall outside private insurance arrangements.

For example, damage to a hydropower facility can generate direct physical repair costs as well as lost generation revenue. Whether those losses are insured depends on the policy structure, including whether business interruption cover is included, the applicable waiting period and the terms governing interruption caused by physical damage. The available aggregate claims figures do not establish how much of the event's business interruption losses will ultimately be insured or recovered.

A more complete protection-gap assessment would therefore require the final claims data to be reconciled with asset-level damage assessments and the RDNA's sectoral loss estimates. Until then, the figures demonstrate the scale of the financing challenge, not a precise measure of the uninsured share.

### 4.5 Beyond private insurance: public disaster-risk financing

Private insurance is only one layer of disaster-risk financing. Large-scale disasters also require public resources, contingent financing and international support, particularly for public infrastructure, emergency response and recovery needs that cannot be transferred readily to commercial insurers.

Nepal's existing financing arrangements include the World Bank-supported **US$150 million Catastrophe Deferred Drawdown Option (Cat DDO)**, approved in October 2024. The instrument provides contingent sovereign financing that can be accessed following an eligible disaster or emergency, subject to its conditions. It is a credit facility, not an insurance policy or grant; its approval should not be treated as evidence that the funds were drawn down for the August 2026 event.

Separately, on 23 September 2026, the World Bank stated that it had made available **up to US$170 million in emergency financing** to support Nepal's immediate response and the restoration of critical infrastructure and services. This is a separate financing announcement and should not be conflated with the pre-existing Cat DDO.

These instruments illustrate the role of sovereign and development-partner financing in absorbing losses beyond the reach of private insurance. They also highlight the distinction between financing immediate response, restoring damaged assets and meeting longer-term reconstruction and resilience needs.

The RDNA's estimate of US$4.775 billion in recovery and reconstruction needs provides the broader context for this challenge. The scale of the requirement means that recovery cannot be understood solely through the amount of insurance claims submitted or paid.

### 4.6 Implications for catastrophe-risk analysis

The insurance evidence adds a financial dimension to the physical risk analysis developed in the preceding sections.

First, **geographic accumulation matters**. Hydropower facilities, roads, bridges and other infrastructure concentrated along the same river corridor can be affected by a single event. The resulting losses may be significant for individual insurers and their reinsurance counterparties even where the number of affected policies is relatively small.

Second, **gross loss does not determine the final financial burden**. Policy conditions, deductibles, limits, exclusions, business interruption cover and reinsurance arrangements determine how much of the physical loss is transferred to insurers and how much is ultimately retained by insurers, reinsurers, asset owners and the public sector.

Third, **claims settlement is part of the financial impact**. Delays between damage, assessment and payment can constrain the liquidity available to affected businesses and infrastructure operators. The NIA's hydropower findings suggest that this is a structural issue worth considering alongside the scale of the event's reported claims.

Finally, **the protection gap cannot be inferred from a single pair of aggregate figures**. A robust estimate would require consistent asset-level information linking physical damage, insurance coverage, accepted claims, payments and recovery requirements. The available evidence supports a clear conclusion that the disaster generated a substantial recovery-financing challenge, but not a precise event-wide estimate of uninsured losses.

For catastrophe-risk modelling, this distinction is important: estimating physical damage, estimating insured loss and assessing the wider economic financing requirement are related analytical tasks, but they are not interchangeable outputs.


---

## 5. What the Analysis Can and Cannot Support

The preceding sections reconstruct a cascading hazard, place consequences in a high-concentration corridor, demonstrate a transparent exposure–vulnerability–loss calculation, and situate the results against dated insurance and official damage figures. This section states what those results can and cannot support.

### 5.1 Strengths of the present analysis

Three features give the work its value.

- **Mechanism clarity and evidence-status discipline.** The event is represented as a cascading chain (high-altitude rock/ice slope failure → debris flood → corridor impacts), while observed, reported and hypothesised elements are distinguished. A transient landslide dam remains a hypothesis; it is not treated as established.
- **Transparent arithmetic.** The illustrative ground-up loss (~US$33.3 million) is fully determined by a small synthetic exposure table, manually assigned depths and linear depth–damage functions. The calculation is reproducible and its assumptions are visible. Invalid inputs are excluded rather than silently treated as zero.
- **Separation of categories.** Model output, satellite grading, RAPIDA potential building damage, national economic estimates, RDNA reconstruction needs, claims filed and claims paid are kept distinct. No attempt is made to force numerical agreement between them.

### 5.2 Limits

The analysis does not provide:

- A stochastic event catalogue or frequency model derived from this single event.
- Average annual loss (AAL), probable maximum loss (PML) or exceedance-probability (EP) curves.
- Application of policy terms (limits, deductibles, sub-limits, exclusions or reinsurance structures) to convert ground-up loss into insured or net retained loss.
- A hydraulic or debris-flow model that would convert a hazard surface into spatially varying intensity at asset locations.
- A statistically representative or client-specific exposure inventory.

These omissions are deliberate scope boundaries, not temporary data gaps that the present repository claims to close.

A production workflow would require georeferenced assets with defensible values, an intensity representation appropriate to the dominant damage processes, and vulnerability functions suitable for the relevant asset classes and construction context. Insurer applications would additionally require portfolio-level policy and claims data, while public risk-finance applications would require information on public assets, fiscal exposure and existing contingent financing arrangements.

### 5.3 Epistemic and aleatory uncertainty in this event

The residual uncertainty is predominantly epistemic.

- **Epistemic.** Incomplete process representation (depth-only functions omit velocity, sediment concentration, boulder impact and scour); uncalibrated parameters; unresolved source location and volume; and the status of any transient dam. These are uncertainties about the form and parameters of the model, not random variation around a well-specified process.
- **Aleatory.** Once a hazard intensity field and vulnerability function are fixed, residual variability in realised damage can remain. Whether a particular physical mechanism (for example, localised boulder impact or debris blockage) is treated as aleatory depends on what is known and how the model represents the process. An information gap about whether boulders reached a given asset is epistemic; probabilistic representation of a known transport process may be treated as aleatory; improved observations or process understanding can reduce some of that uncertainty.

The distinction matters for model use. Epistemic uncertainty can be reduced through improved process understanding, observations, exposure data and calibration, although it cannot necessarily be eliminated. Aleatory uncertainty represents residual variability in outcomes under a specified model and set of conditions. It is characterised and quantified through probabilistic modelling, while portfolio aggregation and risk transfer help assess and finance its consequences. In the present analysis, neither component is quantified probabilistically; the dominant limitations are epistemic, because the hazard representation, exposure and vulnerability assumptions remain insufficiently established. The absence of a stochastic catalogue is a separate constraint: a single reconstructed event does not establish the frequency dimension of catastrophe risk.

The epistemic/aleatory distinction used here follows the uncertainty typology commonly applied in catastrophe-model governance, in which epistemic uncertainty is reducible through improved knowledge and data while aleatory uncertainty is characterised probabilistically under a specified model (Grossi & Kunreuther 2005).

The four foundations required for any meaningful reconciliation—exposure coverage, hazard intensity representation, vulnerability basis and loss definition—align with the epistemic/aleatory distinction in the following sense: incomplete exposure, an intensity field that omits dominant processes, uncalibrated vulnerability functions, and inconsistent loss definitions are epistemic gaps. Only after those foundations are sufficiently established does residual variability around a specified model become the dominant (aleatory) component. In the present analysis the four foundations remain unaligned, so the uncertainty is predominantly epistemic.

### 5.4 Comparison with a rapid-mapping product (EMSR927)

Copernicus EMSR927 provides image-based damage grading for defined areas of interest (including Syabrubesi), reporting counts of buildings and infrastructure classified as destroyed or damaged (Copernicus EMS EMSR927 Grading product, 27 August 2026). It is a rapid-mapping product designed to support emergency response. It is not a loss model.

The two products serve different purposes:

**Exhibit 3. Comparison of EMSR927 grading and the present analysis**  

| Product | Purpose | Output | What it does not provide |
|---------|---------|--------|--------------------------|
| EMSR927 grading | Rapid situational awareness | Image-based damage classification in specific AOIs | Replacement cost; ground-up or insured loss; corridor-wide totals |
| This analysis | Transparent demonstration of an exposure–vulnerability–loss chain | Illustrative ground-up loss on synthetic assets, with explicit limits | Event-wide loss estimate; calibrated vulnerability; hydraulic intensity field |

*Sources: Copernicus Emergency Management Service, EMSR927 grading products (27 Aug 2026); this study, Section 3.*

The EMSR927 classifications could inform a future exposure or damage-validation exercise, but they cannot directly validate the illustrative loss calculation without aligning asset coverage, classification definitions, spatial extent and observation dates. The two outputs are complementary. Grading products inform what was damaged; the present analysis shows how a loss calculation is structured and where its limits lie. Neither replaces the other.

## 6. Implications

### 6.1 For catastrophe modelling practice when mechanisms remain partly unresolved

When dominant damage processes (velocity, sediment, impact and scour) are incompletely represented, and key elements of the hazard chain remain hypothetical, the appropriate output is a transparent, limited calculation. A more comprehensive estimate would require additional observations, a defensible intensity representation and explicit treatment of uncertainty.

The practical implication is that model governance must treat process uncertainty as a first-order constraint. Until the four foundations (exposure coverage, hazard intensity representation, vulnerability basis and loss definition) are aligned, numerical reconciliation with official aggregates is not informative. Status tags and the separation of model output from external benchmarks prevent the most common error in portfolio case studies: retuning a toy model until it matches a headline total.

### 6.2 For insurance and public risk financing in high-concentration mountain corridors

The event shows that a single cascading trigger in a narrow mountain corridor can produce correlated losses across commercial generation capacity, public transport infrastructure, border connectivity and household livelihoods. These losses do not fall inside one insurance portfolio or one financing mechanism.

Section 4.5 describes the sovereign contingent and emergency financing instruments available for public infrastructure. The three-layer residual-risk picture—commercial insurance and reinsurance for identifiable assets (subject to capacity and settlement constraints), sovereign contingent facilities for public infrastructure, and largely retained or humanitarian channels for household and informal risk—is developed across Sections 4.4 and 4.5 and is restated here for the corridor context. The implication for risk-finance design is that the residual is structural: increasing insurance penetration on commercial assets does not automatically cover the public or household layers, nor does it address the correlated nature of the exposure.

The difference between filed claims and total disaster effects (Section 4.4) illustrates the scope mismatch; it is not a measure of the uninsured share of national loss.

### 6.3 Further analytical extensions

**Completed: insured-loss demonstration.**  
An illustrative insured-loss layer that applies hypothetical deductibles and limits to a small set of synthetic assets is implemented in `03_insurance_financial_layer/insured_loss_layer.py`. Under the demonstration terms shown there, the calculation converts a ground-up total of approximately US$33.8 million (from a four-asset subset) into roughly US$21.4 million gross insured and US$12.4 million policyholder-retained loss. The US$12.4 million represents policyholder-retained loss under the hypothetical policy terms; it is not the insurer’s net retained loss after reinsurance. All terms are labelled as demonstration only and the output is not an estimate of actual insured loss. One hydropower asset (A0005) accounts for approximately 94% of that illustrative total; the concentration is intentional for the demonstration and is not a claim about the real portfolio.

**Next: deterministic sensitivity analysis.**  
Define a small deterministic sensitivity set that varies the assumed intensity assigned to selected assets and the vulnerability slopes, and report the resulting loss range. A separate hypothetical higher-intensity case can illustrate financial sensitivity, but should not be presented as a physically modelled transient-dam breach.

**Future: spatial exposure screening.**  
Replace manual asset-location assumptions with a spatial intersection between a modest, openly available asset layer and a clearly defined affected-area footprint. Where a defensible hazard-intensity raster is available, overlay it to assign asset-level intensity values. EMSR927 damage-grading or affected-area products can support spatial screening and comparison, but should not be treated as substitutes for flood-depth or debris-flow intensity surfaces. An observed inundation extent, a satellite-mapped affected area and a modelled hazard extent are different products.

None of these steps would produce AAL, PML or EP curves. They would, however, make the present chain more directly usable for underwriting discussion and for identifying which residual risks must still be absorbed by government, households or the international system.

An illustrative insured-loss layer that applies hypothetical deductibles and limits to a small set of synthetic assets is implemented in `03_insurance_financial_layer/insured_loss_layer.py`. Under the demonstration terms shown there, the calculation converts a ground-up total of approximately US$33.8 million (from a four-asset subset) into roughly US$21.4 million gross insured and US$12.4 million policyholder-retained loss. The US$12.4 million represents policyholder-retained loss under the hypothetical policy terms; it is not the insurer’s net retained loss after reinsurance. All terms are labelled as demonstration only and the output is not an estimate of actual insured loss. One hydropower asset (A0005) accounts for approximately 94% of that illustrative total; the concentration is intentional for the demonstration and is not a claim about the real portfolio.

---

## 7. Conclusion

The August 2026 Nepal–China border flood-debris cascade exposed a high-concentration mountain corridor to a cascading hazard whose dominant processes and full consequences remain only partly resolved. The research question asked what an insurer, reinsurer, or public risk-finance institution would need to understand about the catastrophe risk this event revealed. The analysis supports a clear, limited answer.

What is established is the structure of the risk. A high-altitude rock/ice slope failure generated a debris flood that reached populated and infrastructural assets along the Bhote Koshi–Trishuli corridor within roughly 40 minutes. Consequences concentrated because hydropower, transport, border facilities and settlements share a narrow valley. The illustrative exposure–vulnerability calculation demonstrates that a transparent ground-up loss figure can be produced from stated assumptions, but only for the synthetic assets and depth-only functions used. External figures—satellite grading, RAPIDA estimates, the NDRRMA national loss figure, the RDNA reconstruction needs, and successive NIA claims snapshots—provide independent context. They are not calibration targets and are not interchangeable with the model output or with each other.

What remains unresolved is the quantitative representation required for underwriting or fiscal decision-making. The analysis does not supply a stochastic catalogue, AAL, PML or EP curves, an intensity field that reflects velocity, sediment and impact, Nepal-calibrated vulnerability functions, or the application of policy terms. The dominant uncertainties are epistemic: incomplete process representation, uncalibrated parameters, and unresolved elements of the hazard chain (including the status of any transient dam). A single reconstructed event does not establish frequency. Filed claims capture only a fraction of total disaster effects, and the difference illustrates a scope mismatch rather than a precise insured-loss ratio. Commercial insurance and reinsurance can transfer part of the risk on identifiable commercial assets, subject to capacity and settlement constraints. Public infrastructure and dispersed household risk fall outside that layer and require separate fiscal and humanitarian arrangements.

For an insurer or reinsurer, the essential understanding is therefore threefold: the potential for correlated losses across multiple assets in a single corridor event; the limits of current process representation and the consequent need to treat any loss estimate as conditional on unresolved mechanism assumptions; and the distinction between ground-up physical loss and the insured loss that remains after policy terms and reinsurance. For a public risk-finance institution, the essential understanding is that residual risk is structural. Sovereign contingent facilities (such as the Cat DDO) and later emergency financing can address part of the public-infrastructure and response need, but they do not close the gap for household and informal livelihood losses, nor do they substitute for a clearer view of correlated exposure.

The work does not claim to have estimated event-wide ground-up, insured or residual loss. It demonstrates the analytical chain required to do so, the status discipline needed when mechanisms remain partly hypothetical, and the separation of categories required to avoid forcing agreement between incommensurable figures. The work treats process uncertainty as a first-order constraint on what can be claimed: unresolved mechanisms and incomplete intensity representation limit the analysis to a transparent, conditional calculation rather than an event-wide loss estimate. Those are the elements an insurer, reinsurer or public risk-finance institution would need to understand before treating the August 2026 cascade as a quantified catastrophe risk rather than a documented, high-concentration event whose full financial consequences remain incompletely observed.

## References

Adhikari, S., Subedi, S. et al. (2026) Tsangbu Ri slope failure triggers massive flash flood across the Himalaya and shakes the globe – the seismic observations. *Seismica*, October 2026. https://seismica.library.mcgill.ca/article/view/3433

Banjade, Y. (2026) Insurers have paid just 4 percent of Bhotekoshi flood claims. *The Kathmandu Post*, 28 October.

Copernicus Emergency Management Service (2026) EMSR927: Nepal – Flood. Grading products, 27 August 2026. European Commission.

Fuchs, S., Heiss, K. & Hübl, J. (2007) Towards an empirical vulnerability function for use in debris flow risk assessment. *Natural Hazards and Earth System Sciences*, 7(5), 495–506.

Grossi, P. & Kunreuther, H. (eds) (2005) *Catastrophe Modeling: A New Approach to Managing Risk*. Springer.

Huizinga, J., de Moel, H. & Szewczyk, W. (2017) *Global flood depth-damage functions: Methodology and the database with guidelines*. JRC Technical Reports.

ICIMOD (2026) Press release on the 26 August 2026 Bhote Koshi flood. International Centre for Integrated Mountain Development.

Jakob, M. & Hungr, O. (eds) (2005) *Debris-flow Hazards and Related Phenomena*. Springer.

National Remote Sensing Centre / ISRO (2026) Analysis of Cartosat-3 imagery identifying newly formed water bodies, Rasuwa District, Nepal, 28 August 2026.

NDRRMA / National Planning Commission (2026) *Rapid Damage and Needs Assessment: Rasuwa-Bhotekoshi Flood 2026*. Kathmandu, September.

Nepal Insurance Authority (2026) *Hydropower Insurance in Nepal: Assessment of Trends, Challenges, and Opportunities for Reform*. Kathmandu.

OCHA (2026) Nepal: Rasuwa Flood Situation Report No. 6 (as of 3 September 2026). United Nations.

Park, J. (2026) A multi-source quantitative reconstruction of the 26 August 2026 Bhote Koshi rock-ice avalanche-debris-flow-flood cascade, Nepal. EarthArXiv, September 2026. https://eartharxiv.org/repository/view/15771/

Reuters (2026) NDRRMA statement on property, housing and infrastructure losses from the Rasuwa flood, 4 September 2026.

Shugar, D.H. et al. (2021) A massive rock and ice avalanche caused the 2021 disaster at Chamoli, Indian Himalaya. *Science*, 373(6552), 300–306.

Totschnig, R., Sedlacek, W. & Fuchs, S. (2011) A quantitative vulnerability function for fluvial sediment transport. *Natural Hazards*, 58(2), 681–703.

UNOSAT (2026) Satellite-detected newly formed barrier lakes following an ice-rock avalanche in Rasuwa District, Nepal, as of 28 August 2026. United Nations Satellite Centre.

USGS (2026) M5.2 Landslide, 55 km NW of Kodari, Nepal. Event page, 26 August 2026.

World Bank (2024) Disaster Resilience Development Policy Credit with Catastrophe Deferred Drawdown Option (Cat DDO), approved 8 October 2024.