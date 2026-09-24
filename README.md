# Lunar Rover Game

Browser-based facilitation kit for the **Lunar Rover Mission** innovation simulation
(ODCE — Institute for Organizational Design and Collaboration Engineering, TU Hamburg).

Teams act as competing companies that design, build, program and pitch an Arduino-based
rover under a fixed development budget (17,000,000 units), staged phases, penalties and
peer voting.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | Landing page with links to both views |
| `host.html` | Facilitator dashboard: setup, timers, budget tracking, penalties, bonuses, peer voting, results |
| `player.html` | Projector / student view: live scoreboard, phase, timer |

## Usage

Open `host.html` (facilitator laptop) and `player.html` (projector) **in the same browser
profile and origin**. The player view reads the session state from `localStorage`
(key `lunar_rover_session`) and refreshes every 1.5 s.

### Session formats
- **Full (~4h)** — all phases, including the mid-development pitch (Phase 2A)
- **3h — skip 1st pitch**
- **3h — pre-built chassis** (focus on software, features, strategy)

## GitHub Pages

Pages is served from `main` / root.

- Students: `https://timtisc83.github.io/lunar_rover_game/player.html`
- Facilitator: `https://timtisc83.github.io/lunar_rover_game/host.html`

## Licence

Teaching material released as an Open Educational Resource under CC BY 4.0;
code under the MIT licence.
