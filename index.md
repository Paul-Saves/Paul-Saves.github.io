---
layout: default
title: Biography
---

<div class="row fade-in">
  <div class="col-12">
    <section id="biography" class="mb-5">
      <h1 class="h3 font-weight-bold border-bottom pb-2 mb-4 text-uppercase" style="letter-spacing: 1px;">Professional Biography</h1>
      <p class="text-justify">
        <strong>Paul Saves</strong> is a Contractual Researcher in Computer Science (CNU Section 27) at the <strong>Institute of Research in Computer Science of Toulouse (IRIT/CNRS)</strong>. He holds a Ph.D. in Mathematics and Applications from ONERA and ISAE-SUPAERO, where his doctoral research on high-dimensional multidisciplinary design optimization for aircraft eco-design was recognized with the <strong>2025 Best PhD in Open Science Award</strong> from the French Ministry of Research.
      </p>
      <p class="text-justify">
        His research focuses on the development of <strong>frugal AI</strong> through lightweight surrogate models (e.g., Gaussian processes, random forests) to approximate complex simulations and quantify uncertainty. Dr. Saves' work bridges the gap between <strong>Explainable AI (XAI)</strong> and <strong>Bayesian Optimization</strong>, with applications transitioning from ecological aeronautics to agent-based socio-environmental systems. He is a lead developer of the <strong>Surrogate Modeling Toolbox (SMT 2.0)</strong> and the <strong>SEGOMOE</strong> framework, emphasizing open-source diffusion for global academic and policy-making impact.
      </p>
    </section>

    <div class="row mt-5">
      <div class="col-md-8">
        <!-- Professional Milestones -->
        <h2 class="h5 font-weight-bold mb-4 text-uppercase text-primary" style="letter-spacing: 1px;"><i class="fas fa-stream mr-2"></i> Professional Milestones</h2>
        <div class="news-timeline mb-5">
          <div class="news-item pl-4 mb-3 border-left border-primary" style="position: relative;">
            <div class="news-dot bg-primary" style="position: absolute; left: -5px; top: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
            <span class="text-muted small font-weight-bold">2025</span> 
            <p class="small mb-0">Recipient of the <strong>Prix du Ministère de la Recherche</strong> – Best PhD in Open Science.</p>
          </div>
          <div class="news-item pl-4 mb-3 border-left" style="position: relative;">
            <div class="news-dot bg-light border" style="position: absolute; left: -5px; top: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
            <span class="text-muted small font-weight-bold">2025</span> 
            <p class="small mb-0">Appointed Machine Learning Researcher for <strong>ANR MIMICO</strong> at IRIT.</p>
          </div>
          <div class="news-item pl-4 mb-3 border-left" style="position: relative;">
            <div class="news-dot bg-light border" style="position: absolute; left: -5px; top: 10px; width: 10px; height: 10px; border-radius: 50%;"></div>
            <span class="text-muted small font-weight-bold">2024</span> 
            <p class="small mb-0">Awarded <strong>ISAE-SUPAERO Foundation</strong> Best PhD Thesis Prize.</p>
          </div>
        </div>

        <h2 class="h5 font-weight-bold mb-4 text-uppercase text-primary" style="letter-spacing: 1px;"><i class="fas fa-certificate mr-2"></i> Key Recognitions</h2>
        <ul class="list-unstyled small mb-5">
          <li class="mb-3 d-flex align-items-start">
            <i class="fas fa-award text-warning mr-3 mt-1"></i>
            <div><strong>World Best Paper Award</strong>, AIAA SciTech (2022) – Mixed-variable optimization for aircraft design.</div>
          </li>
          <li class="mb-3 d-flex align-items-start">
            <i class="fas fa-award text-warning mr-3 mt-1"></i>
            <div><strong>Best Student Paper Award</strong>, AIAA Aviation (2024) – System architecture optimization.</div>
          </li>
        </ul>
      </div>

      <div class="col-md-4">
        <!-- Formal Sidebar Data -->
        <div class="card border-0 shadow-sm bg-light mb-4">
          <div class="card-body py-3">
            <h2 class="h6 font-weight-bold text-uppercase mb-3">Research Areas</h2>
            <ul class="list-unstyled small mb-0">
              {% for interest in site.interests %}
              <li class="mb-2"><i class="fas fa-minus text-primary mr-2 small"></i> {{ interest }}</li>
              {% endfor %}
            </ul>
          </div>
        </div>

        <div class="p-2">
          <h2 class="h6 font-weight-bold text-uppercase mb-3">Languages</h2>
          <table class="table table-borderless table-sm small mb-0">
            <tr><td class="pl-0 py-1 font-weight-bold">French</td><td class="py-1 text-right">Native</td></tr>
            <tr><td class="pl-0 py-1 font-weight-bold">English</td><td class="py-1 text-right">C1 (955)</td></tr>
            <tr><td class="pl-0 py-1 font-weight-bold">Spanish</td><td class="py-1 text-right">B2</td></tr>
            <tr><td class="pl-0 py-1 font-weight-bold">Russian</td><td class="py-1 text-right">A1</td></tr>
          </table>
        </div>
      </div>
    </div>
  </div>
</div>
