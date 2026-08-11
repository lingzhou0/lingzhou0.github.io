---
description: Add a paper to Research (give an arXiv ID/DOI to auto-fill)
argument-hint: <arXiv id | DOI | URL>  or  manual title + authors + venue
---
Add a paper to `research.html`. Source: $ARGUMENTS

Follow the "new paper" recipe in CLAUDE.md. If given an arXiv id / DOI / URL, WebFetch it for
the title, author list, and date and fill the entry (keep me as `L. Zhou`, not bolded). Insert
at the **top of the `<ol>`** under the correct year `<h3>`, with `class="publication-item"` and
the right `data-category` (`preprint`/`journal`/`conference`). Confirm the parsed authors/venue
with me before saving if anything is unclear. Cross-check the title against the active-papers
table in `/Users/lingzhou/0RESEARCH/CLAUDE.md`. Show `git diff --stat`, then commit and push — unless something needed a judgment call or is worth my review, in which case surface it and ask before pushing.
