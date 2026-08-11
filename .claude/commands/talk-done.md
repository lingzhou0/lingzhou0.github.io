---
description: File a delivered talk — homepage event → Past, and add it to Talks
argument-hint: <talk title> [@ venue, date]
---
A talk was delivered: $ARGUMENTS

Follow the "delivered / gave" recipe in CLAUDE.md and make BOTH edits:
1. `index.html` — move the matching event `<li>` from **Upcoming Events** to the right year
   under **Past Events (Selected)**, at the top of that year (keep `YYYY/M/D` format).
2. `talks.html` — add the talk under **Invited Talks** (default) or **Contributed Talks and
   Posters**, under the right year `<h3>`, at the top, in `(Mon D, YYYY)` format. Write the talk
   title in **Title Case** (capitalize major words; lowercase `and`/`with`/`of`/`in`/`the`…),
   even when the paper/source title is sentence case.

If the event isn't in Upcoming, or the section/year is ambiguous, ask. If I gave the same title
elsewhere, use a nested `<ul>` per the existing pattern. Show `git diff --stat`, then commit and push — unless something needed a judgment call or is worth my review, in which case surface it and ask before pushing.
