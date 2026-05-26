# DockPops Releases

This repository hosts the public release artifacts for [DockPops](https://dockpops.app) — Mac OS Dock launcher utility.

- **Source code** lives in the private [Pixley-Growth/dockpops](https://github.com/Pixley-Growth/dockpops) repo.
- **DMG downloads** are attached to each GitHub Release here under [Releases](https://github.com/Pixley-Growth/dockpops-releases/releases).
- **Auto-updates** are served via the Sparkle appcast at `docs/appcast.xml`, served via GitHub Pages at <https://pixley-growth.github.io/dockpops-releases/appcast.xml>.

Customers don't need to interact with this repo directly. The DockPops app's "Check for Updates…" menu does all the work behind the scenes — fetching the appcast, downloading the DMG, verifying its EdDSA signature against the public key bundled in the installed app, and relaunching when ready.

Issues, feature requests, support: see the main DockPops support channels.
