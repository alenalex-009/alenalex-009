<!-- ████████████████████████████████████████████████████████████████████████ -->
<!-- ██                   ALEN ALEXANDER — GITHUB PROFILE README           ██ -->
<!-- ██              Cyberpunk · Futuristic · Elite Developer              ██ -->
<!-- ████████████████████████████████████████████████████████████████████████ -->

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    HERO BANNER SECTION                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Animated SVG Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220" width="900" height="220">
  <defs>
    <!-- Neon glow filter -->
    <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Gradient definitions -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#050810;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#0a0f1e;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#060b18;stop-opacity:1"/>
    </linearGradient>
    <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#00f0ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00f0ff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="magentaGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff00aa;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#ff00aa;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ff00aa;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff"/>
      <stop offset="50%" style="stop-color:#ffffff"/>
      <stop offset="100%" style="stop-color:#ff00aa"/>
    </linearGradient>
    <radialGradient id="orb1" cx="30%" cy="50%" r="35%">
      <stop offset="0%" style="stop-color:#00f0ff;stop-opacity:0.12"/>
      <stop offset="100%" style="stop-color:#00f0ff;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="70%" cy="50%" r="35%">
      <stop offset="0%" style="stop-color:#ff00aa;stop-opacity:0.10"/>
      <stop offset="100%" style="stop-color:#ff00aa;stop-opacity:0"/>
    </radialGradient>
    <!-- Clip path for rounded rect -->
    <clipPath id="roundedClip">
      <rect width="900" height="220" rx="18" ry="18"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" rx="18" ry="18" fill="url(#bgGrad)"/>

  <!-- Orb glows -->
  <ellipse cx="270" cy="110" rx="280" ry="140" fill="url(#orb1)"/>
  <ellipse cx="630" cy="110" rx="280" ry="140" fill="url(#orb2)"/>

  <!-- Grid lines (horizontal) -->
  <g opacity="0.06" stroke="#00f0ff" stroke-width="0.5">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <!-- Vertical -->
    <line x1="100" y1="0" x2="100" y2="220"/>
    <line x1="200" y1="0" x2="200" y2="220"/>
    <line x1="300" y1="0" x2="300" y2="220"/>
    <line x1="400" y1="0" x2="400" y2="220"/>
    <line x1="500" y1="0" x2="500" y2="220"/>
    <line x1="600" y1="0" x2="600" y2="220"/>
    <line x1="700" y1="0" x2="700" y2="220"/>
    <line x1="800" y1="0" x2="800" y2="220"/>
  </g>

  <!-- Scanning line animation -->
  <rect x="0" y="0" width="900" height="3" fill="url(#cyanGrad)" opacity="0.7">
    <animate attributeName="y" from="-3" to="220" dur="3.5s" repeatCount="indefinite" ease="linear"/>
    <animate attributeName="opacity" values="0;0.7;0.7;0" keyTimes="0;0.05;0.95;1" dur="3.5s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner decorations -->
  <!-- Top-left -->
  <polyline points="0,30 0,0 30,0" fill="none" stroke="#00f0ff" stroke-width="2.5" filter="url(#neonGlow)"/>
  <!-- Top-right -->
  <polyline points="870,0 900,0 900,30" fill="none" stroke="#00f0ff" stroke-width="2.5" filter="url(#neonGlow)"/>
  <!-- Bottom-left -->
  <polyline points="0,190 0,220 30,220" fill="none" stroke="#ff00aa" stroke-width="2.5" filter="url(#neonGlow)"/>
  <!-- Bottom-right -->
  <polyline points="870,220 900,220 900,190" fill="none" stroke="#ff00aa" stroke-width="2.5" filter="url(#neonGlow)"/>

  <!-- Decorative dots -->
  <circle cx="18" cy="18" r="3" fill="#00f0ff" filter="url(#neonGlow)" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="882" cy="18" r="3" fill="#00f0ff" filter="url(#neonGlow)" opacity="0.9">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="18" cy="202" r="3" fill="#ff00aa" filter="url(#neonGlow)" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="882" cy="202" r="3" fill="#ff00aa" filter="url(#neonGlow)" opacity="0.9">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="1.8s" repeatCount="indefinite"/>
  </circle>

  <!-- Top separator line -->
  <rect x="60" y="2" width="780" height="1.5" fill="url(#cyanGrad)" opacity="0.5"/>
  <!-- Bottom separator line -->
  <rect x="60" y="216" width="780" height="1.5" fill="url(#magentaGrad)" opacity="0.5"/>

  <!-- System label -->
  <text x="30" y="16" font-family="'Courier New', monospace" font-size="7" fill="#00f0ff" opacity="0.6" letter-spacing="2">SYS://PROFILE.INIT</text>
  <text x="720" y="16" font-family="'Courier New', monospace" font-size="7" fill="#ff00aa" opacity="0.6" letter-spacing="2">NODE:ACTIVE ■</text>

  <!-- Main name text -->
  <text x="450" y="95" text-anchor="middle" font-family="'Courier New', monospace" font-size="52" font-weight="900" fill="url(#textGrad)" letter-spacing="8" filter="url(#softGlow)">ALEN ALEX</text>

  <!-- Animated underline -->
  <rect x="150" y="105" width="0" height="2" rx="1" fill="url(#cyanGrad)">
    <animate attributeName="width" from="0" to="600" dur="1.2s" fill="freeze" begin="0.3s"/>
    <animate attributeName="x" from="450" to="150" dur="1.2s" fill="freeze" begin="0.3s"/>
  </rect>

  <!-- Subtitle -->
  <text x="450" y="140" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#aad4ff" letter-spacing="5" opacity="0">
    ◆  FULL-STACK DEVELOPER  ·  AI BUILDER  ·  OPEN SOURCE ·  Readme.md(on progress) ◆
    <animate attributeName="opacity" from="0" to="0.9" dur="0.8s" fill="freeze" begin="1s"/>
  </text>

  <!-- Status indicators -->
  <g transform="translate(270, 165)" opacity="0">
    <circle cx="0" cy="0" r="4" fill="#00ff88">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <text x="12" y="4" font-family="'Courier New', monospace" font-size="9" fill="#00ff88" letter-spacing="1">STATUS: BUILDING</text>
    <animate attributeName="opacity" from="0" to="1" dur="0.5s" fill="freeze" begin="1.4s"/>
  </g>

  <g transform="translate(490, 165)" opacity="0">
    <circle cx="0" cy="0" r="4" fill="#ff00aa">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <text x="12" y="4" font-family="'Courier New', monospace" font-size="9" fill="#ff00aa" letter-spacing="1">MODE: LEARNING</text>
    <animate attributeName="opacity" from="0" to="1" dur="0.5s" fill="freeze" begin="1.6s"/>
  </g>

  <!-- Floating particles -->
  <circle cx="80" cy="80" r="1.5" fill="#00f0ff" opacity="0.6">
    <animate attributeName="cy" values="80;50;80" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820" cy="130" r="1.5" fill="#ff00aa" opacity="0.6">
    <animate attributeName="cy" values="130;100;130" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="160" r="1" fill="#00f0ff" opacity="0.4">
    <animate attributeName="cy" values="160;140;160" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="60" r="1" fill="#ff00aa" opacity="0.4">
    <animate attributeName="cy" values="60;80;60" dur="4.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="30" r="1" fill="#ffffff" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--              ANIMATED TYPING INTRODUCTION                   -->
<!-- ═══════════════════════════════════════════════════════════ -->

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=00F0FF&center=true&vCenter=true&multiline=false&random=false&width=700&height=60&lines=%E2%9A%A1+Full-Stack+Developer+%7C+AI+Builder;%F0%9F%9A%80+Building+the+future%2C+one+commit+at+a+time;%F0%9F%A7%A0+B.Tech+CSE+%7C+Vignan%27s+University;%F0%9F%94%A5+Next.js+%C2%B7+Node.js+%C2%B7+Python+%C2%B7+AI%2FML;%F0%9F%8C%90+Open+Source+Enthusiast+%26+Hackathon+Winner)](https://git.io/typing-svg)

<br/>

<!-- Visitor counter -->
<img src="https://komarev.com/ghpvc/?username=alenalex-009&label=PROFILE+VIEWS&color=00f0ff&style=for-the-badge&labelColor=0d1117" alt="Profile Views"/>
&nbsp;
<img src="https://img.shields.io/github/followers/alenalex-009?label=FOLLOWERS&style=for-the-badge&color=ff00aa&labelColor=0d1117" alt="Followers"/>
&nbsp;
<img src="https://img.shields.io/badge/OPEN%20TO-INTERNSHIPS-00ff88?style=for-the-badge&labelColor=0d1117" alt="Open to Work"/>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  ANIMATED WAVE SEPARATOR                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 60" width="100%" height="40" preserveAspectRatio="none">
  <defs>
    <linearGradient id="wave1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00f0ff;stop-opacity:0.8"/>
      <stop offset="70%" style="stop-color:#ff00aa;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#ff00aa;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,30 C150,60 300,0 450,30 C600,60 750,0 900,30 C1050,60 1200,20 1200,30" fill="none" stroke="url(#wave1)" stroke-width="2">
    <animate attributeName="d" dur="4s" repeatCount="indefinite"
      values="M0,30 C150,60 300,0 450,30 C600,60 750,0 900,30 C1050,60 1200,20 1200,30;
              M0,30 C150,0 300,60 450,30 C600,0 750,60 900,30 C1050,0 1200,40 1200,30;
              M0,30 C150,60 300,0 450,30 C600,60 750,0 900,30 C1050,60 1200,20 1200,30"/>
  </path>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     ABOUT ME SECTION                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<table align="center" border="0" cellspacing="0" cellpadding="0" width="100%">
<tr>
<td width="55%" valign="top">

<div>

### `> whoami`

```bash
┌──────────────────────────────────────────┐
│  Name    : Alen Alex                     │
│  Role    : Full-Stack Developer          │
│  Study   : B.Tech CSE · 2nd Year        │
│  Uni     : Vignan's Institute of IT      │
│  Location: Visakhapatnam, India 🇮🇳      │
│  Status  : Building · Learning · Growing │
└──────────────────────────────────────────┘
```

```python
class AlenAlex:
    pronouns    = "he/him"
    education   = "B.Tech CSE (2023–2027)"
    passion     = ["Full-Stack Dev", "AI/ML", 
                   "Open Source", "Hackathons"]
    current     = ["MERN Stack Mastery", 
                   "Competitive Programming",
                   "System Design"]
    
    def life_motto(self):
        return "Ship fast. Learn faster. Never quit."
```

</div>

</td>
<td width="5%"></td>
<td width="40%" valign="top" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300" alt="coding gif" style="border-radius: 12px;"/>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               ABOUT ME HIGHLIGHT CARDS                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<table border="0" cellspacing="0" cellpadding="10">
<tr>
<td align="center" width="200">

```
⚡ BUILDING
───────────
GridAlert AI
CodeShift
CareerCompassAI
Classroom OS
```

</td>
<td align="center" width="200">

```
📚 LEARNING
───────────
MERN Stack
System Design
DSA / CP
Cloud & DevOps
```

</td>
<td align="center" width="200">

```
🎯 GOALS 2025
───────────────
Land Internship
Master DSA
10+ Projects
Top CRT Rank
```

</td>
<td align="center" width="200">

```
🏆 WINS
───────────────
Hackathon Build
AI Integration
Full-Stack Ship
Multiple MVPs
```

</td>
</tr>
</table>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  ANIMATED SEPARATOR                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━  TECH ARSENAL  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    TECH STACK SECTION                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

### ⚡ Languages

[![Skill Icons](https://skillicons.dev/icons?i=js,ts,python,java,c,html,css&theme=dark&perline=7)](https://skillicons.dev)

### 🚀 Frontend

[![Skill Icons](https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,sass,threejs&theme=dark&perline=6)](https://skillicons.dev)

### 🛠 Backend & Databases

[![Skill Icons](https://skillicons.dev/icons?i=nodejs,express,python,prisma,mongodb,postgresql,mysql&theme=dark&perline=7)](https://skillicons.dev)

### 🤖 AI / Cloud / DevOps

[![Skill Icons](https://skillicons.dev/icons?i=aws,docker,git,github,linux,vercel,firebase&theme=dark&perline=7)](https://skillicons.dev)

### 🧰 Tools & IDEs

[![Skill Icons](https://skillicons.dev/icons?i=vscode,postman,figma,notion&theme=dark&perline=4)](https://skillicons.dev)

</div>

<br/>

<!-- Tech Stack Badges Alternative Row -->
<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   GITHUB STATS SECTION                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━  GITHUB STATS  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<!-- Main Stats + Streak side by side -->
<img src="https://github-readme-stats.vercel.app/api?username=alenalex-009&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&icon_color=ff00aa&text_color=aad4ff&border_radius=12&rank_icon=github&card_width=420" alt="GitHub Stats" height="195"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=alenalex-009&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=aad4ff&border_radius=12&langs_count=8&card_width=360" alt="Top Languages" height="195"/>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                 GITHUB STREAK SECTION                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=alenalex-009&theme=tokyonight-duo&hide_border=true&background=0d1117&ring=00f0ff&fire=ff00aa&currStreakLabel=00f0ff&sideLabels=aad4ff&currStreakNum=ffffff&sideNums=aad4ff&dates=666699&stroke=00f0ff20&border_radius=12" alt="GitHub Streak" width="700"/>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                 ACTIVITY GRAPH SECTION                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━  CONTRIBUTION GRAPH  ━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=alenalex-009&bg_color=0d1117&color=00f0ff&line=ff00aa&point=ffffff&area=true&area_color=00f0ff&hide_border=true&radius=12&title_color=00f0ff&custom_title=Alen%27s%20Contribution%20Graph)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               SNAKE CONTRIBUTION ANIMATION                  -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━━━  THE SNAKE  ━━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<!-- 
  🔧 SETUP: To enable the snake animation, add a GitHub Action workflow at:
     .github/workflows/snake.yml — See: https://github.com/Platane/snk
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alenalex-009/alenalex-009/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/alenalex-009/alenalex-009/output/github-snake.svg"/>
  <img alt="Contribution Snake Animation" src="https://raw.githubusercontent.com/alenalex-009/alenalex-009/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  PROJECTS SHOWCASE                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━  FEATURED PROJECTS  ━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

<br/>

<!-- Project Cards Grid -->
<table align="center" border="0" width="100%">
<tr>

<!-- Project 1: GridAlert -->
<td width="50%" valign="top">

<a href="https://github.com/alenalex-009/gridalert">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=alenalex-009&repo=gridalert&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=aad4ff&icon_color=ff00aa&border_radius=12" alt="GridAlert" width="100%"/>
</a>

```
🔋 GridAlert AI
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
AI-Powered Power Outage Prediction
Platform for Visakhapatnam.
Real-time socket updates · Leaflet
maps · Recharts analytics · Anthropic
SDK integration · Proactive alerts.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Stack: Next.js 14 · Socket.io · AI
```

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio) ![AI](https://img.shields.io/badge/Anthropic_SDK-FF6B35?style=flat-square)

</td>

<!-- Project 2: CodeShift -->
<td width="50%" valign="top">

<a href="https://github.com/alenalex-009/codeshift">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=alenalex-009&repo=codeshift&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=aad4ff&icon_color=ff00aa&border_radius=12" alt="CodeShift" width="100%"/>
</a>

```
🎮 CodeShift
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Multiplayer Among Us-themed coding
game. Real-time code battles with
WebSocket sync, role-based gameplay,
terminal aesthetic UI. Players write
code to survive elimination rounds.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Stack: Node.js · Socket.io · React
```

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Multiplayer](https://img.shields.io/badge/Realtime-FF00AA?style=flat-square)

</td>
</tr>

<tr>
<td width="50%" valign="top">

<!-- Project 3: CareerCompassAI -->
<a href="https://github.com/alenalex-009/careercompassai">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=alenalex-009&repo=careercompassai&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=aad4ff&icon_color=ff00aa&border_radius=12" alt="CareerCompassAI" width="100%"/>
</a>

```
🧭 CareerCompassAI
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
AI-driven career guidance platform.
Genkit-powered recommendation flows,
resume analysis, personalized road-
maps. Multi-step AI conversation.
Full-stack MERN with Firebase auth.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Stack: React · Genkit · Firebase
```

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![AI](https://img.shields.io/badge/Genkit_AI-4285F4?style=flat-square)

</td>

<td width="50%" valign="top">

<!-- Project 4: QuickPick -->
<a href="https://github.com/alenalex-009/quickpick">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=alenalex-009&repo=quickpick&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=aad4ff&icon_color=ff00aa&border_radius=12" alt="QuickPick" width="100%"/>
</a>

```
🍔 QuickPick
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Smart campus food pre-ordering app.
Real-time queue management, MongoDB
Atlas cloud DB, mobile-responsive UI.
Reduces canteen wait time by 60%.
Full CRUD with REST API + Auth.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Stack: React · Vite · Node · MongoDB
```

![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

</td>
</tr>
</table>

<br/>

<div align="center">
<a href="https://github.com/alenalex-009?tab=repositories">
<img src="https://img.shields.io/badge/▶%20VIEW%20ALL%20REPOSITORIES-00f0ff?style=for-the-badge&labelColor=0d1117&logo=github&logoColor=00f0ff" alt="All Repos"/>
</a>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--              ACHIEVEMENTS & TROPHIES SECTION               -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━  HALL OF TROPHIES  ━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

[![Trophy](https://github-profile-trophy.vercel.app/?username=alenalex-009&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&margin-h=6&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,Issues,Experience)](https://github.com/ryo-ma/github-profile-trophy)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--           COMPETITIVE PROGRAMMING / LEETCODE               -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━  COMPETITIVE CODING  ━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<table border="0">
<tr>
<td align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-alen__alex-FFA116?style=for-the-badge&logo=leetcode&logoColor=FFA116&labelColor=0d1117)](https://leetcode.com/alenalex-009)

![LeetCode Stats](https://leetcode-badge-sage.vercel.app/badge/alenalex-009?theme=dark&bgColor=0d1117&border=00f0ff)

</td>
<td align="center" width="30">&nbsp;</td>
<td align="center">

[![CodeChef](https://img.shields.io/badge/CodeChef-alen__alex-5B4638?style=for-the-badge&logo=codechef&logoColor=white&labelColor=0d1117)](https://www.codechef.com/users/alen_alex)

[![Codeforces](https://img.shields.io/badge/Codeforces-alen__alex-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white&labelColor=0d1117)](https://codeforces.com/profile/alenalex-009)

[![HackerRank](https://img.shields.io/badge/HackerRank-alen__alex-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=0d1117)](https://hackerrank.com/alenalex-009)

</td>
</tr>
</table>

<!-- Coding stats SVG visualization -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 80" width="700" height="80">
  <defs>
    <linearGradient id="barGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff"/>
      <stop offset="100%" style="stop-color:#0080ff"/>
    </linearGradient>
    <linearGradient id="barGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff00aa"/>
      <stop offset="100%" style="stop-color:#ff6600"/>
    </linearGradient>
    <linearGradient id="barGrad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff88"/>
      <stop offset="100%" style="stop-color:#00aa55"/>
    </linearGradient>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="700" height="80" rx="10" fill="#0d1117"/>
  <!-- Easy -->
  <text x="20" y="22" font-family="monospace" font-size="10" fill="#aad4ff">EASY</text>
  <rect x="80" y="12" width="0" height="14" rx="3" fill="url(#barGrad3)" filter="url(#glow2)">
    <animate attributeName="width" from="0" to="280" dur="1.5s" fill="freeze"/>
  </rect>
  <text x="370" y="22" font-family="monospace" font-size="10" fill="#00ff88">~70 solved</text>
  <!-- Medium -->
  <text x="20" y="45" font-family="monospace" font-size="10" fill="#aad4ff">MEDIUM</text>
  <rect x="80" y="35" width="0" height="14" rx="3" fill="url(#barGrad2)" filter="url(#glow2)">
    <animate attributeName="width" from="0" to="160" dur="1.5s" fill="freeze" begin="0.2s"/>
  </rect>
  <text x="250" y="45" font-family="monospace" font-size="10" fill="#ff00aa">~40 solved</text>
  <!-- Hard -->
  <text x="20" y="68" font-family="monospace" font-size="10" fill="#aad4ff">HARD</text>
  <rect x="80" y="58" width="0" height="14" rx="3" fill="url(#barGrad1)" filter="url(#glow2)">
    <animate attributeName="width" from="0" to="60" dur="1.5s" fill="freeze" begin="0.4s"/>
  </rect>
  <text x="150" y="68" font-family="monospace" font-size="10" fill="#00f0ff">~15 solved</text>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  SPOTIFY NOW PLAYING                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━━  NOW PLAYING  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<!-- 
  🔧 SETUP: Connect Spotify at https://novatorem.vercel.app/ 
  Replace YOUR_VERCEL_DEPLOYMENT below with your own instance URL
-->
[![Spotify](https://novatorem.vercel.app/api/spotify?background_color=0d1117&border_color=00f0ff)](https://open.spotify.com/user/alenalex-009)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   CONNECT WITH ME                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━  LET'S CONNECT  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<a href="[https://linkedin.com/in/alenalex-009](https://www.linkedin.com/in/alen-alexander-1b4189327/)">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:alenalex5149@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email"/>
</a>
&nbsp;
<!--
<a href="https://twitter.com/alen_alex_dev">
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white&labelColor=0d1117" alt="Twitter"/>
</a>
&nbsp;
<a href="https://alenalex-009.vercel.app">
<img src="https://img.shields.io/badge/Portfolio-FF4500?style=for-the-badge&logo=firefox&logoColor=white&labelColor=0d1117" alt="Portfolio"/>
</a>
&nbsp;
<a href="https://dev.to/alenalex-009">
<img src="https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white&labelColor=0d1117" alt="Dev.to"/>
</a>
&nbsp;
<a href="https://discord.com/users/alenalex-009">
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d1117" alt="Discord"/>
</a>
-->
<br/><br/>

<!-- Coffee Button -->
<a href="https://www.buymeacoffee.com/alenalex-009">
<img src="https://img.shields.io/badge/☕%20BUY%20ME%20A%20COFFEE-FFDD00?style=for-the-badge&labelColor=0d1117&logoColor=FFDD00" alt="Buy Me A Coffee"/>
</a>
&nbsp;
<a href="https://github.com/sponsors/alenalex-009">
<img src="https://img.shields.io/badge/❤%20SPONSOR-EA4AAA?style=for-the-badge&labelColor=0d1117" alt="Sponsor"/>
</a>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                 OPEN SOURCE SECTION                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━  OPEN SOURCE SPIRIT  ━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

<table align="center" border="0" width="90%">
<tr>
<td align="center" width="33%">

**🌟 Stars Earned**

![Stars](https://img.shields.io/github/stars/alenalex-009?style=for-the-badge&color=00f0ff&labelColor=0d1117&logo=github)

</td>
<td align="center" width="33%">

**🍴 Forks Made**

![Forks](https://img.shields.io/github/forks/alenalex-009/gridalert?style=for-the-badge&color=ff00aa&labelColor=0d1117&logo=github)

</td>
<td align="center" width="33%">

**📦 Public Repos**

![Repos](https://img.shields.io/badge/REPOS-15+-00ff88?style=for-the-badge&labelColor=0d1117&logo=github)

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--              DEVELOPER GIF / FUN SECTION                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━  DEVELOPER LIFE  ━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<table border="0">
<tr>
<td align="center" width="33%">

<img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" width="180" alt="Developer typing gif"/>

`> Debugging at 3 AM`

</td>
<td align="center" width="33%">

<img src="https://media.giphy.com/media/ZVik7pIoJlCRa/giphy.gif" width="180" alt="Hackathon gif"/>

`> Hackathon mode ON`

</td>
<td align="center" width="33%">

<img src="https://media.giphy.com/media/l3q2K5jinAlChoCLS/giphy.gif" width="180" alt="Ship it gif"/>

`> Finally it works!`

</td>
</tr>
</table>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                DYNAMIC QUOTE SECTION                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━━━━━  WISDOM  ━━━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

[![Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight&border=true&bg_color=0d1117&border_color=00f0ff&quote_color=aad4ff&author_color=ff00aa)](https://github.com/piyushsuthar/github-readme-quotes)

<br/>

<!-- Personal Motto SVG -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 70" width="600" height="70">
  <defs>
    <linearGradient id="quoteBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#111827"/>
    </linearGradient>
    <filter id="quoteGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="600" height="70" rx="10" fill="url(#quoteBg)" stroke="#00f0ff" stroke-width="0.5" stroke-opacity="0.4"/>
  <!-- Left accent -->
  <rect x="0" y="0" width="4" height="70" rx="2" fill="#00f0ff" filter="url(#quoteGlow)"/>
  <!-- Right accent -->
  <rect x="596" y="0" width="4" height="70" rx="2" fill="#ff00aa" filter="url(#quoteGlow)"/>
  <text x="300" y="28" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#ffffff" font-style="italic">
    " Code is poetry written in logic. Every bug fixed
  </text>
  <text x="300" y="48" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#ffffff" font-style="italic">
    is a verse perfected. Keep writing. "
  </text>
  <text x="300" y="63" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#00f0ff" letter-spacing="2">— Alen Alex</text>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  CURRENT FOCUS SECTION                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━  CURRENTLY ON  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

<table align="center" border="0" width="90%">
<tr>
<td width="50%" valign="top">

**🔨 Currently Building**
- 🤖 ARIA — WhatsApp AI Assistant
- 🎮 CodeDeception — Among Us for Coders
- 📊 Classroom OS — Gamified Learning Platform

</td>
<td width="50%" valign="top">

**📖 Currently Learning**
- ⚡ Advanced MERN Stack patterns
- 🧩 Data Structures & Algorithms
- 🧠 LLM integration & prompt engineering

</td>
</tr>
</table>

<!-- Progress bars SVG -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 160" width="700" height="160">
  <defs>
    <linearGradient id="pg1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff"/>
      <stop offset="100%" style="stop-color:#0050ff"/>
    </linearGradient>
    <linearGradient id="pg2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff00aa"/>
      <stop offset="100%" style="stop-color:#ff6600"/>
    </linearGradient>
    <linearGradient id="pg3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff88"/>
      <stop offset="100%" style="stop-color:#00aaff"/>
    </linearGradient>
    <linearGradient id="pg4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FFD700"/>
      <stop offset="100%" style="stop-color:#FF8C00"/>
    </linearGradient>
    <filter id="pgGlow">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="700" height="160" rx="12" fill="#0d1117"/>
  <rect x="0" y="0" width="700" height="1" fill="#00f0ff" opacity="0.3"/>
  <rect x="0" y="159" width="700" height="1" fill="#ff00aa" opacity="0.3"/>

  <!-- React/Next.js -->
  <text x="20" y="32" font-family="monospace" font-size="11" fill="#aad4ff">React / Next.js</text>
  <rect x="180" y="22" width="460" height="12" rx="6" fill="#1a1f2e"/>
  <rect x="180" y="22" width="0" height="12" rx="6" fill="url(#pg1)" filter="url(#pgGlow)">
    <animate attributeName="width" from="0" to="368" dur="1.5s" fill="freeze" begin="0.2s"/>
  </rect>
  <text x="556" y="32" font-family="monospace" font-size="10" fill="#00f0ff">80%</text>
  <text x="585" y="32" font-family="monospace" font-size="8" fill="#00f0ff">████████░░</text>

  <!-- Node.js -->
  <text x="20" y="62" font-family="monospace" font-size="11" fill="#aad4ff">Node.js / Express</text>
  <rect x="180" y="52" width="460" height="12" rx="6" fill="#1a1f2e"/>
  <rect x="180" y="52" width="0" height="12" rx="6" fill="url(#pg2)" filter="url(#pgGlow)">
    <animate attributeName="width" from="0" to="322" dur="1.5s" fill="freeze" begin="0.4s"/>
  </rect>
  <text x="510" y="62" font-family="monospace" font-size="10" fill="#ff00aa">70%</text>
  <text x="537" y="62" font-family="monospace" font-size="8" fill="#ff00aa">███████░░░</text>

  <!-- Python -->
  <text x="20" y="92" font-family="monospace" font-size="11" fill="#aad4ff">Python / AI/ML</text>
  <rect x="180" y="82" width="460" height="12" rx="6" fill="#1a1f2e"/>
  <rect x="180" y="82" width="0" height="12" rx="6" fill="url(#pg3)" filter="url(#pgGlow)">
    <animate attributeName="width" from="0" to="276" dur="1.5s" fill="freeze" begin="0.6s"/>
  </rect>
  <text x="464" y="92" font-family="monospace" font-size="10" fill="#00ff88">60%</text>
  <text x="491" y="92" font-family="monospace" font-size="8" fill="#00ff88">██████░░░░</text>

  <!-- DSA -->
  <text x="20" y="122" font-family="monospace" font-size="11" fill="#aad4ff">DSA / CP</text>
  <rect x="180" y="112" width="460" height="12" rx="6" fill="#1a1f2e"/>
  <rect x="180" y="112" width="0" height="12" rx="6" fill="url(#pg4)" filter="url(#pgGlow)">
    <animate attributeName="width" from="0" to="184" dur="1.5s" fill="freeze" begin="0.8s"/>
  </rect>
  <text x="373" y="122" font-family="monospace" font-size="10" fill="#FFD700">40%</text>
  <text x="400" y="122" font-family="monospace" font-size="8" fill="#FFD700">████░░░░░░</text>

  <!-- System Design -->
  <text x="20" y="152" font-family="monospace" font-size="11" fill="#aad4ff">System Design</text>
  <rect x="180" y="142" width="460" height="12" rx="6" fill="#1a1f2e"/>
  <rect x="180" y="142" width="0" height="12" rx="6" fill="url(#pg1)" filter="url(#pgGlow)" opacity="0.6">
    <animate attributeName="width" from="0" to="138" dur="1.5s" fill="freeze" begin="1s"/>
  </rect>
  <text x="328" y="152" font-family="monospace" font-size="10" fill="#00f0ff">30%</text>
  <text x="355" y="152" font-family="monospace" font-size="8" fill="#00f0ff">███░░░░░░░</text>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   FUN FACTS SECTION                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
◈ ━━━━━━━━━━━━━━━━━━━━━  FUN FACTS  ━━━━━━━━━━━━━━━━━━ ◈
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

<table align="center" border="0" width="85%">
<tr>
<td align="center"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="size-6">
  <path strokeLinecap="round" strokeLinejoin="round" d="M9 17.25v1.007a3 3 0 0 1-.879 2.122L7.5 21h9l-.621-.621A3 3 0 0 1 15 18.257V17.25m6-12V15a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 15V5.25m18 0A2.25 2.25 0 0 0 18.75 3H5.25A2.25 2.25 0 0 0 3 5.25m18 0V12a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 12V5.25" />
</svg>
<b>every</b> day — code & gains</td>
<td align="center">🌙 Most productive between <b>10 PM – 2 AM</b></td>
</tr>
<tr>
<td align="center">⚡ Built a <b>24-hour hackathon</b> MVP solo</td>
<td align="center">🚀 Ships products before fully understanding them</td>
</tr>
<tr>
<td align="center">📱 Mobile-first thinker, dark-mode purist</td>
<td align="center">🤖 Thinks in <b>APIs</b>, dreams in <b>components</b></td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  ANIMATED FOOTER WAVE                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

<!-- Closing animated SVG footer -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 120" width="900" height="120">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#050810"/>
      <stop offset="100%" style="stop-color:#0a0f1e"/>
    </linearGradient>
    <linearGradient id="waveFooter1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00f0ff;stop-opacity:0.6"/>
      <stop offset="70%" style="stop-color:#ff00aa;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#ff00aa;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="footerText" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f0ff"/>
      <stop offset="100%" style="stop-color:#ff00aa"/>
    </linearGradient>
    <filter id="footerGlow">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="900" height="120" rx="12" fill="url(#footerBg)"/>

  <!-- Top border -->
  <rect x="0" y="0" width="900" height="1.5" fill="url(#waveFooter1)" opacity="0.8"/>

  <!-- Animated wave paths -->
  <path d="M0,60 C225,30 450,90 675,60 C787,44 843,52 900,60 L900,120 L0,120 Z" fill="#00f0ff" opacity="0.03">
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="M0,60 C225,30 450,90 675,60 C787,44 843,52 900,60 L900,120 L0,120 Z;
              M0,60 C225,90 450,30 675,60 C787,76 843,68 900,60 L900,120 L0,120 Z;
              M0,60 C225,30 450,90 675,60 C787,44 843,52 900,60 L900,120 L0,120 Z"/>
  </path>
  <path d="M0,70 C200,50 400,90 600,70 C750,55 825,65 900,70 L900,120 L0,120 Z" fill="#ff00aa" opacity="0.03">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="M0,70 C200,50 400,90 600,70 C750,55 825,65 900,70 L900,120 L0,120 Z;
              M0,70 C200,90 400,50 600,70 C750,85 825,75 900,70 L900,120 L0,120 Z;
              M0,70 C200,50 400,90 600,70 C750,55 825,65 900,70 L900,120 L0,120 Z"/>
  </path>

  <!-- Animated wave line on top -->
  <path d="M0,30 C150,50 300,10 450,30 C600,50 750,10 900,30" fill="none" stroke="url(#waveFooter1)" stroke-width="1.5" opacity="0.7">
    <animate attributeName="d" dur="4s" repeatCount="indefinite"
      values="M0,30 C150,50 300,10 450,30 C600,50 750,10 900,30;
              M0,30 C150,10 300,50 450,30 C600,10 750,50 900,30;
              M0,30 C150,50 300,10 450,30 C600,50 750,10 900,30"/>
  </path>

  <!-- Footer text -->
  <text x="450" y="65" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="url(#footerText)" letter-spacing="3" filter="url(#footerGlow)">
    ALEN ALEX · FULL-STACK DEVELOPER · INDIA
  </text>
  <text x="450" y="85" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#aad4ff" opacity="0.6" letter-spacing="2">
    ⚡ Building tomorrow's web, one commit at a time ⚡
  </text>
  <text x="450" y="105" text-anchor="middle" font-family="'Courier New', monospace" font-size="7" fill="#666699" letter-spacing="1">
    © 2025 Alen Alex · All Rights Reserved
  </text>

  <!-- Pulsing dots -->
  <circle cx="60" cy="70" r="3" fill="#00f0ff" filter="url(#footerGlow)">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="840" cy="70" r="3" fill="#ff00aa" filter="url(#footerGlow)">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<!-- Bottom badge row -->
<br/>

![Made with ❤️](https://img.shields.io/badge/Made%20with-❤%EF%B8%8F-ff00aa?style=for-the-badge&labelColor=0d1117)
&nbsp;
![GitHub](https://img.shields.io/badge/Profile-ALEN%20ALEX-00f0ff?style=for-the-badge&logo=github&labelColor=0d1117)
&nbsp;
![India](https://img.shields.io/badge/🇮🇳-INDIA-FF9933?style=for-the-badge&labelColor=0d1117)

</div>

<!-- ████████████████████████████████████████████████████████████████████████ -->
<!--                                                                          -->
<!--  ██████████████████   CUSTOMIZATION GUIDE   ████████████████████████    -->
<!--                                                                          -->
<!--  Replace the following with YOUR real information:                       -->
<!--                                                                          -->
<!--  1. USERNAME    → Replace all "alenalex-009" with your GitHub username      -->
<!--  2. EMAIL       → alen.alex@example.com → your real email               -->
<!--  3. LINKEDIN    → /in/alenalex-009 → your LinkedIn slug                    -->
<!--  4. TWITTER     → @alen_alex_dev → your Twitter handle                  -->
<!--  5. PORTFOLIO   → alenalex-009.vercel.app → your portfolio URL             -->
<!--  6. LEETCODE    → leetcode.com/alenalex-009 → your LeetCode profile        -->
<!--  7. SPOTIFY     → Deploy novatorem.vercel.app with your Spotify account  -->
<!--  8. SNAKE SVG   → Set up GitHub Action: github.com/Platane/snk          -->
<!--  9. PROJECT REPOS → Replace repo names with your actual repo names       -->
<!--  10. STATS CARDS → They auto-populate once username is correct           -->
<!--                                                                          -->
<!-- ████████████████████████████████████████████████████████████████████████ -->
