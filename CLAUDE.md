# CLAUDE.md

## Project

Static Hugo website for the **DSAIL / MARS workshop** "Data-driven modelling of metallic materials across scales" (Lancaster Castle, 6–8 May 2026).

Deployed to: `https://mbuze.github.io/DSAIL_MARS_materials_workshop_2026/`

## Relation to planning files

This folder is the public GitHub repo. Private planning documents (proposal, notes, emails, logo sources) live alongside it:
```
2510_DSI/
├── private_planning/    ← LaTeX proposal, Obsidian notes, MARS branding
└── DSAIL_MARS_materials_workshop_2026/   ← this repo
```

Canonical speaker/schedule list: `../private_planning/website/obsidian_notes/planning/Up-to-date plan.md`

## Building locally

```bash
hugo server -D
```

## Deployment

Push to `main` branch → GitHub Actions builds and deploys to `gh-pages` branch automatically.

## Common updates

- **Add confirmed speaker**: edit `content/speakers/_index.md`
- **Add Eventbrite link**: edit `content/practical/_index.md`
- **Add talk titles**: edit `content/programme/_index.md`

## Theme

Blowfish (git submodule at `themes/blowfish`). Lancaster University crimson `#b5121b` defined in `assets/css/schemes/lancaster.css`.
