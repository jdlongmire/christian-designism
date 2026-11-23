# WP-CD-0002 execution evidence: link inventory and post-move link check

Date: 2026-11-23. Executed on JD Longmire's approval of the chartered target tree ("Approved", BWM alignment session).

## Pre-move link inventory

Internal: 46 blobs in the repository; 36 text files carried path references to the six moving directories (charter, programme, registry, lines, issues, validation). Every distinct reference was inspected before the move: all were genuine in-repository paths (link targets, backticked path mentions, table cells). No foreign path segments (for example GitHub issue URLs in other repositories) were present to be caught by the rewrite.

Inbound, from other repositories (checked by direct read of the candidate files, after the code-search rate limit was reached; core API readback used throughout):

- jdlongmire/biblical-worldmodel, principles pointer file: absolute URLs naming charter/christian-designism-principles.md and programme/hard-core.md. Companion update required and filed.
- jdlongmire/designed-functional-maturity, README repository map: prose path charter/christian-designism-principles.md. Companion update required and filed.
- jdlongmire/designed-functional-maturity, work-packages/WP-038-erv-explanatory-model.md: prose mention of the christian-designism ERV sub-line, no path. No action.
- jdlongmire/erv-design-model, README: link to this repository's root only. No action.
- READMEs of global-flood-hydrotectonic-model, catastrophic-hydrotectonic-flood-model, creation-cosmology-programmes, creation-actualization-cosmology, post-flood-diversity, oddxian-apologetics, skepticat, oddXian: no christian-designism path references. No action.
- jdlongmire/ai-bridge records (the PR #71 disposition, the SOP, the closure note): prose mentions of the old paths in dated historical records. Left as filed, per the mailbox contract's preservation rule; they record where the documents lived on the dates they name.

## The move

One commit built from the full tree: all 46 blobs re-pathed (charter to 01-charter, programme to 02-programme, registry to 03-registry, lines to 05-lines, issues to 06-issues, validation to 07-validation; 04-work-packages and root files unchanged), blob contents preserved except link rewrites in 33 files. A scripted segment rewrite updated every path reference to the moving directories outside 04-work-packages.

One defect found and fixed in the same pass: the principles document's link to the hard core, filed 2026-11-23 as (programme/hard-core.md) from inside charter/, was already broken before the move for want of ../ ; corrected to (../02-programme/hard-core.md). It is the only content correction beyond path segments.

## Post-move link check

Scripted check over the new tree (branch governance/wp-cd-0002-execute-20261123, after the fix commit): 39 markdown files, 214 relative links resolved against the new path set.

Result: 0 failures.

Human-Curated, AI-Enabled (HCAE)
