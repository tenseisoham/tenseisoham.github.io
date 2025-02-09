---
layout: page
permalink: /projects/
title: projects
description:
nav: true
nav_order: 2
---

<!-- Import Roboto font and custom styling -->
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

body {
  font-family: 'Roboto', sans-serif;
}

/* Grid for 3 columns; graceful fallback to fewer columns on smaller screens */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin: 30px 0;
}

/* Card styling */
.project-card {
  background-color: #2F2F2F; /* Dark tile background */
  border-radius: 8px;
  padding: 20px;
  color: #f2f2f2; /* Light text */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  /* Small jump animation on hover */
  transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out, border 0.2s;
  border: 1px solid transparent; /* Helps the border transition smoothly */
}
.project-card:hover {
  transform: scale(1.02);
  border: 1px solid #40C8EC; /* Highlight border on hover */
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
}

/* Title styling */
.project-card h3 {
  margin-top: 0;
  color: #40C8EC; /* Teal-like color */
  font-size: 1.4rem;
}

/* Emphasized labels (Year, Category) */
.project-card p strong {
  color: #dcdcdc;
}

/* Buttons/Links styling */
.project-card .project-links a {
  display: inline-block;
  margin-right: 10px;
  margin-top: 10px;
  text-decoration: none;
  padding: 6px 12px;
  border-radius: 4px;
  font-weight: 500;
  transition: background-color 0.2s ease-in-out;
}
.project-card .btn-primary {
  background-color: #1E88E5;
  color: #fff;
}
.project-card .btn-info {
  background-color: #26C6DA;
  color: #fff;
}
.project-card .btn-secondary {
  background-color: #9E9E9E;
  color: #fff;
}
.project-card .btn-primary:hover,
.project-card .btn-info:hover,
.project-card .btn-secondary:hover {
  opacity: 0.8;
}

/* Images */
.project-card img {
  max-width: 100%;
  border-radius: 4px;
  margin-bottom: 15px;
}

/* Responsive behavior for smaller screens */
@media (max-width: 1200px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}
@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<h1 style="margin-bottom: 20px;">Projects</h1>

