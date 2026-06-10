# Claw Code

<p align="center">
  <a href="https://github.com/code-yeongyu/lazycodex">
    <img src="https://img.shields.io/badge/LazyCodex-codex%20for%20no--brainers-111111?style=for-the-badge&logo=github&logoColor=white" alt="LazyCodex banner" />
  </a>
  <a href="https://github.com/Yeachan-Heo/gajae-code">
    <img src="https://img.shields.io/badge/Gajae--Code-red--claw%20agent%20harness-B22222?style=for-the-badge&logo=github&logoColor=white" alt="Gajae-Code banner" />
  </a>
</p>

Claw Code is the public Rust implementation of the `claw` CLI agent harness.
The canonical implementation lives in [`rust/`](./rust), and the current source of truth for this repository is **ultraworkers/claw-code**.

## Current repository shape

- **`rust/`** — canonical Rust workspace and the `claw` CLI binary
- **`USAGE.md`** — task-oriented usage guide for the current product surface
- **`PARITY.md`** — Rust-port parity status and migration notes
- **`ROADMAP.md`** — active roadmap and cleanup backlog
- **`PHILOSOPHY.md`** — project intent and system-design framing
- **`src/` + `tests/`** — companion Python/reference workspace and audit helpers; not the primary runtime surface

## Ownership / affiliation disclaimer

- This repository does **not** claim ownership of the original Claude Code source material.
- This repository is **not affiliated with, endorsed by, or maintained by Anthropic**.
