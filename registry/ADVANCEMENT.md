# Advancement Register

Charter [§9](../charter/consilience-is-not-consensus.md#9-conditions-of-abandonment), second half. Introduced in v1.1.

Falsifiers alone are half a specification. A programme that states only what would sink it, and never what would raise it, can claim progress on any favourable result after the fact. These are the thresholds, fixed in advance.

## Status vocabulary

| Status | Meaning |
|---|---|
| `OPEN` | Threshold stated, not met. |
| `PARTIAL` | Some but not all conjuncts satisfied. Detail recorded. |
| `MET` | Threshold satisfied. The programme's comparative standing changes and the charter records it. |

---

## AD-001 – Demarcation criterion applied in advance across three specimen classes

**Status:** `PARTIAL`
**Weight:** Decisive. This is the condition that converts functional maturity from an interpretive stance into a source of advance commitments.

**Threshold.** A demarcation criterion applied in advance to at least three specimen classes, returning at least one verdict the programme would have preferred otherwise, and holding without reassignment.

**Conjuncts, tracked separately.**

| Conjunct | State |
|---|---|
| A criterion exists | **Satisfied.** Functional necessity, offered as provisional at charter §7, v1.1. |
| Applied to ≥3 specimen classes | **Partial.** Two clean applications: crater populations and molecular clock divergence, both assigned to elapsed history. Radiogenic inventory is claimed as a third but is contested; see below. Stellar main-sequence position and sediment fabrics are named as requiring case-by-case treatment and have not been done. |
| ≥1 unwelcome verdict | **Satisfied, arguably twice.** Crater populations assigned to elapsed history places the planetary bombardment record inside the young timeframe. Molecular clock divergence assigned to elapsed history places observed sequence divergence there. Neither is a comfortable result. |
| Applied *in advance* | **Satisfied for the two exclusions.** Both were stated as consequences of the rule rather than derived from a desired answer. |
| Holds without reassignment | **Open.** Cannot be assessed until the criterion has been under pressure for some time. This conjunct is a matter of conduct over time, not a one-off check. |

**Why not `MET`.** The third specimen class is the problem, and it is the one the programme most needs. Radiogenic inventory is offered at charter §6.2 and §7 as passing the criterion, but the pass covers parent nuclides only. Daughter products do not obviously pass, and if they fail, the verdict runs against the auxiliary the criterion was introduced to support. See [I-0006](../issues/open/I-0006-daughter-products-fail-functional-necessity.md).

Until that is adjudicated, the criterion has three clean applications only if the contested one is counted, and counting a contested application to reach a threshold is the manoeuvre this register exists to prevent.

**What would move it to `MET`.** Adjudicate I-0006 honestly, whichever way it goes. Then apply the criterion to stellar main-sequence position and to sediment fabrics, publishing the assignment before checking what the framework would prefer. A criterion that survives an adverse ruling on its own founding case is worth considerably more than one that has only ever been applied where it agrees.

---

## AD-002 – Corroboration of a prediction whose content was unavailable at registration

**Status:** `OPEN`
**Weight:** High. This is the Lakatosian novelty condition stated operationally.

**Threshold.** Corroboration of a registered prediction whose content was not available to the framework at the time of registration. Accommodation of known data does not qualify.

**Registry obligation.** Charter §9 requires the distinction be marked **at entry rather than at adjudication**. This is the single most important procedural rule in the whole register set, because marking novelty after a favourable result is how accommodation launders itself into prediction.

Implemented as a required field on every entry reaching `REGISTERED` in [`PREDICTIONS.md`](PREDICTIONS.md):

> **Novelty at registration:** `NOVEL` (content not available to the framework) | `KNOWN` (data already in hand) | `PARTIAL` (state which part)

An entry registered without this field cannot later be counted toward AD-002.

**Current state.** No prediction has reached `REGISTERED`, so nothing is eligible. P-001 is instructive: charter v1.1 correctly declines to claim predictive priority for the ringwoodite result, which means P-001 will register as `KNOWN` and cannot serve AD-002. That is the right outcome and it cost the programme its only claimed corroboration, which is what an honest register is for.

---

## AD-003 – Hydrotectonic thermal budget closing without a purpose-built auxiliary

**Status:** `OPEN`
**Weight:** High, and higher than it looks. This condition is what would show the heat problem to be specific to accelerated decay rather than endemic to catastrophic reconstruction generally.

**Threshold.** A hydrotectonic thermal budget that closes without an auxiliary introduced for that purpose alone.

**Note on a correction this condition forces.** Charter §9 v1.1 states this as an outstanding condition, which entails that the budget does **not** presently close. The auxiliary register previously recorded A-003 as supplying "a thermal budget that closes." That was an overstatement, made at repository creation and not by the author, and it has been corrected. The charter's more cautious position governs.

**What closing means, stated so that it cannot be claimed loosely.**

1. The full energy budget is accounted: gravitational potential energy released, partitioned across dissipation channels, with the disposal path for each channel named
2. Disposal is traced to the planetary radiative boundary, not merely relocated within the Earth. The failure of accelerated decay was a disposal failure, and a mechanism that only redistributes has not answered it
3. Every parameter enabling the closure is independently motivated by the model's own physics rather than fitted to produce the closure
4. The result survives the circularity check: no derived parameter appears in its own derivation

Condition 3 is the one that decides whether this is advancement or the same move the programme declined in A-002 wearing different clothes.

**Upstream.** [`lines/geology.md`](../lines/geology.md), and Phase 4 (thermal stability) of the hydrotectonics roadmap.

---

## Standing assessment

Three conditions. One `PARTIAL`, two `OPEN`.

AD-001 moving to `PARTIAL` on the strength of charter v1.1 is the first genuine advance the register has recorded. It is also immediately qualified by I-0006, which is the criterion turning on the case it was built to serve. That is uncomfortable and it is exactly what charter §7 committed to when it wrote that an unwelcome verdict stands.
