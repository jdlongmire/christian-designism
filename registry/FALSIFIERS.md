# Falsifier Register

Charter [§9, Conditions of Abandonment](../charter/consilience-is-not-consensus.md#9-conditions-of-abandonment), carried as tracked entries with current status.

The charter states that a programme specifying no falsifiers has forfeited the claim to scientific status. This file is where that claim is made good or shown to be empty. A falsifier stated in a paper and never tracked is a rhetorical gesture. A falsifier tracked here, with a status that can read `TRIGGERED`, is a commitment.

## Status vocabulary

| Status | Meaning |
|---|---|
| `OPEN` | Condition specified, not met, programme continues. |
| `UNMET` | Condition is one the programme is currently failing, on a clock rather than immediately fatal. |
| `TRIGGERED` | Condition met. Charter amendment or programme abandonment required. |
| `RETIRED` | Condition resolved in the programme's favour and no longer live. |

---

## F-001 – Formal contradiction between load-bearing commitments

**Status:** `OPEN`
**Severity:** Immediately fatal. No explanatory yield elsewhere offsets it.

A demonstrated contradiction of the form P and not-P between two commitments in [`programme/hard-core.md`](../programme/hard-core.md).

**How it would be established.** A written derivation, from the hard-core commitments as stated, of a proposition and its negation. The derivation must use the commitments as the programme states them rather than a critic's paraphrase, which is why the hard core is maintained as a separate document with numbered commitments.

**Current assessment.** None demonstrated. Note that this is the weakest of the four conditions, because internal consistency is cheap and the charter says so directly (§7: "Coherence is a low bar").

---

## F-002 – Continued failure to supply a demarcation criterion

**Status:** `UNMET`
**Severity:** Fatal on a longer timescale.

If no principled and operational test distinguishes created-mature initial state from post-deployment process residue, functional maturity (A-001) cannot generate advance predictions about any specific system and should be abandoned as an unfalsifiable accommodation.

**Why `UNMET` rather than `OPEN`.** The charter is explicit that this is "the condition on which the framework's scientific standing turns, and it is the one currently unmet." The programme is failing this condition now. It is not immediately fatal because the criterion is a research task rather than a discovered obstacle, but the clock is running and the charter admits it.

**Movement at v1.1.** A candidate criterion now exists: **functional necessity**, offered as provisional at charter §7. A feature is constitutive if the system could not discharge its function at the moment of deployment without it. The candidate is real progress and is assessed against its own requirements in [`programme/demarcation/`](../programme/demarcation/). It does not retire this condition, for two reasons. It is offered as provisional by the author rather than as settled, and its application to the programme's founding case is contested at [I-0006](../issues/open/I-0006-daughter-products-fail-functional-necessity.md).

**What would retire it.** An operational test, applicable to a specimen in hand, that yields a determinate reading of created-state versus elapsed-process before the answer is known from other sources, and that survives application to cases where the verdict is unwelcome. The threshold is stated as [AD-001](ADVANCEMENT.md#ad-001--demarcation-criterion-applied-in-advance-across-three-specimen-classes).

**What would trigger it.** Sustained failure to produce such a test, or a demonstration that no such test is possible in principle given the framework's commitments. The second would be the stronger result and is the argument a serious critic should be making.

**Reach.** This condition is not confined to geochronology. The functional-maturity reply to the concordance objection depends on the same criterion, and I-0006 raises the possibility that the criterion contradicts it. Charter §8.3 v1.2 states both dependencies in the paper itself. F-002 is therefore load-bearing for the programme's answer to its strongest objection, not only for its geochronological position.

---

## F-003 – Systematic failure of registered predictions

**Status:** `OPEN` (unenforceable as of repository creation)
**Severity:** Line-by-line rather than programme-wide, unless failures are systematic.

Named in the charter:

| Prediction | Registry entry | Registry status |
|---|---|---|
| Pre-loaded architecture expectations fail as deep-Earth and planetary data accumulate | [P-001](PREDICTIONS.md#p-001--pre-loaded-deep-water-budget-in-the-mantle-transition-zone) | `DRAFT` |
| Global Flood Hydrotectonics hydration textures absent where the model requires them | [P-002](PREDICTIONS.md#p-002--hydration-textures-required-by-global-flood-hydrotectonics) | `DRAFT` |
| Registered cosmological forecast resolves against pre-committed falsifiers by its stated date | [P-003](PREDICTIONS.md#p-003--persistence-of-the-h0-and-s8-tensions-under-single-parameter-extensions) | `DRAFT` |

**Honest statement of current standing.** This condition is presently unenforceable, because no prediction in the register has reached `REGISTERED`. The charter conditions abandonment on registered-prediction failure while the register contains no registered predictions. That is a gap in the programme's own falsification machinery, discovered at repository creation and recorded here rather than quietly repaired.

Moving P-001 and P-002 to `REGISTERED` is what makes F-003 real.

---

## F-004 – Exegetical failure of the motivating constraints

**Status:** `OPEN`
**Severity:** Removes the programme's motivating warrant entirely.

A demonstration that the biblical text does not in fact assert the historical propositions the programme treats as constraints: a completed and pronounced-good creation, a functionally mature initial state, a historical Adam, a historical Fall introducing death into the human line, a global hydrological catastrophe, subsequent dispersion.

**Note on priority.** The exegetical question is prior to the scientific one and is not settled by it. A scientific result cannot establish or refute F-004. This condition is adjudicated on exegetical grounds using the inference standard the programme adopts (good and necessary consequence), and the programme's scientific content is downstream of that adjudication rather than a check on it.

**Current assessment.** Not triggered. The programme does not treat this as a closed question, and the constraints in [`programme/hard-core.md`](../programme/hard-core.md) are each annotated with the exegetical basis claimed for them so that the challenge can be made specifically rather than in general.

---

## Standing assessment

Four conditions. One currently `UNMET` (F-002). One currently unenforceable through no fault of its statement (F-003).

The charter's claim that specifying these conditions is "not a concession made under pressure" is only true if the register is maintained when a condition starts going badly. F-002 is going badly now, and it is recorded as such, though charter v1.1 moves it in the right direction for the first time.

## Companion register

Charter v1.1 adds conditions of **advancement** alongside these conditions of abandonment, on the ground that a programme stating only what would sink it can claim progress on any favourable result after the fact. They are carried at [`ADVANCEMENT.md`](ADVANCEMENT.md).
