<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Ali Erdem Gedik — Junior Software Developer. Screens from Eventra, BAOBAB, Fermente Paneli and Fortuna Moda." width="100%">
</picture>

<p>
  <a href="https://www.linkedin.com/in/alierdemgedik/"><img src="https://img.shields.io/badge/LinkedIn-alierdemgedik-1f6f8b?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alierdemgdk58@gmail.com"><img src="https://img.shields.io/badge/Email-alierdemgdk58%40gmail.com-14232c?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-Istanbul%2C%20T%C3%BCrkiye-1f6f8b?style=flat-square" alt="Istanbul, Türkiye">
</p>

Third-year Software Engineering student in a fully English-taught program and part-time Junior
Software Engineer at **Black Wool** since January 2026. I build business systems for real clients,
from the first requirements meeting to the release pipeline, and I care most about the parts that
keep them honest: permissions, data integrity, privacy and measured results.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/numbers-dark.svg">
  <img src="assets/numbers-light.svg" alt="104 permissions · 0 confidently-wrong fields · 614 orders audited in October · 16 of 19 tools read-only" width="100%">
</picture>

| Focus | Measured result |
|---|---|
| **Authorization** | 104 permissions across 36 sections, database-defined roles, field-level visibility for ID numbers and payments — Eventra |
| **Concurrency** | Double booking prevented by locking the hall row inside the transaction; the losing request gets `409 Conflict` — Eventra |
| **Privacy by design** | A marketplace dashboard that never stores buyer personal data; the Excel import stops on any unexpected column — Fermente Paneli |
| **AI with guardrails** | AI reads, code decides: 0 confidently-wrong fields on the evaluation set; AI tools that write only after an exact approval phrase — Fortuna Moda, Black Tool |
| **Measured quality** | 424 test cases in Black Tool, 236 in Fortuna Moda, 189 check scripts in Eventra |

## Selected work · Black Wool

Source code is private; every link is a public case study with masked screenshots, diagrams and the measurements behind each number.

<table>
<tr>
<td colspan="2" valign="top">
<a href="https://github.com/aeg58/eventra-case-study"><img src="assets/projects/eventra.jpg" alt="Eventra reservation calendar" width="100%"></a>

### [Eventra](https://github.com/aeg58/eventra-case-study)
<sub>Project Lead & Developer · in production since Sep 2026 · v1.2.0</sub>

Reservation, finance and operations platform a wedding venue runs its daily business on — calendar across two branches, settings-driven booking form, deposits and cash boxes, contracts as server-side PDFs, 13 reports, QR menu and digital business card. 56 models · 109 API routes · 72 screens.

<img src="https://img.shields.io/badge/Next.js-16-14232c?style=flat-square&logo=nextdotjs"> <img src="https://img.shields.io/badge/Prisma-7-14232c?style=flat-square&logo=prisma"> <img src="https://img.shields.io/badge/MySQL-8.4-14232c?style=flat-square&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/RBAC-104%20permissions-1f6f8b?style=flat-square"> <a href="https://github.com/aeg58/eventra-case-study"><img src="https://img.shields.io/badge/Read%20the%20case%20study-%E2%86%92-1f6f8b?style=flat-square&logo=github"></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/aeg58/baobab-case-study"><img src="assets/projects/baobab.jpg" alt="BAOBAB home page" width="100%"></a>

### [BAOBAB](https://github.com/aeg58/baobab-case-study)
<sub>Developer · live since Oct 2026</sub>

Catalogue and editorial admin for a comics publisher. Page-flip previews, slug history with permanent redirects, JSON-LD in 12 schema.org types.

<img src="https://img.shields.io/badge/Next.js-16-14232c?style=flat-square&logo=nextdotjs"> <img src="https://img.shields.io/badge/SQLite-14232c?style=flat-square&logo=sqlite&logoColor=white"> <a href="https://baobabyayinlari.com"><img src="https://img.shields.io/badge/Live%20site-baobabyayinlari.com-2e7d32?style=flat-square"></a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/aeg58/fermente-panel-case-study"><img src="assets/projects/fermente.jpg" alt="Fermente Paneli overview" width="100%"></a>

### [Fermente Paneli](https://github.com/aeg58/fermente-panel-case-study)
<sub>Project Lead & Developer · on its own server</sub>

Read-only sales, profit and payout-audit dashboard across Trendyol and Hepsiburada. GET-only collector; no buyer personal data stored.

<img src="https://img.shields.io/badge/Next.js-16-14232c?style=flat-square&logo=nextdotjs"> <img src="https://img.shields.io/badge/libSQL-14232c?style=flat-square&logo=sqlite&logoColor=white"> <img src="https://img.shields.io/badge/read--only-by%20design-1f6f8b?style=flat-square">
</td>
</tr>
<tr>
<td valign="top">
<a href="https://github.com/aeg58/fortuna-moda-case-study"><img src="assets/projects/fortuna.jpg" alt="Fortuna Moda order list" width="100%"></a>

