# WP-CSH-0001 — Institutionalize the Coherence Selection Hypothesis

**Date:** 2026-09-28  
**Status:** OPEN / PRE-EMPIRICAL  
**Programme:** Christian Designism  
**Candidate line:** Fundamental physics / structural selection  
**Source baseline:** CSH v3.1 (2026-09-28)  
**Disposition:** Governance work package. Substantive CSH model artifacts are to live in a dedicated repository of record once established.

## 1. Purpose

Institutionalize the Coherence Selection Hypothesis (CSH) as a design-motivated but empirically defeasible research line under the Christian Designism programme.

CSH asks whether, within explicitly specified families of physically consistent effective theories, empirically viable laws or parameters occupy nontrivial extrema of independently motivated functionals measuring structural properties such as stable bound-state diversity, longevity, and capacity for long-lived interacting subsystems.

CSH does **not** currently derive the Standard Model, derive any Standard Model parameter, explain actuality, prove Christian doctrine, identify Christ with a mathematical object, or possess a demonstrated selection operator.

The immediate objective is to create one experiment in which CSH can genuinely lose.

## 2. Programme Placement

### 2.1 Governing repository

This work package belongs in `jdlongmire/christian-designism` because CSH is a methodological Designism research proposal requiring explicit prediction, auxiliary, falsifier, and advancement discipline.

### 2.2 Repository of record

The Christian Designism repository is a governing layer and should not become the substantive CSH model repository. Establish a dedicated CSH repository of record before accumulating code, datasets, calculations, or papers.

Recommended relationship:

- **Christian Designism:** programme governance, status, preregistration pointers, falsification/advancement relationship.
- **CSH repository of record:** mathematical definitions, protocols, code, results, null results, papers.
- **Biblical WorldModel:** may reference CSH as an associated programme where relevant; it should not own CSH.
- **LRT/TRT:** associated upstream ontological programmes. CSH is downstream and empirical. It should not be incorporated into either.

## 3. Dependency Direction

Maintain three methodological levels.

| Level | Question | Standard |
|---|---|---|
| Theology | Why is there a contingent, intelligible world? | Scripture, doctrine, philosophical reasoning |
| Metaphysics | What conditions must a created world satisfy to be determinate, structured, and actual? | Conceptual and modal argument |
| Physics | Do observed laws or parameters extremize a defined, untuned functional in a specified model class? | Mathematics, preregistration, reproducible empirical test |

Theology may motivate investigation. It does not substitute for physical derivation.

**Programme guardrail:** CSH may be false while Christianity remains true. Failure at the physics level does not propagate upward as a falsification of Christian doctrine.

## 4. Theological and Metaphysical Guardrails

Retain the v3.1 distinctions:

1. The Logos is the uncreated Son of God, not a vector, eigenstate, state, operator, functional, or element of a created mathematical space.
2. Mathematical structures used by CSH describe creation and are themselves creaturely abstractions.
3. "For him" in Colossians 1:16 concerns final causality in Christ and must not be translated into a numerical optimization principle.
4. The L-I-A triad is a metaphysical description of creaturely intelligibility, not a physical theory and not a composition of God.
5. Actualization and optimization remain distinct categories. Ranking possible models does not explain why any model is actual.

## 5. Corrections Required Before CSH v3.2

### 5.1 Correct Project B.1 parameterization

v3.1 defines

```
r = m_e / (alpha^2 m_p)
```

but assigns `r_obs = 0.00544062`. This is incorrect.

Using approximately:

- `m_e = 0.511 MeV`
- `m_p = 938.272 MeV`
- `alpha = 1/137.036`

gives

```
alpha^2 m_p ≈ 0.04996 MeV
r_obs ≈ 0.511 / 0.04996 ≈ 10.23
```

The present code therefore scans around an electron mass far below the physical value.

**Required correction:** Prefer the transparent scan variable

```
x = m_e / m_e,observed
```

with `x = 1` denoting the observed electron mass. Preserve the dimensionless `r` formulation only if needed analytically and calculate its observed value correctly.

### 5.2 Correct the scaffold energy conversion

The placeholder expression

```python
Z**2 * ALPHA**2 * m_e_mev * 1e6 / 2
```

already produces an energy in eV. The subsequent division by `27.211` converts the numerical value to Hartree while the result is compared with an eV threshold.

**Required correction:** remove the inconsistent conversion and explicitly document all units.

### 5.3 Relabel the present code

The existing Appendix C code is a hydrogenic diagnostic scaffold. It is not a FAC implementation and cannot establish chemically viable neutral-atom diversity.

Preserve it only as a toy diagnostic with an explicit warning. Do not report its output as Project B.1 evidence.

