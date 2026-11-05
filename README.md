# H446 Networks · interactive workbooks

Static site for GitHub Pages. No build step.

```
index.html                  landing page (links to each lesson)
lesson-1/index.html         Lesson 1 · Fundamentals of Networking workbook
.nojekyll
```

## Deploy
Repo: `eltham-college-cs/h446-networks`, published with GitHub Pages from `main` / root.
Live at `https://eltham-college-cs.github.io/h446-networks/lesson-1/`.

PDF export uses html2pdf.js 0.14.0 (MIT) from jsDelivr, pinned with a subresource-integrity hash. If it is blocked, Export falls back to the print dialog (Save as PDF).

If you use a different repo name, update the links in the slides.com deck: slide 5 “Your workbook” (link and QR code) and the embedded activity on slide 9.

## How students use it
- Answers save in the browser (localStorage) on that device. Nothing is sent anywhere.
- **Export to PDF** downloads `Networks-L1-Workbook-<Name>.pdf` with every answer and an auto-marked score per activity; students attach it to the Teams assignment. **Print instead** opens the same report for Print → Save as PDF if a download is blocked.
- Drag and drop works with a mouse, a touchscreen (drag, or tap a chip then tap a box) and the keyboard (Enter on a chip, Tab to a box, Enter).

## Embed one activity in a slide
Add `?embed=<section id>` to show a single activity full-width, e.g.
`https://eltham-college-cs.github.io/h446-networks/lesson-1/?embed=media`
Section ids: `purpose`, `media`, `hardware`, `hub`, `switch`, `routers`, `addr`, `mvi`, `lanwan`.
