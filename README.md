<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=9ECE6A&center=true&vCenter=true&width=850&height=60&lines=Hi,+I'm+Sudarshan+Patil+H+J;Backend+Infrastructure+Engineer;Open+Source+Contributor+%40+Reticle+%2B+InsForge+%2B+Apicurio;Node.js+%C2%B7+TypeScript+%C2%B7+Java+%C2%B7+PostgreSQL+%C2%B7+Redis"
      alt="Sudarshan's GitHub Typing SVG"
    />
  </a>
</h1>

<h3 align="center">
  Building backend infrastructure, concurrent systems, developer tooling, and security-focused software.
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/sudarshan-patil-hj259227/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:hjsudarshanpatil@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://sudarshan25092007.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://leetcode.com/Sudarshan_patil_h_j/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</p>

<p align="center">
  <img
    src="https://komarev.com/ghpvc/?username=Sudarshan25092007&color=7aa2f7&style=for-the-badge&label=PROFILE+VIEWS"
    alt="Visitor Count"
  />
</p>

---

<h2 align="center">👤 About Me</h2>

<p align="center">
  <b>Backend Infrastructure Engineer</b> focused on systems where correctness, concurrency, reliability, and security actually matter.
</p>

<p align="center">
  I work primarily with <b>Node.js, TypeScript, Java, PostgreSQL, Redis, and Docker</b>,
  and I enjoy going below the API layer to understand how systems behave under
  concurrency, failure, partial state, and adversarial inputs.
</p>

<p align="center">
  Currently contributing to <b>Reticle</b>, <b>InsForge</b>, and <b>Apicurio Registry</b>,
  while building real-time and systems-oriented projects of my own.
</p>

<blockquote align="center">
  <i>
    "Don't just fix the symptom. Understand the system, validate the assumption,
    and then implement the smallest architecture that makes the behavior correct."
  </i>
</blockquote>

---

<h2 align="center">🚀 Open Source</h2>

<h3 align="center">Reticle — AI Agent Verification Layer</h3>

<p align="center">
  <a href="https://github.com/reticlehq/reticle">Reticle Repository</a>
  • TypeScript
  • Node.js
  • MCP
  • Playwright
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20Agent%20Verification-9ECE6A?style=for-the-badge" alt="AI Agent Verification" />
  <img src="https://img.shields.io/badge/Focus-MCP-7AA2F7?style=for-the-badge" alt="MCP" />
  <img src="https://img.shields.io/badge/Platform-Windows%20%2F%20Linux%20%2F%20macOS-1a1b26?style=for-the-badge" alt="Cross Platform" />
</p>

As an active contributor, I work on the benchmark, verification, and browser-state infrastructure behind Reticle.