<!-- Begin the grid -->
<div class="projects-grid">

  <!-- 1) Visual Embeddings Solving Jigsaw Puzzles -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/jigsaw.JPG" alt="Visual Embeddings Jigsaw Preview" />
    <h3>Visual Embeddings Solving Jigsaw Puzzles</h3>
    <p><strong>Year:</strong> Feb - Apr 2024</p>
    <p><strong>Category:</strong> Deep Learning, Graph Neural Networks</p>
    <p>
      Devised a novel deep learning model architecture and corresponding loss functions
      dedicated to representation learning for downstream tasks through the pre-text
      application of jigsaw puzzle paradigms, utilizing Graph Neural Networks and Autoencoders.
    </p>
    <p>
      Pioneered a Segmented Flow warp approach to enhance representation learning,
      achieving a validation accuracy of 60%, competing with current state-of-the-art approaches.
    </p>
    <p><strong>Technologies used:</strong> PyTorch, CNN, ViGNN, Vision Transformer.</p>
    <div class="project-links">
      <a href="https://github.com/tenseisoham/dolphin/tree/main" class="btn btn-primary">Code</a>
      <a href="https://www.youtube.com/watch?v=3YGhiBP-7z8&t=2s" class="btn btn-info">Video</a>
      <a href="https://plakshauniversity1-my.sharepoint.com/personal/soham_petkar_plaksha_edu_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsoham%5Fpetkar%5Fplaksha%5Fedu%5Fin%2FDocuments%2FDL%5FFinal%5FJigsaw%2Epdf&parent=%2Fpersonal%2Fsoham%5Fpetkar%5Fplaksha%5Fedu%5Fin%2FDocuments&ga=1" class="btn btn-secondary">Paper</a>
    </div>
  </div>

  <!-- 2) Quantum Machine Learning Classifiers -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/quantum.JPG" alt="Quantum Machine Learning Preview" />
    <h3>Quantum Machine Learning Classifiers</h3>
    <p><strong>Year:</strong> Mar - May 2024</p>
    <p><strong>Category:</strong> Quantum Machine Learning</p>
    <p>
      Implemented 24 combinations of Feature Maps, Ansatzs, and Optimizers to research
      the efficacy of Quantum kernel‐based classifiers.
    </p>
    <p>
      Our combination of the Z‐Feature map, EfficientSU2 ansatz, and L_BFGS_B optimizer
      outperformed classical SVM in all metrics.
    </p>
    <p><strong>Technologies used:</strong> IBM Qiskit, Quantum Kernel Methods.</p>
    <div class="project-links">
      <a href="https://github.com/tenseisoham/QuantumML/tree/main" class="btn btn-primary">Code</a>
      <a href="https://plakshauniversity1-my.sharepoint.com/personal/soham_petkar_plaksha_edu_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsoham%5Fpetkar%5Fplaksha%5Fedu%5Fin%2FDocuments%2Ffinal%5FquantumML%20report%2Epdf&parent=%2Fpersonal%2Fsoham%5Fpetkar%5Fplaksha%5Fedu%5Fin%2FDocuments&ga=1" class="btn btn-secondary">Paper</a>
    </div>
  </div>

  <!-- 3) SWaV-Based Clustering for Vehicle Identification -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/swav.JPG" alt="SWaV Clustering for Vehicle Re-Identification" />
    <h3>SWaV-Based Clustering for Vehicle Identification</h3>
    <p><strong>Year:</strong> Oct - Nov 2023</p>
    <p><strong>Category:</strong> Self-Supervised Learning, Computer Vision</p>
    <p>
      Used SWaV (Swapping Assignments between Views) based clustering to perform
      vehicle re-identification on the Veri-776 dataset.
    </p>
    <p>
      The model assigns the same cluster to the same vehicle across different images
      and assigns different clusters to different vehicles, effectively improving
      vehicle identification accuracy.
    </p>
    <p><strong>Technologies used:</strong> SWaV, Convolutional Neural Networks (CNN), Self-Supervised Learning.</p>
  </div>

  <!-- 4) ADRENALIN Challenge: Non-Intrusive Load Disaggregation -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/payday.JPG" alt="ADRENALIN NILM Challenge" />
    <h3>ADRENALIN Challenge: Non-Intrusive Load Disaggregation (NILM)</h3>
    <p><strong>Year:</strong> Feb - Apr 2024</p>
    <p><strong>Category:</strong> Energy Disaggregation, Unsupervised Learning</p>
    <p>
      Competed in the ADRENALIN challenge to predict heating and cooling components
      in buildings using Non-Intrusive Load Disaggregation (NILM).
    </p>
    <p>
      Placed 8th worldwide for developing an unsupervised algorithm to accurately
      disaggregate heating and cooling loads from total power main meter readings.
    </p>
    <p><strong>Technologies used:</strong> Unsupervised Learning, NILM, Time-Series Analysis.</p>
    <div class="project-links">
      <a href="https://github.com/tenseisoham/payday/tree/main" class="btn btn-primary">Code</a>
    </div>
  </div>

  <!-- 5) Winner HackPlaksha 24' Healthcare Track -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/we-care.gif" alt="WeCare App" />
    <h3>Winner HackPlaksha 24' Healthcare Track</h3>
    <p><strong>Associated with:</strong> Plaksha University</p>
    <p><strong>Category:</strong> Healthcare, Human Computer Interaction</p>
    <p>
      Developed WeCare, a slouching and blinking monitoring desktop app designed to
      improve user posture and reduce back pain and eye strain by raising alerts when
      slouching or strain occurs for extended periods.
    </p>
    <p>
      <strong>Technologies used:</strong> Strided Transformer weights for body keypoint
      detection and slouch detection, Electron JS, Python, SQL for desktop app development
      and data analysis.
    </p>
    <div class="project-links">
      <a href="https://devfolio.co/projects/wecare-b3b8" class="btn btn-primary">View Project</a>
    </div>
  </div>

  <!-- 6) Easter Egg: Reinforcement Learning Convergence Simulation -->
  <div class="project-card">
    <img src="{{ site.baseurl }}/assets/img/TD_learning.gif" alt="Reinforcement Learning Simulation" />
    <h3 style="font-size: 1.2rem;">Easter Egg: Reinforcement Learning Convergence Simulation</h3>
    <p><strong>Category:</strong> Reinforcement Learning, Temporal Difference Learning</p>
    <p>
      This is not a project but a simulation that visualizes the convergence of a
      reinforcement learning algorithm, specifically temporal difference learning.
      The example is inspired by David Silver's RL course slides, and this GIF was
      generated using Python simulations.
    </p>
    <p>
      You can tweak the hyperparameters or adjust the state space to observe different
      convergence behaviors across epochs.
    </p>
    <div class="project-links">
      <a href="https://github.com/tenseisoham/Temporal-Difference-Learning-Simulation/tree/main" class="btn btn-primary">Code</a>
    </div>
  </div>

</div>
