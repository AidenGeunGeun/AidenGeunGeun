<h1 align="center">Aiden Kim</h1>

<p align="center">
  <em>Aerospace engineering. Token-efficient agent infrastructure. Bash is (mostly) all you need.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/KAIST-0B1120?style=flat-square&labelColor=0B1120&color=38bdf8" alt="KAIST">
  <img src="https://img.shields.io/badge/Aerospace-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Aerospace Engineering">
  <img src="https://img.shields.io/badge/Agent_Infrastructure-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Agent Infrastructure">
  <img src="https://img.shields.io/badge/Daejeon_·_KST-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Daejeon, Korea">
</p>

<p align="center">
  <a href="mailto:skybluejacket@kaist.ac.kr"><img src="https://img.shields.io/badge/Email-skybluejacket@kaist.ac.kr-0B1120?style=for-the-badge&logo=gmail&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="Email"></a>
  <a href="https://x.com/VibeCodeAiden"><img src="https://img.shields.io/badge/X-@VibeCodeAiden-0B1120?style=for-the-badge&logo=x&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="X"></a>
  <a href="https://instagram.com/geun._.daeng"><img src="https://img.shields.io/badge/Instagram-geun._.daeng-0B1120?style=for-the-badge&logo=instagram&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="Instagram"></a>
  <a href="https://github.com/AidenGeunGeun"><img src="https://img.shields.io/badge/GitHub-@AidenGeunGeun-0B1120?style=for-the-badge&logo=github&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="GitHub"></a>
</p>

---

## Now

**Pathtent — CTO** · *Pre-launch B2B SaaS*
AI-assisted patent specification writing and similarity search. Built a structured patent database (Postgres + Cloudflare R2) after KIPRIS proved too limiting. Next.js frontend, FastAPI backend, Chrome extension for inline drafting.

**Airbus Fly Your Ideas — Phase 2** · *Competing for finalist slot, submission end of May 2026*
*In Vitro Firmware Red-Teaming* — autonomous firmware verification pipeline for aerospace supply-chain security. Only three teams are named finalists globally. Mentored by Prof. Yongdae Kim (KAIST SSL).

---

## Featured Work

### Agent Infrastructure

<table>
<tr>
<td width="50%" valign="top">

