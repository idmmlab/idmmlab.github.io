---
layout: page
title: Facilities
permalink: /facilities/
description: Computing resources for multiphysics simulation, large-scale dataset generation, and AI model training.
nav: true
nav_order: 4
---

<p lang="ko">연구실이 직접 운영하는 컴퓨팅 자원으로 다물리 시뮬레이션, 대규모 데이터셋 생성, 생성형 AI 및 대리모델 학습을 수행합니다.</p>

{% assign gpu_count = 0 %}
{% assign total_vram_gb = 0 %}
{% for gpu in site.data.compute_gpus %}
{% assign gpu_count = gpu_count | plus: gpu.count %}
{% assign model_vram_gb = gpu.count | times: gpu.memory_gb %}
{% assign total_vram_gb = total_vram_gb | plus: model_vram_gb %}
{% endfor %}

<div class="facility-stats mt-4 mb-4">
  <div class="facility-stat">
    <div class="facility-stat-value">{{ gpu_count }}</div>
    <div class="facility-stat-label">GPUs</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">{{ total_vram_gb }} GB</div>
    <div class="facility-stat-label">Total GPU memory</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">604</div>
    <div class="facility-stat-label">Server CPU cores</div>
  </div>
  <div class="facility-stat">
    <div class="facility-stat-value">3.5 TB</div>
    <div class="facility-stat-label">Server RAM</div>
  </div>
</div>

<div class="facility-list">

  <div class="card facility-card mb-4 shadow-sm">
    <div class="facility-card-img">
      <h2 class="mb-0" id="gpu-inventory">GPU Inventory</h2>
    </div>
    <div class="card-body">
      <table class="facility-table facility-gpu-table" aria-labelledby="gpu-inventory">
        <thead>
          <tr>
            <th scope="col">NVIDIA GPU model</th>
            <th scope="col">Count</th>
            <th scope="col">VRAM per GPU</th>
          </tr>
        </thead>
        <tbody>
          {% for gpu in site.data.compute_gpus %}
            <tr>
              <th scope="row">{{ gpu.model }}</th>
              <td>{{ gpu.count }}</td>
              <td>{{ gpu.memory_gb }} GB</td>
            </tr>
          {% endfor %}
        </tbody>
      </table>
    </div>
  </div>

  <div class="card facility-card mb-4 shadow-sm">
    <div class="facility-card-img">
      <h2 class="mb-0" id="cpu-cluster">CPU Cluster &amp; Storage</h2>
    </div>
    <div class="card-body">
      <p class="card-text mb-0">The HPC cluster uses a job scheduler for parallel FEM and FVM simulations and dataset generation.</p>
    </div>
    <div class="card-body border-top">
      <table class="facility-table" aria-labelledby="cpu-cluster">
        <tbody>
          <tr>
            <th scope="row">Cluster controller</th>
            <td>2 &times; Xeon Silver 4210R (10 cores each) &middot; 64 GB RAM</td>
          </tr>
          <tr>
            <th scope="row">CPU compute nodes</th>
            <td>Dual Xeon Gold 6226R or 6326 (16 cores per CPU) &middot; 192 GB DDR4 ECC RAM and 1 TB NVMe per node</td>
          </tr>
          <tr>
            <th scope="row">Storage</th>
            <td>128 TB SATA on the CPU cluster (RAID 5) &middot; 64 TB SATA on a GPU server</td>
          </tr>
          <tr>
            <th scope="row">Interconnect</th>
            <td>10 Gbps switched Ethernet</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

</div>
