# Pre-registration: H2b Exogenization Test (E5)

*Version 1.1 · 15 November 2026 · JD Longmire*
*Registry entry: [P-006](../PREDICTIONS.md#p-006--h2b-exogenization-test-e5-foamy-virus-lineage) · Resolution date: 2027-11-15*
*Companion to "Endogenous Retroviruses under Methodological Designism," working outline v0.4 (Sections 5A and 6C; not yet deposited in a repository of record).*
*Related issue: [I-0009](../../issues/open/I-0009-erv-model-copied-history-vs-hc8.md).*

*v1.1 differs from the drafted v1.0 only in: the credence column relabelled as Claude's estimate (author direction), the resolution date added, and the registry cross-references and registration section filled in. No criterion, threshold or expected outcome changed.*

**Status at registration: no foamy-virus, alpharetrovirus or lentivirus tree, alignment, or locus data has been examined for this test.** Everything already seen is listed in Section 3 and excluded from the novelty count.

---

## 1. Purpose

Section 6B of the outline finds that the MD programme has no corroborated use-novel fact in the ERV domain. Explanatory parity requires at least one. This document fixes, before any data are scored:

- the hypotheses,
- the operational criteria and thresholds,
- the expected outcome per lineage,
- what will and will not count as a corroborated novel fact.

Any deviation after registration is logged in Section 9 with its reason.

---

## 2. Hypotheses

For a retroviral lineage L:

- **H2b (exogenization).** The infectious form of L arose from a host-regulated endogenous element.
- **H2a (endogenization).** The endogenous copies of L arose from an infectious form.

The two are not exhaustive across lineages; the model allows each to hold in different lineages. The test scores each lineage separately.

---

## 3. Prior exposure (disclosed and excluded)

| Item already seen | Source | Effect on novelty |
|---|---|---|
| Foamy-like endogenous retroviruses occur in fish and amphibians; a phylogeny of retroviruses including them was published; ray-finned fish lineages show overall co-speciation with hosts | Aiewsakun & Katzourakis 2017 (abstract only) | **Criterion C1 for foamy viruses is not use-novel.** A C1 pass will not count toward novelty |
| HERV-K(HML-2) consensus reconstructs an infectious ancestor | Dewannieux et al. 2006 | HML-2 already scored **Fail**; excluded from the count |
| KoRV is endogenizing now; GALV, KoRV and a rodent provirus (MbRV) are closely related | Tarlinton et al. 2006; Simmons et al. 2014 | KoRV already scored **Fail** at C1; MbRV status open |
| ALV-J env derives from endogenous EAV-HP by recombination | Bai et al. 1995; Benson et al. 1998 | Shows the event-scale mechanism (S3); not a lineage-scale (S2) result |
| Retroviruses derive from LTR retrotransposons | Malik et al. 2000 | Family-scale (S1); does not discriminate |

Not yet seen, and to stay unseen until registration is dated: any foamy-virus locus data (orthology, fixation, ORF integrity, dN/dS, expression); any alpharetrovirus or lentivirus phylogeny with endogenous and exogenous members together.

---

## 4. Operational criteria

H2b **passes** for L only if C1–C4 all hold.

**C1. Nesting.** In a maximum-likelihood or Bayesian tree on reverse transcriptase (pol), the exogenous clade of L is nested within endogenous diversity, with **at least two endogenous lineages branching before the exogenous clade's most recent common ancestor**. Each relevant node must have bootstrap ≥ 70 or posterior probability ≥ 0.95.

**C2. Fixity and orthology.** For each of those earlier endogenous lineages, at least one copy sits at an **orthologous locus in two or more host species**, shown by shared flanking sequence and, where reported, shared target site duplication. It must be **fixed** (no reported insertional polymorphism) in the sampled populations, where population data exist.

**C3. Host-integrated regulation or function.** Among the earlier endogenous lineages:
- at least **one** satisfies (a) or (c), and
- at least **one other** satisfies any of (a), (b) or (c).

where:
- (a) an ORF retained across two or more host species at ≥ 80% of consensus length, with dN/dS < 0.5 (purifying selection in the host);
- (b) documented expression restricted to particular tissues or developmental stages, consistent with host regulation;
- (c) a published perturbation (knockout, deletion, knockdown) with a host phenotype.

**C4. No earlier exogenous lineage.** No exogenous lineage branches before the earlier endogenous lineages that satisfy C2 and C3, at the support thresholds in C1.

**Fail** if any of the following holds:
- the endogenous copies are polymorphic, specific to one lineage, and nested within exogenous diversity;
- a consensus of endogenous copies reconstructs an infectious ancestor;
- C1 or C4 is contradicted at the stated support.

**Inconclusive** if the published data are insufficient to score any criterion. Inconclusive is recorded as such and never upgraded to Pass.

---

## 5. Expected outcomes (stated before scoring)

| Lineage | MD/H2b prediction | Claude's estimate of a Pass (not JD's credence) | Counts toward novelty if Pass? |
|---|---|---|---|
| Foamy / spuma-like | **Pass** | 0.30 | **Yes, for C2 and C3 only** (C1 excluded, Section 3) |
| Gammaretro (MbRV branch) | Pass at the MbRV branch only if MbRV proves endogenous and fixed | 0.15 | Yes |
| Alpharetro (ALV/EAV) | Pass | 0.20 | Yes |
| Lentiviruses | Inconclusive expected (sparse endogenous record) | n/a | n/a |
| Betaretro HML-2 | Fail (already known) | 0 | No |
| Gammaretro KoRV/GALV | Fail at C1 (already known) | 0 | No |

