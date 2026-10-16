# Portfolio site

Darren Lee's portfolio, served at [darrenplee.com](https://darrenplee.com) via GitHub Pages.

Plain HTML/CSS/JS, no build step. Open any `.html` file directly, or serve the folder locally.

## Pages

- **index.html** — about page: photo, role/year, social links, bio
- **coursework.html** — semester/course list
- **projects.html** — project tiles (name, date, cover image, link), newest first
- **projects/** — one detail page per project:
  - `rf-generator-quadrupole-ion-guide.html` — RF Generator for Quadrupole Ion Guide (Spring 2026 to Present)
  - `pcb-board-fusion-dynamics.html` — Drone Docking Station/Structural PDB (Summer 2026)
  - `precision-focus-actuator.html` — Precision Focus Actuator (Fall 2025)
  - `esb-modular-gripper.html` — ESB Modular Gripper (Fall 2025)
  - `project-template.html` — duplicate this for a new project
- **resume.html** — embeds `assets/resume.pdf`

## Updating the resume

1. Replace `assets/resume.pdf` with the new PDF.
2. In `resume.html`, update the "updated" date and bump every `?v=` cache-bust param (format `YYYYMMDD`) so browsers load the new file.

## Images

- `images/profile.jpg` — headshot
- `images/projects/` — project cover images and detail-page images
- `images/nav/` — nav icons

## Design tokens

All colors/fonts live at the top of `css/styles.css` under `:root` — change them once to reskin every page.
