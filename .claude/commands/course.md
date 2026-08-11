---
description: Add a course to the Teaching page
argument-hint: <term>, <course title>[, code][, syllabus url]
---
Add a course to `teaching.html`. Details: $ARGUMENTS

Follow the "new course" recipe in CLAUDE.md: a new `.course-item` `<div>` at the **top** of the
right institution's block (newest term first), term written as `Season YYYY`. Include a role
(`Teaching Assistant,` / `Mentor,`), link (`Syllabus` / `Course Page` / `Recitation Notes`),
and `<span class="course-code">` only if provided. If the institution has no section yet, ask
before adding a new `<h2>`. Show `git diff --stat`, then commit and push — unless something needed a judgment call or is worth my review, in which case surface it and ask before pushing.
