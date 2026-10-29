# Meathax LIST OF GLORY - TREASURE FINDER

GitHub Pages-ready static build. No npm, build step, database, or server is required.

## Deploy on GitHub Pages
1. Create a GitHub repository.
2. Upload **the contents of this ZIP** to the repository root. `index.html` must stay at the root.
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select `main` and `/ (root)`.

## Catalogue snapshot
- MAME 0.289 arcade parents: 11,487
- supplied MiSTer-covered snapshot: 2,434
- Not on MiSTer snapshot: 9,053

The Not on MiSTer mode is based on the supplied coverage snapshot. It is not presented as universal live coverage.

## Included workflow
- Not on MiSTer / All MAME toggle
- search, sorting, pagination
- genre, control, graphics, MAME status, research tier, manufacturer/year and hardware filters
- hide gambling/redemption and console bootleg clutter
- core-hunting, 2D, ambitious 3D, unseen and close-to-my-cores presets
- project stages, notes, interest, seen/hidden state, including a Show hidden recovery toggle
- shortlist/compare
- named saved presets
- workspace export/import
- shareable view links
- research drawer and agent brief
- optional muted hover video previews for the small reviewed-preview set
- remote gameplay screenshots with graceful failure fallback

All workspace data is stored in the browser's localStorage.

Raw provenance inputs are retained under `data/sources/`.
