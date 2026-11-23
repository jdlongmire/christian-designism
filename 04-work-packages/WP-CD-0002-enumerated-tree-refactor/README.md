# WP-CD-0002: Enumerated-tree refactor

**Status:** Executed 2026-11-23 on JD Longmire's approval of the target tree as proposed. Open pending JD's acceptance of the executed refactor.
**Opened:** 2026-11-23, on JD Longmire's direction (BWM alignment session: "Create WP-CD-0002 as a charter, execution after I review the target tree")
**Owner:** JD Longmire (ratifier, and approver of the target tree). Execution, once approved: Thinx-Muse.
**Machine-readable state:** [package.yaml](package.yaml)
**Dependency:** WP-CD-0001 (register and template this package uses). Independent of WP-CD-0001's acceptance.

## Purpose

This repository's top level is an unenumerated set (charter, programme, registry, lines, issues, validation) in an estate whose governed repositories use enumerated trees: biblical-worldmodel runs 00-meta-model through 06-operations, and both biblical-worldmodel and ai-bridge place work packages at 04. Enumeration is not decoration in that pattern: the number states the layer, and the layer states what kind of thing a reader is holding. This package refactors this repository's structure into an enumerated tree on the same logic.

## Target tree (PROPOSED, pending JD's review)

| Current path | Proposed path | Layer rationale |
|---|---|---|
| charter/ | 01-charter/ | The governing text: charter and principles statement |
| programme/ | 02-programme/ | The programme definition: hard core and demarcation |
| registry/ | 03-registry/ | The enforceable registers, including REPOSITORIES.md and preregistrations |
| 04-work-packages/ | 04-work-packages/ | Unchanged. 04 is the work-package layer in biblical-worldmodel and ai-bridge as well; cross-repo consistency fixes this number |
| lines/ | 05-lines/ | The disciplinary line pointers and status records |
| issues/ | 06-issues/ | The open and resolved issue files |
| validation/ | 07-validation/ | Validation material |

Root files (README.md, CITATION.cff, LICENSE, .gitignore) stay at root. JD may renumber, rename, or reject any row; the approved tree, whatever it is, replaces this table in the executing change.

## Why this is its own package

WP-CD-0001's scope and authority boundary exclude structural change, and its verification rests on a contained diff. A tree refactor moves paths, and paths are load-bearing: internal relative links (lines to charter and registry, hard core to charter and registers, issues to registry) and inbound links from other repositories all name current paths. Folding the refactor into WP-CD-0001 would break that package's boundary and its disposition. This package therefore stands alone, chartered first, executed on approval.

## Scope (at execution)

In scope:

1. A full link inventory before any move: every relative link inside this repository, and every inbound link from other jdlongmire repositories naming a current path. Known inbound holders at charter time: the biblical-worldmodel principles pointer (names charter/christian-designism-principles.md and programme/hard-core.md), the designed-functional-maturity repository map (names the charter path), this repository's README and registry/REPOSITORIES.md, and CITATION.cff if it cites paths.
2. The directory moves, by git history-preserving rename where the tooling allows, in a single executing pull request.
3. Rewrite of every internal relative link to the new paths.
4. Companion pull requests in each repository the inventory shows holding an inbound link, updating those paths in step with the move.
5. A README note recording the old-to-new path mapping, so a reader holding an old path can find the new one.

Out of scope:

- Any change to the content of charter, hard-core, register, line, or issue text beyond link paths. A wording change found necessary during execution stops and goes to JD.
- Renumbering or restructuring any other repository.
- Deleting the old paths' history. Git history carries it; no stub files are left unless JD directs otherwise.

## Verification (at execution)

- A scripted link check over this repository after the move: every relative link resolves to a file that exists at the new path. The check must be able to fail, and its output is filed as package evidence.
- The same check, or a targeted readback, for each companion repository's updated links.
- A tree listing read back from main showing the enumerated structure and no leftover unenumerated directory.

## Disposition

Charter open. Execution begins only on JD's recorded approval of the target tree, in this package or in the session that reviews it. On execution and verification, this package closes with the link-check output as evidence.

Human-Curated, AI-Enabled (HCAE)

## Execution record (2026-11-23)

JD approved the target tree as proposed ("Approved", BWM alignment session, 2026-11-23). The refactor executed the same day: full-tree move in one commit, internal path references rewritten in 33 files, one pre-existing broken link (principles to hard core) found by the link check and fixed, companion updates filed in biblical-worldmodel and designed-functional-maturity for the inbound paths they hold. Post-move link check: 214 relative links, 0 failures. Full inventory and check output: [evidence/link-check-2026-11-23.md](evidence/link-check-2026-11-23.md).
