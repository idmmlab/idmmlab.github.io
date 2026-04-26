# LAB_CONTENT.md

Master content document for the **IDMM Lab** (Intelligent Design for Materials & Manufacturing Lab) website. This file is the single source of truth for lab identity, messaging, menu structure, research thrusts, and the English/Korean copy that appears on each page. All pages under `_pages/` should pull their wording from here. Update this file first, then propagate to the site.

---

## 1. Lab Identity

- **Full name (EN):** Intelligent Design for Materials & Manufacturing Lab
- **Full name (KO):** 지능형 재료·제조 설계 연구실
- **Short name / acronym:** IDMM Lab
- **Affiliation:** School of Mechanical Engineering, Soongsil University (숭실대학교 기계공학과)
- **Principal Investigator:** Kang-Hyun Lee, Assistant Professor
- **Tagline (EN):** AI-driven design and digital engineering for materials, parts, and advanced manufacturing systems.
- **Tagline (KO):** 인공지능 기반 설계와 디지털 엔지니어링으로 재료·부품·첨단 제조 시스템을 혁신합니다.

## 2. Mission

**EN.** We develop computational methods that connect *generative AI*, *multiphysics modeling*, and *digital engineering* to design materials, parts, and manufacturing processes that are difficult — or impossible — to design by hand. Our goal is to shorten the loop between scientific understanding and engineered hardware, especially for advanced manufacturing systems where geometry, process, and material behavior are tightly coupled.

**KO.** 본 연구실은 생성형 AI, 멀티피직스 모델링, 디지털 엔지니어링을 결합하여 사람의 직관만으로는 설계가 어려운 재료·부품·제조 공정을 자동화·최적화하는 계산 방법론을 개발합니다. 형상, 공정, 재료 거동이 강하게 결합된 첨단 제조 시스템에서 과학적 이해와 실제 하드웨어 사이의 사이클을 단축하는 것을 목표로 합니다.

## 3. Vision

We aim to make **design itself** a computational object — something that can be parameterized, sampled, simulated, and optimized like any other engineering quantity. By building this foundation for advanced manufacturing, we aspire to contribute tools and methods that the next generation of mechanical, aerospace, and materials engineers will use as everyday infrastructure.

## 4. About the Lab

The Intelligent Design for Materials & Manufacturing (IDMM) Lab at Soongsil University focuses on **AI-driven design and digital engineering** for materials, parts, and advanced manufacturing systems. We combine three complementary capabilities — generative modeling, physics-based simulation, and digital-twin/automation infrastructure — to accelerate how engineers design, simulate, and manufacture complex hardware.

Our work spans the full design loop: representing geometry and material in machine-learnable form, predicting performance via multiphysics simulation, and closing the loop with generative models that propose new designs satisfying multiple constraints. Application domains include metal additive manufacturing (AM), structural lattices and metamaterials, lightweight aerospace components, and digital twins of manufacturing processes.

We work closely with researchers in mechanical engineering, aerospace engineering, materials science, and applied machine learning, and we welcome students who enjoy living at the boundary between physics, computation, and hardware.

## 5. Research Thrusts (3 cards — English, used on Home & Research)

### Thrust 1 — Generative AI for Design

Generative models that propose feasible, manufacturable, performance-driven designs for parts and material microstructures. We focus on representations (implicit / mesh / graph), conditional generation under physical constraints, and inverse design where the target is a performance specification rather than a shape.

### Thrust 2 — Multiphysics & Multiscale Modeling

Physics-based simulation that bridges scales — from microstructure evolution and process physics, up to component-level mechanical and thermal performance. Our emphasis is on simulations that are *fast enough to learn from* and *accurate enough to trust*, so they can be coupled with data-driven design.

### Thrust 3 — Digital Engineering for Advanced Manufacturing

Digital twins, design automation, and end-to-end pipelines that connect CAD/representation, simulation, and manufacturing data. The goal is to turn ad-hoc engineering workflows into reusable, queryable, and improvable digital infrastructure — particularly for metal AM and other advanced manufacturing processes.

## 6. Research Page Structure

Use this structure for `_pages/research.md`. Section 8 below provides the bottom Featured Topics block.

### Intro

We pursue three tightly coupled research thrusts. Each one is useful on its own, but the lab's distinctive contribution lies at their intersection: design methods that are simultaneously *generative*, *physically grounded*, and *manufacturable*.

