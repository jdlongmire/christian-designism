# Proposal: synthesise the ERV work into one repository

**Status:** Steps 1 to 3 **approved by JD** (session of 2026-11-15, 08:41 CT). Scorer: a fresh GPT session opened by JD. Still open: repository name and visibility, and whether the census request's bar on use in WP-038 is relaxed after the lift.
**Drafted:** 2026-11-15 by Claude (thinx-claude), at JD's request.
**Affects:** [`parallel-erv-comparison.md`](parallel-erv-comparison.md), the ERV sub-line in [`../lines/genetics.md`](../lines/genetics.md), and the DFM ERV work packages (not read by the drafter).

## Recommendation

1. Take a snapshot comparison of the two ERV efforts at pinned commits.
2. Then lift the firewall and move the shared ERV work into a new repository.
3. Keep each programme's registry and verdicts where they are, pointing to the new repository.

## Why

- **The independence the 2027 comparison needs is already thin.** Three disclosures and one scope ruling are logged, thinx-muse is running this programme's census, and JD is the source of the model on both sides.
- **The lines are converging.** A-010 depends on instantiation and the functional-maturity criterion, which belong to the DFM framework.
- **The objective needs one answer.** A framing for the ERV "kill shot" should exist once, on one evidence base.

**Stated limit.** The drafter has not read WP-038 or WP-033 and cannot say how much the two efforts overlap.

## Step 1: snapshot comparison (before anything is lifted)

Lifting the firewall cannot be undone. Whether the two efforts converged without contact is the valuable result, so it is captured first.

- **Scorer:** grok is the clean choice (independent verification hand, no recorded ERV involvement) but may not be available. **thinx-gpt is acceptable with three guards**, because it reviewed WP-038 at its G1 gate and so helped shape one of the two efforts:
  1. its report opens by declaring that prior role;
  2. it lists which WP-038 features followed from its own review findings, and those earn no credit as independent convergence;
  3. every score cites repository path and commit, so JD can audit it.
  A fresh session opened by JD with only the pinned inputs is the other option. It meets the protocol's wording, but it would be a Claude instance scoring work Claude drafted.
- **Inputs:** both repositories at pinned commits, the rubric R1–R8, and the disclosure log. Nothing else.
- **Adjudication:** JD.

**Amendment row for `parallel-erv-comparison.md` (for JD to enter):**

> | 2026-11-15 | Comparison brought forward to a snapshot at pinned commits, ahead of a planned synthesis. Made after three logged disclosures and one scope ruling; neither programme had read the other's working results. The 2027-11-15 comparison is withdrawn. |

**Draft request to grok (not sent):**

> **Requested outcome:** Score two ERV efforts against the attached rubric R1–R8 and report in one document, publishing every item including those unfavourable to either.
> **Inputs:** `jdlongmire/christian-designism` at `<commit>`; the DFM repository at `<commit>` (WP-038, WP-033); the rubric and disclosure log in `programme/parallel-erv-comparison.md` and `lines/genetics.md`.
> **Also report:** where the two efforts reached the same position independently, where they differ, and whether any similarity is explained by a logged disclosure.
> **Constraints:** use only the pinned inputs; do not consult either programme's agents; state what you could not assess.
> **Decision gate:** JD adjudicates. Advisory only.

The two commit hashes are for JD or thinx-muse to supply. The drafter must not look up the DFM one.

## Step 2: the new repository

**Working name:** `erv-explanatory-model` (JD to choose).

| Path | Holds |
|---|---|
| `README.md` | Purpose, status, and how programmes reference this repository |
| `GOVERNANCE.md` | What this repository does and does not own; the firewall-lift record; attribution |
| `model/` | The two-population common-deployment model, its layers, open parameters and stated costs |
| `evidence/` | A ledger of data claims, each with source and confidence level |
| `audit/` | The tidiness audit (I-0012 items A1–A5) |
| `census/` | The shared-locus census: scripts, pinned inputs, count tables |
| `predictions/` | Candidate predictions and scoring records, before and after registration |
| `framing/` | The response document for exchanges: concession, localisation, parity claim, falsification conditions |
| `history/` | The working outline and the retired mechanisms, with the grounds on which each was retired |

**Boundary.** The repository owns evidence, model and framing. It owns no hard core and makes no adoption decisions.

## Step 3: what stays in each programme

- Its hard core, its registries (predictions, auxiliaries, falsifiers) and its issues.
- Its own disposition of each auxiliary. The two programmes may adopt or decline the same auxiliary differently, and each records why.
- Registered predictions stay registered where they were registered. P-006 remains here.

## Migration map (this programme)

| Item | Now | After |
|---|---|---|
| Working outline v0.5 | Local only, no repository of record | `history/` |
| A-010 statement and costs | `registry/AUXILIARIES.md` | Model text moves to `model/`; the registry keeps the disposition and a pointer |
| I-0012 audit | `issues/open/` | `audit/`; the issue stays as a pointer |
| Census deliverable | Requested at `validation/erv-census/` | `census/` |
| P-006 pre-registration and scoring | `registry/preregistrations/` | Stays; mirrored by pointer in `predictions/` |
| Disclosure log, comparison protocol | `lines/genetics.md`, `programme/` | Stay, closed with the lift record |

## Decisions for JD

1. Synthesise, or keep the parallel design.
2. Scorer for the snapshot.
3. Repository name and visibility.
4. Whether the census request to thinx-muse is amended once the firewall lifts (it currently bars use in WP-038).
5. Who creates the repository. This is an operations action for thinx-muse; the drafter cannot create repositories.

Human-curated, AI-enabled (HCAE).
