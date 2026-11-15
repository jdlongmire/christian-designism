# P-006 Interim Scoring Record: First Reader

**Prediction:** P-006 (E5/H2b exogenization), pre-registration v1.1
**Lineage scored:** Foamy viruses (Spumaretrovirinae), the highest-credence candidate at registration (0.30, Claude's estimate, not JD's credence)
**Reader:** Claude (claude.ai research session), first reader
**Date:** 2026-11-15
**Status:** FOAMY LINEAGE SCORED **FAIL**. C1 recorded as UNDERDETERMINED as written. See Appendix B (2026-11-15, second pass).
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
| C1 | **UNDERDETERMINED as written** (see Appendix B) | Fish FLERVs sister to all other FVs, PP 1.0 (Ruboyianes & Worobey 2016). Aiewsakun 2017 clade support bootstrap >84, PP 1.00. Gecko EFVs closer to mammalian FVs than tuatara is, PP 1.00. |
| C2 | **FAIL** (confirmed, Appendix B) | Gecko lineage qualifies. Every other candidate lineage checked, cartilaginous fish and amphibians included, shows no cross-species orthologous locus. |
| C3 | **FAIL** (confirmed, Appendix B) | Gecko lineage satisfies (a). No second lineage satisfies (a), (b) or (c); no dN/dS, restricted-expression or perturbation evidence exists for any other earlier-branching lineage. |
| C4 | **LIKELY PASS** | No exogenous FV lineage is placed basal to the earliest qualifying endogenous lineage in the published trees consulted. Held as likely rather than confirmed pending a full re-examination of exogenous FV placement. |

**Conjunction:** not satisfied. As of the second pass the candidate lineage space is exhausted for this lineage and the failures are confirmed rather than provisional, so the foamy lineage is scored **Fail**. This resolves the foamy lineage only. P-006 itself stands open to its registered date of 2027-11-15, since the alpharetrovirus and MbRV candidates are unscored.

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

Pre-registration §7.4 requires an independent reader scoring from the same sources without access to the §5 expectations. **Run 2026-11-15. Returned no scores. §7.4 is NOT satisfied and remains outstanding.** See Appendix A.

---

## 7. Contributions

- Criteria C1-C4, source order, and the scoring frame: Claude, adopted by JD at registration.
- This scoring pass, the lineage-by-lineage assessment, the Inconclusive call, and the §5 limitation: Claude.
- Adjudication of the interim call and of any criteria amendment: JD.

---

## Appendix A: Second-reader pass, 2026-11-15 (null result)

An independent reader was run without access to the §5 expectations or to this record, scoring C1-C4 from the published literature. **It returned no substantive scores.** Its only retrieval channel (WebSearch) returned titles and URLs with no snippet text across eight query formulations; full-text retrieval was unavailable to it for the same reason it was unavailable to the first reader. It declined to reconstruct bootstrap values, host counts, ORF lengths or dN/dS figures from background familiarity, and marked every criterion UNCERTAIN.

**Standing:** §7.4 is not discharged. No disagreement log is possible, because there are no competing scores. The second-reader pass must be re-run once full-text access is restored, and it must be re-run blind: this record is now written, so the re-run reader must not be given it.

**What the pass did contribute.** Two observations about the structure of the criteria, which do not depend on source text and which I judge sound:

1. **C2 genome-availability constraint (independent convergence).** The second reader reached §5 of this record's observation independently: a lineage whose host clade has one sequenced or one extant species cannot satisfy C2 regardless of evidence quality. It named coelacanth (*Latimeria*, two extant species with very unequal genomic resources) alongside tuatara. Recorded as convergent, arrived at from the criterion's logic rather than from this record.

