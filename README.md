# Living World — Hearth & Hinterland (v0.4)

**Play on Android:** https://tkar19.github.io/living-world-public-/

This public repository contains **only the generated standalone HTML game**. The authoritative modular source, automated tests, and development history remain in the private `tkar19/living-world` repository.

## What's new in v0.4

- Map-first full-screen game view with five context-driven dock menus, including a touch-friendly mobile drawer.
- Softer terrain, more layered trees and coastlines, closer starting camera, and improved visual work activities.
- Extended autonomous Leytide ecology: persistent forest bloom/withering, passive local farming influence, resident experiences and voluntary grove tending. Magic acts even if the player does nothing.
- Continued 10-minute day (1×) and optional alternate speeds, with natural sub-hour movement interpolation.
- Save schema v3 with tested import migration from older v1/v2 worlds, preserving history and settlement state.

## Important Android instructions

Open the link directly in a modern Android browser; no computer, command-line setup or paid account is needed. Use **World → Export world** to preserve a portable backup before clearing browser storage or updating. Earlier local worlds are migrated on load; forward compatibility with older game versions is not guaranteed.

To construct: open **Build** in the bottom dock, choose a building, close the drawer by selecting the building, then tap a clear patch of grass on the world map. Drag to pan; pinch with two fingers to zoom.

**Verification:** the HTML blob published as `index.html` was confirmed identical to the verified private development artifact. Actual physical Android device testing and CDN cache propagation are not independently guaranteed by source CI.

## No private sources in this repository

No model API, billing, external runtime service or third-party game assets are required. Release history and source remain in private development.
