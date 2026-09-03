<p align="center">
  <img src="https://raw.githubusercontent.com/glowku/smash-bross-pepe/main/1.gif" alt="Pepe & Cat Smash Gameplay Showcase" width="100%">
</p>

# Pepe & Cat Smash

<p align="center">
  <a href="https://github.com/glowku/smash-bross-pepe/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/glowku/smash-bross-pepe?style=flat&color=blue" alt="License MIT">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/stargazers">
    <img src="https://img.shields.io/github/stars/glowku/smash-bross-pepe?style=flat&color=yellow" alt="Stars">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/network/members">
    <img src="https://img.shields.io/github/forks/glowku/smash-bross-pepe?style=flat&color=blue" alt="Forks">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/issues">
    <img src="https://img.shields.io/github/issues/glowku/smash-bross-pepe?style=flat&color=red" alt="Issues">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/pulls">
    <img src="https://img.shields.io/github/issues-pr/glowku/smash-bross-pepe?style=flat&color=green" alt="Pull Requests">
  </a>
  <a href="https://glowku.github.io/smash-bross-pepe/">
    <img src="https://img.shields.io/badge/Play_Online-ff69b4?style=flat&logo=githubpages&logoColor=white" alt="Play Online">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/commits/main">
    <img src="https://img.shields.io/github/last-commit/glowku/smash-bross-pepe?style=flat&color=purple" alt="Last Commit">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Made_with-Vanilla_JS-f7df1e?style=flat&logo=javascript&logoColor=black" alt="Made with Vanilla JS">
  </a>
  <a href="https://github.com/glowku/smash-bross-pepe/deployments">
    <img src="https://img.shields.io/github/deployments/glowku/smash-bross-pepe/github-pages?style=flat&label=Deployment&color=success" alt="Deployment">
  </a>
</p>


---

## Overview

**Pepe & Cat Smash** is a fast‑paced, 2D pixel‑art arena brawler built entirely with vanilla web technologies (HTML5, CSS, JavaScript). The game features responsive controls, high‑impact physics, and a roster of distinct meme‑inspired characters. Players charge attacks to launch opponents across the arena – with a full charge sending rivals flying over **3,000 miles** for an instant knockout.

The project is **open‑source** (MIT license), fully modular, and designed for easy extension. Whether you are a developer, pixel artist, or game designer, you are invited to contribute new characters, arenas, gameplay mechanics, or visual improvements.

[**Launch the live demo**](https://glowku.github.io/smash-bross-pepe/) – no installation required.

---

## Features

- **Launch Physics** – Charge your attack to determine knockback distance; max charge = instant KO beyond 3,000 miles.
- **10 Unique Character Classes** – Each fighter has a distinct moveset, stats, and special abilities.
- **Pixel‑Art Aesthetic** – Retro visuals combined with a 3D arena perspective for depth.
- **Adaptive AI Opponent** – The CPU adjusts its strategy based on your playstyle.
- **Low‑Latency Controls** – Responsive input for precise movement, aiming, and attack timing.
- **Match Statistics** – Track damage dealt, longest combo, biggest ejection, and KOs per round.
- **Best‑of‑3 KO System** – The first to land 3 knockouts wins the match.

---

## Gameplay & Controls

The game uses an **AZERTY keyboard layout** by default (adjustable in the code).

| Key | Action |
|-----|--------|
| `Q` / `D` | Move left / right |
| `Z` / `Space` | Jump (air recovery when launched beyond 2,500 miles) |
| `J` (hold) | Aim (direction) + charge basic attack |
| `K` (hold) | Charged special attack #1 |
| `L` (hold) | Charged special attack #2 |

**Combat mechanics**:

- **Aim anywhere** – Use `◀` / `▶` + `Z` (up) + `S` (down for spike) to direct attacks.
- **Charge levels** – 50% charge ≈ 1,000 miles (survivable); 100% charge = 3,000 miles (KO).
- **Defense** – Hold the direction opposite to incoming knockback to reduce distance.
- **Air save** – If you are launched beyond 2,500 miles, you gain a bonus third jump to recover.
- **Win condition** – Land 3 KOs on your opponent.

---

## Development

### Tech Stack

- **JavaScript (ES6)** – Pure logic, no frameworks.
- **HTML5 Canvas** – Rendering engine for pixel graphics and animations.
- **CSS3** – UI styling, responsive layout, and transitions.
- **GitHub Pages** – Hosting for the live demo.

### Project Structure
smash-bross-pepe/
├── index.html # Main game page
├── 1.gif # Gameplay showcase
├── LICENSE # MIT license
├── README.md # This file
└── .github/
└── workflows/ # GitHub Actions for automatic Pages deployment

text

### Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/glowku/smash-bross-pepe.git
Open index.html in any modern browser – no build tools or dependencies required.

(Optional) Serve with a local development server for live reload.

Contributing
We welcome contributions of all kinds – code, art, sound, documentation, or ideas. The project is structured to make adding new content straightforward.

What you can add
New characters – Create custom sprites (32×32 or 64×64 pixel art), define stats, and implement unique abilities.

Arenas and hazards – Design interactive stages with moving platforms, traps, or environmental effects.

Gameplay enhancements – Power‑ups, alternative win conditions, or local multiplayer support.

Audio & visual polish – Sound effects, background music, improved UI, or particle systems.

Contribution workflow
Fork the repository on GitHub.

Create a feature branch:

bash
git checkout -b feature/your-feature-name
Make your changes and commit them with a clear message.

Push to your fork:

bash
git push origin feature/your-feature-name
Open a Pull Request against the main branch of the original repository.

Guidelines
Keep code clean and well‑commented (JSDoc style appreciated).

Ensure new features do not break existing gameplay.

Test your changes in at least two different browsers.

For art assets, please provide source files (PSD, Aseprite, etc.) alongside the exported sprites.

License
Distributed under the MIT License. See the LICENSE file for full details.

Acknowledgments
Inspired by classic platform fighters and internet meme culture.

Built with passion by the open‑source community.

<p align="center"> <a href="https://github.com/glowku/smash-bross-pepe"> <img src="https://img.shields.io/badge/Star_on_GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="Star"> </a> <a href="https://glowku.github.io/smash-bross-pepe/"> <img src="https://img.shields.io/badge/Play_Now-ff69b4?style=flat-square&logo=googlechrome&logoColor=white" alt="Play"> </a> </p>
<p align="center"> <sub>Made with 💥 and 🐸 by the community. Smash on!</sub> </p>
