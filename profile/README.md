# Dungeon Master Game Engine (DMGE)

Official open-source organization and asset ecosystem for **DMGE** — the next-generation, offline-first Virtual Tabletop (VTT) and procedural world simulation engine.

---

## ⚡ Core Philosophy & Architecture

- **100% Offline-First**: Built with IndexedDB and PWA service workers. Pull asset libraries once from GitHub and play indefinitely with zero internet connectivity.
- **JEV System 1 Decision Architecture**: Joint Evaluation Vector decision model performing multi-head classification and continuous scoring in sub-millisecond timeframes. No cloud LLMs, zero token costs, and zero hallucination.
- **Wave Function Collapse (WFC)**: Procedural dungeon, cavern, and wild map synthesis driven by 4-way socket adjacency constraints with automated line-of-sight raycasting walls (`BlockingSegment`).
- **In-Browser Dictation**: Native Web Speech API integration translating Game Master spoken descriptions into live, populated battlemaps in real time.
- **Scripted Actors & 8-Way Spriting**: Directional spritesheets, transparent WebM ambient video props, and bytecode patrol scripting.

---

## 📦 Asset Repositories

| Repository | Purpose | Format |
| :--- | :--- | :--- |
| [**dmge-tiles**](https://github.com/dmge-net/dmge-tiles) | Modular, socket-tagged tile library for procedural WFC map generation | 4-way sockets, normalized LOS walls, biomes |
| [**dmge-props**](https://github.com/dmge-net/dmge-props) | Interactive props, animated tokens, and scripted NPCs | WebM, SVG/PNG, 8-way sprites, patrol scripts |

---

## 🌐 Community & Links

- **Website**: [dmge.net](https://dmge.net)
- **Organization**: [github.com/dmge-net](https://github.com/dmge-net)
