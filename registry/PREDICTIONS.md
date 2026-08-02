# Prediction Registry

The enforcement instrument for [`charter/consilience-is-not-consensus.md`](../charter/consilience-is-not-consensus.md) §7 and §9. A prediction that is not entered here is not a prediction of this programme, and the charter may not cite it as one.

## Rules

1. **Append, never rewrite.** An entry's `Claim` and `Falsifier` fields are frozen once the status reaches `REGISTERED`. Corrections are made by superseding the entry, with the superseded entry retained and marked.
2. **Falsifier before registration.** An entry cannot reach `REGISTERED` without a falsifier stated in terms that a hostile reader could apply.
3. **Resolution date before registration.** Open-ended predictions are unadjudicable and count as accommodation under the charter's own criterion.
4. **Novelty marked at entry, never at adjudication.** Charter §9 v1.1 requires this explicitly, and it is the most important procedural rule in the register set: marking novelty after a favourable result is how accommodation launders itself into prediction. Every entry reaching `REGISTERED` carries a **Novelty at registration** field valued `NOVEL` (content not available to the framework at registration), `KNOWN` (data already in hand), or `PARTIAL` (stating which part). An entry lacking the field cannot later be counted toward [AD-002](ADVANCEMENT.md#ad-002--corroboration-of-a-prediction-whose-content-was-unavailable-at-registration).
5. **Status is evidence-driven.** `CORROBORATED` requires a cited observation. `FAILED` is recorded with the same care as `CORROBORATED`, and the charter is amended accordingly.

## Status vocabulary

| Status | Meaning |
|---|---|
| `DRAFT` | Claim stated, falsifier or resolution date missing. Not citable by the charter. |
| `REGISTERED` | Claim, falsifier and resolution date fixed. Adjudicable. |
| `CORROBORATED` | Resolved in the programme's favour against the registered falsifier. |
| `FAILED` | Resolved against the programme. Charter amendment required. |
| `SUPERSEDED` | Replaced by a later entry; retained for the record. |

---

## P-001 – Pre-loaded deep-water budget in the mantle transition zone

| Field | Value |
|---|---|
| **Line** | Geochronology / functional maturity |
| **Status** | `DRAFT` |
| **Claim** | Functional maturity anticipates geological architecture delivered stocked rather than accumulated, including a substantial pre-loaded deep-water budget in the mantle transition zone. The expectation concerns **realized hydration**, not storage capacity; capacity to roughly 2.5 wt% in wadsleyite and ringwoodite was already established by theory and high-pressure experiment. |
| **Evidence cited in charter** | Pearson et al. (2014), first terrestrial ringwoodite as a diamond inclusion from Juína, resolving the question locally toward hydration at approximately 1 wt%. |
| **Novelty at registration** | `KNOWN`. Charter v1.1 explicitly declines any assertion of predictive priority. This entry cannot serve [AD-002](ADVANCEMENT.md#ad-002--corroboration-of-a-prediction-whose-content-was-unavailable-at-registration). |
| **Falsifier** | *Not yet stated in registrable form.* Candidate: systematic accumulation of transition-zone hydration measurements converging on values consistent with progressive subduction-driven hydration rather than an initial endowment, with no residual requiring a pre-loaded budget. |
| **Resolution date** | Not set. |
| **Prior blocking issue** | [I-0002](../issues/resolved/I-0002-pearson-priority-verification.md), **resolved** at charter v1.1. The author restated the claim at the strength the evidence supports and withdrew the priority assertion rather than defending it. The entry is no longer blocked on that question. |
| **Why it is not yet `REGISTERED`** | Falsifier and resolution date outstanding. The claim itself is now correctly scoped, so registration is a matter of finishing the specification rather than resolving a dispute. |

---

## P-002 – Hydration textures required by Global Flood Hydrotectonics

| Field | Value |
|---|---|
| **Line** | Geology |
| **Status** | `DRAFT` |
| **Claim** | The hydraulic-collapse mechanism requires specific hydration textures along detachment horizons, and predicts their presence where the model requires block motion to have occurred. |
| **Falsifier** | *Not yet stated.* Charter §9 asserts one exists ("predicts hydration textures that are not observed where the model requires them") without specifying the horizon, texture class, or sampling criterion. |
| **Resolution date** | Not set. |
| **Blocking issue** | [I-0001](../issues/open/I-0001-gfh-falsifier-list.md). The source model is in Phase 0 of its own roadmap with the one-page falsifier list still outstanding. |
| **Upstream** | [`lines/geology.md`](../lines/geology.md) → `jdlongmire/global-flood-hydrotectonic-model` |
| **Why it is not yet `REGISTERED`** | The charter currently cites this prediction as adjudicable. It is not. Either the upstream falsifier list lands, or charter §§7 and 9 must be softened to "stated, pending registration." This is the single largest traceability gap in the programme as of repository creation. |

---

## P-003 – Persistence of the H0 and S8 tensions under single-parameter extensions

| Field | Value |
|---|---|
| **Line** | Astronomy / cosmology |
| **Status** | `DRAFT` |
| **Claim** | The Hubble constant and structure-growth tensions will not resolve under single-parameter extensions to the standard cosmological model. |
| **Falsifier** | Stated in the charter to have been committed in advance. *The committing document has not been located.* |
| **Resolution date** | Stated in the charter to exist. *Not located.* |
| **Blocking issue** | [I-0003](../issues/open/I-0003-cosmology-prereg-location.md) |
| **Why it is not yet `REGISTERED`** | Charter §7 describes this as "the correct instrument for the purpose" and conditions its value on being "adjudicated rather than revised." An unlocated pre-registration cannot be adjudicated and cannot be shown not to have been revised. Either the original document is recovered and deposited here verbatim with its timestamp, or the prediction is re-registered from today with a new resolution date and no priority claim. |

---

## P-004 – Genomic degradation constrains elapsed generational time

| Field | Value |
|---|---|
| **Line** | Genetics |
| **Status** | `DRAFT` |
| **Claim** | Deleterious mutations accumulate faster than purifying selection removes them, constraining the duration over which extant genomes can have persisted (Sanford 2005). |
| **Falsifier** | *Not yet stated.* Requires a quantitative form: a specified selection-efficiency threshold above which the load argument fails, and the empirical measurement that would establish it. |
| **Resolution date** | Not set. |
| **Note** | The charter correctly records this as contested within population genetics and correctly locates the contest as empirical. That is the right posture, but it does not by itself make the line adjudicable for this programme. |

---

## P-005 – Ecological zonation predicts stratigraphic position

| Field | Value |
|---|---|
| **Line** | Paleontology |
| **Status** | `DRAFT` |
| **Claim** | Fossil succession reflects pre-catastrophe ecological zonation, hydrodynamic sorting, differential mobility, and inundation sequence, and therefore predicts patterns relating ecological setting to stratigraphic position and to biogeographic distribution. |
| **Falsifier** | *Not yet stated.* Requires operationalization: a named taxon set, a measurable zonation proxy, and the distribution that would count against the account. |
| **Resolution date** | Not set. |
| **Note** | This is the least operationalized line in the programme. It is stated qualitatively in charter §6.3 and generates no advance commitment in its present form. |

---

## Standing assessment

Five entries. **Zero at `REGISTERED`.**

This is the honest state of the programme at repository creation, and recording it is the point of the instrument. Charter §7 claims the programme "has produced testable content" and "has recorded some corroborations." Both claims are defensible in substance and neither is yet enforceable through this registry. Charter §9 makes registered-prediction failure a condition of abandonment, which is unenforceable while the register is empty of registered predictions.

Closing P-001 and P-002 to `REGISTERED` is the highest-value near-term work in the programme, ahead of any new disciplinary content.