## 6. Redesign of Project B.1

### 6.1 Problem with the current observable

The proposed count

> neutral atoms with at least one electronic bound state above 1 eV

is likely structurally biased toward monotonic behavior as electron mass increases, because Coulomb binding energies scale approximately upward with electron mass. Mere existence of one bound electron is too weak a proxy for chemical diversity.

A null or monotonic result under this observable must be recorded as such. It must not be repaired post hoc merely to recover an extremum near the observed electron mass.

### 6.2 Revised observable hierarchy

Develop B.1 in stages:

1. existence of at least one electronic bound state;
2. stability of a neutral many-electron configuration;
3. number of bound electrons;
4. ionization-energy windows;
5. differentiated valence structures;
6. chemically distinguishable stable structures.

Each level requires an operational definition fixed before inspecting whether the observed parameter lies near an extremum.

### 6.3 Competing constraints

An informative interior extremum normally requires competing effects. Identify, derive, and justify such effects independently rather than inserting penalty terms because they move the optimum toward observation.

### 6.4 Pre-registration

Before the substantive scan, preregister:

- parameter range and sampling strategy;
- fixed constants and why they are fixed;
- nuclear dataset and isotope-selection rules;
- operational definition of each observable;
- thresholds and sensitivity ranges;
- computational method and software versions;
- definition of an extremum;
- definition of "near";
- sharp-maximum versus plateau criteria;
- negative controls;
- success, null, and adverse-result criteria.

## 7. Anti-Tuning Requirement

This is a central methodological constraint for CSH.

A hypothesis proposing that physical parameters are selected by coherence cannot explain fine tuning by fine-tuning the definition of coherence.

Candidate functionals must therefore satisfy an anti-tuning discipline:

1. definitions are fixed before inspecting target-location results;
2. terms require independent physical or mathematical motivation;
3. weights may not be introduced solely to place the observed point near an extremum;
4. reasonable alternative operationalizations must be reported;
5. sensitivity of the extremum to those alternatives must be quantified;
6. arbitrary target points should not be equally recoverable by modest functional redesign;
7. post-result modifications are versioned and identified as post hoc unless independently motivated.

This anti-tuning requirement is itself a potentially substantive methodological contribution of CSH.

## 8. Negative Controls

Apply the same methodology to controls where no privileged optimum is expected.

The purpose is to determine whether the analysis pipeline generically manufactures extrema.

At minimum, test:

- alternative admissible parameter locations;
- perturbed functional definitions fixed without reference to the observed point;
- synthetic model families with known structure;
- shuffled or surrogate targets where mathematically meaningful.

A method capable of placing arbitrary targets near an extremum does not provide evidence for coherence selection.

## 9. Success and Null Criteria

Before execution, define quantitative criteria.

Distinguish at least:

- **sharp interior extremum containing the observed value:** candidate support, subject to robustness and controls;
- **broad plateau containing the observed value:** evidence of robustness/viability, not selection;
- **monotonic functional:** no support from that functional;
- **extremum materially displaced from observation:** adverse result for that functional;
- **extremum unstable under reasonable operational definitions:** functional not sufficiently well-defined to support CSH;
- **target recoverable only after post hoc additions or weighting:** degenerating auxiliary behavior.

No result from a single conditional scan constitutes a derivation of a physical constant "from nothing."

## 10. Falsification Ladder

CSH should be progressively weakened, reformulated, or abandoned as an empirical selection programme if:

1. independently motivated candidate functionals are predominantly monotonic or featureless;
2. extrema move arbitrarily under reasonable operational definitions;
3. observed parameters are unexceptional relative to appropriate controls;
4. arbitrary parameter points can readily be made extremal by modest functional redesign;
5. explanatory success requires post hoc terms or weights whose primary role is to recover the observed point;
6. purported extrema disappear under higher-fidelity physics;
7. multiple independently motivated coherence measures produce mutually incompatible preferred regions without an independent rule for adjudication.

Null and adverse results are first-class programme artifacts and must remain in the corpus.

## 11. Research Architecture

### CSH-0 — Formalization

Define:

- candidate model families `T`;
- admissibility and consistency conditions;
- parameter-space structure and measures;
- observables;
- candidate functionals;
- regulator/cutoff treatment;
- anti-tuning rules;
- preregistration standard.

### CSH-1 — Toy Models

Determine whether independently motivated structural functionals produce nontrivial interior extrema in finite-dimensional systems whose mathematics is controlled.

Purpose: establish that the selection concept is mathematically informative before making Standard Model claims.

### CSH-2 — Atomic/Chemical Parameter Scans

Begin with electron mass, fine-structure constant, and selected mass ratios.