The estimates are Claude's, retained by agreement as a record against which the result can be checked. They are not JD's credences. A low estimate does not lower the bar.

---

## 6. What counts toward parity

- **One corroborated use-novel fact** = a Pass in any lineage marked "Yes" in Section 5, on the criteria marked as novel there.
- A foamy-virus Pass counts as **one** fact (C2 + C3 jointly), not two.
- A Fail in a lineage predicted to Pass is recorded as a **disconfirmation** in the outline's ledger (Section 6A). It is not reinterpreted after the fact.
- No new auxiliary may be introduced to rescue a Fail without being logged as a belt change and graded under Lakatos's ad hoc criteria.

---

## 7. Analysis plan

1. **Desk study first.** Published trees, locus tables, expression and perturbation data only. No new sequencing.
2. **Source search order for foamy viruses (to be consulted only after registration is dated):** Aiewsakun & Katzourakis 2017 (full text and supplementary tables); published reports of endogenous foamy viruses in sloth, coelacanth and other hosts (to locate; specific citations not yet verified); ERV databases such as gEVE; Hayward et al. 2013 broad retrovirus phylogenomics.
3. **Scoring order.** Score C1 and C4 from the trees; then C2 from locus data; then C3. Record each score with its source and support value **before** reading the authors' interpretive discussion where possible.
4. **Two-reader check.** The scored table is checked by a second reader (a separate agent with no access to this document's Section 5 expectations), who scores from the same sources. Disagreements are logged, not averaged away.
5. **Report all lineages scored**, including Fails and Inconclusives.

---

## 8. Bias statement

- JD holds the MD position and prefers a Pass.
- Claude, which drafted the criteria, carries a trained default toward methodological naturalism.
- The criteria and thresholds above are fixed now so that neither preference can move them after the data are seen.

---

## 9. Deviation log

| Date | Deviation | Reason |
|---|---|---|
| 2026-11-15 | Attribution wording only: "drafter's estimate" and "the assistant" replaced by "Claude"; contributions section added. No criterion, threshold, expected outcome or estimate value changed. Made before any Section 7 source was consulted. | Collaborator attribution convention agreed by JD and Claude. |

---

## 10. Registration

Registered in this repository as [P-006](../PREDICTIONS.md#p-006--h2b-exogenization-test-e5-foamy-virus-lineage) before any Section 7 source was consulted. The public date is the push and pull-request timestamp of the commit that adds this file; later edits are prohibited except through the Section 9 deviation log.

- SHA-256 of the drafted v1.0 text: `93109d8cfd106718d14875eefbadc79d9f7c061aedd855f99451651978bccfe8`
- Resolution date: **2027-11-15**. If scoring is incomplete by then, every unscored lineage is recorded as `Inconclusive` and the entry is adjudicated on what was scored.

---

## Contributions

- **JD Longmire:** methodological designism framing; the explanatory-parity burden; the decision to run the work as a Lakatosian programme; the "patched code base" intuition behind the maintenance layer; registration decisions and accountability for the document.
- **Claude (Anthropic), collaborator:** the H2b test design and criteria C1–C4; the prior-exposure disclosure; the estimates in Section 5; drafting.

For journal publication, Claude's role is stated in a contributions or methods statement, consistent with COPE's position that AI tools cannot be listed as authors.

---

## References

Aiewsakun, P. and Katzourakis, A. (2017) 'Marine origin of retroviruses in the early Palaeozoic Era', *Nature Communications*, 8, 13954.

Bai, J., Payne, L.N. and Skinner, M.A. (1995) *Journal of Virology*, 69(2), pp. 779–784.

Benson, S.J., Ruis, B.L., Fadly, A.M. and Conklin, K.F. (1998) *Journal of Virology*, 72(12), pp. 10157–10164.

Dewannieux, M. et al. (2006) *Genome Research*, 16(12), pp. 1548–1556.

Malik, H.S., Henikoff, S. and Eickbush, T.H. (2000) *Genome Research*, 10(9), pp. 1307–1318.

Simmons, G. et al. (2014) *PLoS ONE*, 9(9), e106954.

Tarlinton, R.E., Meers, J. and Young, P.R. (2006) *Nature*, 442, pp. 79–81.
