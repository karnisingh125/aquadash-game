# AquaDash — Underwater Endless Fish Runner

An interactive, browser-based underwater endless runner web game inspired by the Google Chrome Dino game, built using **HTML5 Canvas, CSS3, and Vanilla JavaScript** through an AI-assisted Prompt Engineering workflow.

## Features
- **Dino-Style Underwater Gameplay:** Swim along the ocean floor, jump over coral spikes and sea urchins, and dive under floating jellyfish.
- **Distance-Based Speed Scaling:** Speed increases smoothly with running distance (`1.0x` up to `~2.0x`) for fair, progressive difficulty.
- **Responsive Jump Physics:** Variable jump height (short tap vs. full press) and 90 ms jump buffering.
- **Safe Pearl Collectibles:** Glowing pearls award `+25` bonus points with collision-free spawn clearance from obstacles.
- **Synthesized Web Audio SFX:** Built-in jump, pearl, milestone, and crash sounds with a Mute toggle (no external audio files required).
- **Zero Dependencies:** Runs directly in any modern browser with no build step or backend required.

## Controls
- **Jump / Swim Up:** `Space`, `Up Arrow`, `W`, or click/tap the stage
- **Dive / Duck:** Hold `Down Arrow`, `S`, or the on-screen Dive button
- **Pause / Resume:** `P` or the Pause button

## Project Structure
- `index.html` — Complete self-contained HTML5, CSS3, and JavaScript game
- `.cursor/rules/web_game_rules.mdc` — Cursor AI coding standards used during development
- `LICENSE` — MIT License
- `README.md` — Audited project documentation

## How to Run Locally
1. Clone or download this repository.
2. Double-click `index.html` (or open it in Chrome, Edge, or Firefox).

## Deploy on Vercel
1. Push this repository to GitHub.
2. Log in to [Vercel](https://vercel.com), click **Add New Project**, and import your GitHub repository.
3. Keep the default static settings (Framework Preset: **Other**, Build Command: empty, Output Directory: `.`) and click **Deploy**.

## License
This project is licensed under the MIT License — see the `LICENSE` file for details.