### [Fortuna Moda](https://github.com/aeg58/fortuna-moda-case-study)
<sub>Project Lead & Developer · panel live since Oct 2026</sub>

WhatsApp and Instagram orders turned into checked DHL eCommerce shipments. AI reads, code decides; 236 test cases.

<img src="https://img.shields.io/badge/Next.js-16-14232c?style=flat-square&logo=nextdotjs"> <img src="https://img.shields.io/badge/PostgreSQL-14232c?style=flat-square&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/OCR-local%20model-1f6f8b?style=flat-square">
</td>
<td valign="top">
<a href="https://github.com/aeg58/black-tool-case-study"><img src="assets/projects/black-tool.svg" alt="Black Tool gateway diagram" width="100%"></a>

### [Black Tool](https://github.com/aeg58/black-tool-case-study)
<sub>Project Lead & Developer · internal tool</sub>

MCP gateway that lets an AI assistant read client ad and marketplace accounts brand by brand. 16 of 19 tools read-only; writes need `YAZMA OK` and start paused.

<img src="https://img.shields.io/badge/MCP-server-14232c?style=flat-square"> <img src="https://img.shields.io/badge/AES--256--GCM-credentials-14232c?style=flat-square"> <img src="https://img.shields.io/badge/tests-424-1f6f8b?style=flat-square">
</td>
</tr>
</table>

## Systems, algorithms & data

Individual coursework, documented as standalone repositories; each README states the course context.

| Repository | What it shows |
|---|---|
| [posix-pi-benchmark](https://github.com/aeg58/posix-pi-benchmark) · C | **3.67×** at 4 threads on 4 cores, flat beyond — the plateau is the hardware limit, not a defect |
| [shortest-path-algorithms](https://github.com/aeg58/shortest-path-algorithms) · C | BFS, Dijkstra and A* over 1,000 vertices; the A* heuristic is kept **admissible**, so it matches Dijkstra |
| [max-flow-min-cost](https://github.com/aeg58/max-flow-min-cost) · C++ | Edmonds–Karp and min-cost max flow written from scratch on a residual graph |
| [clustering-algorithms-comparison](https://github.com/aeg58/clustering-algorithms-comparison) · Python | Seven algorithms, six metrics — the best silhouette score picks the *least* informative model |
| [budget-planner](https://github.com/aeg58/budget-planner) · Java | PBKDF2-HMAC-SHA256 password storage with constant-time verification |

<sub>More: [recursive-file-copy](https://github.com/aeg58/recursive-file-copy) · [algorithm-task-3](https://github.com/aeg58/algorithm-task-3) · [statistical-analysis-report](https://github.com/aeg58/statistical-analysis-report) · [conference-hall-reservation](https://github.com/aeg58/conference-hall-reservation) · [snake-game-js](https://github.com/aeg58/snake-game-js) · [tourism-equipment-rental-uml](https://github.com/aeg58/tourism-equipment-rental-uml)</sub>

## Stack

<p>
<img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-14232c?style=flat-square&logo=javascript&logoColor=f7df1e"> <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/Java-b07219?style=flat-square&logo=openjdk&logoColor=white"> <img src="https://img.shields.io/badge/C%20%2F%20C%2B%2B-00599c?style=flat-square&logo=c&logoColor=white"> <img src="https://img.shields.io/badge/SQL-1f6f8b?style=flat-square&logo=postgresql&logoColor=white"><br>
<img src="https://img.shields.io/badge/Next.js-14232c?style=flat-square&logo=nextdotjs"> <img src="https://img.shields.io/badge/React-149eca?style=flat-square&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-417e38?style=flat-square&logo=nodedotjs&logoColor=white"> <img src="https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma"> <img src="https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479a1?style=flat-square&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/SQLite-003b57?style=flat-square&logo=sqlite&logoColor=white"> <img src="https://img.shields.io/badge/MCP-14232c?style=flat-square"><br>
<img src="https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Caddy-1f6f8b?style=flat-square&logo=caddy&logoColor=white"> <img src="https://img.shields.io/badge/Linux-14232c?style=flat-square&logo=linux&logoColor=white"> <img src="https://img.shields.io/badge/Vitest-6e9f18?style=flat-square&logo=vitest&logoColor=white"> <img src="https://img.shields.io/badge/Playwright-2ead33?style=flat-square&logo=playwright&logoColor=white">
</p>

**Certifications:** [HackerRank Software Engineer](https://www.hackerrank.com/certificates/6971d09ac7a7) · [Software Engineer Intern](https://www.hackerrank.com/certificates/c62b37e63cdb) · [Problem Solving (Intermediate)](https://www.hackerrank.com/certificates/41b9bc04dbe3) · [SQL (Advanced)](https://www.hackerrank.com/certificates/91a62c957726) · Anthropic Claude Code 101 and Claude Code in Action · English B2 (FSMEPT 71/100)
