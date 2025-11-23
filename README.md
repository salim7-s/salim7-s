<!-- =========================
     Salim Khan — Compact, Premium README (Fixed)
     Paste this into your profile README.md
     Replace placeholder links if needed
     ========================= -->

<div align="center">

<!-- Glowing animated SVG banner (renders inline; not inside a code block) -->
<svg width="100%" height="160" viewBox="0 0 1200 160" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" style="border-radius:12px">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0" stop-color="#00f7ff"/>
      <stop offset="0.5" stop-color="#7c3aed"/>
      <stop offset="1" stop-color="#ff6ec7"/>
    </linearGradient>

    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <linearGradient id="waveGrad" x1="0" x2="1">
      <stop offset="0" stop-color="#0ea5e9"/>
      <stop offset="1" stop-color="#7c3aed"/>
    </linearGradient>
  </defs>

  <!-- background -->
  <rect width="100%" height="100%" rx="12" fill="#0b1220"/>

  <!-- animated wave -->
  <g filter="url(#glow)">
    <path id="wave" d="M0,110 C150,70 350,150 600,110 C850,70 1050,150 1200,110 L1200,160 L0,160 Z" fill="url(#waveGrad)" opacity="0.18">
      <animate attributeName="d" dur="8s" repeatCount="indefinite"
        values="
          M0,110 C150,70 350,150 600,110 C850,70 1050,150 1200,110 L1200,160 L0,160 Z;
          M0,120 C150,90 350,60 600,120 C850,180 1050,40 1200,120 L1200,160 L0,160 Z;
          M0,110 C150,70 350,150 600,110 C850,70 1050,150 1200,110 L1200,160 L0,160 Z" />
    </path>
  </g>

  <!-- main text with neon stroke -->
  <g transform="translate(40,46)">
    <text x="0" y="0" font-family="Fira Code, monospace" font-size="32" fill="#e6f7ff" style="font-weight:700">
      <tspan>Hi 👋, I'm </tspan>
      <tspan fill="url(#g)" style="font-weight:800" font-size="36">Salim Khan</tspan>
    </text>

    <text x="0" y="44" font-family="Fira Code, monospace" font-size="16" fill="#9fbadf">
      <tspan>Full-Stack Developer · Building clean backend systems</tspan>
    </text>

    <!-- small animated tags -->
    <g transform="translate(0,74)">
      <rect x="0" y="-18" width="220" height="28" rx="6" fill="#071126" stroke="url(#g)" stroke-width="1"/>
      <text x="12" y="2" font-family="Fira Code, monospace" font-size="13" fill="#bfefff">Node.js · Express · MySQL</text>

      <rect x="240" y="-18" width="160" height="28" rx="6" fill="#071126" stroke="#7c3aed" stroke-width="1"/>
      <text x="250" y="2" font-family="Fira Code, monospace" font-size="13" fill="#d7c7ff">Clean APIs · Tests</text>

      <rect x="420" y="-18" width="180" height="28" rx="6" fill="#071126" stroke="#ff6ec7" stroke-width="1">
        <animate attributeName="opacity" values="1;0.6;1" dur="3s" repeatCount="indefinite"/>
      </rect>
      <text x="430" y="2" font-family="Fira Code, monospace" font-size="13" fill="#ffd7f0">CI · Deploy</text>
    </g>
  </g>

</svg>

<!-- typing headline (image) -->
<p>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=800&color=00F7FF&center=true&vCenter=true&width=680&lines=Learning+%2F+Building+%2F+Shipping;Engineering+clean+backend+systems;Ship+small+%2B+iterate+fast" alt="typing" />
</p>

</div>

<!-- subtle separator -->
<p align="center">
  <svg width="100%" height="18" viewBox="0 0 1200 18" preserveAspectRatio="none"><path d="M0 9h1200" stroke="#1b2330" stroke-width="18" stroke-linecap="round" opacity="0.8"/></svg>
</p>

<div align="center">

## 🚀 Snapshot
- **Project:** Water Conservation System — *Node.js · Express · MySQL* (private)  
- **Focus:** Clean APIs · DB schema · tests · CI/CD  
- **Short-term:** DB migrations → API tests → CI → Deploy

</div>

---

## ⚡ Skills (animated icons)
<div align="center">
  <img src="https://skillicons.dev/icons?i=js,nodejs,express,mysql,react,html,css,tailwind,cpp,java,git&perline=8" />
</div>

---

## 📌 Quick Projects (pinned)
<div align="center">
[![Water Conservation](https://img.shields.io/badge/Water--Conservation-Backend-blue?style=for-the-badge&logo=git)](https://github.com/salim7-s/water-conservation-website)
&nbsp;
[![DevSprint](https://img.shields.io/badge/DevSprint-Kanban-green?style=for-the-badge&logo=trello)](#)
&nbsp;
[![InsightHub](https://img.shields.io/badge/InsightHub-Analytics-purple?style=for-the-badge&logo=datadog)](#)
</div>

---

## 📊 Live Visuals & Animated Stats
<div align="center">

<!-- activity heatmap -->
<img src="https://activity-graph.herokuapp.com/graph?username=salim7-s&theme=react-dark&area=true&hide_border=true" alt="activity-graph" width="720" style="max-width:100%;border-radius:8px;margin-bottom:8px" />

<!-- stats -->
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=salim7-s&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="github-stats" height="130" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=salim7-s&layout=compact&theme=tokyonight&hide_border=true" alt="top-langs" height="130" />
</p>

<!-- streak -->
<p>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=salim7-s&theme=tokyonight&hide_border=true" alt="streak" height="78" />
</p>

</div>

---

## 📈 Focus Radar (compact)
<p align="center">
  <img src="https://img.shields.io/badge/Backend-85%25-0ea5e9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Database-78%25-8b5cf6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DSA-62%25-f97316?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-60%25-06b6d4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DevOps-40%25-10b981?style=for-the-badge" />
</p>

---

## 🔗 Links (glassy badges)
<p align="center">
  <a href="mailto:boymigma@gmail.com"><img src="https://img.shields.io/badge/Email-boymigma%40gmail.com-111827?style=for-the-badge&logo=gmail" alt="email" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin" alt="linkedin" /></a>
  &nbsp;
  <a href="https://github.com/salim7-s"><img src="https://img.shields.io/badge/GitHub-@salim7--s-161616?style=for-the-badge&logo=github" alt="github" /></a>
  &nbsp;
  <!-- Local uploaded banner/resume fallback (replace after uploading into repo if desired) -->
  <a href="/mnt/data/51a0ab26-793f-4dcd-9ae7-a9c9a0564030.png" download><img src="https://img.shields.io/badge/Resume-Download-7c3aed?style=for-the-badge&logo=file" alt="resume" /></a>
</p>

---

## 🎯 Short-Term Goals
- ✅ DB migrations & seed scripts  
- ✅ Unit tests for core API flows  
- 🔜 CI for automated tests & linting  
- 🔜 Deploy backend to cloud with auto-deploy

---

## 🛠 Philosophy (one line)
> I build readable, testable modules and prefer incremental, ship-and-measure improvements over big-bang rewrites.

---

<div align="center">
Made compact • Designed for clarity • Built to ship
</div>

<!-- EOF -->
