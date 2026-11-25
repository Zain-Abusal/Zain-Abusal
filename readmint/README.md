# Profile design setup

The profile combines two visual systems:

- **shieldcn** supplies the top and closing header artwork, using the Surface and Glow styles with a dark zinc palette and Geist typography.
- **Readmint** supplies the activity ticker, contribution visualization and stack graphic.

The README is intentionally restrained: no giant badge wall, no bright accent colors, compact project summaries and clear section hierarchy.

Readmint design files and fonts are fetched from the upstream repository at build time and pinned to `v0.5.1`.

## Customize

- Edit `settings.json` for the Readmint copy and stack groups.
- Edit `designs/horizon/renders.json` to change which Readmint graphics render.
- Edit the shieldcn header image URLs in the root `README.md` to change the header style, title or subtitle.

Upstream:
- https://shieldcn.dev/showcase
- https://github.com/MrLarkyy/Readmint
