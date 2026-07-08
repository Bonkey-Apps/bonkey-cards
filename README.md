# Bonkey Cards

Public GitHub Pages site for **Bonkey Cards** — an offline-first mobile card
game (Hearts, Spades, Tens, Go Fish, Gin Rummy).

- **Landing page:** served at the repository root.
- **Free web demo (solo-only):** served under [`/app/`](./app/).

This repository is a **deployment target only**. Its contents (the landing
site and the `app/` web export) are published automatically from the private
`Bonkey-Apps/bonkey-cards-app` repo via its `CI Pages Deploy` workflow, which
opens and auto-merges `web-export-*` pull requests here. Do not edit the
generated files by hand — changes are made in `bonkey-cards-app` and flow
downstream.

> The web build is **solo-play only**: there is no Bluetooth in a browser, so
> multiplayer is unavailable on web by design.
