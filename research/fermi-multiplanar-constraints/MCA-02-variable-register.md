# MCA-02: Candidate variable and dependency register
Status: INITIAL ONTOLOGY, uncalibrated. Date: 2026-11-21.

## Typing
- **N** necessary under a stated target/pathway; **E** enabling or favorable; **H** hypothesis-dependent; **O** observation process.
- **Measured** means a relevant observable exists; it does not mean the complete conditional probability is known.
- **Unknown** marks an unconstrained transition rate, not zero probability.

| ID | Plane | Variable / condition | Type | Evidence status | Candidate parents / dependencies |
|---|---|---|---|---|---|
| U01 | Cosmological | stable nuclei and chemically diverse matter | N for known biochemistry | physics constrained; counterfactual distribution unknown | fundamental constants, interaction structure |
| U02 | Cosmological | long-lived stellar energy sources | N for modeled stellar pathways | observed; alternative pathways not excluded | U01, gravity, nuclear reaction rates |
| G01 | Galactic | heavy-element enrichment | E/N for terrestrial rocky pathways | observed/model-dependent | stellar history, nucleosynthesis, galactic epoch |
| G02 | Galactic | hazardous transient exposure | E | observed/model-dependent | star formation, galactic position, time |
| S01 | Stellar | usable stellar lifetime | E/N for specified pathway | observed/model-dependent | stellar mass, composition, U02 |
| S02 | Stellar | activity and irradiance variability | E | measured for sampled stars | stellar age, rotation, magnetic activity |
| P01 | Planetary | persistent solvent and energy gradients | H/N for specified biochemistry | partial observations; universal requirement unknown | S01, S02, orbit, atmosphere, geophysics |
| P02 | Planetary | long-term climate/geochemical cycling | E | Earth evidence; cross-world prevalence unknown | P01, interior dynamics, atmosphere |
| B01 | Prebiotic | origin of a self-sustaining replicating system | N for evolutionary pathway | one historical lineage; rate unknown | P01, P02, chemistry, time |
| B02 | Biochemical | sustainable heredity and metabolism | N for known life | observed on Earth; origin pathway unknown | B01, resources, environmental stability |
| E01 | Evolutionary | complex multicellular organization | H for human-like pathway | Earth history observed; transition rate uncertain | B02, oxygenation, ecology, contingency |
| E02 | Evolutionary | persistence through extinction bottlenecks | E | Earth record; general distribution uncertain | G02, P02, E01 |
| C01 | Cognitive | flexible general cognition | H | observed in multiple Earth lineages; rate uncertain | E01 or alternate pathways, ecology |
| C02 | Technological | cumulative culture and material technology | N for defined technological target | one confirmed technological lineage | C01, anatomy, ecology, resources |
| V01 | Civilizational | persistence and activity duration | E | one censored human case; distribution unknown | C02, hazards, institutions |
| V02 | Civilizational | expansion / signaling behavior | H | unknown extraterrestrial distribution | V01, incentives, energy, engineering |
| O01 | Observational | survey sensitivity and search coverage | O | measured for particular searches | instrument, target selection, frequency, time |
| O02 | Observational | signal or artifact detection probability | O | model-dependent | V02, O01, propagation, false-positive controls |

## Structural constraints
1. U01/U02 are universe-level shared conditions, not independent per-star draws.
2. G01/G02 vary jointly with location and galactic epoch.
3. S01/S02 and planetary environment share stellar ancestry; naive marginal multiplication double-counts effects.
4. B01/B02 are not assigned frequencies from one Earth history.
5. E01/C01 are pathway-specific; alternative technological routes must remain admissible.
6. V02 and O01/O02 govern observation. Absence of detection is evidence only after search completeness is specified.
7. Conditioning on observers (Earth as a selected observation) must be explicit.

## First model architecture
Hierarchical generative model: global U -> galaxy-time environments G -> star-system conditions S,P -> biochemical emergence B -> evolutionary/cognitive transitions E,C -> civilization V -> observational process O. Permit latent common causes and alternative pathways. Compare (a) hierarchical Bayesian network, (b) event-history / hazard model, (c) robust imprecise-probability bounds. Propagate uncertainty, do not assign unjustified point estimates.

## Testable and non-testable elements
- Testable now: exoplanet occurrence and host-star demographics; survey completeness; some stellar/galactic hazards.
- Potentially testable: independent biosignatures, technological artifacts, additional abiogenesis examples.
- Currently weakly identifiable: abiogenesis hazard, intelligence-transition distribution, civilization lifetimes.
- Counterfactual fundamental-constant distributions: not empirically measured; avoid claims of numerical probability without a justified reference measure.

## Adversarial questions
- Which listed requirements are actually necessary versus Earth-specific?
- Are any filters consequences of the same underlying cause?
- How do results change under alternate biochemical pathways?
- Can selection effects fully explain Earth's early life and late technology?
- What likelihood does a null SETI observation supply given actual survey coverage?
- Does any conclusion remain robust to broad, defensible prior families?

## Exit criteria for MCA-02
Each variable requires operational definition, units/domain, cited source, evidence grade, dependence justification, uncertainty family, and falsification or observational update pathway before numerical use.
