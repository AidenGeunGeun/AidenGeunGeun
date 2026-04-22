<h1 align="center">Aiden Kim</h1>

<p align="center">
  <a href="https://github.com/AidenGeunGeun">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1800&color=38bdf8&center=true&width=640&lines=Aerospace+engineering;Token-efficient+agent+infrastructure;Bash+is+all+you+need" alt="Tagline">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/KAIST-38bdf8?style=flat-square&labelColor=0B1120" alt="KAIST">
  <img src="https://img.shields.io/badge/Aerospace-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Aerospace">
  <img src="https://img.shields.io/badge/Agent_Infrastructure-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Agent Infrastructure">
  <img src="https://img.shields.io/badge/Daejeon_·_KST-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Daejeon, Korea">
</p>

<p align="center">
  <a href="mailto:skybluejacket@kaist.ac.kr"><img src="https://img.shields.io/badge/skybluejacket%40kaist.ac.kr-0B1120?style=for-the-badge&logo=gmail&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="Email"></a>
  <a href="https://x.com/VibeCodeAiden"><img src="https://img.shields.io/badge/@VibeCodeAiden-0B1120?style=for-the-badge&logo=x&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="X"></a>
  <a href="https://instagram.com/geun._.daeng"><img src="https://img.shields.io/badge/geun.__.daeng-0B1120?style=for-the-badge&logo=instagram&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="Instagram"></a>
  <a href="https://github.com/AidenGeunGeun"><img src="https://img.shields.io/badge/@AidenGeunGeun-0B1120?style=for-the-badge&logo=github&logoColor=38bdf8&labelColor=0B1120&color=1e293b" alt="GitHub"></a>
</p>

---

## Currently

<table>
<tr><td>

**Pathtent** &nbsp;·&nbsp; CTO &nbsp;·&nbsp; *Pre-launch B2B SaaS*

AI-assisted patent specification writing and similarity search. Built a structured patent database (Postgres + Cloudflare R2) after KIPRIS proved too limiting. Next.js frontend, FastAPI backend, Chrome extension for inline drafting.

</td></tr>
</table>

<table>
<tr><td>

**Airbus Fly Your Ideas** &nbsp;·&nbsp; Phase 2 &nbsp;·&nbsp; *Submission end of May 2026*

*In Vitro Firmware Red-Teaming* — autonomous firmware verification pipeline for aerospace supply-chain security. Competing for one of three global finalist slots. Mentored by Prof. Yongdae Kim (KAIST SSL).

</td></tr>
</table>

---

## Featured Work

### Agent Infrastructure

<table>
<tr><td>

