# Maël Ritouet

Computer engineering student at **ISEN Méditerranée** (Toulon), heading for the **cybersecurity** track.
I learn by building things end to end, then measuring whether they actually work.

Right now: building **Poly'sen**, a Polymarket-like play-money prediction market for ISEN students, and working toward an **AI × security** project (attacking and defending AI agents in an isolated lab).

---

## Featured projects

### ♟️ [self-trained-chessbot](https://github.com/maelritouet/self-trained-chessbot) · [play it in your browser](https://maelritouet.github.io/self-trained-chessbot/)
A small GPT (10.7M / 25.2M params) trained from scratch on 3M Lichess games. It is never told the rules: it learns to write moves one character at a time.
- **97.7%** legal moves on first try, solves **26%** of puzzles rated under 1000
- Full pipeline: data streaming → training on a Kaggle T4 → evaluation vs Stockfish → ONNX export → in-browser inference, models on Hugging Face
- 15 written design decisions, test suite, model card

`PyTorch` `Transformers` `ONNX Runtime Web` `python-chess` `Hugging Face`

### 🌊 [ThermoMaris](https://github.com/maelritouet/OCEAN-HACKATON) · Ocean Hackathon Toulon 2026
Interactive educational map of marine heatwaves off the French coast, built with a team of 10.
- Live Copernicus Marine data pipeline + marine-heatwave detection (Hobday method)
- FastAPI backend, React/TypeScript front with three depth levels (discover / explore / expert)

`Python` `FastAPI` `TypeScript` `React` `Vite`

### 🔐 [Azure VM Hardening Lab](https://github.com/maelritouet/Azure-VM-Hardening-Lab)
Securing an Ubuntu VM on Azure: SSH key-only access, no root login, UFW, NSG rules restricted to a single IP, all scripted.

`Azure` `Linux` `Bash` `UFW`

### 🎮 [Medieval Fantasy](https://github.com/maelritouet/medieval-fantasy-c)
A complete 2D platformer written from scratch in C in 10 days: 9 levels, 3 enemy types, 180+ animated sprites, saved best times. There's no game engine, so the physics, collisions, rendering, camera and level loading are all hand-built.
- Physics that feels good to play: coyote time, jump buffering, double jump, dash, AABB collisions
- Custom BMP → ARGB sprite loader using bitwise operations to get transparency from a library with no alpha channel
- Levels drawn as ASCII grids and parsed at load time; raw X11 keyboard reading to get held keys

`C` `OpenGL` `X11` `Make`

---

## Stack

**Languages:** Python · C · TypeScript/JavaScript · Bash · PHP
**Security:** Elastic SIEM · Wazuh · Wireshark · Azure NSG · Linux hardening
**ML:** PyTorch · ONNX · Hugging Face · Kaggle
**Tools:** Git · Linux (Fedora) · Claude Code

## Certifications
Cisco Junior Cybersecurity Analyst path · Cisco Cyber Threat Management · Security Blue Team Junior Analyst · arcX Cyber Threat Intelligence 101

## Languages
French (native) · English (C1) · Romanian (B1+) · German (B1) · Chinese (learning)

---

Outside of code I'm a freelance photographer → [maelritouet.art](https://maelritouet.art)
[LinkedIn](https://linkedin.com/in/maelritouet)