| Contribution | Engineering Work |
|---|---|
| [#439](https://github.com/reticlehq/reticle/pull/439) | Fixed Windows benchmark process orchestration, including `pnpm.cmd`, platform-aware process teardown, and Windows-safe child-process handling. |
| [#570](https://github.com/reticlehq/reticle/pull/570) | Built the MCP tool profiler harness with dynamic `tools/list` discovery, fixture orchestration, safe tool execution, and latency/error/payload telemetry. Shipped with Reticle v2.12.0. |
| [#580](https://github.com/reticlehq/reticle/pull/580) | Built regression enforcement around benchmark invariants, detecting errors, timeouts, protocol crashes, missing tools, and payload regressions while treating latency as advisory. |
| [#735](https://github.com/reticlehq/reticle/pull/735) | Designed opt-in `seedStorage` for `reticle_lease`, supporting pre-navigation cookies, `localStorage`, and `sessionStorage` with origin isolation, one-time injection, and concurrent acquisition protection. |
| [#865](https://github.com/reticlehq/reticle/pull/865) | Fixed a causal verification flaw by evaluating `STATE` predicates before actions, preventing pre-existing state from being falsely attributed to an action. |

### Verification Work

- Validated **30/30 advertised MCP tools** through the benchmark harness.
- Added deterministic regression checks for errors, timeouts, protocol crashes, missing tools, and payload regressions.
- Added pre-navigation browser state injection while preserving origin and context isolation.
- Added regression coverage for causal verification correctness.
- Validated **15/15 targeted**, **72/72 parity**, and **288/288 honesty** tests for the STATE verification fix.

---

<h3 align="center">Apicurio Registry — CNCF Sandbox Project</h3>

<p align="center">
  <a href="https://github.com/Apicurio/apicurio-registry">Apicurio Registry</a>
  • Java
  • Quarkus
  • JSON Schema
  • Maven
</p>

My contribution focused on correctness in the MCP tool backward-compatibility checker.

| Issue / PR | Engineering Work |
|---|---|
| [#9178](https://github.com/Apicurio/apicurio-registry/issues/9178) | Identified a correctness gap where schema-breaking MCP tool changes could pass silently due to incomplete type/null handling. |
| [#9181](https://github.com/Apicurio/apicurio-registry/pull/9181) | Developed the direct fix with **19 targeted tests**, iterating through maintainer review on union types, property-type removal, and untyped-to-typed transitions. |
| [#9301](https://github.com/Apicurio/apicurio-registry/issues/9301) | Filed the architectural follow-up after maintainer feedback identified the existing `JsonSchemaDiffLibrary` as the better abstraction for JSON Schema compatibility. |
| [#9368](https://github.com/Apicurio/apicurio-registry/pull/9368) | Developed the redirected implementation across Maven modules, replacing approximately **170 lines** of shallow comparison logic with delegation to `JsonSchemaDiffLibrary` and adding regression coverage for JSON Schema compatibility semantics. |

The work evolved from a direct correctness fix into a deeper architectural implementation after maintainer review. The final PR was closed because the implementation scope was reserved for the LFX mentorship term.

---

<h3 align="center">InsForge — Backend Infrastructure Contributor</h3>

<p align="center">
  <a href="https://github.com/InsForge/InsForge">InsForge</a>
  • YC-Backed
  • TypeScript
  • Node.js
  • PostgreSQL
</p>

<p align="center">
  <a href="https://github.com/InsForge/InsForge/pulls?q=is%3Apr+author%3ASudarshan2509200715+is%3Amerged">
    <img src="https://img.shields.io/badge/10%20Merged%20PRs-9ECE6A?style=for-the-badge&logo=github&logoColor=white" alt="10 Merged PRs" />
  </a>
  <img src="https://img.shields.io/badge/Security-Focused-ff6b6b?style=for-the-badge" alt="Security Focused" />
  <img src="https://img.shields.io/badge/Backend-Infrastructure-7AA2F7?style=for-the-badge" alt="Backend Infrastructure" />
</p>

My work spans backend infrastructure, security hardening, database performance, configuration architecture, and reliability.

| PR | Contribution |
|---|---|
| [#1795](https://github.com/InsForge/InsForge/pull/1795) | Built Phase 1 of a PostgreSQL-native durable messaging queue with outbox/DLQ persistence, `LISTEN/NOTIFY` + polling fallback, atomic `SKIP LOCKED` claims, lease recovery, retries/backoff, idempotency, and duplicate-delivery safeguards. |
| [#1626](https://github.com/InsForge/InsForge/pull/1626) | Hardened file uploads against stored XSS using magic-byte content detection, unsafe MIME handling, `nosniff`, forced downloads, and upload content-type pinning; added **22 regression tests**. |
| [#1660](https://github.com/InsForge/InsForge/pull/1660) | Fixed a timing side-channel in admin authentication using pre-hashing and `crypto.timingSafeEqual()`. |
| [#1807](https://github.com/InsForge/InsForge/pull/1807) | Restricted internal PostgreSQL, PostgREST, and Deno service ports to `127.0.0.1` to prevent unintended public exposure. |
| [#1811](https://github.com/InsForge/InsForge/pull/1811) | Hardened canonical cloud deployment Compose configurations by restricting PostgreSQL, PostgREST, Deno, and auth ports to loopback. |
| [#1494](https://github.com/InsForge/InsForge/pull/1494) | Reduced repeated database metadata scans using a 60-second in-memory table-count cache with batched exact-count fallback. |
| [#1519](https://github.com/InsForge/InsForge/pull/1519) | Bounded table-count caching to prevent unbounded memory growth. |
| [#1526](https://github.com/InsForge/InsForge/pull/1526) | Added AI token-cost safeguards and promise-based cache stampede prevention for concurrent model requests. |
| [#1541](https://github.com/InsForge/InsForge/pull/1541) | Externalized AI token limits and added upstream failure protection with circuit-breaker behavior and stale-cache fallback. |
| [#1351](https://github.com/InsForge/InsForge/pull/1351) | Centralized **55+ environment-variable reads across 21 files** into a typed `AppConfig`, with **49 tests** covering configuration behavior and regressions. |
| [#1443](https://github.com/InsForge/InsForge/pull/1443) | Improved backend type safety, standardized OAuth errors, and introduced OpenAPI deprecation/sunset metadata. |

### Messaging Infrastructure 

The messaging project started from a feature request I proposed after investigating the existing infrastructure and identifying the lack of a durable background-job system.

The architecture was developed collaboratively with the maintainers:

```text
Application
    │
    ▼
Transactional Enqueue
    │
    ▼
PostgreSQL Durable Queue
    │
    ├──────────────► LISTEN / NOTIFY ───────► Worker
    │                                         │
    │                                         ▼
    │                                  Atomic Claim
    │                                  + Lease
    │                                         │
    │                                         ▼
    │                                   EmailService
    │                                         │
    │                            ┌────────────┴────────────┐
    │                            ▼                         ▼
    │                          Sent                  Retry / Backoff
    │                                                        │
    │                                                        ▼
    │                                                   Dead Letter
    │
    └──────────────► Polling / Reconciliation
```
The Phase 1 implementation intentionally focuses on infrastructure rather than adding SMS, Push, or a new public messaging SDK.
[PR](https://github.com/InsForge/InsForge/pull/1795)
### Key mechanisms include:

- PostgreSQL-backed durable jobs.
- Transactional enqueue.
- LISTEN/NOTIFY for low-latency wake-up.
- Polling fallback for missed notifications.
- FOR UPDATE SKIP LOCKED for concurrent workers.
- Claim tokens and lease-based recovery.
- Retry scheduling with exponential backoff.
- Dead-letter handling.
- Idempotency and duplicate-delivery safeguards.
- Reconciliation for expired/orphaned jobs.
- Graceful worker lifecycle handling.
- Existing EmailService as the first delivery handler.
<h3 align="center">Other Open Source Contributions</h3> <p align="center"> <a href="https://github.com/vijayamsand/PyChem-Pro">PyChem-Pro</a> </p>

Contributed a small refactor to a shared discrete-calculation module used by the molecular simulation force-field implementation, replacing direct private-field access with a public accessor.

<h2 align="center">🛠️ Projects</h2> <h3>🏏 IPL Auction Platform — Concurrent Real-Time System</h3> <p> <b>Node.js • TypeScript • Redis • PostgreSQL • Socket.IO • Docker</b> </p> <p> A real-time concurrent auction system focused on race-condition-safe bidding, server-authoritative state, crash recovery, and synchronization across clients. </p>

```text
Clients
   │
   ▼
Socket.IO
   │
   ▼
Auction Server
   │
   ├──────────────► Redis
   │                 ├── SETNX Mutex
   │                 ├── Lock Token
   │                 ├── Lua Release
   │                 ├── Pub/Sub
   │                 └── Auction State
   │
   └──────────────► PostgreSQL
                     └── Durable Bid / Audit State
```
Key Engineering
- Designed a concurrency-safe bidding engine using Redis SETNX mutexes.
- Used token-validated Lua release to prevent incorrect lock ownership release.
- Used PostgreSQL for durable bid and audit state.
- Used Redis Pub/Sub for live auction state propagation.
- Implemented server-authoritative epoch timers.
- Added Redis-backed state recovery and state-sync hydration.
- Added 13 integration suites covering 61 tests across bidding, mutexes, transactions, recovery, and host controls.
- Stress-tested concurrent bidding behavior.

🔗 [Source Code](https://github.com/Sudarshan25092007/ipl-auction-app)

<h3>📊 XAUUSD High-Frequency Market Data Ingestion Engine</h3> <p> <b>Python • TCP • PostgreSQL • Docker • MetaTrader 5</b> </p> <p> An event-driven backend system bridging MetaTrader 5 with a stateful Python processing engine for high-frequency market telemetry. </p>
Architecture

```text
MetaTrader 5
     │
     │ TCP
     ▼
Python TCP Bridge
     │
     │ newline-delimited framing
     ▼
Async Processing Engine
     │
     ├──────────► Sliding Window / Signals
     │
     └──────────► PostgreSQL
                    │
                    └── 2s timeout
                           │
                           ▼
                     Local CSV Fallback
```
Key Engineering
- Built a native TCP bridge between MetaTrader 5 and Python.
- Used newline-delimited framing to safely reconstruct TCP stream messages.
- Handles 3,000+ packets/minute under the designed workload.
- Uses asynchronous PostgreSQL persistence with connection pooling.
- Automatically degrades to local CSV persistence after database timeout.
- Maintains a separate processing layer from network and persistence I/O.
- Includes MT5 position reconciliation and state synchronization.
- Uses statistical regime detection and risk-gating logic for market telemetry.

🔗 [Source Code
](https://github.com/Sudarshan25092007/XAUUSD-ENGINE)
<h2 align="center">🎓 Education</h2> <p align="center"> <b>Scaler School of Technology — Computer Science & AI</b><br> 2025 – 2029 • Bengaluru, India </p> <p align="center"> <b>BITS Pilani — B.Sc. (Hons.), Computer Science</b><br> 2025 – 2029 • Online / Distance Learning </p>
<h2 align="center">🏆 Achievements</h2> <p align="center"> <b>10</b> merged pull requests into InsForge • <b>Active Contributor</b> to Apicurio Registry • <b>Selected Contributor</b> — GirlScript Summer of Code 2026 </p>
<h2 align="center">⚡ Tech Stack & Skills</h2> 
<h3 align="center">Languages</h3> <p align="center"> 
<img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" /> 
<img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" /> 
<img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" /> 
<img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" /> 
<img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="SQL" /> </p> 
<h3 align="center">Backend & Infrastructure</h3> <p align="center"> <img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" /> <img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="Express" /> <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" /> <img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" /> 
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" /> <img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" /> <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" /> 
<img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub" /> </p> 
<h3 align="center">Core Engineering Areas</h3> <p align="center"> 
<img src="https://img.shields.io/badge/Distributed%20Systems-1a1b26?style=for-the-badge&color=9ECE6A" alt="Distributed Systems" /> 
<img src="https://img.shields.io/badge/Concurrent%20Systems-1a1b26?style=for-the-badge&color=7AA2F7" alt="Concurrent Systems" /> <img src="https://img.shields.io/badge/Security%20Hardening-1a1b26?style=for-the-badge&color=ff6b6b" alt="Security Hardening" /> <img src="https://img.shields.io/badge/Database%20Optimization-1a1b26?style=for-the-badge&color=bb9af7" alt="Database Optimization" /> <img src="https://img.shields.io/badge/TCP%20Networking-1a1b26?style=for-the-badge&color=73daca" alt="TCP Networking" /> 
<img src="https://img.shields.io/badge/API%20Design-1a1b26?style=for-the-badge&color=e0af68" alt="API Design" /> 
<img src="https://img.shields.io/badge/Concurrency-1a1b26?style=for-the-badge&color=ff9e64" alt="Concurrency" /> <img src="https://img.shields.io/badge/Testing-1a1b26?style=for-the-badge&color=79c0ff" alt="Testing" /> </p>
<h2 align="center">📊 GitHub Analytics</h2> <p align="center"> <a href="https://github.com/Sudarshan25092007"> 
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sudarshan25092007&theme=tokyo-night&hide_border=true&bg_color=1a1b26" alt="GitHub Activity Graph" width="100%" /> </a> </p> <p align="center"> <a href="https://github.com/Sudarshan25092007"> <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Sudarshan25092007&theme=tokyonight" alt="GitHub Profile Summary" /> </a> </p> <p align="center"> <a href="https://github.com/Sudarshan25092007"> 
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sudarshan25092007&theme=tokyonight&hide_border=true&background=1a1b26" alt="GitHub Streak" /> </a> </p> <p align="center"> <img src="https://leetcard.jacoblin.cool/Sudarshan_patil_h_j?theme=tokyonight&font=Fira%20Code&ext=activity" alt="LeetCode Stats" /> </p> <p align="center"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake-dark.svg" /> 
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake.svg" /> <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/Sudarshan25092007/Sudarshan25092007/output/github-contribution-grid-snake.svg" /> </picture> </p>
<h2 align="center">📫 Contact</h2> <p align="center"> Open to backend engineering internships, systems work, and meaningful open-source collaborations. </p> <p align="center"> <a href="mailto:hjsudarshanpatil@gmail.com"> <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /> </a> <a href="https://www.linkedin.com/in/sudarshan-patil-hj259227/"> 
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /> </a> <a href="https://sudarshan25092007.github.io/portfolio/"> <img src="https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio" /> </a> <a href="https://leetcode.com/Sudarshan_patil_h_j/"> <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /> </a> </p> <p align="center"> 
<i>Backend Infrastructure • Distributed Systems • Concurrent Systems • Security • Open Source</i> </p>
