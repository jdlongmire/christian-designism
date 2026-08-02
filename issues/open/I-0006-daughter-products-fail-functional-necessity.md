# I-0006 – Daughter products may fail the functional-necessity criterion

**Opened:** 2026-08-02 (charter v1.1)
**Severity:** High. The criterion introduced to rescue functional maturity may rule against it on its founding case.
**Related:** [A-001](../../registry/AUXILIARIES.md#a-001--functional-maturity-of-origins), [F-002](../../registry/FALSIFIERS.md#f-002--continued-failure-to-supply-a-demarcation-criterion), [AD-001](../../registry/ADVANCEMENT.md#ad-001--demarcation-criterion-applied-in-advance-across-three-specimen-classes), charter §6.2 and §7

## The problem

Charter v1.1 §7 states the candidate demarcation criterion:

> a feature is constitutive if the system could not discharge its function at the moment of deployment without it

and immediately applies it:

> Section 6.2 already relies on this reasoning for radiogenic inventory, which passes, since a habitable planet requires the heat engine and a heat engine requires long-lived parent nuclides **with their attendant daughter products**.

The emphasis is added. That final clause is where the argument is doing work the criterion does not license.

Apply the criterion strictly, feature by feature:

| Feature | Required to discharge function at deployment? | Verdict |
|---|---|---|
| U-238, Th-232, K-40 (parents) | Yes. The heat engine is the function, and these are its fuel. | **Constitutive** |
| Pb-206, Pb-207, Ar-40, Sr-87, Nd-143 (radiogenic daughters) | No. They are inert with respect to mantle convection, the geodynamo, and every other function named at §6.2. A planet deployed with parents and no daughters runs its heat engine exactly as well. | **Elapsed history** |

If daughter products read as elapsed history, then the daughter-to-parent ratio is a clock in the ordinary sense, and it is measuring post-deployment time. That is precisely the conclusion functional maturity was constructed to avoid.

## Why this cannot be waved through

Charter §7 v1.1 commits in advance:

> Where the criterion returns a result the programme would rather not have, the result stands. A demarcation rule that never contradicts the interpreter is an overlay wearing a rule's clothing.

This is that case, arriving in the same section that stated the rule.

## Counters available, and what each costs

**"A working planet requires geochemically realistic rock, and realistic rock contains radiogenic daughters."** This is a different criterion, verisimilitude rather than functional necessity, and it is the appearance-of-age move that §6.2 explicitly distinguishes functional maturity from. Invoking it collapses the distinction the section is built on. High cost.

**"Some daughters are functionally necessary."** The strongest case is atmospheric Ar-40, which is radiogenic and constitutes roughly one per cent of the atmosphere. But an atmosphere discharges its function without argon, so the case is weak, and it covers one nuclide out of the set. Even if granted, it does not rescue Pb-206, Pb-207, Sr-87 or Nd-143, which are the systems whose concordance §8.3 relies on. Low cost, low yield.

**"Equilibrium thermal structure requires a decay history."** A deployed planet's thermal profile can be specified directly at t=0. This does not go through.

**Accept the verdict and restructure.** Concede that daughters read as elapsed history, and rebuild the geochronological position on what that permits. This is the honest option and it is more survivable than it first appears, because it converts the dispute from "what does the isotopic record record" into "what elapsed interval does it record and under what conditions," which is a narrower and more tractable question. High cost to the current §6.2, but it is the option consistent with the rule as stated.

## Knock-on to §8.3

The concordance reply at §8.3 depends on daughters being constitutive. If they are elapsed history, then concordance across systems with different half-lives is exactly what elapsed process predicts, functional maturity offers no separate account, and the objection at §8.3 recovers its status as a decisive discriminator. This is the same dependency flagged in the v1.0 §8.3 concession, now sharpened by the programme's own criterion rather than by an outside critic.

## Third path, opened after this issue was written

[I-0008](I-0008-ordinal-cardinal-amendment.md) proposes an ordinal commitment with cardinal agnosticism. On that framing this issue drops substantially in severity without being answered.

If the programme commits to the order of the sequence and holds that the physical measure does not integrate across a fiat boundary, then daughter products reading as elapsed history is absorbable. The ratio measures a post-deployment interval; what it does not do is establish a duration summed across the boundary, and summation across the boundary is the disputed operation rather than a conclusion the ratio delivers.

This is relief from severity, not resolution. The question migrates from geochronology into [F-002](../../registry/FALSIFIERS.md#f-002--continued-failure-to-supply-a-demarcation-criterion), where locating the boundary becomes the whole problem. It was always going to be decided there.

## What resolution requires

A written adjudication, entered here, that either:

1. Derives the necessity of daughter products from the deployment function without appealing to verisimilitude, or
2. Accepts the verdict and states what the geochronological position becomes

Option 1 is worth attempting and should not be assumed available. Option 2 is not a defeat of the programme; it is a defeat of one auxiliary, which is what the protective belt is for.

## Status

Open. Blocks AD-001 from reaching `MET`, since the third specimen class is contested. A-001 carries the liability.
