# WP-MCA-0001: Multiplanar Constraint Analysis of the Fermi Paradox

**Status:** PROPOSED / research framing only  
**Date:** 2026-11-21  
**Owner:** James D. Longmire  
**Programme:** Christian Designism  
**Research posture:** Methodologically neutral constraint accounting; no design inference is presumed or required.

## Research question
Does the apparent Fermi Paradox survive a comprehensive, dependency-aware accounting of conditions necessary for the emergence, persistence, expansion, and detectability of technological intelligence?

## Initial conjecture
The expectation that technologically intelligent civilizations should be abundant may rest on incomplete treatment of interacting constraints across distinct planes. This is a conjecture to test, not a result.

## Definitions and boundaries
- **Plane:** A domain of constraints and variables operating at a distinguishable physical or organizational scale.
- **Viability:** Satisfaction of explicitly specified necessary conditions for the target outcome.
- **Target outcome:** Technologically capable intelligence, with emergence, persistence, expansion, and observability modeled separately.
- **Joint probability:** The probability that all relevant conditions obtain, using conditional distributions; independence is not presumed.
- **Selection effect:** Conditioning on our existence as observers, which must be included in inference.
- Cosmological constants are shared universe-wide; they cannot be naively multiplied as independent planet-level filters.
- The Fermi question is principally about expected *detectable* civilizations, not merely life-bearing worlds.

## Work breakdown
| ID | Deliverable | Acceptance criterion |
|---|---|---|
| MCA-01 | Systematic literature review and provenance ledger | Primary works located; coverage and conflicts recorded; no claims of exhaustive search without documented protocol |
| MCA-02 | Ontology of constraint planes | Variables, units, necessary/sufficient/enabling classifications, evidence strength, and unknowns |
| MCA-03 | Directed dependency graph | Within-plane and cross-plane dependencies, common causes, correlated constraints, and selection effects |
| MCA-04 | Probabilistic model specification | Explicit conditional factorization, priors/likelihoods, uncertainty intervals, and alternative pathways |
| MCA-05 | Sensitivity and adversarial analysis | Range and structural sensitivity, prior robustness, alternate hypotheses, and critic review |
| MCA-06 | Reproducible research synthesis | Code/data provenance, assumptions, uncertainty disclosures, conclusions, and unresolved questions |

## Candidate planes (provisional)
1. Cosmological: constants, stable matter, chemical and stellar feasibility.
2. Galactic: metallicity, radiation hazards, galactic dynamical environment.
3. Stellar: stellar lifetime, variability, planetary system architecture.
4. Planetary: stable environments, solvents, energy, cycling, geology, atmosphere.
5. Prebiotic and biochemical: plausible origin pathways, replication, compartmentalization, metabolism.
6. Evolutionary and ecological: major transitions, complexity, extinction and contingency.
7. Cognitive and technological: cognition, cumulative culture, technological capability.
8. Civilizational and observational: longevity, expansion, signaling, detectability, survey completeness.

## Model skeleton
Let U be universe-level parameters, X_j local planetary-system conditions, T_j technological emergence, L_j longevity, and D_j detectability. Estimate the posterior predictive distribution of N_detectable conditional on observational evidence and observer selection, rather than multiplying marginal rarity claims. For any ordered conditions A_1...A_n:
P(A_1 ∩ ... ∩ A_n) = P(A_1) × ∏_{i=2}^n P(A_i | A_1,...,A_{i-1}).
This identity does not itself supply any probabilities.

## Evidence discipline
Label each statement as empirical measurement, established derivation, model-dependent inference, conjecture, or unknown. Search for primary sources before secondary summaries. Do not assign numerical probabilities to unmeasured transitions without transparent sensitivity ranges. Record contrary evidence. No fabricated citations. Separate a hypothesis's explanatory scope from its evidentiary support.

## Decision criteria
- **Paradox attenuated:** a defensible parameter region yields low expected detectable civilizations, with disclosed sensitivity.
- **Paradox persists:** well-constrained parameters robustly predict widespread detectability despite null observations.
- **Underdetermined:** present evidence cannot distinguish these regimes.
These are provisional adjudication criteria, not precommitted findings.

## First research sprint
1. Build literature coverage matrix for Drake-equation uncertainty, Sandberg-Drexler-Ord (2018), Rare Earth, Bayesian abiogenesis, evolutionary transitions, galactic habitability, and SETI selection functions. Verify each primary source and exact bibliographic metadata.
2. Build variable register with evidence confidence and cross-plane dependencies.
3. Identify which variables are measurable, bounded, or unconstrained.
4. Draft competing model architectures and falsification/criticism protocol.
5. Return a gap analysis before numerical modeling.

## Governance
This work package is a proposed sub-line, not an alteration to the programme's hard core or existing prediction/falsifier registers. Any eventual registered prediction follows the repository's existing preregistration and change-control conventions. Human-curated, AI-enabled (HCAE).