### Thrust 1 — Generative AI for Design

**Overview.** We build generative models — diffusion, autoregressive, and graph-based — that learn from physics simulations and existing designs to propose new geometries, lattice topologies, and material distributions. Unlike pure shape generation, our outputs are conditioned on engineering targets (stiffness, weight, manufacturability) and on process constraints.

**Key topics.**

- Conditional generative models for parts and lattices
- Inverse design under multi-objective performance targets
- Manufacturability-aware generation (build orientation, overhangs, support, residual stress)
- Learned design representations (implicit fields, graphs, voxels)

**Representative projects.** *(Coming soon — placeholder for ongoing work.)*

### Thrust 2 — Multiphysics & Multiscale Modeling

**Overview.** We develop and use multiphysics simulations — thermal, mechanical, microstructural — for materials and manufacturing processes, with an emphasis on metal additive manufacturing. We are especially interested in surrogate-model-friendly simulations: ones structured so that machine learning can absorb their behavior and reuse it during design.

**Key topics.**

- Process–structure–property modeling for metal AM
- Multiscale simulation linking microstructure to component performance
- Surrogate and reduced-order models for design-time use
- Uncertainty quantification across scales

**Representative projects.** *(Coming soon — placeholder for ongoing work.)*

### Thrust 3 — Digital Engineering for Advanced Manufacturing

**Overview.** We build digital infrastructure — digital twins, automation pipelines, and data layers — that lets generative models and simulations talk to real manufacturing processes. The aim is reusable engineering software, not one-off scripts: shared representations of geometry, process, and material that survive across projects.

**Key topics.**

- Digital twins of additive and hybrid manufacturing processes
- Design automation pipelines (CAD ↔ simulation ↔ ML)
- Process-aware data infrastructure for AM
- Closed-loop design–simulate–manufacture workflows

**Representative projects.** *(Coming soon — placeholder for ongoing work.)*

## 7. Keywords / Tags

Used for hero badges, meta tags, and categorization.

- Generative AI
- Multiphysics Modeling
- Digital Twins
- Design Automation
- Advanced Manufacturing

Secondary: metal additive manufacturing, inverse design, surrogate modeling, lattices and metamaterials, design representation, scientific machine learning.

## 8. Featured Research Topics (bottom block on Research page)

A short list of concrete topics the lab is actively interested in. These are intentionally narrower than the thrusts and meant to give prospective students a tangible sense of what they could work on.

- **Generative design of lightweight aerospace components** — diffusion / flow-based models conditioned on stiffness, weight, and AM process constraints.
- **Process–structure–property surrogates for metal AM** — fast, differentiable surrogates trained from multiphysics simulations, usable inside design loops.
- **Inverse design of mechanical metamaterials** — learning lattice/microstructure families with target macroscopic responses.
- **Digital twins for additive manufacturing** — process-aware representations linking sensor data, simulation, and as-built geometry.
- **Manufacturability-aware generative models** — generative pipelines that produce designs with built-orientation, support, and residual-stress considerations baked in.
- **Scientific ML for multiphysics** — operator learning and physics-informed approaches for thermal/mechanical fields in manufacturing.

## 9. Menu Structure

### Current version (6 items)

`HOME · TEAM · RESEARCH · PUBLICATIONS · NEWS · JOIN US`

| order | Label | Page file | permalink |
|-------|-------|-----------|-----------|
| 1 | Home | `_pages/about.md` | `/` |
| 2 | Team | `_pages/people.md` | `/team/` |
| 3 | Research | `_pages/research.md` | `/research/` |
| 4 | Publications | `_pages/publications.md` | `/publications/` |
| 5 | News | `_pages/news.md` | `/news/` |
| 6 | Join Us | `_pages/joinus.md` | `/join/` |

The lab's mailing address and contact email live at the **bottom of the Join Us page**, so prospective students see application instructions and where to send materials in one place. There is no separate `Contact` tab.

