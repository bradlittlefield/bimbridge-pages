# bimbridge-pages

Public GitHub Pages host for [BIMBridge](https://github.com/bradlittlefield/bimbridge) interactive project dashboards.

Source code lives in the private `bimbridge` repo. This repo contains only compiled HTML dashboards, served free via GitHub Pages.

## Dashboards

| Project | URL |
|---|---|
| LPD Analysis | https://bradlittlefield.github.io/bimbridge-pages/lpd-analysis.html |

## How it works

1. Dashboard built as a React artifact in Claude
2. Compiled to self-contained HTML (no build step — Babel via CDN)
3. Committed here
4. Notion embeds the `github.io` URL in the project page

## Adding a new dashboard

Drop a `.html` file in the root of this repo and commit. It's live immediately at `https://bradlittlefield.github.io/bimbridge-pages/<filename>.html`.