**[recall](https://github.com/AidenGeunGeun/recall)** &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; [`@skybluejacket/recall`](https://www.npmjs.com/package/@skybluejacket/recall)

CWD-scoped semantic memory for AI agents. Cross-session continuity — journal entries live outside the context window, retrieved on demand. Agents hallucinate when they reconstruct state from compressed context; `recall` grounds them in actual notes.

<sub>`embeddings` &nbsp;·&nbsp; `sqlite` &nbsp;·&nbsp; `cli` &nbsp;·&nbsp; `cwd-scoped`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[transcribe-cli](https://github.com/AidenGeunGeun/transcribe-cli)** &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; [`@opencode/transcribe-cli`](https://www.npmjs.com/package/@opencode/transcribe-cli)

Local document-to-markdown OCR for researchers. PDFs, DOCX, XLSX, HWP, images — all offline, no cloud. Clean text takes the fast path. Math-dense pages route through GLM-OCR. Suspicious output is flagged, not silently trusted.

<sub>`glm-ocr` &nbsp;·&nbsp; `local-first` &nbsp;·&nbsp; `multi-format` &nbsp;·&nbsp; `cli`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[code-intel](https://github.com/AidenGeunGeun/code-intel)** &nbsp;·&nbsp; `TypeScript`

Structural codebase retrieval engine. Three paths: `search` for compact entity lookup, `trace` for bounded relationship walks, `gather` for evidence before reading files. BM25 + vector + rerank over a tree-sitter-parsed graph. Relationships, not strings.

<sub>`tree-sitter` &nbsp;·&nbsp; `bm25` &nbsp;·&nbsp; `embeddings` &nbsp;·&nbsp; `hybrid-retrieval`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[exa-cli](https://github.com/AidenGeunGeun/exa-cli)** &nbsp;·&nbsp; `JavaScript` &nbsp;·&nbsp; [`@skybluejacket/exa-cli`](https://www.npmjs.com/package/@skybluejacket/exa-cli)

Three-tier web research via the Exa Search API. `auto`, `synthesis`, `deep` — pick the work-to-cost ratio per question. JSON-in, JSON-out. No server, no config, one env var.

<sub>`exa-api` &nbsp;·&nbsp; `agent-first` &nbsp;·&nbsp; `json-io`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[todoist-cli](https://github.com/AidenGeunGeun/todoist-cli)** &nbsp;·&nbsp; `JavaScript`

Headless Todoist automation. Tasks, projects, sections, users — all scriptable from any agent workflow. JSON-first. No web UI round-trips.

<sub>`todoist-api` &nbsp;·&nbsp; `headless` &nbsp;·&nbsp; `json-io`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[OpenCodeOrchestra](https://github.com/AidenGeunGeun/OpencodeOrchestra)** &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; ★2

Multi-layer agent orchestration. PM plans, orchestrator executes, specialists investigate, audit, document. Each role has its own depth, permissions, and model. Fork of OpenCode v1.2.5.

<sub>`multi-agent` &nbsp;·&nbsp; `orchestration` &nbsp;·&nbsp; `depth-aware` &nbsp;·&nbsp; `opencode-fork`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[opencode-context-compress](https://github.com/AidenGeunGeun/opencode-context-compress)** &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; ★2

Manual-first context compression plugin. No autonomous loops, no per-turn nudges. Compression runs only when you trigger `/compress manage`. The agent chooses what to fold and how tersely. You own the when.

<sub>`opencode-plugin` &nbsp;·&nbsp; `manual-first` &nbsp;·&nbsp; `context-management`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[the-hive](https://github.com/AidenGeunGeun/the-hive)** &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; *Shelved*

Multi-agent architectural deliberation. Domain rooms debate adversarially, synthesis room unifies, human gate approves. Produces ledgers, not code. Phases 0–5 complete, 9 packages, 113 passing tests. Shelved after architectural exploration — kept stable and documented.

<sub>`multi-agent` &nbsp;·&nbsp; `deliberation` &nbsp;·&nbsp; `architecture-first`</sub>

</td></tr>
</table>

### Research & Experiments

<table>
<tr><td>

**[thinking-token](https://github.com/AidenGeunGeun/thinking-token)** &nbsp;·&nbsp; `Python` &nbsp;·&nbsp; *Research*

Can open-source reasoning models match Claude Opus 4.5's encrypted-thinking preservation *without* the proprietary infrastructure? Built a two-view agent (private retained reasoning, clean public conversation) and benchmarked six retention strategies on **τ²-bench telecom** (114 tasks, ~20 turns each) with Qwen3.5 at 2B / 4B / 9B. **Raw retention beats summarized retention. A 3-turn sliding window performs ≈ full retention** (+3.5pp on 9B). Strong directional result — long-horizon agent reliability without encrypted-memory infra.

<sub>`qwen3.5` &nbsp;·&nbsp; `τ²-bench` &nbsp;·&nbsp; `two-view-agent` &nbsp;·&nbsp; `retention-strategies`</sub>

</td></tr>
</table>

### Web Apps

<table>
<tr><td>

**[GraduateKAIST](https://github.com/AidenGeunGeun/GraduateKAIST)** &nbsp;·&nbsp; `TypeScript` · `Next.js` &nbsp;·&nbsp; [live ↗](https://graduatekaist.vercel.app)

KAIST transcript → graduation progress in one upload. Drops the anxious "can I graduate?" question into a clear answer plus a what-if GPA simulator for remaining credits. Everything happens client-side in the browser — no upload, no server, no retention. Department-specific analysis for AE, ME, CS, EE.

<sub>`next.js` &nbsp;·&nbsp; `react-19` &nbsp;·&nbsp; `tailwind-v4` &nbsp;·&nbsp; `privacy-first`</sub>

</td></tr>
</table>

### Systems & Exploration

<table>
<tr><td>

**[blue-pcbang-dropship](https://github.com/AidenGeunGeun/blue-pcbang-dropship)** &nbsp;·&nbsp; `PowerShell`

One-click Overwatch 2 server selector fix for a PC bang chain whose disk image strips `CHANGE_CONFIG` rights from the Windows Firewall service's DACL. The leftover `WRITE_DAC` bit is the foothold — grants Admin rights back, refreshes SCM, starts the service. dropship runs.

<sub>`windows-scm` &nbsp;·&nbsp; `dacl` &nbsp;·&nbsp; `reverse-engineering`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[ZoomToText](https://github.com/AidenGeunGeun/ZoomToText)** &nbsp;·&nbsp; `Python`

Windows-native Whisper ASR. Local GPU or CPU, loopback capture for system audio, timestamped transcripts. Built for private Zoom calls and lectures. No cloud.

<sub>`whisper` &nbsp;·&nbsp; `windows-loopback` &nbsp;·&nbsp; `local-first`</sub>

</td></tr>
</table>

### Aerospace

<table>
<tr><td>

**[PINN_Guidance](https://github.com/AidenGeunGeun/PINN_Guidance)** &nbsp;·&nbsp; `Python` · `MATLAB`

Physics-informed neural networks for air-to-air missile guidance. Classical 3-DOF simulator → differentiable physics + PMP stack → PINN rebuild. Learns costate and final time. Computes control from PMP structure. Rolls out through differentiable dynamics.

<sub>`pinn` &nbsp;·&nbsp; `optimal-control` &nbsp;·&nbsp; `pontryagin` &nbsp;·&nbsp; `missile-guidance`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[hvt-missile-sim](https://github.com/AidenGeunGeun/hvt-missile-sim)** &nbsp;·&nbsp; `MATLAB` &nbsp;·&nbsp; ★2

High-Value Target missile defense simulation. Parameterizable threat profiles and interceptor airframes, PNG / APN / variants with full 6-DOF rigid-body dynamics.

<sub>`6-dof` &nbsp;·&nbsp; `guidance-laws` &nbsp;·&nbsp; `interception`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[6dofsim](https://github.com/AidenGeunGeun/6dofsim)** &nbsp;·&nbsp; `MATLAB`

Standalone six-degree-of-freedom missile simulator. Full rigid-body dynamics with aerodynamic lookup tables, built for guidance law testing in isolation.

<sub>`6-dof` &nbsp;·&nbsp; `aerodynamic-lookup` &nbsp;·&nbsp; `testbed`</sub>

</td></tr>
</table>

<table>
<tr><td>

**[Coop_guidance](https://github.com/AidenGeunGeun/Coop_guidance)** &nbsp;·&nbsp; `Python`

Cooperative guidance law for multi-agent interception. Shared-information policies over a team of pursuers.

<sub>`multi-agent` &nbsp;·&nbsp; `cooperative-guidance`</sub>

</td></tr>
</table>

<sub>*Archive: [9M723-Iskander-missile-trajectory](https://github.com/AidenGeunGeun/9M723-Iskander-missile-trajectory) — preserved copy of a deleted repo with solid 6-DOF aeroballistic modeling. Kept for reference, not authored by me.*</sub>

---

## Research

<table>
<tr><td>

**KAIST Flight Dynamics and Control Lab (FDCL)** &nbsp;·&nbsp; Prof. Chang Hoon Lee &nbsp;·&nbsp; 2024–2025

One-year individual study and paid research. Collaborated on air-to-air missile **range estimation** — real-time on-board computation of the no-escape zone for HUD rendering. Hit **60 Hz with high fidelity** on compute-constrained cockpit hardware.

<sub>*Actively looking for more KAIST lab opportunities at the aerospace / CS intersection.*</sub>

</td></tr>
</table>

<table>
<tr><td>

**Undergraduate Research — PINNs for Aerospace Applications** &nbsp;·&nbsp; 2024–2025

Physics-informed neural networks for guidance and trajectory estimation. Parallel track to the FDCL work.

</td></tr>
</table>

---

## Background

<table>
<tr><td>

<kbd>B.S. Aerospace Engineering · KAIST · 2021–2026 · 5th year, on semester leave</kbd>

| Year | |
|:---|:---|
| **2025–** | CTO, **Pathtent** |
| 2025 | **Hanwha Aerospace Special Award** — ROK Air Force Academy Academic Conference |
| 2024–2025 | **FDCL, KAIST** — individual study + paid researcher under Prof. Chang Hoon Lee |
| 2024–2025 | **Undergraduate Research** — PINNs for aerospace applications |
| **2026** | **Airbus Fly Your Ideas — Phase 2**, competing for finalist |

</td></tr>
</table>

---

## Tech

<p>
  <img src="https://img.shields.io/badge/-Python-0B1120?style=for-the-badge&logo=python&logoColor=38bdf8&labelColor=0B1120" alt="Python">
  <img src="https://img.shields.io/badge/-TypeScript-0B1120?style=for-the-badge&logo=typescript&logoColor=38bdf8&labelColor=0B1120" alt="TypeScript">
  <img src="https://img.shields.io/badge/-PyTorch-0B1120?style=for-the-badge&logo=pytorch&logoColor=38bdf8&labelColor=0B1120" alt="PyTorch">
  <img src="https://img.shields.io/badge/-MLX-0B1120?style=for-the-badge&logo=apple&logoColor=38bdf8&labelColor=0B1120" alt="MLX">
  <img src="https://img.shields.io/badge/-MATLAB-0B1120?style=for-the-badge&labelColor=0B1120" alt="MATLAB">
  <img src="https://img.shields.io/badge/-React-0B1120?style=for-the-badge&logo=react&logoColor=38bdf8&labelColor=0B1120" alt="React">
  <img src="https://img.shields.io/badge/-Next.js-0B1120?style=for-the-badge&logo=nextdotjs&logoColor=38bdf8&labelColor=0B1120" alt="Next.js">
  <img src="https://img.shields.io/badge/-FastAPI-0B1120?style=for-the-badge&logo=fastapi&logoColor=38bdf8&labelColor=0B1120" alt="FastAPI">
  <img src="https://img.shields.io/badge/-PostgreSQL-0B1120?style=for-the-badge&logo=postgresql&logoColor=38bdf8&labelColor=0B1120" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/-LaTeX-0B1120?style=for-the-badge&logo=latex&logoColor=38bdf8&labelColor=0B1120" alt="LaTeX">
  <img src="https://img.shields.io/badge/-Bash-0B1120?style=for-the-badge&logo=gnubash&logoColor=38bdf8&labelColor=0B1120" alt="Bash">
</p>

---

## Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AidenGeunGeun&theme=github-compact&hide_border=true&bg_color=0B1120&color=f1f5f9&line=38bdf8&point=38bdf8&area=true&area_color=1e293b" alt="Contribution activity">
</p>
