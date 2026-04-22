<h1 align="center">Aiden Kim</h1>

<p align="center">
  <em>Aerospace engineering. Token-efficient agent infrastructure. Bash is (mostly) all you need.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/KAIST-0B1120?style=flat-square&labelColor=0B1120&color=38bdf8" alt="KAIST">
  <img src="https://img.shields.io/badge/Aerospace_Engineering-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Aerospace Engineering">
  <img src="https://img.shields.io/badge/Agent_Infrastructure-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Agent Infrastructure">
  <img src="https://img.shields.io/badge/Safety--Critical_Systems-0B1120?style=flat-square&labelColor=0B1120&color=1e293b" alt="Safety-Critical Systems">
</p>

---

## Connect

```
 Daejeon, Korea               (UTC +09:00)
 skybluejacket@kaist.ac.kr
 X            @VibeCodeAiden
 Instagram    geun._.daeng
 GitHub       @AidenGeunGeun
```

---

## Now

**Pathtent — CTO** · *Pre-launch B2B SaaS*
AI-assisted patent specification writing and similarity search. Built a structured patent database (Postgres + Cloudflare R2) after KIPRIS proved too limiting. Next.js frontend, FastAPI backend, Chrome extension for inline drafting.

**Airbus Fly Your Ideas — Phase 2** · *Competing for finalist slot (top 3), submission end of May 2026*
*In Vitro Firmware Red-Teaming* — autonomous firmware verification pipeline for aerospace supply-chain security. Mentored by Prof. Yongdae Kim (KAIST SSL).

---

## Featured Work

### Agent Infrastructure