2. **C3(c) is near-unobtainable for the lineages C1 selects (new).** C3's first conjunct requires (a) or (c); (b) alone cannot discharge it. Route (c), a published perturbation phenotype, requires transgenic or knockout work in the host. The lineages C1 forces into consideration are deep ones in non-model organisms, where no such platform exists and in the coelacanth's case cannot exist. So the first conjunct rests on (a), which requires >=2 hosts and therefore inherits the constraint in (1). C1 selects for depth and antiquity; C3(a)/(c) selects for experimental tractability and multiple sequenced genomes. The two pull against each other.

**Assessment.** Point (2) is the more consequential of the two and I accept it. It means the C2/C3 failures recorded in §2 are partly structural: they report what the criteria can be fed, not only what the phylogeny shows. That does not rescue the prediction. A criterion that cannot be satisfied by available evidence yields no support for the model either, and the registered conjunction stands unsatisfied. But it changes what a Fail at resolution would mean, and it bears on whether C3 as written was well-formed at registration.

**Not adopted here.** The second reader proposed revisions to C1, C2, C3(a) and C4, including a minimum-genome-availability precondition that would record data-limited lineages as unevaluable rather than Fail. Those are not applied. Any amendment goes through the deviation log in the pre-registration, pre-resolution, with the amendment and its date recorded, and is JD's call. Amending a criterion after seeing that it fails is exactly the move the pre-registration exists to constrain, so the default is to leave C1-C4 as registered and let them return whatever they return on 2027-11-15.

**C4 note.** The second reader observed that C4 has no defined reference node while C2 and C3 are unresolved, since it is evaluated relative to the earliest lineage qualifying under them. The "LIKELY PASS" in §2 should be read accordingly: it records that no exogenous FV lineage appears basal to the candidate endogenous lineages in the trees consulted, not that C4 has been evaluated against a fixed node.

---

## Appendix B: Second pass, 2026-11-15. Both open avenues closed; foamy lineage scored Fail

§4 of the first pass held the verdict at Inconclusive on two open avenues. Both were
checked with full text in hand. Neither yields a second qualifying lineage, and the
check turned up a defect in C1 that the first pass did not see.

### B.1 Cartilaginous fish EFVs: fail C2 and C3

Wang, Chen & Cui, *J Virol* 96:e01816-22 (PMC9972966). This was the high-leverage
candidate, since a lineage basal to the teleost FLERVs would sit at the base of the
tree. It fails.

- **C2 fails.** The paper reports no shared insertion sites, no flanking-sequence
  comparison, no synteny, no target site duplications and no insertion-polymorphism
  analysis. Each lineage occurs within a single host: 6 hits in *Amblyraja radiata*,
  6 in *Pristis pectinata*, and 136 in *Scyliorhinus torazame* across three lineages.
  Multiple integrations in one genome are not cross-species orthology.
- **C3 fails on all three routes.** No dN/dS or other selection analysis is reported,
  so (a) fails. The only expressed contig is expFVesp in *Etmopterus spinax*, with no
  tissue named, and the genome-derived CFEFVs "could not be confirmed to be
  transcribed", so (b) fails. No perturbation work exists, so (c) fails.
- Most copies are degraded: solo LTRs outnumber full-length copies heavily
  (242 to 5 in ERV-Spuma.a-Sto), and the authors conclude most cartilaginous fish FVs
  have been eliminated by their hosts.

### B.2 Amphibian lineages: fail C2 and C3

Chen, Zhang, Wei & Cui, *J Virol* 95:e00484-21 (PMC8223930), full text.

- **C2 fails.** No amphibian EFV is shown at an orthologous locus in two species. The
  words orthologous, flanking sequence, synteny, target site duplication and insertion
  polymorphism do not appear in the paper. Each element was characterized from one
  genome, and for the frog lineage ERV-Spuma-Smu in *Spea multiplicata* the authors
  state that other species in the same genus do not carry such FVs. Cross-species
  transmission in this paper is inferred from phylogenetic incongruence, not from
  shared insertions. All salamander lineages (ERV-Spuma.a-Ame, .b-Ame, and the
  excluded .c-Ame) are within the axolotl alone.
