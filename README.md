Pinball Project Template
========================

[![Pinball Project Template](https://github.com/deathsave/pinball-project-template/actions/workflows/python-app.yml/badge.svg)](https://github.com/deathsave/pinball-project-template/actions/workflows/python-app.yml)

This is an opinionated starter template for creating Mission Pinball Framework
(MPF) based machine configurations.

Directory Structure
-------------------

```text
.
├── .gitignore          # Patterns we don't want in version control
├── .github/workflows/  # Config for running automated tests on `git push`
├── .xubuntu/           # Production machine setup scripts/config
├── bin/                # Developer and runtime entrypoints (dev/run/test)
├── code/               # Machine-wide custom code goes here
├── config/             # Primary/base configuration
├── data/               # (system) High scores and other production data
├── images/             # Slide assets and preload artwork
├── modes/              # Per-mode config/code/assets
├── monitor/            # Plotting switches/lights in `mpf monitor`
├── shows/              # Reusable shows (see https://missionpinball.org/latest/shows/content/)
├── sounds/             # Audio assets (music/sfx/voice, often with preload/)
├── tests/              # Pytest integration/unit tests for game behavior (DON'T SKIP THIS)
├── videos/             # Video loops/clips for attract and mode displays
├── logs/               # (system) Local runtime logs for debugging
├── Procfile.dev        # Config for multi-process dev (mpf, mpf-mc, monitor)
└── README.md           # This file
```

Real projects built around this starter template:

- [COMBAT!](https://github.com/deathsave/combat)
- [Grand Prix '86](https://github.com/deathsave/grand-prix)
- [Futurama](https://github.com/deathsave/futurama)

- Optional directories are added as projects grow (`docs/`, `web/`, `fonts/`, `misc/`,
  `code/`) without changing the core layout.
