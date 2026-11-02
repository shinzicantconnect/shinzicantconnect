<!--
  ╔══════════════════════════════════════════════════════════════════╗
  ║  Sai Mendoza — GitHub Profile README                               ║
  ║  How to edit this file:                                            ║
  ║   1. Banner: the <svg> block below is 100% self-contained          ║
  ║      (no external images). GitHub's README sanitizer strips        ║
  ║      <style>/@keyframes from inline SVG, so all motion here uses   ║
  ║      native SMIL <animate>/<animateTransform> tags instead — edit  ║
  ║      the values="" / dur="" attributes on those to adjust it.      ║
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
<!-- Motion is native SMIL (<animate>/<animateTransform>) because  -->
<!-- GitHub's README sanitizer strips <style>/<script> from SVG.   -->
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
      <stop offset="0%" stop-color="#58a6ff">
        <animate attributeName="stop-color" values="#58a6ff;#bc8cff;#39d0d8;#58a6ff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#bc8cff">
        <animate attributeName="stop-color" values="#bc8cff;#39d0d8;#58a6ff;#bc8cff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#39d0d8">
        <animate attributeName="stop-color" values="#39d0d8;#58a6ff;#bc8cff;#39d0d8" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <pattern id="gridPattern" width="40" height="40" patternUnits="userSpaceOnUse">
      <animateTransform attributeName="patternTransform" type="translate" values="0 0; 40 40; 0 0" dur="14s" repeatCount="indefinite"/>
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#30363d" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bgGrad)"/>
  <rect width="940" height="260" x="-20" y="-20" fill="url(#gridPattern)" opacity="0.4"/>

  <!-- Pulsing background glow behind the name -->
  <circle cx="450" cy="110" r="160" fill="url(#glow)">
    <animate attributeName="r" values="160;182;160" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.55;1;0.55" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Decorative twinkling sparks -->
  <circle cx="120" cy="50" r="2.5" fill="#58a6ff">
    <animate attributeName="opacity" values="0;1;0" dur="3s" begin="0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="780" cy="60" r="2" fill="#58a6ff">
    <animate attributeName="opacity" values="0;1;0" dur="3s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="170" r="2" fill="#58a6ff">
    <animate attributeName="opacity" values="0;1;0" dur="3s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="160" r="2.5" fill="#58a6ff">
    <animate attributeName="opacity" values="0;1;0" dur="3s" begin="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="30" r="2" fill="#58a6ff">
    <animate attributeName="opacity" values="0;1;0" dur="3s" begin="2.4s" repeatCount="indefinite"/>
  </circle>

  <!-- Centered name + tagline (gently floating) -->
  <text x="450" y="112" font-family="'Segoe UI', Verdana, Arial, sans-serif" font-size="54" font-weight="800" fill="url(#textGrad)" text-anchor="middle">
    Sai Mendoza
    <animateTransform attributeName="transform" type="translate" values="0 0; 0 -6; 0 0" dur="3.5s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="148" font-family="'Segoe UI', Verdana, Arial, sans-serif" font-size="18" font-weight="400" fill="#8b949e" text-anchor="middle" letter-spacing="2">
    IT STUDENT • WEB DEVELOPER • BUILDER
    <animateTransform attributeName="transform" type="translate" values="0 0; 0 -6; 0 0" dur="3.5s" begin="0.15s" repeatCount="indefinite"/>
  </text>
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
