<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=160&color=0:0B1120,50:1e293b,100:0B1120&section=header&text=Aiden%20Kim&fontSize=64&fontColor=f1f5f9&fontAlign=50&fontAlignY=55&animation=fadeIn" alt="Aiden Kim">
</p>

<p align="center">
  <a href="https://github.com/AidenGeunGeun">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1500&color=38bdf8&center=true&width=620&lines=Aerospace+engineering;Token-efficient+agent+infrastructure;Bash+is+%28mostly%29+all+you+need" alt="Tagline">
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

## &nbsp;&nbsp;⬢&nbsp;&nbsp;Currently

> [!NOTE]
> ### [Pathtent](https://github.com/AidenGeunGeun) &nbsp;·&nbsp; CTO &nbsp;·&nbsp; *Pre-launch*
>
> AI-assisted patent specification writing and similarity search. Built a structured patent database (Postgres + Cloudflare R2) after KIPRIS proved too limiting. **Next.js** frontend, **FastAPI** backend, **Chrome extension** for inline drafting.

> [!IMPORTANT]
> ### Airbus Fly Your Ideas &nbsp;·&nbsp; Phase 2 &nbsp;·&nbsp; *Submission May 2026*
>
> ***In Vitro Firmware Red-Teaming*** — autonomous firmware verification pipeline for aerospace supply-chain security. Competing for one of three global finalist slots. Mentored by Prof. Yongdae Kim (KAIST SSL).

---

## &nbsp;&nbsp;⬡&nbsp;&nbsp;Featured Work

<p>
  <img src="https://img.shields.io/badge/🟢_Live-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Live">
  <img src="https://img.shields.io/badge/🔵_Shipping-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Shipping">
  <img src="https://img.shields.io/badge/🟣_Research-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Research">
  <img src="https://img.shields.io/badge/⚫_Shelved-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Shelved">
  <img src="https://img.shields.io/badge/⚪_Archive-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Archive">
</p>

### Agent Infrastructure

<table>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-recall-38bdf8?style=for-the-badge&labelColor=0B1120" alt="recall">
</picture>

#### [recall](https://github.com/AidenGeunGeun/recall) &nbsp;<sup>[`npm`](https://www.npmjs.com/package/@skybluejacket/recall)</sup>

CWD-scoped semantic memory for AI agents. Cross-session continuity — journal entries live outside the context window, retrieved on demand.

> *Agents hallucinate when they reconstruct state from compressed context.* `recall` *grounds them in actual notes.*

<sub>`TypeScript` · `Embeddings` · `SQLite` · `CLI`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-transcribe--cli-38bdf8?style=for-the-badge&labelColor=0B1120" alt="transcribe-cli">
</picture>

#### [transcribe-cli](https://github.com/AidenGeunGeun/transcribe-cli) &nbsp;<sup>[`npm`](https://www.npmjs.com/package/@opencode/transcribe-cli)</sup>

Local document-to-markdown OCR for researchers. PDFs, DOCX, XLSX, HWP, images — all offline, no cloud.

> *Clean text takes the fast path. Math-dense pages route through GLM-OCR. Suspicious output gets flagged, not silently trusted.*

<sub>`TypeScript` · `GLM-OCR` · `Local-first`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-code--intel-38bdf8?style=for-the-badge&labelColor=0B1120" alt="code-intel">
</picture>

#### [code-intel](https://github.com/AidenGeunGeun/code-intel)

Structural codebase retrieval engine. Three paths: `search` for compact entity lookup, `trace` for bounded relationship walks, `gather` for evidence before reading files.

> *BM25 + vector + rerank over a tree-sitter-parsed graph. Relationships, not strings.*

<sub>`TypeScript` · `tree-sitter` · `BM25 + embeddings`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-exa--cli-38bdf8?style=for-the-badge&labelColor=0B1120" alt="exa-cli">
</picture>

#### [exa-cli](https://github.com/AidenGeunGeun/exa-cli) &nbsp;<sup>[`npm`](https://www.npmjs.com/package/@skybluejacket/exa-cli)</sup>

Three-tier web research via the Exa Search API. `auto`, `synthesis`, `deep` — pick the work-to-cost ratio per question.

> *JSON-in, JSON-out. No server, no config, one env var.*

<sub>`JavaScript` · `Exa API` · `Agent-first`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-todoist--cli-38bdf8?style=for-the-badge&labelColor=0B1120" alt="todoist-cli">
</picture>

