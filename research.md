---
layout: page
title: Research
---

<div class="row fade-in">
  <div class="col-12">
    <section id="abstract" class="mb-5">
      <p class="text-justify lead">
        My research develops a unified methodological framework for the <strong>exploration of complex systems</strong> through <strong>Frugal and Explainable AI (XAI)</strong>. By integrating surrogate modeling, active learning, and interpretability analysis, I aim to transform opaque "black-box" simulations into transparent recommendation tools for critical decision-making in engineering and socio-environmental contexts.
      </p>
      <p class="text-justify small text-secondary">
        My approach follows an iterative <strong>co-design</strong> philosophy, bridging the gap between descriptive simulation and prescriptive action. This work is applied to two main kontrast families: the multidisciplinary optimization of technical systems (e.g., green aircraft) and the assessment of agent-based models (ABM) for environmental risks, such as wildfires and climate change mitigation.
      </p>
    </section>

    <hr class="my-5">

    <!-- Core Research Contributions -->
    <section id="contributions" class="mb-5">
      <h2 class="h5 font-weight-bold mb-4 text-primary text-uppercase"><i class="fas fa-microscope mr-2"></i> Core Research Contributions</h2>
      
      <div class="contribution-item mb-5">
        <h3 class="h6 font-weight-bold text-dark mb-2">1. Unified Workflows for Automated Exploration</h3>
        <p class="small text-justify text-secondary">
          I propose a formal methodological framework that unifies <strong>physics-based modeling, adaptive sampling (DoE), and surrogate training</strong> into a single iterative loop. This workflow handles noise, convergence failures, and epistemic uncertainty quantification, enabling the large-scale exploration of complex systems in seconds rather than hours.
        </p>
      </div>

      <div class="contribution-item mb-5">
        <h3 class="h6 font-weight-bold text-dark mb-2">2. Heterogeneous and Hierarchical Design Spaces</h3>
        <p class="small text-justify text-secondary">
          A major contribution of my work is the <strong>native management of mixed-variable design spaces</strong> (continuous, integer, and categorical). I have formalized algebraic distances and hierarchical kernels that allow emulators to relate information between different architectures and operational modes, implemented in the <strong>SMT 2.0</strong> and <strong>SEGOMOE</strong> toolboxes.
        </p>
      </div>

      <div class="contribution-item mb-5">
        <h3 class="h6 font-weight-bold text-dark mb-2">3. Methodological Validation of XAI for Engineering</h3>
        <p class="small text-justify text-secondary">
          I introduced specific metrics (e.g., NDCG between explanations) to <strong>evaluate the reliability of XAI outputs</strong>. My research identifies where surrogate model artifacts might mislead decision-makers, providing a diagnostic layer that ensures physical insights (via Shapley values or Sobol indices) are consistent with the underlying complex system.
        </p>
      </div>
    </section>

    <!-- Strategic Projects -->
    <section id="projects" class="mb-5">
      <h2 class="h5 font-weight-bold mb-4 text-primary text-uppercase"><i class="fas fa-project-diagram mr-2"></i> Strategic Research Projects</h2>
      
      <div class="card border-0 bg-light shadow-sm mb-4">
        <div class="card-body">
          <h3 class="h6 font-weight-bold mb-1">ANR MIMICO (2025 - Present). Grant Number ANR-24-CE23-0380 </h3>
          <p class="small text-muted mb-0"><strong>Hybrid Modeling for Agent-Based Systems</strong>. Combining ABM with simplified surrogate representations to evaluate urban mobility policies and dense crowd dynamics.</p>
        </div>
      </div>

      <div class="card border-0 bg-light shadow-sm mb-4">
        <div class="card-body">
          <h3 class="h6 font-weight-bold mb-1">Aeronautical Decarbonation. EU Comission, Horizon 2020 COLOSSUS and AGILE 4.0 projects.  Grant Numbers 815122 and  101097120  </h3>
          <p class="small text-muted mb-0">Applying Bayesian optimization to eco-designed aircraft architectures. These works were recognized by two AIAA Best Paper awards for contributions to "green aviation."</p>
        </div>
      </div>
    </section>

    <!-- Academic Supervision -->
    <section id="supervision" class="mb-5">
      <h2 class="h5 font-weight-bold mb-4 text-primary text-uppercase"><i class="fas fa-users mr-2"></i> Academic Supervision</h2>
      
      <div class="pl-3 border-left border-primary">
        <h3 class="h6 font-weight-bold mb-3 small text-uppercase">Ph.D. Supervision</h3>
        <ul class="list-unstyled small mb-4">
          <li class="mb-2"><i class="fas fa-user-graduate text-muted mr-2"></i> <strong>Gaston Plat</strong> (2025 - Present), "Uncertainty quantification for ABMs in climate risk."</li>
        </ul>

        <h3 class="h6 font-weight-bold mb-3 small text-uppercase text-muted">Master's Alumni</h3>
        <div class="row small">
          <div class="col-md-6">
            <ul class="list-unstyled">
              <li class="mb-1"><i class="fas fa-check text-success mr-2"></i> Raul Carreira Rufato (M2, 2024)</li>
              <li class="mb-1"><i class="fas fa-check-circle text-success mr-2"></i> Robin Grapin (M2, 2024)</li>
            </ul>
          </div>
          <div class="col-md-6">
            <ul class="list-unstyled">
              <li class="mb-1"><i class="fas fa-check text-success mr-2"></i> Hugo Reimereinger (Master, 2024)</li>
              <li class="mb-1"><i class="fas fa-check-circle text-success mr-2"></i> Nicolas Gonel (M2, 2024)</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Global Research Network -->
    <section id="network" class="mb-5">
      <h2 class="h5 font-weight-bold mb-4 text-primary text-uppercase"><i class="fas fa-globe-americas mr-2"></i> Global Research Network</h2>
      <p class="small text-justify text-secondary mb-4">
        My research is built on strong international collaborations across <strong>Europe, North America, and Southeast Asia</strong>. This network bridges academic theory with industrial requirements in aerospace and socio-environmental policy.
      </p>
      <div class="card border-0 bg-light shadow-sm">
        <div class="card-body py-3 d-flex justify-content-between align-items-center">
          <span class="small font-weight-bold text-uppercase" style="letter-spacing: 1px;">Scientific Co-authorship Graph</span>
          <a href="{{ site.dblp_url }}" target="_blank" class="btn btn-sm btn-outline-primary shadow-sm">View on DBLP <i class="fas fa-share-alt ml-1"></i></a>
        </div>
      </div>
    </section>
  </div>
</div>
