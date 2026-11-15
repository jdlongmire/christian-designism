# I-0012 – Audit: how tidy is the shared-ERV evidence?

**Opened:** 2026-11-15, at JD's direction
**Severity:** Medium. Bears on A-010's costs and on how the ERV argument is framed in exchanges.
**Related:** [A-010](../../registry/AUXILIARIES.md#a-010--common-deployment-two-population-erv-model), [I-0009](I-0009-erv-model-copied-history-vs-hc8.md), symmetry rule S1–S5 in [`registry/AUXILIARIES.md`](../../registry/AUXILIARIES.md)

## Question

JD's hypothesis: the literature is shaped around its premises and the evidence is less tidy than the argument from shared ERVs presents. This issue tests that item by item.

## Ground rules

1. Untidiness is not refutation. Each item states what result would matter and what would not.
2. The audit is symmetric. Findings that favour the mainstream reading are recorded with the same prominence.
3. The mainstream's auxiliaries (lineage sorting, gene conversion, assembly quality) are legitimate under S1–S5. The audit asks how much work they do, and whether they are tested independently.

## Items

| # | Claim audited | Finding so far | Open task | What would matter |
|---|---|---|---|---|
| A1 | Shared positions are established on unbiased genomes | Earlier ape assemblies were guided by the human reference, which "humanized" them (Kronenberg et al. 2018, *Science*). The ERV counts in A-010 date from that era. The complete ape genomes (Yoo et al. 2025, *Nature* 641:401) were built without that guidance; the paper reports **species-specific** ERV insertions (its repeat supplement) and attributes the gorilla and chimpanzee excess to PtERV1. A **shared-locus** census on these assemblies was not located. | Read the Yoo et al. repeat supplement; search for any orthologous-ERV census on the complete assemblies; assess whether one can be computed from the public alignments. | A materially lower shared fraction than the 2005–2011 counts. If the fraction holds, A1 closes in the mainstream's favour. |
| A2 | LTR divergence is a reliable clock | Reviews concede gene conversion and recombination between LTRs can mislead (Hayward 2017). A 25,144-element plant audit found about a quarter of nested elements with higher LTR divergence than the element they inserted into (Jedlicka et al. 2020). In primates, a chimpanzee-specific insertion shows 9% LTR divergence, far too old for its distribution (Polavarapu et al. 2006), and PtERV1 divergence exceeds neutral expectation (Yohn et al. 2005). | Find or construct a primate audit: the fraction of loci whose LTR age contradicts their species distribution. | A high contradiction rate would weaken the divergence gradient, cost 3 of A-010. A low rate leaves cost 3 standing. |
| A3 | The locus census is stable | One survey counts old loci at 568 in human, 362 in chimpanzee and 197 in gorilla, and attributes the gap to sequencing and assembly quality on the premise that the counts should match (Magiorkinis et al. 2015). | Check whether later assemblies close the gap. | Persistent mismatch on complete assemblies. Closure favours the mainstream reading. |
| A4 | Presence and absence are scored evenly | Shared loci are counted as support. HERV-K-GC1 (present in gorilla and chimpanzee, empty site in human; Barbulescu et al. 2001) and 187 mobile-element insertions inconsistent with the ape phylogeny (Hormozdiari et al. 2013) are assigned to lineage sorting. | Count ERV loci specifically that conflict with the standard tree, and the ratio to congruent ones. | A conflict rate above what lineage sorting predicts from independent data. |
| A5 | Nested shared mutations are shown at scale | The standard demonstration is Johnson & Coffin (1999). How many loci it rests on, and whether it has been repeated genome-wide, is `UNCERTAIN`; not yet checked. | Read the primary; search for genome-scale replications. | A demonstration resting on a handful of loci with no replication. |

## A1 progress, 2026-11-15

Read: Yoo et al., bioRxiv v2 full text (preprint of the *Nature* paper; `MEDIUM`, verify against the published version).

- The paper's ERV analysis covers **species-specific insertions only**. It reports no count or fraction of ERV loci shared between human and chimpanzee or among apes. **No shared-locus census exists in this paper.**
- Full-length species-specific ERVs with target site duplications and gag/pol domains: gorilla 44, human 12, chimpanzee 3.
- 12.5–27.3% of the genome fails to align or departs from simple one-to-one alignment, concentrated in centromeres, telomeres, acrocentric regions and segmental duplications. Gap divergence affects 5 to 15 times more sequence than single-nucleotide divergence.
- Lineage sorting is estimated at about 39.5% of the autosomes and about 24% of the X, roughly 7.5 points higher than estimates from less complete genomes.
- The paper notes that complete genomes do not remove annotation biases that favour human.

**Reading.** The premise of A1 holds: the shared-ERV counts in circulation predate human-independent assemblies, and the paper that produced those assemblies did not recount them. Whether the shared fraction changes is unknown. The rise in the lineage-sorting estimate with completeness shows the tidy figures moved when the hard regions were included.

**Next for A1.** Search for a later orthologous-ERV census on these assemblies. Failing that, a census can be computed from the public assemblies, repeat annotations and alignments. This session cannot reach that data (its network is limited to package registries and GitHub), so the computation needs another route, to be decided by JD.

## Recorded against the hypothesis

- Insertion presence/absence markers are strongly congruent with the standard tree (Salem et al. 2003; Hormozdiari et al. 2013).
- Lineage sorting has independent support: lower on the X chromosome, patterned by gene class (Rivas-González et al. 2023).
- Independent infection does not reproduce positions: PtERV1, about 95.8% non-orthologous (Yohn et al. 2005).
- Much of the unaligned sequence in the complete-genome comparisons is repeat sequence, and alignment gaps also appear between human genomes (Ardern, commentary; secondary, `LOW`).

## Source confidence

Findings are from search extracts and partial full text read on 2026-11-15, `MEDIUM` unless marked. Author attributions for Hayward 2017, Hormozdiari et al. 2013, Salem et al. 2003, Rivas-González et al. 2023 and Magiorkinis et al. 2015 are from memory and must be verified against the papers before citation elsewhere.

## Status

Open. A1 is first.
