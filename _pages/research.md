---
layout: page
title: Research
permalink: /research/
description: AI-driven design, multiphysics modeling, and digital engineering for advanced manufacturing.
nav: true
nav_order: 3
---

We pursue four tightly coupled research thrusts. Each one is useful on its own, but the lab's distinctive contribution lies at their intersection: design methods that are simultaneously **generative**, **physically grounded**, and **manufacturable**.

<div class="thrust-list mt-4">

  <div class="card thrust-card mb-4 shadow-sm">
    <div class="thrust-card-img d-flex align-items-end" style="height: 200px; background: linear-gradient(135deg, #1E3A8A 0%, #3B82F6 100%);">
      <div class="p-3 text-white">
        <small class="text-uppercase" style="letter-spacing: 0.08em; opacity: 0.85;">Thrust 1</small>
        <h3 class="mb-0" style="color: white;">Generative AI for Advanced Materials &amp; Component Design</h3>
      </div>
    </div>
    <div class="card-body">
      <p class="card-text mb-3">Generative models that propose feasible, manufacturable, performance-driven designs for parts and material microstructures.</p>
    </div>
    <div class="card-body border-top">
      <img src="{{ '/assets/img/GenAI_design.png' | relative_url }}" alt="Generative AI for Advanced Materials & Component Design" class="thrust-detail-img">
      <p><strong>Overview.</strong> We build generative models — diffusion, autoregressive, and graph-based — that learn from physics simulations and existing designs to propose new geometries, lattice topologies, and material distributions. Unlike pure shape generation, our outputs are conditioned on engineering targets (stiffness, weight, thermal margin, finite life, manufacturability) and on process constraints.</p>
      <p class="mb-2"><strong>Key topics.</strong></p>
      <ul class="mb-0">
        <li>Physics-guided generative models</li>
        <li>Inverse design under multi-objective performance targets</li>
        <li>Manufacturability-aware generation</li>
        <li>Learned design representations (implicit fields, graphs, voxels)</li>
      </ul>
      <p lang="ko" class="mt-3 mb-0">생성형 AI를 활용하여 고성능 소재 미세구조와 부품 형상을 설계하는 연구입니다. 제조 가능성, 성능 목표, 다양한 물리적 제약조건을 함께 고려하여 실제 제작 가능한 설계안을 탐색하고 제안하는 것을 목표로 합니다.</p>
    </div>
  </div>

  <div class="card thrust-card mb-4 shadow-sm">
    <div class="thrust-card-img d-flex align-items-end" style="height: 200px; background: linear-gradient(135deg, #1E3A8A 0%, #0891B2 100%);">
      <div class="p-3 text-white">
        <small class="text-uppercase" style="letter-spacing: 0.08em; opacity: 0.85;">Thrust 2</small>
        <h3 class="mb-0" style="color: white;">Multiphysics &amp; Multiscale Modeling</h3>
      </div>
    </div>
    <div class="card-body">
      <p class="card-text mb-3">Physics-based simulation (FEM, FVM) that bridges scales — from microstructure evolution and process physics to component-level mechanical and thermal performance.</p>
    </div>
    <div class="card-body border-top">
      <img src="{{ '/assets/img/PSP.gif' | relative_url }}" alt="Multiphysics & multiscale modeling — PSP linkages" class="thrust-detail-img">
      <p><strong>Overview.</strong> We develop and use multiphysics simulations — thermal, mechanical, microstructural — for materials and manufacturing processes, with an emphasis on metal additive manufacturing. We are especially interested in surrogate-model-friendly simulations, structured so that machine learning can absorb their behavior and reuse it during design.</p>
      <p class="mb-2"><strong>Key topics.</strong></p>
      <ul class="mb-0">
        <li>Process-Structure-Property (PSP) linkages</li>
        <li>Multiscale simulation linking microstructure to component performance</li>
        <li>Surrogate and reduced-order models for design-time use</li>
        <li>Uncertainty quantification across scales</li>
      </ul>
      <p lang="ko" class="mt-3 mb-0">소재의 물성 예측을 위해 다양한 물리 현상과 길이 스케일을 통합적으로 해석하는 연구입니다. FEM, FVM 등 물리 기반 시뮬레이션을 활용하여 공정 중 물리 현상, 미세구조 변화, 최종 소재 물성을 연결하고, 공정-구조-물성(Process-Structure-Property) 관계를 구축합니다.</p>
    </div>
  </div>

  <div class="card thrust-card mb-4 shadow-sm">
    <div class="thrust-card-img d-flex align-items-end" style="height: 200px; background: linear-gradient(135deg, #1E3A8A 0%, #10B981 100%);">
      <div class="p-3 text-white">
        <small class="text-uppercase" style="letter-spacing: 0.08em; opacity: 0.85;">Thrust 3</small>
        <h3 class="mb-0" style="color: white;">Sparse-to-Rich 2D/3D Material Characterization &amp; Reconstruction</h3>
      </div>
    </div>
    <div class="card-body">
      <p class="card-text mb-3">Data-efficient prediction of 3D microstructures, properties, and performance from limited 2D observations — expanding local surface data into representative 3D volumes.</p>
    </div>
    <div class="card-body border-top">
      <img src="{{ '/assets/img/2D3DMicro_rev.png' | relative_url }}" alt="Sparse-to-Rich 2D/3D material characterization & reconstruction" class="thrust-detail-img">
      <p><strong>Overview.</strong> This thrust aims to enable data-efficient prediction of 3D material structures, properties, and performance from limited 2D observations. By expanding local 2D surface information into representative 3D microstructures, this approach provides a pathway to infer internal structures that are difficult to directly observe. The reconstructed 3D data will be validated using paired 2D/3D datasets and integrated with uncertainty quantification and physics-guided analysis for robust materials prediction.</p>
      <p class="mb-2"><strong>Key topics.</strong></p>
      <ul class="mb-0">
        <li>2D-to-3D dimensionality expansion of material microstructures</li>
        <li>Surface-to-volume inference for internal 3D structure prediction</li>
        <li>Data-efficient 3D property and performance prediction from local 2D data</li>
        <li>Paired 2D/3D dataset construction for model training and validation</li>
        <li>Uncertainty quantification for reliable 2D-to-3D prediction</li>
        <li>Physics-guided validation of predicted 3D microstructures and behavior</li>
      </ul>
      <p lang="ko" class="mt-3 mb-0">제한된 2D 이미지와 국소 관측 데이터만으로 3D 소재 미세구조, 물성, 성능을 예측하는 데이터 효율적 모델링 연구입니다. 2D 표면 정보를 대표적인 3D 체적 구조로 확장하여 관찰하기 어려운 내부 구조와 3D 거동을 추론합니다.</p>
    </div>
  </div>

  <div class="card thrust-card mb-4 shadow-sm">
    <div class="thrust-card-img d-flex align-items-end" style="height: 200px; background: linear-gradient(135deg, #1E3A8A 0%, #7C3AED 100%);">
      <div class="p-3 text-white">
        <small class="text-uppercase" style="letter-spacing: 0.08em; opacity: 0.85;">Thrust 4</small>
        <h3 class="mb-0" style="color: white;">Digital Engineering for Advanced Manufacturing</h3>
      </div>
    </div>
    <div class="card-body">
      <p class="card-text mb-3">Digital twins, design automation, and end-to-end pipelines that connect CAD, simulation, and manufacturing data.</p>
    </div>
    <div class="card-body border-top">
      <img src="{{ '/assets/img/AgenticAI.png' | relative_url }}" alt="Digital engineering & agentic AI for advanced manufacturing" class="thrust-detail-img">
      <p><strong>Overview.</strong> We build agentic AI and digital infrastructure — digital twins, design automation pipelines, and process-aware data layers — that enables generative models, simulations, and manufacturing processes to interact within closed-loop engineering workflows. The aim is reusable engineering software, not one-off scripts: shared representations of geometry, process, material, and performance that can evolve across projects.</p>
      <p class="mb-2"><strong>Key topics.</strong></p>
      <ul class="mb-0">
        <li>Agentic AI for advanced manufacturing workflows</li>
        <li>Digital twins of additive and hybrid manufacturing processes</li>
        <li>Design automation pipelines linking CAD, simulation, and machine learning</li>
        <li>Process-aware data infrastructure for manufacturing</li>
        <li>Design–simulate–manufacture workflows</li>
        <li>AI-agent-assisted decision-making for materials, process, and part design</li>
      </ul>
      <p lang="ko" class="mt-3 mb-0">CAD, 시뮬레이션, 제조 데이터를 연결하는 디지털 엔지니어링 연구입니다. 디지털 트윈, 설계 자동화, end-to-end 데이터 파이프라인을 통해 첨단 제조 공정과 부품 설계의 효율성과 신뢰성을 높이는 것을 목표로 합니다.</p>
    </div>
  </div>

</div>