Pages hidden from the navbar (`nav: false`): `blog.md`, `cv.md`, `teaching.md`, `dropdown.md`, `projects.md`, `repositories.md`, `books.md`. The al-folio template files `profiles.md` and `about_einstein.md` are deleted (replaced by this fork's `people.md` / Team page).

### Expanded version (later, when needed)

`HOME · TEAM · RESEARCH · PUBLICATIONS · NEWS · TEACHING · GALLERY · JOIN US`

Add `TEACHING` once the PI is teaching regular courses. Add `GALLERY` once there is enough visual content (lab photos, simulation snapshots, hardware). If the contact/recruiting messaging grows long enough that Join Us no longer fits one page, split off a dedicated `CONTACT` tab.

## 10. Join Us

**EN.** We are actively recruiting motivated graduate students (M.S. and Ph.D.) and undergraduate researchers interested in AI-driven design, multiphysics simulation, and advanced manufacturing. You do **not** need to have done all three; we expect students to grow into the intersection. A strong background in *one* of (a) machine learning / scientific computing, (b) mechanics or materials, or (c) manufacturing / CAD / simulation is a good starting point.

**What we look for.** Curiosity about the physics behind manufacturing, willingness to write real code, and the patience to debug simulations and models that do not work the first time. Prior research experience is helpful but not required.

**What to send.**

1. A short CV (one or two pages is fine).
2. A short paragraph (a few sentences is enough) describing what you would like to work on and why.
3. *(Optional)* Links or PDFs of any prior project, paper, or code you would like us to look at.

Send the above to the lab email listed at the bottom of the Join Us page.

**KO.** 본 연구실은 인공지능 기반 설계, 멀티피직스 시뮬레이션, 첨단 제조에 관심 있는 **석·박사 대학원생**과 **학부 연구생**을 모집하고 있습니다. 세 분야 모두에 능숙할 필요는 없습니다 — (a) 머신러닝/과학적 계산, (b) 역학/재료, (c) 제조/CAD/시뮬레이션 중 **한 분야**에 단단한 기초가 있다면 충분히 합류할 수 있습니다.

**우리가 보는 것.** 제조 뒤에 있는 물리에 대한 호기심, 실제로 코드를 쓰는 데 익숙해지려는 의지, 그리고 처음에 잘 안 되는 시뮬레이션·모델을 끝까지 디버깅할 수 있는 끈기입니다. 연구 경험은 도움이 되지만 필수는 아닙니다.

**보내주실 자료.**

1. 짧은 CV (1~2 페이지면 충분합니다).
2. 어떤 주제를 왜 하고 싶은지 짧은 단락 (몇 문장이면 충분합니다).
3. *(선택)* 보여주고 싶은 이전 프로젝트, 논문, 또는 코드 링크/PDF.

위 자료를 Join Us 페이지 하단에 안내된 연구실 이메일로 보내주시면 됩니다.

## 11. PI Bio (used on People page)

**Kang-Hyun Lee**, Ph.D.
Assistant Professor, School of Mechanical Engineering, Soongsil University

Prior to joining Soongsil University, Dr. Lee was a Postdoctoral Associate in the Department of Mechanical Engineering at MIT, where he worked on a DARPA project applying generative AI to the design and manufacturing of reusable rocket components. He received his Ph.D. and M.S. in Aerospace Engineering from Seoul National University, with a dissertation on multiphysics and multiscale simulation of metal additive manufacturing. His current research interests are generative design, multiphysics simulation, and digital engineering for advanced manufacturing.

## 12. 최종 추천 메인 페이지 문안 (Home)

### English (primary)

> **Intelligent Design for Materials & Manufacturing Lab**
> *AI-driven design and digital engineering for materials, parts, and advanced manufacturing systems.*
>
> The IDMM Lab at Soongsil University builds computational methods that connect generative AI, multiphysics modeling, and digital engineering. We design materials, parts, and manufacturing processes that are difficult to design by hand — and we build the digital infrastructure that makes those methods reusable across problems.
>
> Our work cuts across three thrusts — *Generative AI for Design*, *Multiphysics & Multiscale Modeling*, and *Digital Engineering for Advanced Manufacturing* — with an application focus on metal additive manufacturing, lightweight structural components, and mechanical metamaterials.
>
> We are a new lab and we are recruiting. If you are a student interested in working at the intersection of AI, physics, and manufacturing, please see the **Join Us** page.

### Korean (short subtitle / footer)

> 숭실대학교 기계공학과 IDMM 연구실은 생성형 AI, 멀티피직스 모델링, 디지털 엔지니어링을 결합하여 재료·부품·첨단 제조 시스템을 설계하는 계산 방법론을 연구합니다. 새로 시작하는 연구실로, 함께할 학생을 모집하고 있습니다.

---

*Last updated: 2026-04-26.*
