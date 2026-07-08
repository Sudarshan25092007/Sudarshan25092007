<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=9ECE6A&center=true&vCenter=true&width=700&lines=Hi,+I'm+Sudarshan+Patil+H+J;Backend+Infrastructure+Engineer;Open+Source+Contributor+@+InsForge;Node.js+%C2%B7+TypeScript+%C2%B7+PostgreSQL+%C2%B7+Redis" alt="Typing SVG" />
  </a>
</h1>
<h3 align="center">Building production backend systems, database performance tools, and real-time concurrent infrastructure.</h3>
<p align="center">
  <a href="#about-me"><b>About</b></a> • 
  <a href="#open-source"><b>Open Source</b></a> • 
  <a href="#projects"><b>Projects</b></a> • 
  <a href="#skills"><b>Skills</b></a> • 
  <a href="#contact"><b>Contact</b></a>
</p>
<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=Sudarshan25092007&theme=tokyonight&no-frame=true&no-bg=true&margin-w=15&rank=S,AAA,AA,A,B" alt="GitHub Trophies" />
  </a>
</p>
<h2 align="center" id="about-me">👤 About Me</h2>
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1000&color=7AA2F7&center=true&vCenter=true&width=800&lines=18-year-old+Backend+Infrastructure+Engineer.;6+merged+PRs+to+InsForge+(YC-backed,+12K+stars).;Specializing+in+Node.js,+TypeScript,+PostgreSQL,+Redis.;Security-focused:+XSS,+timing+attacks,+cache+stampede+prevention.;Studying+CS+@+BITS+Pilani+%2B+Scaler+School+of+Technology." alt="Typing SVG" />
  </a>
</p>
<blockquote align="center">
  <p>
    <i>"I specialize in backend infrastructure — database performance optimization, security hardening, and real-time concurrent systems. I contribute to <b>InsForge</b> (YC-backed, 12K GitHub stars) where I've shipped production fixes for O(1) row counters, AI gateway token cost caps, cache stampede prevention, and stored XSS mitigation. Currently building a <b>real-time concurrent auction system</b> with Redis atomic operations and WebSocket pub/sub."</i>
  </p>
</blockquote>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
<h2 align="center" id="open-source">🚀 Open Source</h2>
<h3 align="center">InsForge — Backend Infrastructure Contributor</h3>
<p align="center"><a href="https://github.com/InsForge/InsForge">github.com/InsForge/InsForge</a> • 12K+ Stars • YC-Backed</p>
<p align="center">
  <a href="https://github.com/InsForge/InsForge/pulls?q=is%3Apr+author%3ASudarshan25092007+is%3Amerged">
    <img src="https://img.shields.io/badge/Merged%20PRs-7-9ECE6A?style=for-the-badge&logo=github&logoColor=white" alt="Merged PRs" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Contributor%20Rank-%237-7AA2F7?style=for-the-badge&logo=github&logoColor=white" alt="Contributor Rank" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Commits-39%2B-1a1b26?style=for-the-badge&logo=git&logoColor=9ECE6A" alt="Commits" />
  </a>
</p>
<table align="center">
  <tr>
    <td align="center"><b>PR</b></td>
    <td align="center"><b>Impact</b></td>
    <td align="center"><b>Tech</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1351">#1351</a></td>
    <td>Centralized 55+ scattered env vars into typed <code>AppConfig</code> (21 files, 49 tests)</td>
    <td>TypeScript, Config Architecture</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1494">#1494</a></td>
    <td>Replaced O(n) <code>SELECT COUNT(*)</code> with trigger-backed O(1) row counters</td>
    <td>PostgreSQL, Triggers, Performance</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1519">#1519</a></td>
    <td>Bounded <code>tableCountCache</code> with LRU-style size limiting to prevent memory leaks</td>
    <td>LRU Cache, Memory Management</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1526">#1526</a></td>
    <td>Token cost caps on AI gateway + promise-lock cache stampede prevention</td>
    <td>Security, Rate Limiting, Redis</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1541">#1541</a></td>
    <td>Externalized token cap configuration with security boundary tests</td>
    <td>Security, Test Architecture</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1626">#1626</a></td>
    <td>Magic-byte MIME validation to prevent stored XSS via file upload</td>
    <td>Security, XSS Prevention</td>
  </tr>
  <tr>
    <td><a href="https://github.com/InsForge/InsForge/pull/1443">#1443</a></td>
    <td>Deno global type safety, OAuth AppError standardization, OpenAPI sunset headers</td>
    <td>Type Safety, OAuth, API Design</td>
  </tr>
