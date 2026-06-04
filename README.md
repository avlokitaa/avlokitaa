<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<!--                            HERO BANNER                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<!-- Animated SVG Hero Banner -->
<!--Will Make later- probably upload an image or something-->
  <!-- Background -->
  <rect width="900" height="280" fill="#080808"/>
  <rect width="900" height="280" fill="url(#sunGlow)"/>

  <!-- Decorative border lines -->
  <rect x="20" y="20" width="860" height="240" fill="none" stroke="#B8860B" stroke-width="0.5" stroke-dasharray="4,8"/>
  <rect x="24" y="24" width="852" height="232" fill="none" stroke="#FFD700" stroke-width="0.3" opacity="0.3"/>

  <!-- Corner ornaments -->
  <g fill="none" stroke="#FFD700" stroke-width="1" opacity="0.7">
    <path d="M20,20 L50,20 M20,20 L20,50"/>
    <path d="M880,20 L850,20 M880,20 L880,50"/>
    <path d="M20,260 L50,260 M20,260 L20,230"/>
    <path d="M880,260 L850,260 M880,260 L880,230"/>
  </g>

  <!-- Sun (top center) -->
  <g filter="url(#softGlow)">
    <circle cx="450" cy="84" r="28" fill="url(#sunCore)" class="glow-pulse"/>
    <!-- Sun rays (rotating) -->
    <g class="sun-ray" opacity="0.6">
      <line x1="450" y1="48" x2="450" y2="40" stroke="#FFD700" stroke-width="2"/>
      <line x1="450" y1="120" x2="450" y2="128" stroke="#FFD700" stroke-width="2"/>
      <line x1="414" y1="84" x2="406" y2="84" stroke="#FFD700" stroke-width="2"/>
      <line x1="486" y1="84" x2="494" y2="84" stroke="#FFD700" stroke-width="2"/>
      <line x1="424.5" y1="58.5" x2="419" y2="53" stroke="#FFD700" stroke-width="1.5"/>
      <line x1="475.5" y1="109.5" x2="481" y2="115" stroke="#FFD700" stroke-width="1.5"/>
      <line x1="475.5" y1="58.5" x2="481" y2="53" stroke="#FFD700" stroke-width="1.5"/>
      <line x1="424.5" y1="109.5" x2="419" y2="115" stroke="#FFD700" stroke-width="1.5"/>
    </g>
  </g>

  <!-- Left Wing -->
  <g class="hero-text" opacity="0.85" filter="url(#glow)">
    <path d="M370,160 C340,130 280,110 240,95 C270,110 290,130 300,155 C270,125 210,108 170,100 C205,118 230,140 238,165 C210,138 155,122 115,118 C155,138 185,162 190,185 C175,185 370,168 370,168 Z" fill="#B8860B" opacity="0.7"/>
    <path d="M370,160 C340,130 280,110 240,95 C270,110 290,130 300,155 C270,125 210,108 170,100 C205,118 230,140 238,165 C210,138 155,122 115,118 C155,138 185,162 190,185 C175,185 370,168 370,168 Z" fill="none" stroke="#FFD700" stroke-width="0.8" opacity="0.9"/>
    <!-- Wing feather details -->
    <line x1="300" y1="150" x2="250" y2="135" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
    <line x1="310" y1="160" x2="245" y2="150" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
    <line x1="320" y1="165" x2="240" y2="163" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
  </g>

  <!-- Right Wing -->
  <g class="hero-text" opacity="0.85" filter="url(#glow)">
    <path d="M530,160 C560,130 620,110 660,95 C630,110 610,130 600,155 C630,125 690,108 730,100 C695,118 670,140 662,165 C690,138 745,122 785,118 C745,138 715,162 710,185 C725,185 530,168 530,168 Z" fill="#B8860B" opacity="0.7"/>
    <path d="M530,160 C560,130 620,110 660,95 C630,110 610,130 600,155 C630,125 690,108 730,100 C695,118 670,140 662,165 C690,138 745,122 785,118 C745,138 715,162 710,185 C725,185 530,168 530,168 Z" fill="none" stroke="#FFD700" stroke-width="0.8" opacity="0.9"/>
    <line x1="600" y1="150" x2="650" y2="135" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
    <line x1="590" y1="160" x2="655" y2="150" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
    <line x1="580" y1="165" x2="660" y2="163" stroke="#FFD700" stroke-width="0.5" opacity="0.5"/>
  </g>

  <!-- Falling feathers -->
  <g>
    <path class="feather1" d="M340,120 C338,125 342,130 340,135 C337,130 335,125 340,120 Z" fill="#FFD700" opacity="0.8" transform="translate(320, 80)"/>
    <path class="feather2" d="M340,120 C338,125 342,130 340,135 C337,130 335,125 340,120 Z" fill="#FFD700" opacity="0.6" transform="translate(550, 70)"/>
    <path class="feather3" d="M340,120 C338,125 342,130 340,135 C337,130 335,125 340,120 Z" fill="#FFD700" opacity="0.5" transform="translate(480, 90)"/>
  </g>

  <!-- Name -->
  <text x="450" y="190" text-anchor="middle" font-family="Georgia, serif" font-size="38" font-weight="bold" fill="#FFD700" filter="url(#glow)" letter-spacing="8">AVLOKITA</text>

  <!-- Role -->
  <text x="450" y="215" text-anchor="middle" font-family="Georgia, serif" font-size="12" fill="#C0A060" letter-spacing="5">✦  SOFTWARE ENGINEER IN THE MAKING  ✦</text>

  <!-- Divider -->
  <line x1="330" y1="228" x2="570" y2="228" stroke="#B8860B" stroke-width="0.5" opacity="0.6"/>
  <circle cx="450" cy="228" r="2" fill="#FFD700" opacity="0.8"/>

  <!-- Quote -->
  <text x="450" y="248" text-anchor="middle" font-family="Georgia, serif" font-size="10" fill="#8B7340" font-style="italic" letter-spacing="1">He laughed as he fell, because he knew to fall is to have soared once.</text>
