# Eniversal

Eniversal is a builder network for Indian students: a place to show work, have deep conversations, find collaborators, launch projects, and meet at events.

This repository currently contains the product vision, PRD, UI/UX draft, repository research, and an interactive collection of 80 flywheels. The flywheel page explains the core loop in simple language:

**Feature → data → learning → improvement → impact → people → repeat**

## Materials

- `design/Eniversal 80 Flywheels.html` — standalone interactive HTML with a master wheel and 80 circular flywheels. Open it directly in a browser.
- `docs/Eniversal Vision.md` — product vision, audiences, six pillars, principles, and connected loop.
- `docs/Eniversal Flywheel Atlas.md` — detailed explanation of 80 candidate loops, measurements, failure modes, agent trajectories, and build order.
- `docs/Eniversal PRD.md` — initial product requirements and launch framing.
- `design/Eniversal UI-UX Draft.html` — current screen and feature draft.
- `design/networking-trajectory.html` — compact explainer for how networking changes as the product evolves toward agent assistance.
- `research/Eniversal repository research.pdf` — repository triage and implementation research.
- `research/all_platform_repositories.csv` — repository inventory used by the research.
- `design/Eniversal sketch.png` — source whiteboard sketch.

## Host the flywheel collection

The repository root contains `index.html`, so it is ready for any static host. It needs no build command, package install, server code, database, or external dependency.

- **GitHub Pages:** enable Pages for the `main` branch and repository root.
- **Netlify:** import the repository with build command empty and publish directory `.`.
- **Vercel:** import the repository as a static project with no build command.
- **Local:** open `index.html` directly in a browser.

The hosted entry point is the same interactive collection as `design/Eniversal 80 Flywheels.html`: it includes search, group filtering, step explanations, and a larger view for each wheel. `404.html` mirrors the single-page app so static hosts can serve the experience for fallback routes.

## Status

This is a product and design repository. The implementation is a documented direction and prototype material; the backend and production integration are not included yet.
