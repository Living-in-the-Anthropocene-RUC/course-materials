# How to add your materials

Written for the teaching team. You do not need to install anything, you do not need to learn git,
and you cannot break this by uploading a file. Everything below happens in your web browser.

You need a free GitHub account and an invitation to the
[Living-in-the-Anthropocene-RUC](https://github.com/Living-in-the-Anthropocene-RUC) organization.
Laura sends the invitation.

## Upload your slides

1. Open the [`sessions/`](sessions) folder and click the folder with your date on it. Folders are
   numbered and dated, so session 6 on 12 October is `06_2026-10-12_climate-psychology`.
2. Click the green **Add file** button near the top right, then **Upload files**.
3. Drag your PDF into the box, or click **choose your files**.
4. In the small box underneath, write one line saying what you added, for example
   `Add slides for 12 October session`.
5. Click **Commit changes**.

The file is public within a few seconds. You can upload several files at once, and you can upload a
newer version of the same file later. Old versions stay in the history, so nothing is lost.

## Edit the text of your session page

Every session folder has a `README.md` (the session description) and a `readings.md` (the reading
list). To change either one:

1. Click the file name to open it.
2. Click the pencil icon at the top right.
3. Type. The formatting is Markdown: `#` starts a heading, `-` starts a bullet, `**bold**` is bold.
   Anything you type as plain text works fine.
4. Click **Commit changes**, then **Commit changes** again in the box that appears.

Please fill in your name and your session title in your `README.md`, and add a two or three sentence
blurb. That blurb is what a student outside the elective reads when deciding whether to come.

## Readings: cite them, do not upload them

**Do not upload publisher PDFs of journal articles or book chapters.** This repository is public.
Sharing a licensed PDF with the students on Moodle is fine, because Moodle is a closed classroom.
Putting the same PDF on the open web is redistribution, and it is not ours to authorize.

Instead, add the citation and a DOI link to your `readings.md`. Like this:

```
Nakkerud, E. (2021). "There Are Many People Like Me, Who Feel They Want to Do
Something Bigger": An Exploratory Study of Choosing Not to Have Children Based on
Environmental Concerns. Ecopsychology, 13(3), 200-209.
https://doi.org/10.1089/eco.2020.0057

RUC students: available through the university library. Registered students also
find the PDF on Moodle.
```

Two exceptions you can upload in full:

- Anything you wrote yourself: your own slides, handouts, worksheets, exercise instructions.
- Anything openly licensed. If the article page says Creative Commons, CC BY, or open access, the
  PDF can live here. Add the license name next to the citation.

If you are not sure, cite it and leave the PDF on Moodle. That is always safe.

## What format to upload

**PDF for slides.** Students open PDFs on any phone or laptop, and the layout does not shift. Export
from PowerPoint or Keynote with File, then Export or Save as PDF.

Add the `.pptx` or `.key` file next to the PDF only if you want colleagues to reuse or adapt your
slides. That is welcome but not expected.

Handouts and exercise instructions are best as PDF too, or as Markdown text if you prefer to write
them directly in the browser.

## Naming files

Lower case, hyphens instead of spaces, date at the end, and only English letters:

```
climate-psychology-slides-2026-10-12.pdf     yes
commons-game-handout-2026-11-02.pdf          yes

Slides ÆØÅ 12. oktober (endelig version).pdf  no
```

Spaces and Danish characters in filenames break links for some students, so the repository sticks to
plain ASCII.

## This is the open web

Everything you commit is visible to anyone, is indexed by search engines, and stays in the history
even after you delete it. So please keep out:

- Student names, student numbers, grades, and anything from an exam
- Photographs of people who did not agree to be published
- Passwords and account details, including the Instagram login
- Drafts you would not want a stranger to read

If something sensitive does get committed, tell Laura or John rather than just deleting it. Deleting
a file does not remove it from the history, and cleaning that up properly takes a separate step.

## Starting a session folder from scratch

All ten session folders already exist, so you should not need to create one. If you do need a new
folder, copy the two files from [`sessions/_TEMPLATE`](sessions/_TEMPLATE) and fill them in.

## Questions

Ask Laura Horn (lhorn@ruc.dk) about the course and the materials. Ask John Shorter about anything
GitHub is doing that it should not.
