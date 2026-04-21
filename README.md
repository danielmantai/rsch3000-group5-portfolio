# RSCH3000 Group 5 Portfolio of Learning

Static HTML portfolio site for the RSCH3000 Applied Research Methods final summative assessment (April 2026).

**Group 5:** Jacob Meissner, Daniel Mantai, Lexi Match
**Instructor:** Dr. Mary McNabb
**Institution:** Northern Alberta Institute of Technology

## What this is

A nine-page static site presenting the group's applied research on homelessness in Edmonton, organized around the ESN Connect shelter-issued identity concept. The live prototype (ESNConnect worker portal) is a separate deliverable linked from the Prototype page.

## Pages

1. `index.html` — Home, project summary, team bios
2. `research-question.html` — Research question and rationale
3. `systemic-design.html` — Iceberg, causal loop, empathy map, future-state map
4. `literature-review.html` — Evidence base with critical appraisal
5. `prototype.html` — ESNConnect worker portal and the ESN ID card
6. `business-model.html` — Business Model Canvas
7. `final-proposal.html` — Pitch, systemic impact, trade-offs, stakeholder perspectives
8. `reflections.html` — Ethics, AI use, group learnings
9. `references.html` — Consolidated APA 7 list

## Local preview

Open `index.html` directly in a browser. No build step, no dependencies beyond Google Fonts (loaded via CDN).

## Deployment (GitHub Pages)

1. Create a fresh GitHub repo named `rsch3000-group5-portfolio` under your account.
2. Copy the contents of this folder (everything except `README.md` if desired) to the repo root.
3. Push to `main`.
4. Repo Settings → Pages → Source: Deploy from branch → `main` / `/ (root)`.
5. Site will be live at `https://<username>.github.io/rsch3000-group5-portfolio/` within a minute.

## Design direction

Editorial / academic journal aesthetic. Deliberately distinct from ESNConnect (which uses institutional blue + gold and a utility-software dashboard layout) so the portfolio and the prototype read as two separate deliverables.

- Display: Fraunces (variable serif)
- Body: Inter Tight
- Ink: `#0b2545` deep navy
- Paper: `#faf6f0` warm cream
- Accent: `#c65f4f` muted terracotta

All tokens in `assets/css/styles.css`.

## Status

Skeleton + ported content. Placeholders remain for:
- Team bios and headshots (group members to provide)
- Literature review critical appraisal (Jacob)
- Final Proposal opening hook and closing CTA
- Future-state system map image
- Empathy map image (to extract from Week 9 submission)
- Consolidated APA 7 reference list (Daniel)
- Optional narrated pitch video (group decision by Apr 21)
- ESNConnect live URL for the prototype button

Each placeholder is clearly labeled in the HTML with `<div class="placeholder">` blocks so the group can scan for what's missing.
