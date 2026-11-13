# Maël Ritouet

Computer engineering student at **ISEN Méditerranée** (Toulon), heading for the **cybersecurity** track.
I learn by building things end to end, then measuring whether they actually work.

Right now: building **Poly'sen**, a play-money prediction market for ISEN students, and working toward an **AI × security** project (attacking and defending AI agents in an isolated lab).

---

## Featured projects

### ♟️ [self-trained-chessbot](https://github.com/maelritouet/self-trained-chessbot) · [play it in your browser](https://maelritouet.github.io/self-trained-chessbot/)
A small GPT (10.7M / 25.2M params) trained from scratch on 3M Lichess games. It is never told the rules: it learns to write moves one character at a time.
- **97.7%** legal moves on first try, solves **26%** of puzzles rated under 1000
- Full pipeline: data streaming → training on a Kaggle T4 → evaluation vs Stockfish → ONNX export → in-browser inference, models on Hugging Face
- 15 written design decisions, test suite, model card

`PyTorch` `Transformers` `ONNX Runtime Web` `python-chess` `Hugging Face`

### 🌊 [ThermoMaris](https://github.com/maelritouet/thermomaris) · Ocean Hackathon Toulon 2026
Interactive educational map of marine heatwaves off the French coast, built with a team of 10.
- Live Copernicus Marine data pipeline + marine-heatwave detection (Hobday method)
- FastAPI backend, React/TypeScript front with three depth levels (discover / explore / expert)

`Python` `FastAPI` `TypeScript` `React` `Vite`

### 🔐 [Azure VM Hardening Lab](https://github.com/maelritouet/Azure-VM-Hardening-Lab)
Securing an Ubuntu VM on Azure: SSH key-only access, no root login, UFW, NSG rules restricted to a single IP, all scripted.

`Azure` `Linux` `Bash` `UFW`

### 🎮 [Platformer.C](https://github.com/maelritouet/Platformer.C)
Medieval-fantasy platformer in C  I owned the physics engine and rendering: coyote time, jump buffering, AABB collisions, bitwise ARGB transparency.

`C` `X11`

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
