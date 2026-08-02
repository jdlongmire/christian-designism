# Christian Designism

**A research programme governed by biblical historical claims, held to Lakatosian criteria.**

This repository is the programme's governing layer. It holds the charter, the hard core, the registers that make the charter's falsifiers enforceable, and pointers to the disciplinary lines. Model-level work lives in its own repositories and is not duplicated here.

---

## The claim, and what it is not

The programme's founding argument is that the assertion "there is no scientific path to a young universe" conflates two distinct properties: **consensus**, which describes the distribution of belief in a research community, and **consilience**, which in Whewell's original sense describes the unforced convergence of inductions drawn from independent classes of facts. The inference from absent consensus to absent coherent alternative does not go through.

That argument establishes something narrow. It does not establish that this programme currently exhibits greater consilience than the standard reconstruction, that consensus is epistemically worthless, or that coherence is truth. The charter states all three disclaimers explicitly, and the distinction between **consilience sought and consilience achieved** is maintained throughout.

Start here: **[`charter/consilience-is-not-consensus.md`](charter/consilience-is-not-consensus.md)**

---

## Why this repository exists as an institution rather than a paper

A programme that specifies falsifiers in prose and tracks them nowhere has specified nothing. The charter conditions the programme's scientific standing on adjudicable predictions and stated conditions of abandonment. The registers are where those commitments are made good, or shown to be empty.

The registers are designed to be able to embarrass the programme, and at creation they do.

| Register | Purpose |
|---|---|
| [`registry/PREDICTIONS.md`](registry/PREDICTIONS.md) | Every claim the programme commits to in advance, with falsifier, resolution date, and novelty marked **at entry**. Append-only once registered. |
| [`registry/AUXILIARIES.md`](registry/AUXILIARIES.md) | The Lakatosian protective belt made explicit, including auxiliaries the programme has **declined**. |
| [`registry/FALSIFIERS.md`](registry/FALSIFIERS.md) | Charter §9 conditions of abandonment, with live status. |
| [`registry/ADVANCEMENT.md`](registry/ADVANCEMENT.md) | Charter §9 conditions of advancement. What would raise the programme's standing, fixed in advance. |
| [`programme/hard-core.md`](programme/hard-core.md) | The numbered commitments held immune by methodological decision, and an explicit list of what is *not* in the hard core. |

---

## Honest standing (charter v1.2)

Recorded up front rather than discovered by a critic.

