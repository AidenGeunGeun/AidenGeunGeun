<p align="center">
  <img src="./assets/profile-banner-v2.jpg" alt="Abstract trajectory and agent-system paths" width="100%">
</p>

<h1 align="center">Aiden Kim</h1>

<p align="center">
  KAIST Aerospace Engineering · MLAI Lab · Agent Infrastructure
</p>

<p align="center">
  <a href="https://aidengeungeun.github.io">Website</a> ·
  <a href="mailto:skybluejacket@kaist.ac.kr">Email</a> ·
  <a href="https://x.com/VibeCodeAiden">X</a>
</p>

I work on ML systems: sparse Mixture-of-Experts inference and LLM serving on Intel Gaudi and Apple Silicon. I also build tools for AI agents and have a background in aerospace guidance and control. I am an Aerospace Engineering undergraduate at KAIST, expected to graduate in February 2028.

## Now & recent

- **[KAIST MLAI Lab](https://www.mlai-kaist.com/)** — Undergraduate researcher under Prof. Sung Ju Hwang, working on efficient MoE inference ([arXiv 2610.37386](https://arxiv.org/abs/2610.37386)) and heterogeneous LLM serving.
- **DeepAuto.ai** (Aug–Sep 2026) — Full-time research engineer on a project basis; independently brought up Kimi K3 serving on Intel Gaudi 2 across 16 HPUs.
- **Pathtent** — Co-founder & CTO, building a patent drafting and prior-art platform.
- **Airbus Fly Your Ideas** — Led *In Vitro Firmware Red-Teaming*. We advanced to the mentored Round 2 from 360+ teams and did not advance to the three-team final.

## Selected work

- **[calibration-free-moe](https://github.com/AidenGeunGeun/calibration-free-moe)** — Code for *Channel Selection for Mixture-of-Experts Decoding Needs No Calibration Data* (vLLM + Triton).
- **[recall](https://github.com/AidenGeunGeun/recall)** — Semantic memory for AI agents without carrying full session history.
- **[transcribe-cli](https://github.com/AidenGeunGeun/transcribe-cli)** — Local document-to-Markdown extraction for PDFs, Office files, images, and more.
- **[code-intel](https://github.com/AidenGeunGeun/code-intel)** — Lightweight code navigation and intelligence for agent workflows.
- **[opencode-context-compress](https://github.com/AidenGeunGeun/opencode-context-compress)** — User-controlled context compression for long-running OpenCode sessions.
- **[GraduateKAIST](https://github.com/AidenGeunGeun/GraduateKAIST)** — Private, client-side graduation planning for KAIST students.
- **[PINN_Guidance](https://github.com/AidenGeunGeun/PINN_Guidance)** — Physics-informed neural networks for real-time aerospace guidance.

[See the full project index →](https://aidengeungeun.github.io/#projects)

## Research

- **Calibration-free MoE activation sparsity** · first author · [arXiv 2610.37386](https://arxiv.org/abs/2610.37386) · 2026

  Keeps 98.1% of full-model accuracy while reading 17.8% of routed-expert weights; MoE blocks run 1.60–1.90× faster than optimized vLLM at batch 1.

- **Kimi K3 on Intel Gaudi 2** · DeepAuto.ai · Aug–Sep 2026

  Brought up a 2.8-trillion-parameter MoE model on Gaudi 2 from scratch across 16 accelerators: 8.7 tok/s single-user decode, 26.6× faster MoE prefill.

- **Heterogeneous LLM serving** · [KAIST MLAI Lab](https://www.mlai-kaist.com/) · 2026

  DGX Spark prefill → Mac Studio MLX decode disaggregation in SGLang: +38.3% aggregate output throughput and −34.8% mean end-to-end latency versus one DGX Spark on Qwen3.6-35B-A3B.

- **Long-context attention behavior** · 2026

  Pilot experiments around RoPE degradation, attention sinks, and position addressability.

- **Agentic completion reliability** · 2026

  Studying whether intent-grounded, trajectory-aware stop gates can reduce false completion in long-horizon coding agents.

- **Aerospace guidance** · 2024—2026

  Missile range estimation, cooperative interception, and PINN-based trajectory generation; the PINN track is currently on hold.

<p align="center">
  <sub>Busan → Daejeon · KAIST Aerospace Engineering</sub>
</p>