</svg>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=IM+Fell+English+SC&size=18&duration=3000&pause=1000&color=B8860B&center=true&vCenter=true&width=600&lines=Computer+Science+Student;Full+Stack+%7C+AI+%7C+Open+Source+%7C+Game+Dev;Daring+to+reach+impossible+heights.)](https://git.io/typing-svg)

</div>

---

<div align="center">

<!-- Section Header SVG -->
<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="240" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="240,25 255,18 255,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="14" fill="#FFD700" letter-spacing="6">THE ASCENT</text>
  <polygon points="460,18 460,32 445,25" fill="#B8860B" opacity="0.5"/>
  <line x1="460" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

</div>

<br/>

> *In the age before the internet, Daedalus gave his son wings and a warning. Icarus chose the sun.*
>
> *Some say he was reckless. I say he was a developer.*

I am **Avlokita**, a Computer Science student navigating the vast, uncharted sky between *what I know* and *what I want to build*.

The journey began with a single line of code; curious, clumsy, and already on fire. Since then, every algorithm learned, every bug fixed at 2 A.M. , every system that finally *clicked* has been another meter of altitude gained.

I am drawn to the intersections: where **Artificial Intelligence** meets human intuition, where **Full Stack Development** turns ideas into living things, where **Open Source** turns solitude into civilization, and where **Game Development** transforms logic into worlds.

My goal is not just a career in tech. It is to *contribute* to the tools people rely on, to the communities that build the future, and to the discipline that turns curious minds into architects of reality.

The wax may soften. The altitude may terrify. But the flight is the point.

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="230" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="230,25 245,18 245,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="14" fill="#FFD700" letter-spacing="6">THE ARSENAL</text>
  <polygon points="455,18 455,32 440,25" fill="#B8860B" opacity="0.5"/>
  <line x1="455" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

*The tools with which the wings were forged*

<br/>

**⬡ Languages**

![C](https://img.shields.io/badge/C-%23A8860C.svg?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-%23B8860B.svg?style=for-the-badge&logo=c%2B%2B&logoColor=black)
![Python](https://img.shields.io/badge/Python-%23C9A227.svg?style=for-the-badge&logo=python&logoColor=black)
![Java](https://img.shields.io/badge/Java-%23DAA520.svg?style=for-the-badge&logo=openjdk&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-%23FFD700.svg?style=for-the-badge&logo=javascript&logoColor=black)

<br/>

**⬡ Web & Mobile**

![HTML5](https://img.shields.io/badge/HTML5-%23B8860B.svg?style=for-the-badge&logo=html5&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-%23C9A227.svg?style=for-the-badge&logo=css3&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-%23FFD700.svg?style=for-the-badge&logo=flutter&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-%23DAA520.svg?style=for-the-badge&logo=firebase&logoColor=black)

<br/>

**⬡ Craft & Collaboration**

![Git](https://img.shields.io/badge/Git-%23A8860C.svg?style=for-the-badge&logo=git&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-%23B8860B.svg?style=for-the-badge&logo=github&logoColor=black)

</div>

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="185" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="185,25 200,18 200,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="14" fill="#FFD700" letter-spacing="4">FLIGHT STATISTICS</text>
  <polygon points="500,18 500,32 485,25" fill="#B8860B" opacity="0.5"/>
  <line x1="500" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

*Altitude recorded. Distance logged.*

<br/>

<p align="center">
  <img src="https://readme-stats-deploy.vercel.app/api?username=avlokitaa&show_icons=true&theme=transparent&title_color=FFD700&text_color=C0A060&icon_color=B8860B&border_color=B8860B&hide_border=false&rank_icon=github" width="49%" alt="GitHub Stats" />
  <img src="https://readme-stats-deploy.vercel.app/api/top-langs/?username=avlokitaa&theme=transparent&title_color=FFD700&text_color=C0A060&border_color=B8860B&layout=compact&langs_count=8" width="49%" alt="Most Used Languages" />
</p>

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=avlokitaa&theme=transparent&hide_border=false&stroke=B8860B&ring=FFD700&fire=FFD700&currStreakLabel=FFD700&sideLabels=C0A060&dates=8B7340&border=B8860B&currStreakNum=FFD700&sideNums=C0A060)

<br/>

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=avlokitaa&bg_color=080808&color=B8860B&line=FFD700&point=FFD700&area=true&area_color=B8860B&border_color=B8860B&hide_border=false&title_color=FFD700)

</div>

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="155" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="155,25 170,18 170,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="13" fill="#FFD700" letter-spacing="4">WINGS FORGED IN CODE</text>
  <polygon points="530,18 530,32 515,25" fill="#B8860B" opacity="0.5"/>
  <line x1="530" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

*Each project — a feather in the architecture of flight*

<br/>

<div align="center">
  <a href="https://github.com/avlokitaa/spotit">
    <img src="https://readme-stats-deploy.vercel.app/api/pin/?username=avlokitaa&repo=spotit&theme=transparent&title_color=FFD700&text_color=C0A060&icon_color=B8860B&border_color=B8860B&description_lines_count=2" width="49%" />
  </a>
  <a href="https://github.com/avlokitaa/SVVAP">
    <img src="https://readme-stats-deploy.vercel.app/api/pin/?username=avlokitaa&repo=SVVAP&theme=transparent&title_color=FFD700&text_color=C0A060&icon_color=B8860B&border_color=B8860B&description_lines_count=2" width="49%" />
  </a>
</div>

</div>

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="155" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="155,25 170,18 170,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="13" fill="#FFD700" letter-spacing="4">THE CONSTELLATION MAP</text>
  <polygon points="530,18 530,32 515,25" fill="#B8860B" opacity="0.5"/>
  <line x1="530" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

*A journey traced across the sky*

</div>

<br/>

```
                              ☀  THE SUN
                              │
                              │   ← Future: Industry, Impact, Legacy
                              │
                         ✦ ─────── ✦   Open Source Contributions
                              │
                    ✦ ─────────────── ✦   First Real Projects
                              │
               ✦ ──────────────────────── ✦   Foundations Built
                              │
          ✦ ───────────────────────────────── ✦   CS Degree Begun
                              │
     ✦ ──────────────────────────────────────────── ✦   First Line of Code
                              │
                         ◈  ORIGIN
```

<br/>

<table align="center">
<tr>
<td align="center" width="20%">

**◈**<br/>**Origin**<br/>*The first spark*<br/><sub>Curiosity without direction. The question: "How does this work?"</sub>

</td>
<td align="center" width="5%">──</td>
<td align="center" width="20%">

**✦**<br/>**Foundations**<br/>*The runway*<br/><sub>C, Python, Java. Data structures. Logic. Learning to think like a machine.</sub>

</td>
<td align="center" width="5%">──</td>
<td align="center" width="20%">

**✦**<br/>**First Flight**<br/>*Liftoff*<br/><sub>First real projects. Web dev discovered. Full stack clicked. Something was built.</sub>

</td>
<td align="center" width="5%">──</td>
<td align="center" width="20%">

**✦**<br/>**Open Skies**<br/>*Now*<br/><sub>Open source. AI/ML. Flutter. Building in public. Seeking collaborators.</sub>

</td>
</tr>
</table>

<br/>

| Milestone | Coordinates | Status |
|---|---|---|
| 🌱 First line of code written | `0° — Ground level` | ✅ Completed |
| 📐 CS Fundamentals mastered | `15° — Low altitude` | ✅ Completed |
| 🔨 First complete project shipped | `30° — Climbing` | ✅ Completed |
| 🌐 Full stack development | `45° — Mid-flight` | ✅ Completed |
| 🤝 First open source contribution | `60° — High altitude` | 🔄 In Progress |
| 🤖 AI/ML integration in projects | `75° — Near the sun` | 🎯 Next target |
| 🏗️ Contribute to major OSS project | `85° — The edge` | 🎯 Future |
| ☀️ Shape tech at scale | `90° — The sun itself` | ∞ The horizon |

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="175" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="175,25 190,18 190,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="13" fill="#FFD700" letter-spacing="4">CURRENT FLIGHT PATH</text>
  <polygon points="510,18 510,32 495,25" fill="#B8860B" opacity="0.5"/>
  <line x1="510" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

*Real-time telemetry*

</div>

<br/>

<table align="center">
<tr>
<td width="50%" valign="top">

### 📡 Systems Online

```yaml
learning:
  - Data Structures & Algorithms
  - Machine Learning Fundamentals
  - Flutter & Mobile Architecture

building:
  - A Game Recommendation App
  - Expanding GitHub portfolio

reading:
  - Tell me your Dreams - Sidney Sheldon
```

</td>
<td width="50%" valign="top">

### 🎯 Current Coordinates

```
▸ ALTITUDE   : Growing daily
▸ SPEED      : Consistently shipping
▸ DIRECTION  : AI + Full Stack + OSS
▸ FUEL       : Curiosity (unlimited)
▸ RISK LEVEL : Acceptable
▸ REGRET     : None
▸ NEXT STOP  : Wherever the problem is

Status: ASCENDING ↑
```

</td>
</tr>
</table>

<br/>

---

<div align="center">

<svg viewBox="0 0 700 50" xmlns="http://www.w3.org/2000/svg" width="700" height="50">
  <rect width="700" height="50" fill="#080808"/>
  <line x1="0" y1="25" x2="225" y2="25" stroke="#B8860B" stroke-width="0.5"/>
  <polygon points="225,25 240,18 240,32" fill="#B8860B" opacity="0.5"/>
  <text x="350" y="31" text-anchor="middle" font-family="Georgia, serif" font-size="14" fill="#FFD700" letter-spacing="6">PHILOSOPHY</text>
  <polygon points="460,18 460,32 445,25" fill="#B8860B" opacity="0.5"/>
  <line x1="460" y1="25" x2="700" y2="25" stroke="#B8860B" stroke-width="0.5"/>
</svg>

</div>

<br/>

<div align="center">

*On curiosity, experimentation, and the dignity of the fall*

</div>

<br/>

> **On Curiosity:**
> Daedalus built the wings because he *had* to know. Not because it was safe. Not because it was approved. Because the problem existed and demanded a solution. Every bug I've chased at midnight, every rabbit hole that consumed an afternoon, that's the same madness. Curiosity is the only honest fuel.

> **On Experimentation:**
> Icarus didn't fly perfectly on his first attempt. He flew *imperfectly* and then *better*. Every failed project, every bricked build, every stack overflow I caused personally taught me more than any successful demo ever did. Failure is data. Run more experiments.

> **On Learning Through Failure:**
> The wax melting was information. It told him: the sun is closer than the theory suggested. The best engineers I admire treat every failure the same way, not as a verdict, but as a measurement. *Interesting. Let's adjust the model.*

> **On Growth:**
> He who never risks the fall never discovers how high the sky truly goes. Safe code is dead code. Safe ambitions are just regrets on a timeline. I would rather build something broken and reach for something impossible than compile cleanly for something no one needed.

<br/>

---

<div align="center">

<!-- Final Banner SVG -->
<svg viewBox="0 0 900 200" xmlns="http://www.w3.org/2000/svg" width="900" height="200">
  <defs>
    <radialGradient id="finalGlow" cx="50%" cy="50%" r="60%">
      <stop offset="0%" style="stop-color:#B8860B;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#080808;stop-opacity:0"/>
    </radialGradient>
    <filter id="finalBlur">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!--<style>
      @keyframes breathe { 0%,100%{opacity:0.7} 50%{opacity:1} }
      .breathe { animation: breathe 5s ease-in-out infinite; }
    </style>
  </defs>-->

  <rect width="900" height="200" fill="#080808"/>
  <rect width="900" height="200" fill="url(#finalGlow)"/>

  <!-- Top and bottom border -->
  <line x1="40" y1="20" x2="860" y2="20" stroke="#B8860B" stroke-width="0.5" opacity="0.5"/>
  <line x1="40" y1="180" x2="860" y2="180" stroke="#B8860B" stroke-width="0.5" opacity="0.5"/>

  <!-- Corner marks -->
  <g fill="none" stroke="#FFD700" stroke-width="0.8" opacity="0.5">
    <path d="M40,20 L60,20 M40,20 L40,40"/>
    <path d="M860,20 L840,20 M860,20 L860,40"/>
    <path d="M40,180 L60,180 M40,180 L40,160"/>
    <path d="M860,180 L840,180 M860,180 L860,160"/>
  </g>

  <!-- Small sun -->
  <circle cx="450" cy="55" r="12" fill="#FFD700" opacity="0.8" class="breathe" filter="url(#finalBlur)"/>
  <g opacity="0.4" class="breathe">
    <line x1="450" y1="35" x2="450" y2="30" stroke="#FFD700" stroke-width="1.5"/>
    <line x1="450" y1="75" x2="450" y2="80" stroke="#FFD700" stroke-width="1.5"/>
    <line x1="430" y1="55" x2="425" y2="55" stroke="#FFD700" stroke-width="1.5"/>
    <line x1="470" y1="55" x2="475" y2="55" stroke="#FFD700" stroke-width="1.5"/>
  </g>

  <!-- Small wings flanking sun -->
  <path d="M400,55 C380,45 355,40 340,38 C355,45 365,52 368,60 C350,48 330,42 315,40 C330,48 345,56 346,65 C400,62 400,60 400,60 Z" fill="#B8860B" opacity="0.5"/>
  <path d="M500,55 C520,45 545,40 560,38 C545,45 535,52 532,60 C550,48 570,42 585,40 C570,48 555,56 554,65 C500,62 500,60 500,60 Z" fill="#B8860B" opacity="0.5"/>

  <!-- Main quote -->
  <text x="450" y="110" text-anchor="middle" font-family="Georgia, serif" font-size="16" fill="#FFD700" filter="url(#finalBlur)" letter-spacing="2" font-style="italic">The sky was never the destination.</text>
  <text x="450" y="135" text-anchor="middle" font-family="Georgia, serif" font-size="16" fill="#FFD700" filter="url(#finalBlur)" letter-spacing="2" font-style="italic">The flight was.</text>

  <!-- Sub-line -->
  <text x="450" y="162" text-anchor="middle" font-family="Georgia, serif" font-size="10" fill="#8B7340" letter-spacing="3">— AVLOKITA  ✦  If I fall, it means I reached somewhere worth falling from.</text>
</svg>

<br/>

---

*Connect with me*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%23B8860B.svg?style=for-the-badge&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/avlokitapathania/)
[![Email](https://img.shields.io/badge/Email-%23FFD700.svg?style=for-the-badge&logo=gmail&logoColor=black)](mailto:avlokita.pathania@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23C9A227.svg?style=for-the-badge&logo=vercel&logoColor=black)](https://YOUR_PORTFOLIO_URL)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=avlokitaa&color=B8860B&style=for-the-badge&label=FLIGHTS+OBSERVED)

<br/>

<sub>*Built with ambition, caffeine, and the audacity of Icarus.*</sub>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->
<!--                                                                           -->
<!--   SETUP CHECKLIST — Replace the following placeholders:                  -->
<!--                                                                           -->
<!--   avlokitaa  → your GitHub username                           -->
<!--   spotit..4   → your top 4 repository names                   -->
<!--   https://www.linkedin.com/in/avlokitapathania/         → your LinkedIn profile path                     -->
<!--   avlokita.pathania@gmail.com            → your contact email                             -->
<!--   YOUR_PORTFOLIO_URL    → your portfolio website URL                     -->
<!--                                                                           -->
<!-- ═══════════════════════════════════════════════════════════════════════════ -->