- **Five predictions registered. Zero at `REGISTERED` status.** All five are `DRAFT`, missing a falsifier, a resolution date, or both. Charter §9 conditions abandonment on registered-prediction failure, which is currently unenforceable.
- **Falsifier [F-002](registry/FALSIFIERS.md#f-002--continued-failure-to-supply-a-demarcation-criterion) is `UNMET`, but moved for the first time.** v1.1 supplies a candidate criterion, **functional necessity**, offered as provisional. It excludes real things: crater populations and molecular clock divergence are both assigned to elapsed history. Assessed at [`programme/demarcation/`](programme/demarcation/).
- **The criterion may rule against the auxiliary it was built to support.** Applied strictly, radiogenic *parent* nuclides pass functional necessity and radiogenic *daughter* products do not, which would make the daughter-to-parent ratio an ordinary clock and would take the §8.3 concordance reply with it. Charter §7 commits in advance that an unwelcome verdict stands. This is the first test of that commitment, it is stated in the paper at §8.3 as of v1.2, and it is open in both directions. [I-0006](issues/open/I-0006-daughter-products-fail-functional-necessity.md) is the highest-value open question in the programme.
- **Two traceability gaps.** The hydrotectonics falsifier list ([I-0001](issues/open/I-0001-gfh-falsifier-list.md)) and the cosmological pre-registration ([I-0003](issues/open/I-0003-cosmology-prereg-location.md)) are both cited by the charter as existing instruments. Neither has been located or produced.
- **The one claimed corroboration was withdrawn by the author.** v1.1 restates the ringwoodite case at the strength the evidence supports and explicitly declines predictive priority ([I-0002](issues/resolved/I-0002-pearson-priority-verification.md), resolved). P-001 will register as `KNOWN` and cannot count toward advancement.
- **One self-generated difficulty.** The adopted geological model creates tension with helium retention in zircons ([I-0004](issues/open/I-0004-helium-retention-tension.md)).

This is the profile of a young programme with a mixed record, which is what the charter claims for it.

---

## Disciplinary lines

Pointers, with status. Substantive content lives upstream.

| Line | Repository of record | Status |
|---|---|---|
| [Geology](lines/geology.md) | [`global-flood-hydrotectonic-model`](https://github.com/jdlongmire/global-flood-hydrotectonic-model) | Hydraulic collapse adopted; blocked on upstream falsifier list |
| [Geochronology](lines/geochronology.md) | this repository | Most developed and most exposed; rests on F-002 |
| [Astronomy / cosmology](lines/astronomy.md) | none | Pre-registration not located; light travel time recorded as an open difficulty |
| [Genetics](lines/genetics.md) | none | Cited without adjudicating its mainstream critics |
| [Paleontology](lines/paleontology.md) | none | Least developed; qualitative only, generates no advance commitment |

---

## The declined auxiliary

The programme's principal evidence that it applies the Lakatosian criterion to itself rather than only to its rivals.

**Accelerated nuclear decay (RATE) is declined as degenerating.** Compressing the decay inventory into creation week and a Flood year leaves the released energy unchanged and raises the power. The decisive constraint sits at the planetary radiative boundary rather than anywhere inside the Earth: shedding 10<sup>29</sup> to 10<sup>30</sup> J within a year requires the surface to radiate continuously at roughly 3,200 to 5,750 K, against a silicate vaporization point near 3,000 K. This is a disposal problem, not a transport problem, which is why the volumetric cooling mechanism proposed in response had to be exotic. That mechanism is motivated by nothing beyond the difficulty it removes, and it overshoots, since cooling sufficient to preserve uranium-rich zircons would freeze the Flood waters.

Declining it costs the programme nothing, because functional maturity treats isotopic inventory as constitutive and incurs no obligation to compress elapsed decay at all. That last clause is exactly what [I-0006](issues/open/I-0006-daughter-products-fail-functional-necessity.md) puts in question, which is why the issue matters beyond geochronology.

Full grounds: [A-002](registry/AUXILIARIES.md#a-002--accelerated-nuclear-decay). Declining the auxiliary does not dismiss the observations; two live RATE-adjacent relationships are recorded in [`lines/geology.md`](lines/geology.md), one favourable and one not.

---

## Contributing

The most useful contributions, in order:

1. **Adjudication of [I-0006](issues/open/I-0006-daughter-products-fail-functional-necessity.md)** – whether radiogenic daughter products can be derived as functionally necessary at deployment without appealing to verisimilitude. A demonstration either way is the highest-value contribution available, and the negative is as welcome as the positive.
2. **Refinement of the demarcation criterion**, or an argument that no such criterion is possible in principle given the framework's commitments. The second would be the stronger result and would trigger F-002. It is the argument a serious critic should be making, and the programme has committed in advance to recording it.
3. **A pointer to prior serious treatment of the demarcation problem** in either the creationist or mainstream philosophy-of-science literature. The claim that none exists is a claim about searches conducted, not a proven negative.
4. **Falsifier statements** for any `DRAFT` prediction, in terms a hostile reader could apply.
5. **Adjudication of the interval-invariance objection** to the anisotropic synchrony convention ([A-005](registry/AUXILIARIES.md#a-005--anisotropic-synchrony-convention)).

Open an issue, or add a file under `issues/open/` following the existing convention.

---

## Author

**James D. Longmire**
ORCID: [0009-0009-1383-7698](https://orcid.org/0009-0009-1383-7698)
Northrop Grumman Fellow (unaffiliated research)
Correspondence: jdlongmire@outlook.com

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). See [LICENSE](LICENSE).

## Citation

> Longmire, J.D. (2026) *Consilience Is Not Consensus: Framework Commitments and the Coherence of a Biblical Chronology*. Version 1.0. Available at: https://github.com/jdlongmire/christian-designism

## Provenance

Human-curated, AI-enabled (HCAE). Research direction, argument, and all substantive positions are the author's. AI assistance was used for drafting support, structural review, and consistency auditing across the charter and registers.