#### [todoist-cli](https://github.com/AidenGeunGeun/todoist-cli)

Headless Todoist automation. Tasks, projects, sections, users — all scriptable from any agent workflow.

> *JSON-first. No web UI round-trips.*

<sub>`JavaScript` · `Todoist API`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🔵-OpenCodeOrchestra-38bdf8?style=for-the-badge&labelColor=0B1120" alt="OpenCodeOrchestra">
</picture>

#### [OpenCodeOrchestra](https://github.com/AidenGeunGeun/OpencodeOrchestra) &nbsp;<sup>★2</sup>

Multi-layer agent orchestration. PM plans, orchestrator executes, specialists investigate, audit, document. Each role has its own depth, permissions, and model.

> *Fork of OpenCode v1.2.5.*

<sub>`TypeScript` · `Multi-agent` · `Orchestration`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🔵-opencode--context--compress-38bdf8?style=for-the-badge&labelColor=0B1120" alt="opencode-context-compress">
</picture>

#### [opencode-context-compress](https://github.com/AidenGeunGeun/opencode-context-compress) &nbsp;<sup>★2</sup>

Manual-first context compression plugin. No autonomous loops, no per-turn nudges. Compression runs only when you trigger `/compress manage`.

> *The agent chooses what to fold and how tersely. You own the when.*

<sub>`TypeScript` · `OpenCode Plugin`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/⚫-the--hive-64748b?style=for-the-badge&labelColor=0B1120" alt="the-hive">
</picture>

#### [the-hive](https://github.com/AidenGeunGeun/the-hive)

Multi-agent architectural deliberation. Domain rooms debate adversarially, synthesis room unifies, human gate approves. Produces ledgers, not code.

> *Phases 0–5 complete. 113 tests passing. Shelved after architectural exploration — kept stable and documented.*

<sub>`TypeScript` · `9 packages` · *Shelved*</sub>

</td>
</tr>
</table>

### Systems & Exploration

<table>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-blue--pcbang--dropship-a78bfa?style=for-the-badge&labelColor=0B1120" alt="blue-pcbang-dropship">
</picture>

#### [blue-pcbang-dropship](https://github.com/AidenGeunGeun/blue-pcbang-dropship)

One-click Overwatch 2 server selector fix for a PC bang chain whose disk image strips `CHANGE_CONFIG` from the Windows Firewall service's DACL.

> *Leftover `WRITE_DAC` bit is the foothold. Grants Admin rights back, refreshes SCM, starts the service.*

<sub>`PowerShell` · `Windows SCM` · `DACL manipulation`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-ZoomToText-a78bfa?style=for-the-badge&labelColor=0B1120" alt="ZoomToText">
</picture>

#### [ZoomToText](https://github.com/AidenGeunGeun/ZoomToText)

Windows-native Whisper ASR. Local GPU or CPU, loopback capture for system audio, timestamped transcripts.

> *No cloud. Built for private Zoom calls and lectures.*

<sub>`Python` · `Whisper` · `Windows loopback`</sub>

</td>
</tr>
</table>

### Aerospace

<table>
<tr>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟣-PINN__Guidance-fbbf24?style=for-the-badge&labelColor=0B1120" alt="PINN_Guidance">
</picture>

#### [PINN_Guidance](https://github.com/AidenGeunGeun/PINN_Guidance)

Physics-informed neural networks for air-to-air missile guidance. Classical 3-DOF simulator → differentiable physics + PMP stack → PINN rebuild.

> *Learns costate and final time. Computes control from PMP structure. Rolls out through differentiable dynamics.*

<sub>`Python` · `MATLAB` · `PINNs` · `Optimal Control`</sub>

</td>
<td width="50%" valign="top">

<picture>
  <img src="https://img.shields.io/badge/🟢-hvt--missile--sim-fbbf24?style=for-the-badge&labelColor=0B1120" alt="hvt-missile-sim">
</picture>

#### [hvt-missile-sim](https://github.com/AidenGeunGeun/hvt-missile-sim) &nbsp;<sup>★2</sup>

High-Value Target missile defense simulation. Parameterizable threat profiles and interceptor airframes, PNG / APN / variants with full 6-DOF rigid-body dynamics.

<sub>`MATLAB` · `6-DOF` · `Guidance laws`</sub>

</td>
</tr>
</table>

**More aerospace work**

