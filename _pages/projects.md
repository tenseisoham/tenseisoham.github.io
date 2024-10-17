---
layout: page
permalink: /projects/
title: projects
description:
nav: true
nav_order: 2
---

<!-- Custom entry for Visual Embeddings Solving Jigsaw Puzzles -->
<div class="project-entry d-flex align-items-center" style="display: flex; align-items: center; gap: 20px;">

  <!-- Left: Image -->
  <div class="project-image">
    <img src="{{ site.baseurl }}/assets/img/jigsaw.jpg" alt="Visual Embeddings Jigsaw Preview" style="max-width: 300px; margin-top: 10px;" />
  </div>

  <!-- Right: Project Info -->
  <div class="project-info">
    <h3>Visual Embeddings Solving Jigsaw Puzzles</h3>
    <p><strong>Year:</strong> Feb - Apr 2024</p>
    <p><strong>Category:</strong> Deep Learning, Graph Neural Networks</p>

    <div class="project-description">
      <p>Devised a novel deep learning model architecture and corresponding loss functions dedicated to representation learning for downstream tasks through the pre-text application of jigsaw puzzle paradigms, utilizing Graph Neural Networks and Autoencoders.</p>
      <p>Pioneered a Segmented Flow warp approach to enhance representation learning, achieving a validation accuracy of 60%, competing with current state-of-the-art approaches in the domain.</p>
      <p><strong>Technologies used:</strong> PyTorch, CNN, ViGNN, Vision Transformer.</p>
    </div>

    <div class="project-links">
      <a href="link-to-code" class="btn btn-primary">Code</a>
      <a href="link-to-paper" class="btn btn-secondary">Paper</a>
    </div>
  </div>
</div>


<hr style="border: 1px solid lightgrey; margin: 20px 0;" />

<div class="project-entry d-flex align-items-center" style="display: flex; align-items: center; gap: 20px;">

  <!-- Left: Image -->
  <div class="project-image">
    <img src="{{ site.baseurl }}/assets/img/quantum.jpg" alt="Quantum Machine Learning Preview" style="max-width: 300px;" />
  </div>

  <!-- Right: Project Info -->
  <div class="project-info">
    <h3>Quantum Machine Learning Classifiers</h3>
    <p><strong>Year:</strong> Mar - May 2024</p>
    <p><strong>Category:</strong> Quantum Machine Learning</p>

    <div class="project-description">
      <p>Implemented 24 combinations of Feature Maps, Ansatzs, and Optimizers to research the efficacy of Quantum kernel‐based classifiers.</p>
      <p>Our combination of the Z‐Feature map, EfficientSU2 ansatz, and L_BFGS_B optimizer outperformed classical SVM in all metrics.</p>
      <p><strong>Technologies used:</strong> IBM Qiskit, Quantum Kernel Methods.</p>
    </div>

    <div class="project-links">
      <a href="link-to-code" class="btn btn-primary">Code</a>
      <a href="link-to-paper" class="btn btn-secondary">Paper</a>
    </div>
  </div>
  
</div>


<hr style="border: 1px solid lightgrey; margin: 20px 0;" />

<div class="project-entry d-flex align-items-center" style="display: flex; align-items: center; gap: 20px;">

  <!-- Left: Image -->
  <div class="project-image">
    <img src="{{ site.baseurl }}/assets/img/swav.jpg" alt="SWaV Clustering for Vehicle Re-Identification" style="max-width: 300px;" />
  </div>

  <!-- Right: Project Info -->
  <div class="project-info">
    <h3>SWaV-Based Clustering for Vehicle Identification</h3>
    <p><strong>Year:</strong> Oct - Nov 2023</p>
    <p><strong>Category:</strong> Self-Supervised Learning, Computer Vision</p>

    <div class="project-description">
      <p>Used SWaV (Swapping Assignments between Views) based clustering to perform vehicle re-identification on the Veri-776 dataset.</p>
      <p>The model assigns the same cluster to the same vehicle across different images and assigns different clusters to different vehicles, effectively improving vehicle identification accuracy.</p>
      <p><strong>Technologies used:</strong> SWaV, Convolutional Neural Networks (CNN), Self-Supervised Learning.</p>
    </div>

    <!-- <div class="project-links">
      <a href="link-to-code" class="btn btn-primary">Code</a>
      <a href="link-to-paper" class="btn btn-secondary">Paper</a>
    </div>-->
  </div> 
  
</div>

<hr style="border: 1px solid lightgrey; margin: 20px 0;" />
<div class="project-entry d-flex align-items-center" style="display: flex; align-items: center; gap: 20px;">

  <!-- Left: Image -->
  <div class="project-image">
    <img src="{{ site.baseurl }}/assets/img/payday.jpg" alt="ADRENALIN NILM Challenge" style="max-width: 300px;" />
  </div>

  <!-- Right: Project Info -->
  <div class="project-info">
    <h3>ADRENALIN Challenge: Non-Intrusive Load Disaggregation (NILM)</h3>
    <p><strong>Year:</strong> Feb - Apr 2024</p>
    <p><strong>Category:</strong> Energy Disaggregation, Unsupervised Learning</p>

    <div class="project-description">
      <p>Competed in the ADRENALIN challenge to predict heating and cooling components in buildings using Non-Intrusive Load Disaggregation (NILM).</p>
      <p>Placed 8th worldwide for developing an unsupervised algorithm to accurately disaggregate heating and cooling loads from total power main meter readings.</p>
      <p><strong>Technologies used:</strong> Unsupervised Learning, NILM, Time-Series Analysis.</p>
    </div>

    <div class="project-links">
      <a href="https://github.com/tenseisoham/payday/tree/main" class="btn btn-primary">Code</a>
    </div>
  </div>
  
</div>


<!-- Easter Egg Section -->
<div class="project-entry d-flex align-items-center" style="display: flex; align-items: center; gap: 20px; margin-top: 50px; border-top: 2px solid lightgrey; padding-top: 20px;">

  <!-- Left: GIF -->
  <div class="project-image">
    <img src="{{ site.baseurl }}/assets/img/TD_learning.gif" alt="Reinforcement Learning Simulation" style="max-width: 300px;" />
  </div>

  <!-- Right: Easter Egg Info -->
  <div class="project-info">
    <h3 style="font-size: 1.5rem;">Easter Egg: Reinforcement Learning Convergence Simulation</h3>
    <p><strong>Category:</strong> Reinforcement Learning, Temporal Difference Learning</p>

    <div class="project-description">
      <p>This is not a project but a simulation that visualizes the convergence of a reinforcement learning algorithm, specifically temporal difference learning. The example is inspired by David Silver's RL course slides, and this GIF was generated using Python simulations.</p>
      <p>You can tweak the hyperparameters or adjust the state space to observe different convergence behaviors across epochs.</p>
    </div>

    <div class="project-links">
      <a href="https://github.com/tenseisoham/Temporal-Difference-Learning-Simulation/tree/main" class="btn btn-primary">Code</a>
    </div>
  </div>

</div>
