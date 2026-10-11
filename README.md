<h1 align="center">Philipos Hailu Abrham</h1>

<p align="center">
  <b>Software Engineer</b><br/>
  Go · C# / .NET · TypeScript · transactional backends and algorithms
</p>

<p align="center">
  Software Engineer at Innosphere · BSc Software Engineering student at AASTU · Addis Ababa, Ethiopia<br/>
  <b>Open to software engineer roles</b>
</p>

<p align="center">
  <a href="https://philips-portfolio-psi.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-View_Site-10B981?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/philipos-hailu"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hailuphilip@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://codeforces.com/profile/philipos"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="https://leetcode.com/u/philipos"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
</p>

---

<h2 align="center">About</h2>

<p align="center">
  At Innosphere I work on the payment, settlement and ledger core of Hibret Fund, a Go crowdfunding platform.<br/>
  Before that I worked on a manufacturing ERP at Brana and led a 5-engineer frontend squad at Eskalate.
</p>

<p align="center">
  I care about the parts of backend work that have to be right: transactions that balance, retries that are safe,<br/>
  and clear contracts between services. I also solve algorithm problems, 1,100+ on LeetCode and Codeforces so far.
</p>

---

<h2 align="center">🛠️ Stack</h2>

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="48" alt="Go" title="Go" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="48" alt="C#" title="C#" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="48" alt="TypeScript" title="TypeScript" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="48" alt="Python" title="Python" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="48" alt="C++" title="C++" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="48" alt="Dart" title="Dart" />

  <br /><br />

  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" height="48" alt=".NET" title="ASP.NET Core" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="48" alt="PostgreSQL" title="PostgreSQL" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="48" alt="SQLite" title="SQLite" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="48" alt="Docker" title="Docker" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="48" alt="GitHub Actions" title="GitHub Actions" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/swagger/swagger-original.svg" height="48" alt="OpenAPI" title="OpenAPI" />

  <br /><br />

  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="48" alt="Next.js" title="Next.js" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="48" alt="Flutter" title="Flutter" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" height="48" alt="Tailwind CSS" title="Tailwind CSS" />
  <img width="16" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="48" alt="Git" title="Git" />
</div>

---

<h2 align="center">Selected work</h2>

### Hibret Fund

<sub>Innosphere · Aug 2026 – Present · Go, PostgreSQL, Chi, Docker · private codebase, in development</sub>

A crowdfunding and payments platform built as a 30-module hexagonal Go monolith. My part: core pieces of the payment, settlement and ledger system.

- Double-entry ledger with optimistic concurrency control, so debits and credits balance inside one atomic transaction
- Transactional outbox for at-least-once event delivery, and idempotency keys for safe retries
- Dual-approval (maker-checker) payout flow with compensation on failure
- Telebirr integration with HMAC-signed requests, webhook verification and reconciliation, tested against the sandbox
- GitHub Actions CI/CD: format, lint, architecture-boundary checks and tests on every PR, Docker deploys to GCP

### Brana ERP

<sub>Brana Software Solution · Jan 2026 – Aug 2026 · ASP.NET Core, PostgreSQL, Next.js · private codebase, in development</sub>

A manufacturing ERP built by a team. My part:

- Recursive bill-of-materials explosion engine that resolves nested sub-assembly shortfalls against live stock
- Event-driven inventory and production workflows (6 flows) between modules
- Quality-gate checks that block work-order closure while inspections are open
- Next.js dashboards for BOM editing, work-order analytics and warehouse dispatch and receiving

### EthioGuide

<sub>Eskalate · Jul 2025 – Sep 2025 · Next.js, TypeScript, OpenAPI, React Query · [Frontend repo](https://github.com/Ethio-Guide/ethio-guide-frontend)</sub>

An AI guide to 50+ Ethiopian government procedures.

- Led a 5-engineer frontend squad inside a 14-person cross-functional team
- Defined OpenAPI contracts and a BFF layer so frontend and backend could build in parallel

### BirrNote

<sub>Personal project · May 2026 – Present · Flutter, SQLite (Drift), Gemini</sub>

An offline-first personal finance app.

- Reads Telebirr and CBE bank SMS alerts and logs expenses automatically, with duplicate detection
- Budget engine that tracks spending power across the Gregorian and 13-month Ethiopian calendars
- Gemini-based expense parsing in Amharic, Afaan Oromo, Tigrinya and English, with JSON schema validation

---

<h2 align="center">How I build</h2>

- **Correctness before speed.** Code that moves state should be atomic, auditable and safe to retry.
- **Idempotency everywhere.** Requests retry, webhooks arrive twice, workers fail over.
- **Contracts first.** Shared schemas let teams build in parallel without integration surprises.

---

<h2 align="center">Algorithms &amp; recognition</h2>

- **1,100+ problems** solved on LeetCode and Codeforces through the A2SV advanced algorithms program (Google-backed)
- **A2SVian of the Year, 3rd place** among 150+ students at AASTU
- **DSA Track Mentor** at Google Developer Group AASTU, mentoring 21+ students in data structures and competitive programming
- **BSc Software Engineering** student at Addis Ababa Science and Technology University, CGPA 3.72 / 4.0

---

<p align="center">Open to software engineer roles · <a href="https://philips-portfolio-psi.vercel.app/">Portfolio</a> · <a href="https://linkedin.com/in/philipos-hailu">LinkedIn</a></p>
