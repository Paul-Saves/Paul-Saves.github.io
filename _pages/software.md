---
permalink: /software/
layout: page
title: Scientific Software
---

<div class="row fade-in">
  <div class="col-12">
    <p class="text-justify mb-5">
      I develop and maintain open-source software tools for surrogate modeling, Bayesian optimization, and explainable machine learning. Developing robust, reproducible software is a core component of my scientific identity. All algorithms and numerical experiments discussed in my publications are implemented across these frameworks, ensuring transparency and reproducibility.
    </p>

    <!-- SMT 2.0 -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #28a745 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              SMT 2.0: Surrogate Modeling Toolbox
            </h2>
            <div class="mb-3">
              <span class="badge badge-success mr-2"><i class="fas fa-lock-open mr-1"></i> Open Source (BSD-3)</span>
              <span class="badge badge-warning text-dark shadow-sm"><i class="fas fa-trophy mr-1"></i> French Open Science Award 2026</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Lead Developer & Maintainer</span>
          </div>
        </div>

        <p class="small text-justify text-secondary">
          SMT is a Python toolbox for surrogate modeling, Bayesian optimization, and design-space exploration, developed for researchers and engineers. The framework has been applied to diverse high-stakes engineering problems including rocket engine injectors, aircraft fuel consumption modeling, high-order finite element methods, solar energy planning, and wind turbine design.
        </p>

        <h4 class="h6 font-weight-bold text-dark mt-4">Interfaces & Interoperability:</h4>
        <ul class="small text-secondary mb-4">
          <li class="mb-2"><strong><code>Scikit-learn Interface</code></strong>: Developed interoperability layers bridging SMT surrogate models with the broader Python <code>sklearn</code> machine learning ecosystem.</li>
        </ul>



        <div class="mt-3 border-top pt-3">
          <a href="https://github.com/SMTorg/smt" target="_blank" class="btn btn-sm btn-outline-dark mr-2 shadow-sm mb-2"><i class="fab fa-github mr-1"></i> Source Code</a>
          <a href="https://smt.readthedocs.io/" target="_blank" class="btn btn-sm btn-outline-primary shadow-sm mr-2 mb-2"><i class="fas fa-book mr-1"></i> Documentation</a>
        </div>
      </div>
    </div>

    <!-- smt-explainability -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #6f42c1 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              smt-explainability: Explainable Surrogate Modeling
            </h2>
            <div class="mb-3">
              <span class="badge text-white mr-2" style="background-color: #6f42c1;"><i class="fas fa-lock-open mr-1"></i> Open Source (BSD-3)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Core Developer</span>
          </div>
        </div>

        <p class="small text-justify text-secondary">
          <strong>smt-explainability</strong> is a standalone extension <strong>based on SMT</strong> dedicated to mixed-hierarchical Explainable AI (XAI). It provides automated XAI metrics, advanced global sensitivity analysis, and comprehensive visualization workflows to interpret expensive surrogate models.
        </p>



        <div class="mt-3 border-top pt-3">
          <a href="https://github.com/SMTorg/smt-explainability" target="_blank" class="btn btn-sm btn-outline-dark mr-2 shadow-sm"><i class="fab fa-github mr-1"></i> Source Code</a>
        </div>
      </div>
    </div>

    <!-- smt-design-space-ext -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #fd7e14 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              smt-design-space-ext: Hierarchical Variable Handling
            </h2>
            <div class="mb-3">
              <span class="badge text-white mr-2" style="background-color: #fd7e14;"><i class="fas fa-lock-open mr-1"></i> Open Source (BSD-3)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Core Developer</span>
          </div>
        </div>

        <p class="small text-justify text-secondary">
          <strong>smt-design-space-ext</strong> is a standalone extension <strong>based on SMT</strong> that provides robust support for complex mixed-discrete and hierarchical design variables, which are essential for framing high-dimensional system engineering problems.
        </p>



        <div class="mt-3 border-top pt-3">
          <a href="https://github.com/SMTorg/smt-design-space-ext" target="_blank" class="btn btn-sm btn-outline-dark mr-2 shadow-sm"><i class="fab fa-github mr-1"></i> Source Code</a>
        </div>
      </div>
    </div>

    <!-- SMT-optim -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #20c997 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              SMT-optim: Surrogate-Based Optimization
            </h2>
            <div class="mb-3">
              <span class="badge text-white mr-2" style="background-color: #20c997;"><i class="fas fa-lock-open mr-1"></i> Open Source (Apache-2.0)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Core Developer</span>
          </div>
        </div>

        <p class="small text-justify text-secondary">
          <strong>smt-optim</strong> is an open-source Python package for Bayesian optimization tailored for expensive-to-evaluate black-box research applications. It is a standalone extension <strong>based on SMT</strong> that provides scalable frameworks for <strong>constrained</strong> and <strong>multi-fidelity</strong> global optimization across mixed-variable design spaces.
        </p>

        <h4 class="h6 font-weight-bold text-dark mt-4">Key Features:</h4>
        <ul class="small text-secondary mb-4">
          <li class="mb-2"><strong>Multi-fidelity:</strong> Implements state-of-the-art multi-fidelity frameworks (MFSEGO, VF-PI) for both nested and non-nested design spaces.</li>
          <li class="mb-2"><strong>Constraints Handling:</strong> Supports both equality and inequality black-box constraints with automated boundary management and probability of feasibility penalization.</li>
        </ul>



        <div class="mt-3 border-top pt-3">
          <a href="https://github.com/SMTorg/smt-optim" target="_blank" class="btn btn-sm btn-outline-dark mr-2 shadow-sm"><i class="fab fa-github mr-1"></i> Source Code</a>
          <a href="https://smtorg.github.io/smt-optim/" target="_blank" class="btn btn-sm btn-outline-primary shadow-sm"><i class="fas fa-book mr-1"></i> Documentation</a>
        </div>
      </div>
    </div>

    <!-- SEGOMOE -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #dc3545 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              SEGOMOE: Mixture-of-Experts Bayesian Optimizer
            </h2>
            <div class="mb-3">
              <span class="badge badge-danger mr-2"><i class="fas fa-lock mr-1"></i> Proprietary</span>
              <span class="badge badge-secondary shadow-sm"><i class="fas fa-stamp mr-1"></i> Inventeur-Auteur Répub. Fr. (#2948)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Lead Developer & Co-Inventor</span>
          </div>
        </div>

        <p class="small text-justify text-secondary mb-3">
          High-performance constrained Bayesian optimization framework co-developed by ISAE-SUPAERO and ONERA. I restructured the core architecture and integrated advanced capabilities including multi-fidelity evaluation, multi-objective optimization, heterogeneous variable handling, and scalable surrogate-assisted exploration algorithms.
        </p>
        <p class="small text-justify text-secondary mb-0 border-left border-warning pl-3">
          <strong>Framework Interoperability:</strong> Led software integrations bridging ONERA's optimization capabilities (SEGOMOE/SMT) with major aerospace design and system architecture frameworks. This includes developing interfaces for the <strong>FAST-OAD</strong> overall aircraft design framework, as well as <strong>DLR</strong> (German Aerospace Center) tools like <strong>SBArchOpt</strong> and <strong>OpenTurbofanArchitecting</strong>, enabling the resolution of realistic, hierarchical aircraft problems under hidden constraints.
        </p>

        <div class="mt-3 border-top pt-3">
          <a href="https://hal.science/hal-05636767" target="_blank" class="btn btn-sm btn-outline-secondary shadow-sm"><i class="fas fa-file-pdf mr-1"></i> Technical Reference</a>
        </div>
      </div>
    </div>

    <!-- GAMA Platform -->
    <div class="card border-0 shadow-sm bg-light mb-5" style="border-left: 5px solid #17a2b8 !important;">
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-start mb-2">
          <div>
            <h2 class="h4 font-weight-bold mb-1 text-dark">
              GAMA Platform: Agent-Based Modeling & Simulation
            </h2>
            <div class="mb-3">
              <span class="badge badge-info mr-2"><i class="fas fa-lock-open mr-1"></i> Open Source (GPL-3)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="text-muted small font-weight-bold text-uppercase">Role</span><br>
            <span class="font-weight-bold text-primary">Regular Developer</span>
          </div>
        </div>

        <p class="small text-justify text-secondary">
          GAMA is an advanced open-source platform for spatially explicit multi-agent simulation. The platform enables large-scale, GIS-integrated socio-ecological modeling using the high-level GAML language.
        </p>
        
        <p class="small text-justify text-secondary mb-4">
          My work primarily focuses on the development of exploration and optimization tools integrated into the platform, as well as contributing as a regular developer to specific GAML models applied to agro-ecology.
        </p>

        <div class="mt-3 border-top pt-3">
          <a href="https://github.com/gama-platform/gama" target="_blank" class="btn btn-sm btn-outline-dark mr-2 shadow-sm"><i class="fab fa-github mr-1"></i> Source Code</a>
          <a href="https://gama-platform.org/" target="_blank" class="btn btn-sm btn-outline-primary shadow-sm"><i class="fas fa-globe mr-1"></i> Website</a>
        </div>
      </div>
    </div>

  </div>
</div>
