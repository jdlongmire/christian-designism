# P-006 Interim Scoring Record: First Reader

**Prediction:** P-006 (E5/H2b exogenization), pre-registration v1.1
**Lineage scored:** Foamy viruses (Spumaretrovirinae), the highest-credence candidate at registration (0.30, Claude's estimate, not JD's credence)
**Reader:** Claude (claude.ai research session), first reader
**Date:** 2026-11-15
**Status:** INTERIM, INCONCLUSIVE (leaning Fail)
**Resolution date:** 2027-11-15 (unchanged)

This record is pre-resolution working product. It does not resolve P-006 and does not alter the registered criteria. Per pre-registration §6, an Inconclusive outcome is never upgraded to Pass.

---

## 1. Criteria as registered (abbreviated)

- **C1** Nesting: the candidate exogenous lineage nests inside a tree in which at least two endogenous lineages branch earlier, at bootstrap ≥70 or PP ≥0.95.
- **C2** Orthology: each of those earlier-branching endogenous lineages has orthologous, fixed loci in ≥2 host species.
- **C3** Functional necessity: one earlier lineage satisfies (a) or (c); another satisfies any of (a)-(c).
  - (a) ORF ≥80% of consensus length with dN/dS <0.5 across ≥2 hosts
  - (b) restricted expression
  - (c) published perturbation phenotype
- **C4** No exogenous lineage branches earlier than the earliest qualifying endogenous lineage.

Novelty classification: PARTIAL. C1 is a known result. C2 and C3 are novel requirements.

---

## 2. Scores

| Criterion | Score | Basis |
|---|---|---|
| C1 | **PASS** (known) | Fish FLERVs sister to all other FVs, PP 1.0 (Ruboyianes & Worobey 2016). Aiewsakun 2017 clade support bootstrap >84, PP 1.00. Gecko EFVs closer to mammalian FVs than tuatara is, PP 1.00. |
| C2 | **FAIL as written** (1 of 2 required lineages) | Gecko lineage qualifies. No second endogenous lineage branching earlier has demonstrated cross-species orthology. |
| C3 | **FAIL as written** (1 of 2 required lineages) | Gecko lineage satisfies (a). No second lineage confirmed on (a), (b) or (c). |
| C4 | **LIKELY PASS** | No exogenous FV lineage is placed basal to the earliest qualifying endogenous lineage in the published trees consulted. Held as likely rather than confirmed pending a full re-examination of exogenous FV placement. |

**Conjunction:** C2 and C3 both fail as written, so the registered conjunction is not satisfied. The record is marked Inconclusive rather than Fail because the candidate lineage space is not exhausted (see §4).

---

## 3. Lineage-by-lineage detail

### 3.1 Gecko (ERV-Spuma-Ppi / ERV-Spuma-Gja) — qualifies on C2 and C3

- Orthology: host flanking sequences orthologous between *Paroedura picta* and *Gekko japonicus*; synteny in the EMC1 intron. Two host species. **C2 satisfied.**
- Function: *env* 943/942 aa, dN/dS 0.14 (CI 0.08-0.54), "fully coding competent with evidence for strong purifying selection", >96 Myr old, likely transcriptionally active. Described as the first known co-opted EFVs. **C3(a) satisfied.**
- Source: Aiewsakun, Simmons & Katzourakis (2019) *Viruses* 11:641. HIGH confidence (primary, direct quotation).

### 3.2 Teleost fish (FLERVs) — fails C2

- "unable to detect any orthologous fish EFVs". Deepest-branching lineage, so its failure on C2 is the structurally important one.
- Source: Aiewsakun & Katzourakis, primary. HIGH confidence.

### 3.3 Tuatara (ERV-Spuma-Spu) — cannot qualify

- Single extant species (*Sphenodon punctatus*). C2 requires ≥2 host species and is unsatisfiable in principle for this lineage. Noted as a structural limitation of the criterion, not a result.

### 3.4 Coelacanth (CoeEFV) — fails C2 on available data

- No cross-species orthology demonstrated between *Latimeria chalumnae* and *L. menadoensis* in the sources located. MEDIUM confidence (absence of evidence in accessible literature, not a published negative).

### 3.5 Avian EndFVs — do not qualify

- Orthologous across two *Ciconia* storks with a shared TSD, so C2-type evidence exists, but the lineage is placed *within* the mammalian FV clade, not earlier, so it is out of scope for C1/C2 as registered. ORFs carry stop codons, so C3(a) fails independently.

### 3.6 Amphibians — do not supply a second lineage

Chen, Zhang, Wei & Cui (2021) *J Virol* 95:e00484-21.

- Host coverage: FVs confirmed in 8 salamanders, 2 frogs, 1 caecilian.
- Salamanders: FVs "maintained a co-evolutionary pattern with their hosts" dating to the Paleozoic; three distinct FV lineages integrated into one salamander genome. The two dated salamander lineages (ERV-Spuma.a-Ame 18.92-55.95 Mya; ERV-Spuma.b-Ame 2.39-24.89 Mya) are reported within *Ambystoma mexicanum*. No locus-level orthology across ≥2 salamander species is demonstrated in the accessible text. **C2 not met.**
- Caecilian: a lineage in the two-lined caecilian (*Rhinatrema bivittatum*) "expressed all complete major genes", reported at both DNA and RNA level; the authors identify a potential expressed form (exCFVrbi) as possibly "the first exogenous form of foamy virus existing in species other than mammals". Single host species, so C2 is unsatisfiable for this lineage. Expression is whole-transcriptome rather than restricted, so C3(b) is not met either.
- Frogs: FVs "much more likely acquired from cross-species (class level) transmission in the Cenozoic era", which weakens rather than supports earlier-branching endogenous status.
- Confidence: MEDIUM. Abstract, discussion and the Chinese Academy of Sciences release were read directly; the full text could not be retrieved (Europe PMC `fullTextXML` for PMC8223930 returned rate-limit errors on repeated attempts, and the ASM page required an approval that was not granted). Flagged for verification against the primary before this record is treated as settled.

---

## 4. Why Inconclusive rather than Fail

Two open avenues remain inside the registered resolution window:

1. **Supplementary data not yet read.** Chen et al. (2021) supplementary tables may report salamander orthology across species. This is the single most likely source of a second qualifying lineage.
2. **Later literature.** Chevrotain EFVs (Wang/Chen/Cui line of work) show seven orthologous insertions across *Tragulus javanicus* and *T. kanchil*, and cartilaginous fish EFVs (Wang, Chen & Cui 2022, *J Virol* 96:e01816-22) are described as "rooting to vertebrate counterparts". Neither has been scored. The cartilaginous fish lineage is the more consequential: if it branches earlier than teleost FLERVs and has cross-species orthology, it is a direct C2 candidate at the base of the tree.

Neither avenue is a reason to soften the criteria. Both are reasons to withhold a Fail until they are checked.

## 5. Observed limitation of the criteria (not a revision)

C2 is unsatisfiable in principle for any lineage whose host clade has a single extant species (tuatara, coelacanth pair aside). This was not anticipated at registration. Recording it here as an observation; any amendment goes through the deviation log in the pre-registration, not through this file.

---

## 6. Second-reader status

Pre-registration §7.4 requires an independent reader scoring from the same sources without access to the §5 expectations. **Not yet run.** Disagreements will be logged as an appendix to this file.

---

## 7. Contributions

- Criteria C1-C4, source order, and the scoring frame: Claude, adopted by JD at registration.
- This scoring pass, the lineage-by-lineage assessment, the Inconclusive call, and the §5 limitation: Claude.
- Adjudication of the interim call and of any criteria amendment: JD.
