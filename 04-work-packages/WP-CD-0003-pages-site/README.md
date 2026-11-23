# WP-CD-0003: GitHub Pages site for the governing repository, at designism.thinxai.net

**Status:** In execution, 2026-11-23. Directed by JD Longmire in the BWM alignment session: stand up a Pages site for this repository on the biblical-worldmodel pattern, with the custom domain designism.thinxai.net included in this package's scope on his instruction.

## Purpose

The governing layer had no published face: its charter, hard core, and registers were readable only inside GitHub. This package gives the programme a public front door that presents the framework and points to the documents of record, which stay where they are. The site is presentation, not a second source: nothing on it supersedes the governing texts in this repository.

## Scope

1. A site source at `08-site/` (continuing the enumerated tree): MkDocs configuration, the pinned dependency set proven by the biblical-worldmodel build, and four pages (home, the programme, registers, lines and repositories) drawn from the governing texts without new claims.
2. A publication workflow at `.github/workflows/pages.yml` on the biblical-worldmodel pattern: pinned action versions, a strict MkDocs build as the gate, artifact upload, and deployment only from main.
3. GitHub Pages enabled on this repository with the workflow build type.
4. The custom domain **designism.thinxai.net** set on the Pages site, mirroring worldmodel.thinxai.net. The DNS record itself (a CNAME from designism to jdlongmire.github.io) sits in the thinxai.net zone, outside this repository; if it is not already present, adding it is JD's step and is recorded here as the package's one external dependency.
5. A website pointer in this repository's README.

## Verification

- The strict MkDocs build passes locally before filing, and the workflow's build job passes on the pull request.
- After merge and enablement, the deployed site is fetched at its live address and the four pages are confirmed present.
- The package closes when the site serves over HTTPS at designism.thinxai.net. If the DNS record is outstanding, the package stays open with that single item named.

## Out of scope

- Moving or duplicating governing content into the site. The documents of record remain the files in this repository; the site links to them.
- Any change to charter, hard-core, or register content.

Human-Curated, AI-Enabled (HCAE)
