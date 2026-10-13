# Systematically Developing Software with AI

**Illustrative course concept, prepared for a university teaching demonstration, October 2026.**

This repository holds a small static website for a hypothetical course concept: *Systematically Developing Software with AI*, Bachelor Computer Science, 3rd semester, 14 weeks. It is a teaching artifact. It is not an existing course offering, and no enrolment, submission or examination system stands behind it.

The content mirrors the course concept documents prepared alongside the teaching demonstration: the fourteen-week schedule, the week 5 lecture and its exercise, the weekly exercise track, the semester project, and the source register behind the resources page.

## What is here

| File | Page |
|---|---|
| `index.html` | Overview: course frame, learning objectives, AI-use policy, refresher links |
| `schedule.html` | The fourteen weeks, by block, with project milestones |
| `week5.html` | Week 5: objectives, lecture outline, Exercise 5 in full, reading |
| `exercises.html` | Weeks 1 to 13: what to do, what to submit, which milestone it feeds |
| `project.html` | The five project options, the milestones, the final deliverable |
| `resources.html` | Primary sources, grouped, with venues |
| `style.css` | The single stylesheet |

Plain HTML and CSS. No JavaScript, no build step, no tracking, no external fonts. It is designed to be read on a phone, since the link is distributed by QR code.

## Running it locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publishing

The site is served by GitHub Pages from the repository root on the default branch. Repository settings, Pages, source "Deploy from a branch", branch `main`, folder `/ (root)`.

## Conventions

- British spelling throughout.
- No em dashes. Colons, commas and middle dots instead.
- Palette: blue `#005176`, cyan `#00A1C0`, coral `#E05A52`, ink `#33383D`, muted `#8C8C8C`, tint `#EFF4F7`, pale `#DDE8EE`. Arial and Helvetica stack.
- Every page carries the honesty line in its footer.
- No university branding, no module code, no department name.
- Resources link to primary sources only. Nothing from anyone else's teaching material appears here.