- **C3 fails.** No dN/dS or selection test and no perturbation work for any amphibian
  lineage. The caecilian evidence is transcriptome-derived with no tissue named, so it
  is expression without restriction and does not meet (b).
- The caecilian exCFVrbi, which the authors float as a possible non-mammalian
  exogenous FV, is weaker than the abstract suggests: the contigs could not be
  assembled at genome level, they match the endogenous ERV-Spuma-Rbi consensus at
  98 to 100%, the authors could not examine viral particles, and they concede it
  could be expression of the endogenous copy. It is not usable as the candidate
  exogenous lineage for C1 either.

### B.3 New finding: C1 is underdetermined as written

C1 asks whether a candidate exogenous lineage nests inside a tree in which two
endogenous lineages branch earlier, at bootstrap >=70 or PP >=0.95. It presupposes
one tree. Foamy virus gene trees disagree, and both papers say so plainly.

- CFEFVs sit at the base of all FVs in the POL phylogeny, and form a sister lineage
  to amphibian FVs in the ENV phylogeny.
- Chen et al. state that the pol and env phylogenies differ, with the caecilian
  lineage sister to salamander FVs in POL but grouping with ERV-Spuma-Rbi in ENV.

So which lineages "branch earlier" is gene-dependent, and C1 names no gene. Two
further problems compound it. Support values are often absent at exactly the nodes
C1 depends on: the basal POL placement of CFEFVs carries no reported node value, and
Chen et al. hide values below 70% in their figures, so an unreported node may be
weakly supported rather than well supported. And the first pass recorded C1 as a
known pass on the strength of fish FLERVs being sister to all other FVs at PP 1.0,
a placement that the CFEFV result displaces.

C1 is therefore reclassified from **PASS (known)** to **UNDERDETERMINED as written**.
This is a correction to the first pass, not a new criterion. It does not rescue the
prediction: C2 and C3 fail on their own terms regardless of which gene tree governs.

### B.4 Verdict

The foamy lineage, the highest-credence candidate at registration, is scored **Fail**.
C2 and C3 fail with the candidate space exhausted. C1 cannot be scored as written.
C4 has no fixed reference node, since it is defined relative to the lineages
qualifying under C2 and C3 and none do.

P-006 remains open to 2027-11-15. The alpharetrovirus and MbRV candidates are
unscored, and a Fail on one lineage is not a Fail on the prediction.

### B.5 Registered-criteria integrity

No criterion is amended here, and none should be. C1 through C4 were registered to be
hard, they have returned a clear negative on the leading candidate, and amending them
after watching them fail would convert a clean result into noise. The defects found
in C1 and C3 are recorded for the next pre-registration, not retrofitted to this one.

Two rules are proposed for the registry on the strength of what this pass found:

1. **Feasibility check at registration.** Each criterion must name at least one
   lineage for which evidence of the type it demands has already been published.
   C3(c) would have failed this check: a perturbation phenotype is unobtainable for
   the deep non-model organisms C1 selects.
2. **Determinacy check at registration.** A criterion resting on phylogenetic
   position must name the gene or concatenation whose tree governs, and must say how
   an unreported node value is treated. C1 would have failed this check.

### B.6 Programme standing

This is the programme's first registered prediction to return a negative on its
leading candidate, and it is recorded as a negative. On the parallel-comparison
rubric that is an R2 entry (failed predictions) against us, and the fact that it is
logged rather than quietly reinterpreted is the thing R6 and R7 are there to measure.
The honest entry is worth more to the programme than the prediction was.

### B.7 Second reader

Still not discharged. The first attempt returned no scores for want of source access.
The sources are now identified and readable, so the pass can be run properly. The
first reader recommends it not be run by an agent this reader briefs, and not by
thinx-gpt, which sits on the other side of the parallel-programme firewall.

Human-Curated, AI-Enabled (HCAE)
