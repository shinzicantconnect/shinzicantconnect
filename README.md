<!--
  ╔══════════════════════════════════════════════════════════════════╗
  ║  Sai Mendoza — GitHub Profile README                               ║
  ║  How to edit this file:                                            ║
  ║   1. Banner: the <svg> block below is 100% self-contained          ║
  ║      (no external images). Edit the <text> content or the          ║
  ║      <style>/@keyframes rules to change the animation.             ║
  ║   2. Featured Links: update the badge URLs / hrefs in that         ║
  ║      section to point to new projects.                             ║
  ║   3. Tech Stack: edit the `i=` query param on the skillicons.dev   ║
  ║      URL to add/remove tech badges (comma-separated, no spaces).   ║
  ║   4. Colors: the banner uses GitHub's dark theme background        ║
  ║      (#0d1117) to blend seamlessly in dark mode.                   ║
  ╚══════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ============================================================ -->
<!-- ANIMATED HEADER BANNER (inline SVG, no external image hosts) -->
<!-- ============================================================ -->
<svg width="100%" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sai Mendoza banner">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="50%" stop-color="#0f1420"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="55%">
      <stop offset="0%" stop-color="#58a6ff" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#58a6ff" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#58a6ff"/>
      <stop offset="50%" stop-color="#bc8cff"/>
      <stop offset="100%" stop-color="#39d0d8"/>
    </linearGradient>
    <pattern id="gridPattern" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#30363d" stroke-width="1"/>
    </pattern>
    <style>
      <![CDATA[
        .bg-rect { fill: url(#bgGrad); }
        .grid-rect {
          fill: url(#gridPattern);
          opacity: 0.4;
          animation: gridDrift 14s linear infinite;
        }
        .glow-circle {
          fill: url(#glow);
          animation: pulseGlow 4s ease-in-out infinite;
          transform-origin: 450px 110px;
        }
        .title-text {
          font-family: 'Segoe UI', Verdana, Arial, sans-serif;
          font-size: 54px;
          font-weight: 800;
          fill: url(#textGrad);
          text-anchor: middle;
          animation: floatText 3.5s ease-in-out infinite;
        }
        .subtitle-text {
          font-family: 'Segoe UI', Verdana, Arial, sans-serif;
          font-size: 18px;
          font-weight: 400;
          fill: #8b949e;
          text-anchor: middle;
          letter-spacing: 2px;
          animation: floatText 3.5s ease-in-out infinite;
          animation-delay: 0.15s;
        }
        .spark {
          fill: #58a6ff;
          opacity: 0;
          animation: twinkle 3s ease-in-out infinite;
        }
        @keyframes floatText {
          0%, 100% { transform: translateY(0px); }
          50% { transform: translateY(-6px); }
        }
        @keyframes pulseGlow {
          0%, 100% { opacity: 0.55; transform: scale(1); }
          50% { opacity: 1; transform: scale(1.12); }
        }
        @keyframes gridDrift {
          0% { transform: translate(0, 0); }
          100% { transform: translate(40px, 40px); }
        }
        @keyframes twinkle {
          0%, 100% { opacity: 0; }
          50% { opacity: 1; }
        }
      ]]>
    </style>
  </defs>

  <!-- Background -->
  <rect class="bg-rect" width="900" height="220"/>
  <rect class="grid-rect" width="940" height="260" x="-20" y="-20"/>
  <circle class="glow-circle" cx="450" cy="110" r="160"/>

  <!-- Decorative twinkling sparks -->
  <circle class="spark" cx="120" cy="50" r="2.5" style="animation-delay:0s"/>
  <circle class="spark" cx="780" cy="60" r="2" style="animation-delay:0.6s"/>
  <circle class="spark" cx="200" cy="170" r="2" style="animation-delay:1.2s"/>
  <circle class="spark" cx="700" cy="160" r="2.5" style="animation-delay:1.8s"/>
  <circle class="spark" cx="450" cy="30" r="2" style="animation-delay:2.4s"/>

  <!-- Centered name + tagline -->
  <text x="450" y="112" class="title-text">Sai Mendoza</text>
  <text x="450" y="148" class="subtitle-text">IT STUDENT • WEB DEVELOPER • BUILDER</text>
</svg>

<br/>

<!-- ============================================================ -->
<!-- FEATURED LINKS                                                -->
<!-- ============================================================ -->
<!-- Edit the href below to update your portfolio link/badge -->
<a href="https://sai-dev-port.vercel.app" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-Visit%20Site-58a6ff?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Portfolio Website"/>
</a>

</div>

<br/>

## 🚀 Featured Projects

<!-- Add a new row to this table to feature another project -->
| Project | Description | Link |
|---|---|---|
| **CITEC UDays Attendance System** | QR-code based attendance management system built with Next.js | [View Repo](https://github.com/Daniel2525-ui/CITEC-UDays-Attendance-System) |
| **PopSeatReserve** | Web app for browsing and reserving seats in real time | [View Repo](https://github.com/shinzicantconnect/PopSeatReserve) |
| **Drip** | A web project exploring a modern, clean UI/UX build | [View Repo](https://github.com/shinzzzzyyyy/Drip) |

<br/>

<!-- ============================================================ -->
<!-- TECH STACK                                                    -->
<!-- ============================================================ -->
<div align="center">

### 🛠️ Tech Stack

<!-- Add/remove tech by editing the comma-separated `i=` list below -->
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,tailwind,supabase,postgres,vercel,git,html,css,nodejs,python" alt="Sai's tech stack"/>

</div>

<br/>

<!-- ============================================================ -->
<!-- FOOTER                                                        -->
<!-- ============================================================ -->
<div align="center">

<sub>Built with ❤️ by Sai Mendoza — this README animates natively via inline SVG, no external image hosting required.</sub>

</div>
