# Primer — Synaesthesia Engine

Context for picking up this project in a new session.

## What it is

A single-file browser visualizer (`index.html`). No build, no dependencies,
no backend. All HTML/CSS/JS is inline in that one file.

## State

- Published as a public GitHub repo: `nodesaint/synaesthesia-engine`.
- Deployed via GitHub Pages from the `main` branch root.
- Live at: https://nodesaint.github.io/synaesthesia-engine/

## How to deploy changes

The repo serves `main` directly. To ship:

```bash
git add -A && git commit -m "your message" && git push
```

GitHub Pages rebuilds automatically within ~1 minute.

## Notes

- The only source file is `index.html`. Edit it directly.
- Keep it dependency-free and self-contained — that's the design constraint.