```
╭─ recall ─────────────────────── @skybluejacket/recall ─╮
│  $ recall "deployment bug from last sprint"            │
│  → journal/2026-03-14.md   lines 42–67                 │
│  → journal/2026-03-18.md   lines 88–103                │
│                                                         │
│  CWD-scoped semantic memory for agents.                 │
│  Grounds hallucinating sessions in real notes.          │
╰──────────── github.com/AidenGeunGeun/recall ──────────╯
```
<sub>**[→ recall](https://github.com/AidenGeunGeun/recall)** · [npm](https://www.npmjs.com/package/@skybluejacket/recall) · Semantic journal search · TypeScript</sub>

```
╭─ transcribe-cli ──────────── @opencode/transcribe-cli ─╮
│  $ transcribe ./papers/pinn-guidance.pdf               │
│  [fast path]    text/layout OK     12 pages            │
│  [glm-ocr]      equation-dense     5 pages             │
│  → ./papers/pinn-guidance.md                           │
│                                                         │
│  Local, offline OCR. Fast path for clean text,         │
│  GLM-OCR for math-dense pages. No cloud, ever.          │
╰──────── github.com/AidenGeunGeun/transcribe-cli ──────╯
```
<sub>**[→ transcribe-cli](https://github.com/AidenGeunGeun/transcribe-cli)** · [npm](https://www.npmjs.com/package/@opencode/transcribe-cli) · Document OCR for researchers · TypeScript</sub>

```
╭─ code-intel ──────────────────── structural retrieval ─╮
│  $ code-intel trace auth middleware → sessionStore     │
│  → middleware/auth.ts:validateToken                    │
│  → services/session/store.ts:get                       │
│  → 2 hops · BM25 + vector + rerank                     │
│                                                         │
│  Indexed codebase graph with three retrieval paths:     │
│  search, trace, gather. Relationships, not strings.     │
╰──────────── github.com/AidenGeunGeun/code-intel ──────╯
```
<sub>**[→ code-intel](https://github.com/AidenGeunGeun/code-intel)** · Structural code retrieval engine · TypeScript</sub>

```
╭─ exa-cli ─────────────────── three-tier web research ─╮
│  $ exa-cli '{"query":"current Node.js LTS"}'           │
│  {                                                      │
│    "tier":   "auto",                                    │
│    "result": "Node.js 22.x (Jod)",                     │
│    "sources": [ ... ]                                   │
│  }                                                      │
│                                                         │
│  JSON-in, JSON-out. Three tiers: auto, synthesis,      │
│  deep. Pick the work-to-cost ratio per question.       │
╰──────────── github.com/AidenGeunGeun/exa-cli ─────────╯
```
<sub>**[→ exa-cli](https://github.com/AidenGeunGeun/exa-cli)** · Agent-first web research · JavaScript</sub>

```
╭─ todoist-cli ───────────────── headless task automation ╮
│  $ todoist-cli tasks create \\                          │
│      --content "Ship profile README" --priority 4       │
│  {"id": "8219...", "url": "https://..."}               │
│                                                         │
│  JSON-first Todoist control. Tasks, projects,           │
│  sections, users — scriptable from any agent.           │
╰────────── github.com/AidenGeunGeun/todoist-cli ───────╯
```
<sub>**[→ todoist-cli](https://github.com/AidenGeunGeun/todoist-cli)** · Headless Todoist for agents · JavaScript</sub>

```
╭─ OpenCodeOrchestra ─────── multi-layer agent protocol ─╮
│  PM          "ship the auth refactor"                   │
│    └─ Orchestrator (spec + phases)                      │
│         ├─ Investigator  (read-only trace)              │
│         ├─ Auditor       (spec compliance)              │
│         └─ Docs          (API updates)                  │
│                                                         │
│  Each role: its own depth, permissions, and model.      │
│  Fork of OpenCode v1.2.5.                               │
╰──── github.com/AidenGeunGeun/OpencodeOrchestra ───────╯
```
<sub>**[→ OpenCodeOrchestra](https://github.com/AidenGeunGeun/OpencodeOrchestra)** · Depth-aware agent orchestration · TypeScript</sub>

```
╭─ opencode-context-compress ─── manual-first compression ╮
│  user   > /compress manage                              │
│  agent  > compress_map()  → 99 entries, ~146K tokens    │
│  agent  > compress(b0, "profile README design")         │
│  agent  > compress(b1, "repo creation + rendering")     │
│  → ~30K tokens remaining, tail untouched                │
│                                                         │
│  No autonomous loops. Agent decides what to fold.       │
╰── github.com/AidenGeunGeun/opencode-context-compress ─╯
```
<sub>**[→ opencode-context-compress](https://github.com/AidenGeunGeun/opencode-context-compress)** · Explicit context management · TypeScript</sub>

### Systems & Exploration

```
╭─ the-hive ─────────── multi-agent architectural debate ╮
│  task        design patent-similarity ranking service   │
│  room:frontend  ·  room:backend  ·  room:database       │
│    → adversarial domain deliberation                    │
│  room:synthesis                                         │
│    → unified proposal + evidence trail                  │
│  human gate   approve / reject with feedback            │
│                                                         │
│  Shelved. Phases 0–5 complete. 113 passing tests.       │
╰──────────── github.com/AidenGeunGeun/the-hive ────────╯
```
<sub>**[→ the-hive](https://github.com/AidenGeunGeun/the-hive)** · Multi-agent architecture deliberation · TypeScript · *Shelved*</sub>

```
╭─ blue-pcbang-dropship ──────── windows firewall DACL ─╮
│  problem   PC bang disk image nukes mpssvc            │
│            + strips CHANGE_CONFIG from Admin ACE       │
│  foothold  leftover WRITE_DAC on the DACL             │
│  fix       grant Admin rights back, refresh SCM,      │
│            start service → dropship runs              │
│                                                        │
│  One-click Overwatch 2 server selector fix.            │
╰─ github.com/AidenGeunGeun/blue-pcbang-dropship ──────╯
```
<sub>**[→ blue-pcbang-dropship](https://github.com/AidenGeunGeun/blue-pcbang-dropship)** · Systems reverse-engineering · PowerShell</sub>

### Aerospace

```
╭─ PINN_Guidance ───────── physics-informed guidance NN ─╮
│  classical 3-DOF sim  →  differentiable physics + PMP  │
│                       →  PINN rebuild of costate/tf    │
│  learn  λ(t), t_f     compute  u from PMP structure   │
│  rollout through differentiable dynamics               │
│                                                         │
│  Ongoing individual research. Paused for ~2 months.    │
╰──────── github.com/AidenGeunGeun/PINN_Guidance ───────╯
```
<sub>**[→ PINN_Guidance](https://github.com/AidenGeunGeun/PINN_Guidance)** · Physics-informed neural guidance · Python + MATLAB</sub>

```
╭─ hvt-missile-sim ──────── HVT intercept · MATLAB · 6DOF ╮
│  targets      parameterizable ballistic threat profiles │
│  interceptors configurable airframe + seeker models     │
│  guidance     PNG · APN · variants · comparison runs    │
│                                                         │
│  Full six-degree-of-freedom rigid-body dynamics.        │
╰────────── github.com/AidenGeunGeun/hvt-missile-sim ───╯
```
<sub>**[→ hvt-missile-sim](https://github.com/AidenGeunGeun/hvt-missile-sim)** · HVT defense simulation · MATLAB</sub>

```
╭─ 6dofsim ──────────────────── rigid-body missile sim ─╮
│  Full 6DOF dynamics + aerodynamic lookup tables.       │
│  Built standalone for guidance law testing.            │
╰──────────── github.com/AidenGeunGeun/6dofsim ─────────╯
```
<sub>**[→ 6dofsim](https://github.com/AidenGeunGeun/6dofsim)** · Six-DOF missile simulator · MATLAB</sub>

```
╭─ Coop_guidance ───────────── multi-agent interception ╮
│  Cooperative guidance law with shared-information      │
│  intercept. Python implementation.                     │
╰────────── github.com/AidenGeunGeun/Coop_guidance ─────╯
```
<sub>**[→ Coop_guidance](https://github.com/AidenGeunGeun/Coop_guidance)** · Cooperative guidance · Python</sub>

<sub>*Archive: [9M723-Iskander-missile-trajectory](https://github.com/AidenGeunGeun/9M723-Iskander-missile-trajectory) — preserved copy of a deleted repo with solid 6DOF aeroballistic modeling. Kept for reference.*</sub>

---

## Research

**KAIST Flight Dynamics and Control Lab (FDCCL)** · Prof. Chang Hoon Lee · 2024–2025
- One-year individual study + paid research
- Collaborated on **air-to-air missile range estimation**: real-time on-board computation of no-escape zone for HUD display. Hit **60 Hz with high fidelity** on compute-constrained cockpit hardware.
- Continuing to look for aerospace / CS crossover opportunities at KAIST labs.

**Undergraduate Research — PINNs for Aerospace Applications** · 2024–2025
- Physics-informed neural networks for guidance and trajectory estimation.

---

## Background

**B.S. Aerospace Engineering, KAIST** · 2021–2026 (5th year, on semester leave)

| Year | |
|---|---|
| 2025– | **CTO, Pathtent** |
| 2025 | **Hanwha Aerospace Special Award** — Republic of Korea Air Force Academy Academic Conference |
| 2024–2025 | **FDCCL, KAIST** — Prof. Chang Hoon Lee — individual study + paid researcher |
| 2024–2025 | **Undergraduate Research** — PINNs for Aerospace Applications |
| 2026 | **Airbus Fly Your Ideas — Phase 2** (competing for finalist) |

---

## Tech

<p align="center">
  <img src="https://img.shields.io/badge/Python-0B1120?style=flat-square&logo=python&logoColor=f1f5f9&labelColor=0B1120" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-0B1120?style=flat-square&logo=typescript&logoColor=f1f5f9&labelColor=0B1120" alt="TypeScript">
  <img src="https://img.shields.io/badge/PyTorch-0B1120?style=flat-square&logo=pytorch&logoColor=f1f5f9&labelColor=0B1120" alt="PyTorch">
  <img src="https://img.shields.io/badge/MLX-0B1120?style=flat-square&logo=apple&logoColor=f1f5f9&labelColor=0B1120" alt="MLX">
  <img src="https://img.shields.io/badge/MATLAB-0B1120?style=flat-square&logo=mathworks&logoColor=f1f5f9&labelColor=0B1120" alt="MATLAB">
  <img src="https://img.shields.io/badge/React-0B1120?style=flat-square&logo=react&logoColor=f1f5f9&labelColor=0B1120" alt="React">
  <img src="https://img.shields.io/badge/Next.js-0B1120?style=flat-square&logo=nextdotjs&logoColor=f1f5f9&labelColor=0B1120" alt="Next.js">
  <img src="https://img.shields.io/badge/FastAPI-0B1120?style=flat-square&logo=fastapi&logoColor=f1f5f9&labelColor=0B1120" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-0B1120?style=flat-square&logo=postgresql&logoColor=f1f5f9&labelColor=0B1120" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/LaTeX-0B1120?style=flat-square&logo=latex&logoColor=f1f5f9&labelColor=0B1120" alt="LaTeX">
  <img src="https://img.shields.io/badge/Bash-0B1120?style=flat-square&logo=gnubash&logoColor=f1f5f9&labelColor=0B1120" alt="Bash">
</p>

---

## Activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=AidenGeunGeun&theme=dark&hide_border=true&background=0B1120&ring=38bdf8&fire=38bdf8&currStreakLabel=f1f5f9" alt="GitHub streak">
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AidenGeunGeun&theme=github-compact&hide_border=true&bg_color=0B1120&color=f1f5f9&line=38bdf8&point=38bdf8&area=true" alt="Contribution activity">
</p>

---

<p align="center">
  <sub><em>Aerospace engineering. Token-efficient agent infrastructure.</em></sub>
</p>
