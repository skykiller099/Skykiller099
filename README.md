<!--
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
   SKYKILLER099 · GITHUB PROFILE README · v3.0
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
-->

<div align="center">

<!-- ═══════════════ ANIMATED SVG HEADER ═══════════════ -->

<svg viewBox="0 0 900 200" width="900" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020510"/>
      <stop offset="100%" style="stop-color:#030a1a"/>
    </linearGradient>
    <linearGradient id="glow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#003aff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#003aff;stop-opacity:0"/>
    </linearGradient>
    <filter id="blur-glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="200" fill="url(#bg)" rx="4"/>

  <!-- Grid lines horizontal -->
  <g stroke="#071830" stroke-width="0.6" opacity="0.8">
    <line x1="0" y1="25" x2="900" y2="25"/>
    <line x1="0" y1="50" x2="900" y2="50"/>
    <line x1="0" y1="75" x2="900" y2="75"/>
    <line x1="0" y1="100" x2="900" y2="100"/>
    <line x1="0" y1="125" x2="900" y2="125"/>
    <line x1="0" y1="150" x2="900" y2="150"/>
    <line x1="0" y1="175" x2="900" y2="175"/>
  </g>
  <!-- Grid lines vertical -->
  <g stroke="#071830" stroke-width="0.6" opacity="0.8">
    <line x1="100" y1="0" x2="100" y2="200"/>
    <line x1="200" y1="0" x2="200" y2="200"/>
    <line x1="300" y1="0" x2="300" y2="200"/>
    <line x1="400" y1="0" x2="400" y2="200"/>
    <line x1="500" y1="0" x2="500" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
    <line x1="700" y1="0" x2="700" y2="200"/>
    <line x1="800" y1="0" x2="800" y2="200"/>
  </g>

  <!-- Scan line sweep -->
  <rect x="0" y="0" width="900" height="2" fill="url(#glow)" opacity="0.6">
    <animateTransform attributeName="transform" type="translate" from="0,-2" to="0,202" dur="3.5s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner brackets -->
  <g stroke="#00d4ff" stroke-width="1.5" fill="none" opacity="0.85">
    <line x1="18" y1="32" x2="18" y2="16"/><line x1="18" y1="16" x2="34" y2="16"/>
    <line x1="882" y1="32" x2="882" y2="16"/><line x1="882" y1="16" x2="866" y2="16"/>
    <line x1="18" y1="168" x2="18" y2="184"/><line x1="18" y1="184" x2="34" y2="184"/>
    <line x1="882" y1="168" x2="882" y2="184"/><line x1="882" y1="184" x2="866" y2="184"/>
  </g>

  <!-- Side accent lines -->
  <line x1="6" y1="60" x2="6" y2="140" stroke="#00d4ff" stroke-width="1.5" opacity="0.4"/>
  <line x1="894" y1="60" x2="894" y2="140" stroke="#00d4ff" stroke-width="1.5" opacity="0.4"/>

  <!-- HUD labels -->
  <text x="24" y="12" font-family="monospace" font-size="7" fill="#00d4ff" opacity="0.6" letter-spacing="2">SYS://PROFILE.LOAD</text>
  <text x="730" y="12" font-family="monospace" font-size="7" fill="#00d4ff" opacity="0.6" letter-spacing="1.5">STATUS: ONLINE  ●</text>

  <!-- Glow behind title -->
  <text x="450" y="102" font-family="'Courier New', monospace" font-size="60" font-weight="900"
    fill="#00d4ff" opacity="0.06" text-anchor="middle" letter-spacing="16" filter="url(#blur-glow)">SKYKILLER099</text>

  <!-- Main title -->
  <text x="420" y="102" font-family="'Courier New', monospace" font-size="60" font-weight="900"
    fill="#daeeff" opacity="0.96" text-anchor="middle" letter-spacing="14">SKYKILLER</text>

  <!-- 099 neon accent -->
  <text x="808" y="102" font-family="'Courier New', monospace" font-size="60" font-weight="900"
    fill="#00d4ff" text-anchor="middle" letter-spacing="4" filter="url(#blur-glow)">099</text>

  <!-- Subtitle -->
  <text x="450" y="136" font-family="monospace" font-size="10.5" fill="#2d5c80" text-anchor="middle" letter-spacing="7">FULL-STACK  DEVELOPER  ·  SYSTEMS  ·  AUTOMATION</text>

  <!-- Bottom bar -->
  <rect x="220" y="165" width="460" height="1" fill="#081e38"/>
  <rect x="220" y="165" width="0" height="1" fill="#00d4ff" opacity="0.7">
    <animate attributeName="width" from="0" to="460" dur="2.2s" fill="freeze" begin="0.3s"/>
  </rect>
  <text x="220" y="179" font-family="monospace" font-size="6.5" fill="#1a3a5a" letter-spacing="1">BOOT.SEQUENCE</text>
  <text x="610" y="179" font-family="monospace" font-size="6.5" fill="#00d4ff" opacity="0.65" letter-spacing="1">[ 99.9% UPTIME ]</text>
</svg>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=13&duration=2800&pause=1200&color=00D4FF&background=00000000&center=true&vCenter=true&width=680&height=30&lines=%3E+boot+sequence+initialized+...+kernel+loaded;%3E+stack%3A+C+·+C%2B%2B+·+JS+·+TS+·+Python+·+Node.js;%3E+domains%3A+Systems+·+Web+·+Automation+·+Bots;%3E+philosophy%3A+"Write+code+that+outlives+you.")](https://github.com/skykiller099)

<br/><br/>

</div>

---

<div align="center"><sub><code>◈ SECTOR 01 — IDENTITY MATRIX ◈</code></sub></div>

---

<br/>

```
╔══[ SYS://USER.PROFILE ]══════════════════════════════════════════════════════╗
║                                                                              ║
║   ident    ──›  Skykiller099                                                 ║
║   class    ──›  Full-Stack Developer                                         ║
║   tier     ──›  ██████████  E L I T E                                        ║
║                                                                              ║
║   domains  ──›  [ Systems ]  [ Web ]  [ Automation ]  [ Bots ]              ║
║   stack    ──›  C · C++ · JavaScript · TypeScript · Python · Node.js        ║
║   os       ──›  Linux (primary)  ·  Windows (secondary)                     ║
║   editor   ──›  VS Code  ·  Sublime Text                                    ║
║                                                                              ║
║   uptime   ──›  99.9%  ●  ALWAYS ONLINE                                     ║
║   status   ──›  [ BUILDING ]  [ LEARNING ]  [ SHIPPING ]                    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

```python
#!/usr/bin/env python3
# skykiller099 — runtime profile

from typing import Literal
from dataclasses import dataclass, field

@dataclass
class Developer:
    alias:   str         = "Skykiller099"
    stack:   list[str]   = field(default_factory=lambda: [
                             "C", "C++", "JavaScript",
                             "TypeScript", "Python", "Node.js"
                           ])
    domains: list[str]   = field(default_factory=lambda: [
                             "Systems", "Web",
                             "Automation", "Bots"
                           ])
    mode:    Literal["elite"] = "elite"
    coffee:  float       = float("inf")
    limits:  None        = None

    def run(self) -> None:
        while True:
            self.build()
            self.learn()
            self.ship()

if __name__ == "__main__":
    Developer().run()
```

<br/>

---

<div align="center"><sub><code>◈ SECTOR 02 — PERFORMANCE METRICS ◈</code></sub></div>

---

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=skykiller099&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&bg_color=020510&title_color=00d4ff&icon_color=00d4ff&text_color=4d7fa8&ring_color=00d4ff" height="170"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=skykiller099&layout=compact&hide_border=true&theme=tokyonight&bg_color=020510&title_color=00d4ff&text_color=4d7fa8&langs_count=8" height="170"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=skykiller099&hide_border=true&background=020510&ring=00d4ff&fire=00aaff&currStreakLabel=00d4ff&sideLabels=4d7fa8&dates=1a3a5a&currStreakNum=e8f6ff&sideNums=e8f6ff&theme=dark" height="170"/>

</div>

<br/>

---

<div align="center"><sub><code>◈ SECTOR 03 — TECHNOLOGY MATRIX ◈</code></sub></div>

---

<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,js,ts,python,html,css&theme=dark&perline=7"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=nodejs,express,electron,discord,npm,axios&theme=dark&perline=6"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=mongodb,mysql,sqlite&theme=dark&perline=3"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,kali,raspberrypi,windows&theme=dark&perline=6"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=vscode,sublime,git,github,bash&theme=dark&perline=5"/>

</div>

<br/>

---

<div align="center"><sub><code>◈ SECTOR 04 — SKILL CALIBRATION ◈</code></sub></div>

---

<br/>

```
  ┌─────────────────────────────────────────────────────────────────────────┐
  │  TARGET: skykiller099  ·  SCAN: DEEP  ·  MODE: FULL SPECTRUM           │
  ├─────────────────────────┬────────────────────────────┬──────────────────┤
  │  DOMAIN                 │  TECHNOLOGY                │  PROFICIENCY     │
  ├─────────────────────────┼────────────────────────────┼──────────────────┤
  │  Systems / Low-Level    │  C · C++                   │  ▰▰▰▰▰▰▰▰▱▱  80% │
  │  Web Front-End          │  HTML · CSS · JS · TS      │  ▰▰▰▰▰▰▰▰▰▱  90% │
  │  Back-End               │  Node.js · Python · Expr   │  ▰▰▰▰▰▰▰▰▱▱  80% │
  │  Databases              │  SQL · MongoDB · SQLite    │  ▰▰▰▰▰▰▰▱▱▱  70% │
  │  Infrastructure         │  Linux · Apache · Pterod   │  ▰▰▰▰▰▰▰▰▱▱  80% │
  │  Automation & Bots      │  Discord.js · Electron     │  ▰▰▰▰▰▰▰▰▰▱  90% │
  ├─────────────────────────┴────────────────────────────┴──────────────────┤
  │  COMPOSITE  ████████████████████░░░░  82 / 100   [ ◈ ELITE TIER ]     │
  └─────────────────────────────────────────────────────────────────────────┘
```

<br/>

---

<div align="center"><sub><code>◈ SECTOR 05 — ACTIVITY FEED ◈</code></sub></div>

---

<br/>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=skykiller099&bg_color=020510&color=00d4ff&line=00d4ff&point=e8f6ff&area_color=00d4ff12&area=true&hide_border=true&radius=3&custom_title=Contribution+Timeline)](https://github.com/skykiller099)

</div>

<br/>

---

<div align="center"><sub><code>◈ SECTOR 06 — CONTRIBUTION TRACE ◈</code></sub></div>

---

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/skykiller099/skykiller099/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/skykiller099/skykiller099/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/skykiller099/skykiller099/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>

---

<div align="center"><sub><code>◈ SECTOR 07 — ACHIEVEMENT LOG ◈</code></sub></div>

---

<br/>

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=skykiller099&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8)](https://github.com/skykiller099)

</div>

<br/>

---

<div align="center"><sub><code>◈ SECTOR 08 — UPLINK ◈</code></sub></div>

---

<br/>

<div align="center">

[![GitHub](https://img.shields.io/badge/GITHUB-skykiller099-00d4ff?style=for-the-badge&logo=github&logoColor=00d4ff&labelColor=020510)](https://github.com/skykiller099)
&ensp;
[![Followers](https://img.shields.io/github/followers/skykiller099?label=FOLLOWERS&style=for-the-badge&logo=github&color=00d4ff&labelColor=020510)](https://github.com/skykiller099?tab=followers)
&ensp;
[![Views](https://komarev.com/ghpvc/?username=skykiller099&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS&labelColor=020510)](https://github.com/skykiller099)

<br/><br/>

```
  ╔═══════════════════════════════════════════════════════════════════════╗
  ║                                                                       ║
  ║   ◈  Open for collaborations  ·  Open to new challenges             ║
  ║   ◈  Let's build something that matters.                            ║
  ║                                                                       ║
  ║   skykiller099@github:~$ git commit -m "next big thing"  ▌           ║
  ║                                                                       ║
  ╚═══════════════════════════════════════════════════════════════════════╝
```

<br/>

<sub>
<code>◈ skykiller099</code>
&nbsp;·&nbsp;
<code>fork · star · ship</code>
&nbsp;·&nbsp;
<code>write code that outlives you</code>
</sub>

<br/><br/>

</div>

---

<!--
╔══════════════════════════════════════════════════════════════════════╗
  SETUP GUIDE
╠══════════════════════════════════════════════════════════════════════╣

  1. Create a PUBLIC repo named exactly: skykiller099
  2. Place README.md at the root.

  3. Snake — create .github/workflows/snake.yml :

─────────────────────────────────────────────────────────────────────
name: snake
on:
  schedule: [{cron: "0 */12 * * *"}]
  workflow_dispatch:
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_token: ${{ secrets.GITHUB_TOKEN }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
─────────────────────────────────────────────────────────────────────

  Then: Actions tab → Run workflow once manually.

╚══════════════════════════════════════════════════════════════════════╝
-->
