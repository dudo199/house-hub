# House Completion Hub

A single-page project hub for finishing a 3-level townhouse: a 3D / 2D model of the house, tasks by trade and room, a timeline, floor plans with furniture, electrical and plumbing points, distribution boards and circuits with BS 7671 checks, PDF drawings, wall works, and a budget with supplier quotes.

## Two ways to open it

- **In Claude** (main version, with AI features): the hub's Claude artifact link.
- **On GitHub Pages**: https://dudo199.github.io/house-hub/ — the same app. It saves to the private repo `dudo199/house-hub-data` (file `sync/github.json`) using a fine-grained GitHub access key you paste in once per device. AI features (Brain dump, Plan my dates, next steps) and photo uploads only work in Claude.

A scheduled task keeps the two in step about once an hour. Where the same item was changed in both, the newer change wins.

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript in one file). Contains no house data.