Run one-dimensional scans before joint scans. Preserve conditionality: fixing other parameters is an assumption, not a derivation.

### CSH-3 — Robustness and Controls

Test whether extrema:

- survive defensible alternative definitions;
- survive higher-fidelity calculations;
- remain exceptional against negative controls;
- are not artifacts of cutoffs, parameterization, or chosen measure.

### CSH-4 — Higher-Energy Extensions

Only after CSH-0 through CSH-3 demonstrate nontrivial success should the programme attempt Standard Model or GUT parameter relations.

## 12. Disposition of Current Projects

### Project B.1 / Atomic stability

**Disposition:** PRIORITY, REVISE BEFORE RUN.

It is the first empirical gate after correction and preregistration.

### Generations from proton stability

**Disposition:** DEFER.

The question is highly model-dependent. Proton lifetime depends on GUT representation, symmetry-breaking scale, threshold corrections, Yukawa structure, flavor mixing, and effective operators. Avoid the present formulation that asks whether three generations "uniquely permit" the observed bound until a specific model class makes that question well-defined.

### Modified Born rule

**Disposition:** QUARANTINE / SPECULATIVE.

No present derivation connects a model-space coherence functional to quantum measurement probabilities. Any modification faces normalization, composition, contextuality, no-signalling, relativistic compatibility, and precision constraints.

It is an additional hypothesis, not presently a consequence of CSH. It must not be used as an early empirical test of the core conjecture.

### Operator formulation

**Disposition:** CONDITIONAL FUTURE WORK.

Do not presently list self-adjointness, compactness, ground-state existence, or uniqueness as unconditional open problems. The theory space `T` has not been shown to carry a Hilbert-space structure.

Use the conditional formulation:

> If a later representation of T supplies an appropriate Hilbert-space structure and independently motivates an operator formulation, determine whether a corresponding operator can be rigorously defined and whether the relevant spectral properties follow.

## 13. Relationship to LRT and TRT

CSH should remain organizationally distinct.

- **LRT** addresses the reality and preconditions of logical order.
- **TRT** addresses Logic, Information, and Action/Actualization as irreducible ontological categories.
- **CSH** asks a downstream empirical question about structural extrema within created physical parameter/model spaces.

LRT/TRT may supply philosophical context. Their truth must not be made dependent on a favorable CSH result, and CSH may not borrow their metaphysical claims as empirical evidence.

## 14. Deliverables

- [ ] Establish dedicated CSH repository of record using the Longmire research-programme conventions.
- [ ] Preserve CSH v3.1 unchanged as a provenance artifact.
- [ ] Produce CSH v3.2 incorporating the corrections and dispositions in this WP.
- [ ] Replace `r_obs` error and audit every numerical constant/unit in Appendix C.
- [ ] Separate diagnostic toy code from production atomic-structure code.
- [ ] Define the B.1 observable hierarchy.
- [ ] Write a B.1 preregistration before executing the target scan.
- [ ] Define negative controls and anti-tuning tests.
- [ ] Define quantitative success/null/adverse criteria.
- [ ] Establish null-result retention policy.
- [ ] Add a CSH pointer/status entry to Christian Designism once the repository of record exists.
- [ ] Evaluate whether BWM should expose CSH only as an associated-programme link.
- [ ] Defer GUT/generation work pending model-class definition.
- [ ] Quarantine modified-Born-rule work from the core empirical programme.
- [ ] Make operator-theoretic work explicitly conditional.

## 15. Acceptance Criteria

This WP is complete when:

1. CSH has a repository of record;
2. v3.1 is preserved;
3. v3.2 corrects the mathematical/code errors;
4. B.1 has a preregistered protocol with independently motivated observables;
5. success, null, adverse, and falsification criteria are fixed before target inspection;
6. negative controls are specified;
7. no operator ontology is assumed without mathematical warrant;
8. speculative Born-rule work is separated from the core programme;
9. CSH's relationship to Christian Designism, BWM, LRT, and TRT is documented;
10. the first empirical test is capable, by construction, of returning a result that counts against CSH.

## 16. Governing Principle

> CSH must earn every scientific claim through untuned definitions, rigorous derivation, reproducible calculation, and empirical risk.

The next substantive move is not to add more selection theory. It is to construct one preregistered experiment in which CSH can genuinely lose.

## 17. Provenance

This work package captures the author's CSH v3.1 proposal and the 2026-09-28 critical review of its programme architecture, Project B.1 parameterization and code, empirical observables, anti-tuning requirements, negative controls, falsification ladder, and corpus disposition.

Human-curated, AI-enabled (HCAE). Final research positions remain subject to author adjudication.
