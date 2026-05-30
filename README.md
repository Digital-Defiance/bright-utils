# Bright Utils

Documentation hub for the [BrightDate](https://brightdate.org) utility ecosystem — file search, networking, timing, and the shell that ties them together.

**Live site:** [brightutils.digitaldefiance.org](https://brightutils.digitaldefiance.org)

## What's here

This repo is GitHub Pages only. The site lives in [`docs/index.html`](docs/index.html) and covers:

- The full **Bright Utils** stack (BSH, brightdate-rust, bright-findutils, bright-iputils)
- Color-enhanced, feature-extended tooling
- Unified [`%` format spec](https://github.com/Digital-Defiance/brightdate-rust/blob/main/FORMAT-SPEC.md) across the ecosystem
- Install instructions via the [Homebrew tap](https://github.com/Digital-Defiance/homebrew-tap)

## Related projects

| Project | Tools |
|---------|-------|
| [brightdate-rust](https://github.com/Digital-Defiance/brightdate-rust) | `bdate`, `btime`, `buptime`, `bcal`, `bwatch` |
| [bright-findutils](https://github.com/Digital-Defiance/bright-findutils) | `bfind`, `blocate`, `bupdatedb`, `bxargs` |
| [bright-iputils](https://github.com/Digital-Defiance/bright-iputils) | `bping`, `bclockdiff`, `btraceroute`, `bmtr`, `baudit` |
| [bsh](https://github.com/Digital-Defiance/bsh) | BrightShell — zsh-compatible shell with BrightDate built in |

Submodules in this repo mirror those projects for local reference.

## Deploy

Pushes to `main` that touch `docs/**` automatically deploy via GitHub Actions (`.github/workflows/pages.yml`).

To preview locally, open `docs/index.html` in a browser.
