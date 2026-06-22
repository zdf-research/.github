<!--
  ZDF Research — Organisation Profile
  github.com/zdf-research

  Zentrum für Digitale Forschung
  ——————————————————————————————————————————————————————————
  For those who read source: Zanzariere di Fase.
  The screen keeps the signal clean.
-->

<div align="center">

```
╔════════════════════════════════════════════════╗
║                                                ║
║   ▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓   ║
║   ░░                                      ░░   ║
║   ▓▓        Z D F   R E S E A R C H       ▓▓   ║
║   ░░                                      ░░   ║
║   ▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓   ║
║                                                ║
╚════════════════════════════════════════════════╝
```

**`ZENTRUM FÜR DIGITALE FORSCHUNG`**

*An independent research collective bridging statistical learning theory*  
*and hardware-aware implementation of large language models.*

---

![Status](https://img.shields.io/badge/status-active_research-000000?style=flat-square)
![Phase](https://img.shields.io/badge/phase-curriculum_I-1a1a1a?style=flat-square)
![Compute](https://img.shields.io/badge/compute-H100_cluster-2a2a2a?style=flat-square)
![License](https://img.shields.io/badge/code-MIT-3a3a3a?style=flat-square)

</div>

---

## § 1 &nbsp;&nbsp; Mission

ZDF Research exists to close a specific gap. Modern machine learning practice has bifurcated into two populations: those who call APIs, and those who understand what the APIs are doing. The distance between these two populations is measured not in years of experience but in willingness to read the paper, derive the equation, and write the kernel.

Our operational mandate is the progressive construction of hardware-aware autoregressive language models from mathematical first principles — every component understood, every design decision traced to a source, every implementation profiled against the metal.

We do not treat neural networks as black boxes. We treat them as highly structured physical systems, bounded by memory bandwidth, register pressure, and numerical precision, and we build accordingly.

---

## § 2 &nbsp;&nbsp; Research Charter

**TENET 1:** No wrapper library where a raw tensor operation can be written.
**TENET 2:** No graph break shall pass unexamined into the compilation layer.
**TENET 3:** No claim without a derivation. No derivation without an implementation.
**TENET 4:** No pivot table shall be reformatted on institute time.

---

## § 3 &nbsp;&nbsp; Active Repositories

| Repository | Description | Status |
|:---|:---|:---:|
| [`curriculum`](https://github.com/zdf-research/curriculum) | 12-week reading & build programme. nanoGPT from first principles. | `active` |
| [`implementations`](https://github.com/zdf-research/curriculum/tree/main/implementations) | Per-member model implementations, profiled against a fixed leaderboard | `active` |
| [`presentations`](https://github.com/zdf-research/curriculum/tree/main/presentations) | Weekly seminar slides and derivation notes | `active` |
| [`meta`](https://github.com/zdf-research/meta) | Group governance, RFC proposals, sprint planning | `active` |

---

## § 4 &nbsp;&nbsp; Curriculum Overview

The first cohort follows a structured 12-week programme divided into two phases.

**Phase I — Build It** `weeks 01–06`

> Foundations of vector semantics, gradient flow, scaled dot-product attention, multi-head attention, gated feed-forward sublayers, and positional encodings. Output: a working autoregressive transformer trained on natural language.

**Phase II — Understand & Optimise It** `weeks 07–12`

> Rotary position embeddings, grouped-query attention, KV cache engineering, FlashAttention I/II, kernel compilation via `torch.compile` and FlexAttention, mixed-precision training, and formal evaluation methodology.

Full syllabus, weekly references, and code milestones: [`curriculum/README.md`](https://github.com/zdf-research/curriculum)

---

## § 5 &nbsp;&nbsp; Leaderboard

Validation cross-entropy on a fixed held-out split of WikiText-103, evaluated via `common/eval.py` under a shared BPE tokeniser. Updated after each weekly session.

> Current standings: [`LEADERBOARD.md`](https://github.com/zdf-research/curriculum/blob/main/LEADERBOARD.md)

---

## § 6 &nbsp;&nbsp; Compute Infrastructure

ZDF Research operates on dedicated compute clusters on Azure Machine Learning. Cluster access is governed by the principle that **scale is used when scale teaches something new** — not as a substitute for understanding.

Members may additionally maintain access to personal cloud GPU instances (Lambda Labs, Vast.ai) for exploratory work and rapid iteration outside group sessions.

---

## § 7 &nbsp;&nbsp; Membership & Contribution

ZDF Research is closed and invitation-based. Membership is extended to data scientists who demonstrate both rigour and a functional sense of irony about the state of enterprise data work.

---

## § 8 &nbsp;&nbsp; Research Lineage & Affiliation

ZDF Research draws its methodological tradition from the independent research model — small, focused, technically "uncompromising". We acknowledge with respect the intellectual lineage of:

`Vaswani et al., 2017` &nbsp;·&nbsp; `Ba et al., 2016` &nbsp;·&nbsp; `Su et al., 2021` &nbsp;·&nbsp; `Dao et al., 2022–2024`  
`Ainslie et al., 2023` &nbsp;·&nbsp; `Shazeer, 2020` &nbsp;·&nbsp; `Karpathy, 2022–2024`

And the broader open-source community without whom none of this would be reproducible.

---

## § 9 &nbsp;&nbsp; The Ψ Monogram

<div align="center">

```
         The Ψ operator acts on the space of engineering time.
         It maps: {corporate overhead} ——→ {tractable research problems}.

         Eigenvalue: approximately one well-understood transformer block per week.
```

*The mesh passes signal. It cancels noise. This has always been the design.*

</div>

---

<div align="center">

```
  ░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░▓▓░░
```

`ZDF RESEARCH` &nbsp;·&nbsp; `EST. 2026` &nbsp;·&nbsp; `UNCLASSIFIED`

*"Someone has to build the thing that makes the dashboards obsolete."*

</div>