| Repo | Pitch | Stack |
|---|---|---|
| [6dofsim](https://github.com/AidenGeunGeun/6dofsim) | Standalone 6-DOF missile simulator with aerodynamic lookup tables for guidance law testing | `MATLAB` |
| [Coop_guidance](https://github.com/AidenGeunGeun/Coop_guidance) | Cooperative guidance law for multi-agent interception, shared-information policies | `Python` |
| [9M723-Iskander-missile-trajectory](https://github.com/AidenGeunGeun/9M723-Iskander-missile-trajectory) <sup>⚪ archive</sup> | Preserved copy of a deleted repo with solid 6-DOF aeroballistic modeling | `Jupyter` |

---

## &nbsp;&nbsp;◈&nbsp;&nbsp;Research

> [!TIP]
> ### KAIST Flight Dynamics and Control Lab (FDCL) &nbsp;·&nbsp; 2024–2025
> **Prof. Chang Hoon Lee** · One-year individual study + paid research.
>
> Collaborated on air-to-air missile **range estimation** — real-time on-board computation of the no-escape zone for HUD rendering. Hit **60 Hz with high fidelity** on compute-constrained cockpit hardware.
>
> *Actively looking for more KAIST lab opportunities at the aerospace / CS intersection.*

**Undergraduate Research — PINNs for Aerospace Applications** · 2024–2025
Physics-informed neural networks for guidance and trajectory estimation. Parallel track to FDCL work.

---

## &nbsp;&nbsp;◇&nbsp;&nbsp;Background

<kbd>B.S. Aerospace Engineering · KAIST · 2021–2026 · 5th year, on semester leave</kbd>

| Year | Role / Recognition |
|:---|:---|
| **2025–** | CTO, **Pathtent** |
| 2025 | **Hanwha Aerospace Special Award** — ROK Air Force Academy Academic Conference |
| 2024–2025 | **FDCL, KAIST** — individual study + paid researcher under Prof. Chang Hoon Lee |
| 2024–2025 | **Undergraduate Research** — PINNs for aerospace applications |
| **2026** | **Airbus Fly Your Ideas — Phase 2**, competing for finalist |

---

## &nbsp;&nbsp;⬢&nbsp;&nbsp;Tech

<p>
  <img src="https://img.shields.io/badge/-Python-0B1120?style=for-the-badge&logo=python&logoColor=38bdf8&labelColor=0B1120" alt="Python">
  <img src="https://img.shields.io/badge/-TypeScript-0B1120?style=for-the-badge&logo=typescript&logoColor=38bdf8&labelColor=0B1120" alt="TypeScript">
  <img src="https://img.shields.io/badge/-PyTorch-0B1120?style=for-the-badge&logo=pytorch&logoColor=38bdf8&labelColor=0B1120" alt="PyTorch">
  <img src="https://img.shields.io/badge/-MLX-0B1120?style=for-the-badge&logo=apple&logoColor=38bdf8&labelColor=0B1120" alt="MLX">
  <img src="https://img.shields.io/badge/-MATLAB-0B1120?style=for-the-badge&logo=mathworks&logoColor=38bdf8&labelColor=0B1120" alt="MATLAB">
  <img src="https://img.shields.io/badge/-React-0B1120?style=for-the-badge&logo=react&logoColor=38bdf8&labelColor=0B1120" alt="React">
  <img src="https://img.shields.io/badge/-Next.js-0B1120?style=for-the-badge&logo=nextdotjs&logoColor=38bdf8&labelColor=0B1120" alt="Next.js">
  <img src="https://img.shields.io/badge/-FastAPI-0B1120?style=for-the-badge&logo=fastapi&logoColor=38bdf8&labelColor=0B1120" alt="FastAPI">
  <img src="https://img.shields.io/badge/-PostgreSQL-0B1120?style=for-the-badge&logo=postgresql&logoColor=38bdf8&labelColor=0B1120" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/-LaTeX-0B1120?style=for-the-badge&logo=latex&logoColor=38bdf8&labelColor=0B1120" alt="LaTeX">
  <img src="https://img.shields.io/badge/-Bash-0B1120?style=for-the-badge&logo=gnubash&logoColor=38bdf8&labelColor=0B1120" alt="Bash">
</p>

---

## &nbsp;&nbsp;⬣&nbsp;&nbsp;Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AidenGeunGeun&theme=github-compact&hide_border=true&bg_color=0B1120&color=f1f5f9&line=38bdf8&point=38bdf8&area=true&area_color=1e293b" alt="Contribution activity">
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=80&color=0:0B1120,50:1e293b,100:0B1120&section=footer" alt="Footer">
</p>