#### [recall](https://github.com/AidenGeunGeun/recall)
[`@skybluejacket/recall`](https://www.npmjs.com/package/@skybluejacket/recall) · TypeScript

CWD-scoped semantic memory for AI agents. Cross-session continuity — journal entries stay outside the context window, retrieved on demand.

<sub>Agents hallucinate when they reconstruct state from compressed context. `recall` grounds them in actual notes.</sub>

</td>
<td width="50%" valign="top">

#### [transcribe-cli](https://github.com/AidenGeunGeun/transcribe-cli)
[`@opencode/transcribe-cli`](https://www.npmjs.com/package/@opencode/transcribe-cli) · TypeScript

Local document-to-markdown OCR for researchers. PDFs, DOCX, XLSX, HWP, images — all offline.

<sub>Clean text takes the fast path. Math-dense pages route through GLM-OCR. Suspicious output gets flagged, not silently trusted.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [code-intel](https://github.com/AidenGeunGeun/code-intel)
TypeScript

Structural codebase retrieval. Three paths: `search` for entity lookup, `trace` for bounded relationship walks, `gather` for evidence before reading files.

<sub>BM25 + vector + rerank over a tree-sitter-parsed graph. Not grep.</sub>

</td>
<td width="50%" valign="top">

#### [exa-cli](https://github.com/AidenGeunGeun/exa-cli)
[`@skybluejacket/exa-cli`](https://www.npmjs.com/package/@skybluejacket/exa-cli) · JavaScript

Three-tier web research via the Exa Search API. `auto`, `synthesis`, `deep` — pick the work-to-cost ratio per question.

<sub>JSON-in, JSON-out. No server, no config, one env var.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [todoist-cli](https://github.com/AidenGeunGeun/todoist-cli)
JavaScript

Headless Todoist automation. Tasks, projects, sections, users — all scriptable from any agent workflow.

<sub>JSON-first. No web UI round-trips.</sub>

</td>
<td width="50%" valign="top">

#### [OpenCodeOrchestra](https://github.com/AidenGeunGeun/OpencodeOrchestra)
TypeScript · ★2

Multi-layer agent orchestration. PM plans, orchestrator executes, specialists investigate, audit, and document. Each role has its own depth, permissions, and model.

<sub>Fork of OpenCode v1.2.5.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [opencode-context-compress](https://github.com/AidenGeunGeun/opencode-context-compress)
TypeScript · ★2

Manual-first context compression plugin. No autonomous loops, no per-turn nudges. Compression runs only when you trigger `/compress manage`.

<sub>The agent chooses what to fold and how tersely. You own the when.</sub>

</td>
<td width="50%" valign="top">

#### [the-hive](https://github.com/AidenGeunGeun/the-hive)
TypeScript · *Shelved*

Multi-agent architectural deliberation. Domain rooms debate adversarially, synthesis room unifies, human gate approves. Produces ledgers, not code.

<sub>Phases 0–5 complete, 113 tests passing. Shelved after architectural exploration.</sub>

</td>
</tr>
</table>

### Systems & Exploration

<table>
<tr>
<td width="50%" valign="top">

#### [blue-pcbang-dropship](https://github.com/AidenGeunGeun/blue-pcbang-dropship)
PowerShell

One-click Overwatch 2 server selector fix for a PC bang chain whose disk image strips `CHANGE_CONFIG` from the Windows Firewall service's DACL.

<sub>Leftover `WRITE_DAC` bit is the foothold. Grants Admin rights back, refreshes SCM, starts the service.</sub>

</td>
<td width="50%" valign="top">

#### [ZoomToText](https://github.com/AidenGeunGeun/ZoomToText)
Python

Windows-native Whisper ASR. Local GPU/CPU, loopback capture for system audio, timestamped transcripts.

<sub>No cloud. Built for private Zoom calls and lectures.</sub>

</td>
</tr>
</table>

### Aerospace

<table>
<tr>
<td width="50%" valign="top">

#### [PINN_Guidance](https://github.com/AidenGeunGeun/PINN_Guidance)
Python + MATLAB

Physics-informed neural networks for air-to-air missile guidance. Classical 3-DOF simulator → differentiable physics + PMP stack → PINN rebuild.

<sub>Learns costate and final time. Computes control from PMP structure. Rolls out through differentiable dynamics.</sub>

</td>
<td width="50%" valign="top">

#### [hvt-missile-sim](https://github.com/AidenGeunGeun/hvt-missile-sim)
MATLAB · ★2

High-Value Target missile defense simulation. Parameterizable threat profiles and interceptor airframes, PNG / APN / variants with full 6-DOF rigid-body dynamics.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [6dofsim](https://github.com/AidenGeunGeun/6dofsim)
MATLAB

Standalone six-degree-of-freedom missile simulator. Full rigid-body dynamics with aerodynamic lookup tables, built for guidance law testing in isolation.

</td>
<td width="50%" valign="top">

#### [Coop_guidance](https://github.com/AidenGeunGeun/Coop_guidance)
Python

Cooperative guidance law for multi-agent interception. Shared-information policies over a team of pursuers.

</td>
</tr>
</table>

<sub>*Archive: [9M723-Iskander-missile-trajectory](https://github.com/AidenGeunGeun/9M723-Iskander-missile-trajectory) — preserved copy of a deleted repo with solid 6-DOF aeroballistic modeling. Kept for reference, not authored by me.*</sub>

---

## Research

**KAIST Flight Dynamics and Control Lab (FDCL)** · Prof. Chang Hoon Lee · 2024–2025
One-year individual study and paid research. Collaborated on air-to-air missile **range estimation** — real-time on-board computation of the no-escape zone for HUD rendering. Hit **60 Hz with high fidelity** on compute-constrained cockpit hardware.

*Actively looking for more KAIST lab opportunities at the aerospace / CS intersection.*

**Undergraduate Research — PINNs for Aerospace Applications** · 2024–2025
Physics-informed neural networks for guidance and trajectory estimation. Parallel track to the FDCL work.

---

## Background

**B.S. Aerospace Engineering, KAIST** · 2021–2026 · 5th year, on semester leave

| Year | |
|---|---|
| 2025– | **CTO, Pathtent** |
| 2025 | **Hanwha Aerospace Special Award** — ROK Air Force Academy Academic Conference |
| 2024–2025 | **FDCL, KAIST** — individual study + paid research under Prof. Chang Hoon Lee |
| 2024–2025 | **Undergraduate Research** — PINNs for aerospace applications |
| 2026 | **Airbus Fly Your Ideas — Phase 2**, competing for finalist slot |

---

## Tech

<p align="center">
  <img src="https://img.shields.io/badge/Python-0B1120?style=flat-square&logo=python&logoColor=38bdf8&labelColor=0B1120" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-0B1120?style=flat-square&logo=typescript&logoColor=38bdf8&labelColor=0B1120" alt="TypeScript">
  <img src="https://img.shields.io/badge/PyTorch-0B1120?style=flat-square&logo=pytorch&logoColor=38bdf8&labelColor=0B1120" alt="PyTorch">
  <img src="https://img.shields.io/badge/MLX-0B1120?style=flat-square&logo=apple&logoColor=38bdf8&labelColor=0B1120" alt="MLX">
  <img src="https://img.shields.io/badge/MATLAB-0B1120?style=flat-square&logo=mathworks&logoColor=38bdf8&labelColor=0B1120" alt="MATLAB">
  <img src="https://img.shields.io/badge/React-0B1120?style=flat-square&logo=react&logoColor=38bdf8&labelColor=0B1120" alt="React">
  <img src="https://img.shields.io/badge/Next.js-0B1120?style=flat-square&logo=nextdotjs&logoColor=38bdf8&labelColor=0B1120" alt="Next.js">
  <img src="https://img.shields.io/badge/FastAPI-0B1120?style=flat-square&logo=fastapi&logoColor=38bdf8&labelColor=0B1120" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-0B1120?style=flat-square&logo=postgresql&logoColor=38bdf8&labelColor=0B1120" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/LaTeX-0B1120?style=flat-square&logo=latex&logoColor=38bdf8&labelColor=0B1120" alt="LaTeX">
  <img src="https://img.shields.io/badge/Bash-0B1120?style=flat-square&logo=gnubash&logoColor=38bdf8&labelColor=0B1120" alt="Bash">
</p>

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AidenGeunGeun&show_icons=true&hide_border=true&bg_color=0B1120&title_color=38bdf8&text_color=f1f5f9&icon_color=38bdf8&include_all_commits=true&count_private=true&hide=contribs" alt="GitHub stats" width="48%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AidenGeunGeun&layout=compact&hide_border=true&bg_color=0B1120&title_color=38bdf8&text_color=f1f5f9&langs_count=8" alt="Top languages" width="48%">
</p>

---

<p align="center">
  <sub><em>Aerospace engineering. Token-efficient agent infrastructure.</em></sub>
</p>
