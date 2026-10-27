---
layout: page
permalink: /team/
title: Team
description: Members of the IDMM Lab (지능형 소재 및 제조 설계 연구실).
nav: true
nav_order: 2
---

<section class="team-section" id="advisor">
  <h2 class="team-section-title">Advisor</h2>
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
      <p style="margin-bottom: 0.25rem;">
        Assistant Professor, School of Mechanical Engineering, Soongsil University
      </p>
      <p class="pi-secondary-affiliation">
        Research Affiliate, Massachusetts Institute of Technology (MIT)
      </p>
      <p>
        📧 <a href="mailto:kanghl@ssu.ac.kr">kanghl@ssu.ac.kr</a>
        &nbsp;·&nbsp;
        <a href="https://www.linkedin.com/in/kang-hyun-lee-125b17206/" target="_blank" rel="noopener" title="LinkedIn"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
      </p>
      <p>
        Kang-Hyun Lee is an Assistant Professor in the School of Mechanical
        Engineering at Soongsil University. Prior to joining Soongsil University,
        he worked as a Postdoctoral Associate in the
        <a href="https://decode.mit.edu/" target="_blank" rel="noopener">DeCoDE Lab</a>
        in the Department of Mechanical Engineering at the Massachusetts
        Institute of Technology (MIT), where he contributed to a DARPA-funded research
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
    <li>Applied Energy (Elsevier)</li>
    <li>Journal of Computational Design and Engineering (Oxford Academic)</li>
  </ul>
</section>

<section class="team-section" id="students">
  <h2 class="team-section-title">Students</h2>
  <div class="member-grid mt-4">
    <div class="member-card">
      <div class="member-photo">
        {%
          include figure.liquid
          loading="lazy"
          path="assets/img/members/kim_seongjun.jpg"
          sizes="168px"
          alt="Kim Seong-Jun"
          cache_bust=true
        %}
      </div>
      <div class="member-body">
        <h3 class="member-name">김성준</h3>
        <div class="member-name-en">Kim Seong-Jun</div>
        <p class="member-focus">Generative AI for design optimization</p>
        <button type="button" class="member-publications-toggle" data-toggle="collapse" data-target="#publications-kim-seongjun" aria-expanded="false" aria-controls="publications-kim-seongjun" aria-label="김성준 Publications">Publications</button>
        <div class="collapse member-publications" id="publications-kim-seongjun">
        </div>
      </div>
    </div>
    <div class="member-card">
      <div class="member-photo">
        {%
          include figure.liquid
          loading="lazy"
          path="assets/img/members/lee_kyeongkwan.jpg"
          sizes="168px"
          alt="Lee Kyeong-Kwan"
          cache_bust=true
        %}
      </div>
      <div class="member-body">
        <h3 class="member-name">이경관</h3>
        <div class="member-name-en">Lee Kyeong-Kwan</div>
        <p class="member-focus">Predictive AI for materials design</p>
        <button type="button" class="member-publications-toggle" data-toggle="collapse" data-target="#publications-lee-kyeongkwan" aria-expanded="false" aria-controls="publications-lee-kyeongkwan" aria-label="이경관 Publications">Publications</button>
        <div class="collapse member-publications" id="publications-lee-kyeongkwan">
        </div>
      </div>
    </div>
    <div class="member-card">
      <div class="member-photo">
        {%
          include figure.liquid
          loading="lazy"
          path="assets/img/members/kim_taeho.jpg"
          sizes="168px"
          alt="Kim Tae-Ho"
          cache_bust=true
        %}
      </div>
      <div class="member-body">
        <h3 class="member-name">김태호</h3>
        <div class="member-name-en">Kim Tae-Ho</div>
        <p class="member-focus">Physics-guided AI for additive manufacturing</p>
        <button type="button" class="member-publications-toggle" data-toggle="collapse" data-target="#publications-kim-taeho" aria-expanded="false" aria-controls="publications-kim-taeho" aria-label="김태호 Publications">Publications</button>
        <div class="collapse member-publications" id="publications-kim-taeho">
        </div>
      </div>
    </div>
    <div class="member-card">
      <div class="member-photo student-photo-placeholder" aria-hidden="true">
        <svg viewBox="0 0 100 100" fill="currentColor" focusable="false">
          <circle cx="50" cy="32" r="18" />
          <path d="M18 92V82a32 32 0 0 1 64 0v10z" />
        </svg>
      </div>
      <div class="member-body">
        <h3 class="member-name">이우승</h3>
        <p class="member-focus">Generative AI and differentiable modeling</p>
        <button type="button" class="member-publications-toggle" data-toggle="collapse" data-target="#publications-lee-wooseung" aria-expanded="false" aria-controls="publications-lee-wooseung" aria-label="이우승 Publications">Publications</button>
        <div class="collapse member-publications" id="publications-lee-wooseung">
        </div>
      </div>
    </div>
  </div>
</section>

<section class="team-section" id="alumni">
  <h2 class="team-section-title">Alumni</h2>
  <p>This section will be updated as members graduate.</p>
</section>
