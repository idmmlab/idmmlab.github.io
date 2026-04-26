---
layout: page
permalink: /team/
title: Team
description: Members of the IDMM Lab (지능형 소재 및 제조 설계 연구실).
nav: true
nav_order: 2
---

<ul class="nav nav-tabs team-tabs" id="teamTab" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link active" id="advisor-tab" data-toggle="tab" href="#advisor" role="tab" aria-controls="advisor" aria-selected="true">Advisor</a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="students-tab" data-toggle="tab" href="#students" role="tab" aria-controls="students" aria-selected="false">Students</a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" id="alumni-tab" data-toggle="tab" href="#alumni" role="tab" aria-controls="alumni" aria-selected="false">Alumni</a>
  </li>
</ul>

<div class="tab-content" id="teamTabContent">

  <div class="tab-pane fade show active" id="advisor" role="tabpanel" aria-labelledby="advisor-tab">
    <div class="row mt-3">
      <div class="col-sm-3">
        {%
          include figure.liquid
          loading="eager"
          path="assets/img/members/PI_Kanghyun.png"
          class="img-fluid rounded"
          alt="Kang-Hyun Lee"
          cache_bust=true
        %}
      </div>
      <div class="col-sm-9">
        <h3 style="margin-top: 0;">Kang-Hyun Lee, Ph.D.</h3>
        <p>Assistant Professor, School of Mechanical Engineering, Soongsil University</p>
        <p>
          📧 <a href="mailto:kanghyun.lee@ssu.ac.kr">kanghyun.lee@ssu.ac.kr</a>
          &nbsp;·&nbsp;
          <a href="https://www.linkedin.com/in/kang-hyun-lee-125b17206/" target="_blank" rel="noopener" title="LinkedIn"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
        </p>
        <p>
          Kang-Hyun Lee is an Assistant Professor in the School of Mechanical
          Engineering at Soongsil University. Prior to joining Soongsil University,
          he worked as a Postdoctoral Associate in the
          <a href="https://decode.mit.edu/" target="_blank" rel="noopener">DeCoDE Lab</a>
          in the Department of Mechanical Engineering at the Massachusetts
          Institute of Technology, where he contributed to a DARPA-funded research
          project on developing generative artificial intelligence for the design
          and manufacturing of reusable rocket components. He received his Ph.D. and
          M.S. from the Department of Aerospace Engineering at Seoul National
          University, with a research focus on multiphysics and multiscale
          simulation of additive manufacturing processes. His current research lies
          at the intersection of generative design and advanced manufacturing,
          aiming to unlock the full potential of manufacturing processes and expand
          the design space for next-generation engineered systems.
        </p>
      </div>
    </div>

    <h4 id="invited-talks">Invited Talks</h4>

    <ol>
      <li><strong>Invited Presentation</strong>, Materials Research Society (MRS) Fall Meeting, 2025. <em>Multiobjective Inverse Design of Compositionally Graded Blisks for Reusable Turbomachinery Using Physics-Guided Diffusion Models.</em></li>
      <li><strong>Invited Seminar</strong>, U.S. Air Force Research Laboratory (AFRL), Materials and Manufacturing Directorate (RX Division), 2025. <em>Exploring Microstructure Design Spaces with Denoising Diffusion Models.</em></li>
      <li><strong>Invited Talk</strong> (Early Career Researcher), Korean Society for Aeronautical and Space Sciences (KSAS) Workshop, 2025. <em>Multiphysics Modeling for PSP Linkages in Metal Additive Manufacturing.</em></li>
      <li><strong>Invited Talk</strong>, Korea Institute of Machinery and Materials (KIMM), Department of 3D Printing, 2024. <em>Multiscale and Multiphysics Simulation of Metal Additive Manufacturing Process.</em></li>
    </ol>

    <h4 id="reviewer-academic-journals">Reviewer for Academic Journals</h4>

    <ul>
      <li>Additive Manufacturing (Elsevier)</li>
      <li>Computer Methods in Applied Mechanics and Engineering (Elsevier)</li>
      <li>Computer-Aided Design (Elsevier)</li>
      <li>Optics &amp; Laser Technology (Elsevier)</li>
      <li>International Journal of Aeronautical and Space Sciences (Springer)</li>
      <li>Advanced Engineering Informatics (Elsevier)</li>
      <li>Journal of Building Engineering (Elsevier)</li>
      <li>Expert Systems with Applications (Elsevier)</li>
    </ul>
  </div>

  <div class="tab-pane fade" id="students" role="tabpanel" aria-labelledby="students-tab">
    <h3 class="mt-3">Graduate Students</h3>
    <p>We are recruiting M.S. and Ph.D. students. See <a href="{{ '/join/' | relative_url }}">Join Us</a> for what to send.</p>

    <h3>Undergraduate Researchers</h3>
    <p>Open positions. Motivated undergraduates are welcome to contact Prof. Lee — see <a href="{{ '/join/' | relative_url }}">Join Us</a>.</p>
  </div>

  <div class="tab-pane fade" id="alumni" role="tabpanel" aria-labelledby="alumni-tab">
    <p class="mt-3">This section will be updated as members graduate.</p>
  </div>

</div>
