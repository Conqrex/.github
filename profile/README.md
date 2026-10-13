<div align="center">

<a href="https://conqrex.com"><img src="assets/conqrex-banner.png" alt="Conqrex — Software &amp; Game Development" width="100%"></a>

<h3><code>CODE. CREATE. CONQUER.</code></h3>

<p><b>An independent software &amp; game development studio.</b><br>
We build our own engine, our own tooling, our own networking —<br>
then we build games on top of them.</p>

<p>
  <img src="https://img.shields.io/badge/Built%20with-C%23-F34113?style=flat-square&labelColor=0D131B" alt="Built with C#">
  <img src="https://img.shields.io/badge/Runs%20on-Web%20·%20Desktop%20·%20Android-F34113?style=flat-square&labelColor=0D131B" alt="Runs on web, desktop and Android">
  <img src="https://img.shields.io/badge/Rendering-WebGPU-F34113?style=flat-square&labelColor=0D131B" alt="WebGPU rendering">
  <img src="https://img.shields.io/badge/Open%20tools-MIT-F34113?style=flat-square&labelColor=0D131B" alt="MIT licensed tools">
</p>

<p>
  <a href="https://conqrex.com"><b>Website</b></a> ·
  <a href="https://conqrex.com/engine"><b>Engine</b></a> ·
  <a href="#open-source"><b>Open Source</b></a> ·
  <a href="https://conqrex.com/about"><b>About</b></a> ·
  <a href="mailto:sancak@conqrex.com"><b>Contact</b></a>
</p>

</div>

---

## Conqrex.Engine

One C# codebase rendering **2D, 2.5D isometric and 3D** — the foundation under every Conqrex title.

<a href="https://conqrex.com/engine"><img src="assets/conqrex-editor.webp" alt="The Conqrex editor with the Astral Veil project open: menus, tools, scene hierarchy and 3D viewport" width="100%"></a>

|     |     |
| --- | --- |
| **Every surface** | One codebase ships to the browser (WebAssembly), Android and desktop (Windows / macOS / Linux), plus a headless dedicated server. |
| **Deterministic core** | A project-selected fixed simulation tick (30–180 Hz, 60 by default) with fixed-point math; rendering interpolates as fast as the surface allows. |
| **Our own GPU layer** | A WebGPU-first rendering hardware interface, with WebGL2 and native `wgpu` backends behind it. |
| **Tools in one editor** | Scenes and prefabs, tile and terrain tools, pixel art (Conqrex Pixel), music (Conqrex Music) and built-in 3D modelling, next to physics, animation, audio and UI. |
| **Human + AI authoring** | AI-assisted tools work through the same operations as the editor's own menus, so every change lands in the undo history. |
| **Multiplayer, in progress** | RPCs, synchronised variables, observers, client prediction and reconciliation, with a dedicated server Player. |

The engine is in active development and public access is not available yet.

**[→ Meet the engine](https://conqrex.com/engine)**

## Games

**Astral Veil** is in development on Conqrex.Engine: a one-finger cosmic survival arcade with seven ships and eleven relics.

<p align="center">
  <a href="https://conqrex.com/#showcase"><img src="assets/astral-veil-home.webp" alt="Astral Veil title screen" width="31%"></a>
  &nbsp;
  <a href="https://conqrex.com/#showcase"><img src="assets/astral-veil-hangar.webp" alt="Astral Veil ship hangar" width="31%"></a>
</p>

Announcements land at **[conqrex.com](https://conqrex.com)**.

## Open source

Tools we built for our own workflow and released for yours.

| Project | What it does |
| --- | --- |
| **[Conqrex.CrewBeacon](https://github.com/Conqrex/Conqrex.CrewBeacon)** | Monitor AI provider quota, weekly limits, live local and remote Paseo agents, attention states and detailed daily usage history from one KDE Plasma 6 panel widget. |
| **[Conqrex.OctoPulse](https://github.com/Conqrex/Conqrex.OctoPulse)** | Every GitHub Actions run across all your repos and orgs, live in one KDE Plasma 6 panel widget — re-run, cancel, dispatch and read logs without opening a browser tab. |
| **[Conqrex.Dockswain](https://github.com/Conqrex/Conqrex.Dockswain)** | Manage Docker hosts over SSH from your panel: containers, compose, logs, SFTP file manager and nginx/certbot tooling. |

Issues and pull requests are welcome on every public repository.

## Work with us

Engine licensing, collaboration, or just a good question —
reach us at **[sancak@conqrex.com](mailto:sancak@conqrex.com)**.

---

<div align="center">

**[conqrex.com](https://conqrex.com)** · [sancak@conqrex.com](mailto:sancak@conqrex.com) · [@SancaK9](https://github.com/SancaK9)

<br>

<a href="https://conqrex.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/conqrex-wordmark-dark.svg">
    <img src="assets/conqrex-wordmark-light.svg" alt="Conqrex" width="240">
  </picture>
</a>

</div>
