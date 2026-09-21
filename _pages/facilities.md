---
layout: page
title: Facilities
permalink: /facilities/
description: In-house HPC clusters, GPU servers, and workstations supporting the lab's simulation and generative AI research.
nav: true
nav_order: 4
---

Our computational work — multiphysics simulation, large-scale surrogate training, and generative model development — runs on hardware the lab owns and operates directly. This gives us long-running simulation campaigns and multi-GPU training without queueing on shared national resources.

<p lang="ko">다물리 시뮬레이션, 대규모 대리모델 학습, 생성형 모델 개발을 연구실이 직접 보유·운영하는 계산 자원에서 수행합니다. 외부 공용 자원의 대기 없이 장시간 시뮬레이션과 다중 GPU 학습을 진행할 수 있습니다.</p>

<div class="facility-stats mt-4 mb-5">
  <div class="facility-stat">
    <div class="facility-stat-value">16</div>
    <div class="facility-stat-label">GPU accelerators</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">604</div>
    <div class="facility-stat-label">CPU cores</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">3.5 TB</div>
    <div class="facility-stat-label">System memory</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">530 GB</div>
    <div class="facility-stat-label">Total GPU memory</div>
  </div>
</div>

<div class="facility-list">

  <div class="card facility-card mb-4 shadow-sm">
    <div class="facility-card-img">
      <h3 class="mb-0">GPU Compute</h3>
    </div>
    <div class="card-body">
      <p class="card-text mb-2">Multi-GPU nodes for training diffusion and surrogate models, and for GPU-accelerated solvers.</p>
      <p lang="ko" class="card-text mb-0">확산 모델·대리모델 학습과 GPU 가속 solver 구동을 위한 다중 GPU 노드입니다.</p>
    </div>
    <div class="card-body border-top">
      <table class="facility-table">
        <tbody>
          <tr>
            <th>GPU node (4U)</th>
            <td>5 &times; NVIDIA RTX 3090 (24 GB GDDR6X) &middot; 2 &times; Xeon Gold 6226R &middot; 192 GB &middot; 10 GbE dual port</td>
          </tr>
          <tr>
            <th>GPU system (5U)</th>
            <td>2 &times; NVIDIA RTX 3090 (24 GB) &middot; 2 &times; Xeon Gold 6226R &middot; 192 GB &middot; 64 TB SATA storage</td>
          </tr>
          <tr>
            <th>GPU server</th>
            <td>NVIDIA RTX 6000 Ada + RTX 4500 Ada &middot; 2 &times; Xeon 6426Y &middot; 256 GB DDR5 &middot; Ubuntu / CUDA / cuDNN</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="card facility-card mb-4 shadow-sm">
    <div class="facility-card-img">
      <h3 class="mb-0">CPU Cluster</h3>
    </div>
    <div class="card-body">
      <p class="card-text mb-2">Rack-mounted HPC cluster under a master node and job scheduler, used for parallel FEM/FVM campaigns and dataset generation.</p>
      <p lang="ko" class="card-text mb-0">마스터 노드와 작업 스케줄러로 관리되는 랙 마운트 HPC 클러스터입니다. 병렬 FEM/FVM 해석과 학습 데이터셋 생성에 사용됩니다.</p>
    </div>
    <div class="card-body border-top">
      <table class="facility-table">
        <tbody>
          <tr>
            <th>Master node (2U)</th>
            <td>2 &times; Xeon Silver 4210R (10C/20T) &middot; 64 GB &middot; 128 TB enterprise SATA (RAID 5)</td>
          </tr>
          <tr>
            <th>Compute nodes (1U)</th>
            <td>2 &times; Xeon Gold 6226R (16C/32T) &middot; 192 GB DDR4 ECC &middot; 1 TB NVMe &middot; per node</td>
          </tr>
          <tr>
            <th>Compute nodes (1U)</th>
            <td>2 &times; Xeon Gold 6326 (16C/32T) &middot; 192 GB DDR4 ECC &middot; 1 TB NVMe &middot; per node</td>
          </tr>
          <tr>
            <th>Interconnect</th>
            <td>10 Gbps L2 switched fabric &middot; 37U rack &middot; rack-mount UPS</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="card facility-card mb-4 shadow-sm">
    <div class="facility-card-img">
      <h3 class="mb-0">Workstations</h3>
    </div>
    <div class="card-body">
      <p class="card-text mb-2">High-performance desktop workstations for interactive model development, CAD/CAE pre- and post-processing, and fast iteration.</p>
      <p lang="ko" class="card-text mb-0">대화형 모델 개발, CAD/CAE 전·후처리, 빠른 반복 실험을 위한 고성능 워크스테이션입니다.</p>
    </div>
    <div class="card-body border-top">
      <table class="facility-table">
        <tbody>
          <tr>
            <th>Workstation A</th>
            <td>2 &times; NVIDIA RTX 5090 (32 GB GDDR7)</td>
          </tr>
          <tr>
            <th>Workstation B</th>
            <td>2 &times; NVIDIA RTX PRO 6000 Blackwell (96 GB GDDR7)</td>
          </tr>
          <tr>
            <th>Legacy workstations</th>
            <td>2 &times; Supermicro dual-socket &middot; 2 &times; Xeon Gold 6240 (18C) &middot; 192 GB &middot; RTX 2080 Ti</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

</div>
