---
description: Check the site before publishing (stale events, broken links, drift)
---
Read-only check of `index.html`, `talks.html`, `research.html`, `teaching.html`, `about.html`
(never touch `Backup/`). Report findings; change nothing unless I say so.

1. **Stale upcoming** — events in `index.html` "Upcoming Events" whose date is before today
   (today's date is in the environment context). List them and offer to roll each into the right
   year under "Past Events (Selected)".
2. **Research filter integrity** — any `<li>` under Publications missing `class="publication-item"`
   or a valid `data-category` (`preprint`/`journal`/`conference`).
3. **Nav drift** — the `<div class="nav">` link list differing across the 5 files.
4. **Ordering** — any year `<h3>` out of descending order, or an entry not newest-first in its group.
5. **Dead links** (only if I ask — needs network) — `href`s that 404.

End with a short prioritized list and offer to fix.
