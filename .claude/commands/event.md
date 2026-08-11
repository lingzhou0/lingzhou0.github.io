---
description: Add an upcoming talk/conference to the homepage
argument-hint: <event name>, <venue/institution>, <date>[, url]
---
Add an upcoming event to the front page. Details: $ARGUMENTS

Follow the "new event" recipe in CLAUDE.md: insert one `<li>` into the **Upcoming Events**
`<ul>` in `index.html`, in descending-date order, using the `YYYY/M/D` date format and the
file's 8-space indentation. Wrap the event name in `<a href="URL">…</a>` only if a URL is given.
If the date or event name is missing, ask. Afterward show `git diff --stat`, then commit and push — unless something needed a judgment call or is worth my review, in which case surface it and ask before pushing.