</table>
<p align="center"><i>Security: Stored XSS mitigation, timing attack fixes, OTP brute-force prevention, Deno secret export hardening</i></p>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
<h2 align="center" id="projects">🛠️ Projects</h2>
<table align="center">
  <tr>
    <td width="50%" valign="top">
      <h3>🏏 IPL Mock Auction Platform</h3>
      <p><b>Node.js • Redis • WebSockets • PostgreSQL</b></p>
      <p>Real-time concurrent auction system with Redis atomic operations for race-condition-safe bid validation. Redis Pub/Sub for live bid broadcasting, sorted sets for leaderboard state management.</p>
      <p><b>Key Engineering:</b> SETNX atomic budget checks, 50-concurrent-bid stress testing, WebSocket reconnect logic, Docker Compose deployment.</p>
      <p><a href="https://github.com/Sudarshan25092007/ipl-auction-app">Source Code</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>📊 XAUUSD High-Frequency Data Ingestion Engine</h3>
      <p><b>Python • FastAPI • MQL5 • Supabase • Docker</b></p>
      <p>Custom Native TCP Bridge (Python ↔ MetaTrader 5) using persistent buffers and newline-delimited packet framing. Processes 1,000–3,000 ticks/minute with zero partial-read errors.</p>
      <p><b>Key Engineering:</b> μ+1.5σ statistical regime detector, μ+4σ Density Shield black swan filter, fault-tolerant Supabase PostgreSQL persistence with in-memory fallback, 10-second MT5 position sync protocol.</p>
      <p><i>Architecture documented. Code release upcoming.</i></p>
    </td>
  </tr>
</table>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
<h2 align="center" id="skills">⚡ Tech Stack</h2>
<p align="center">
  <b>Languages</b><br><br>
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" />
  <img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" />
  <img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
  <img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" />
  <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="SQL" />
</p>
<p align="center">
  <b>Backend & Infrastructure</b><br><br>
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" />
  <img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="Express" />
  <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" />
  <img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" />
  <img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
  <img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" />
  <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
</p>
<p align="center">
  <b>Concepts</b><br><br>
  <img src="https://img.shields.io/badge/REST%20APIs-1a1b26?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-1a1b26?style=for-the-badge" alt="WebSockets" />
  <img src="https://img.shields.io/badge/JWT%20Auth-1a1b26?style=for-the-badge" alt="JWT Auth" />
  <img src="https://img.shields.io/badge/Database%20Triggers-1a1b26?style=for-the-badge" alt="DB Triggers" />
  <img src="https://img.shields.io/badge/EXPLAIN%20ANALYZE-1a1b26?style=for-the-badge" alt="Query Optimization" />
  <img src="https://img.shields.io/badge/Cache%20Stampede%20Prevention-1a1b26?style=for-the-badge" alt="Cache Patterns" />
  <img src="https://img.shields.io/badge/Concurrent%20Systems-1a1b26?style=for-the-badge" alt="Concurrency" />
  <img src="https://img.shields.io/badge/Security%20Hardening-1a1b26?style=for-the-badge" alt="Security" />
</p>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
<h2 align="center">📊 The Code Analytics</h2>
<p align="center">
  <a href="https://github.com/Sudarshan25092007">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sudarshan25092007&theme=tokyo-night&hide_border=true&bg_color=1a1b26" alt="GitHub Activity Graph" width="100%" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/Sudarshan25092007">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Sudarshan25092007&theme=tokyonight" alt="GitHub Profile Summary" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/Sudarshan25092007">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sudarshan25092007&theme=tokyonight&hide_border=true&background=1a1b26" alt="GitHub Streak" />
  </a>
</p>
<p align="center">
  <img src="https://leetcard.jacoblin.cool/Sudarshan_patil_h_j?theme=tokyonight&font=Fira%20Code&ext=activity" alt="LeetCode Stats" />
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake.svg">
  </picture>
</p>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
<h2 align="center" id="contact">📫 Contact</h2>
<p align="center">
  Open to backend engineering internships and open-source collaborations.<br><br>
  <a href="mailto:hjsudarshanpatil@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sudarshan-patil-hj259227/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://sudarshan25092007.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white" /></a>
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sudarshan25092007&color=7aa2f7&style=for-the-badge&label=PROFILE+VIEWS" alt="Visitor Count" />
</p>
<p align="center">
  <i>Backend Infrastructure Engineer • Node.js • TypeScript • PostgreSQL • Redis</i><br>
  <i>© 2026 Sudarshan Patil. All rights reserved.</i>
</p>
