---
layout: archive
title: ""
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /aboutme
  - /me/
---

<div class="bio-box">
  <!-- <h1>I'm Soham Petkar</h1> -->
  <div class="bio-content">
    <div class="bio-text">
      I am a Research Fellow at Sarvam AI, working on foundation models.
      <br><br>
      My past research focuses on efficient pre-training and evaluation of graph–language multimodal models, alongside exploring interpretability and alignment in real-world scenarios using the linear representation hypothesis.
      <br><br>
      Topics that intrigue me include (but aren’t limited to): mechanistic interpretability, alignment,  graph-language modeling, deterministic &amp; stochastic reasoning mechanisms, or anything that imparts tacit knowledge to models!
      <br><br>
      Outside academics and research, I love cinema and music: critically analyzing modern films, filmography, and directing. My team and I have won competitions at BITS-H, Ashoka, and internal university events. I’m also passionate about e‑sports, having competed and worked as an analyst.
      <br><br>
      I also blog (on LessWrong) and tweet (on X) sometimes.
    </div>
  </div>
</div>


<style>
.bio-box {
  background: linear-gradient(135deg, #161b22, #1e2630);
  padding: 1rem 1.25rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  margin: 1.5rem 0;
  color: white;
}

.bio-content {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  flex-wrap: wrap;
}

.bio-text {
  flex: 1 1 300px;
  min-width: 0;
}

.bio-img {
  width: 225px;
  margin-bottom: 0.5rem;
}

/* Responsive for mobile */
@media (max-width: 768px) {
  .bio-content {
    flex-direction:
  }
}

</style>

<!--  -->
<!-- GALLERY -->
<!--  -->
<!--
<h2 style="margin-top: 2rem;">📸 <strong>Gallery</strong></h2>

<div class="gallery-scroll-container">
  <div class="gallery-image-wrapper">
    <img src="/images/gallery1.jpg" alt="Gallery image 1">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery2.jpg" alt="Gallery image 2">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 3">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 4">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 5">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 6">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 7">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 8">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 9">
  </div>
  <div class="gallery-image-wrapper">
    <img src="/images/gallery3.jpg" alt="Gallery image 10">
  </div>
</div>

<style>
.gallery-scroll-container {
  display: flex;
  overflow-x: auto;
  white-space: nowrap;
  gap: 1rem;
  padding: 1rem;
  scroll-snap-type: x mandatory;
  -webkit-overflow-scrolling: touch;
  scroll-behavior: smooth;

  background: linear-gradient(135deg, #161b22, #1e2630);
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(255, 215, 0, 0.08);
  scrollbar-width: none; /* Firefox */
}
.gallery-scroll-container::-webkit-scrollbar {
  display: none; /* Chrome, Safari */
}

.gallery-image-wrapper {
  flex: 0 0 auto;
  scroll-snap-align: start;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease;
}

.gallery-image-wrapper:hover {
  transform: scale(1.05);
}

.gallery-image-wrapper img {
  display: block;
  max-width: 200px;
  object-fit: cover;
}
</style>

<script>
  const gallery = document.querySelector('.gallery-scroll-container');
  let scrollAmount = 1;
  let isUserScrolling = false;

  // Disable auto-scroll while dragging or scrolling
  let isDragging = false;
  let startX;
  let scrollLeft;

  gallery.addEventListener('mousedown', (e) => {
    isDragging = true;
    startX = e.pageX - gallery.offsetLeft;
    scrollLeft = gallery.scrollLeft;
    isUserScrolling = true;
  });

  gallery.addEventListener('mouseleave', () => {
    isDragging = false;
  });

  gallery.addEventListener('mouseup', () => {
    isDragging = false;
    setTimeout(() => isUserScrolling = false, 1500);
  });

  gallery.addEventListener('mousemove', (e) => {
    if (!isDragging) return;
    e.preventDefault();
    const x = e.pageX - gallery.offsetLeft;
    const walk = (x - startX) * 1.5; // scroll-fastness
    gallery.scrollLeft = scrollLeft - walk;
  });

  gallery.addEventListener('scroll', () => {
    isUserScrolling = true;
    clearTimeout(window._scrollTimeout);
    window._scrollTimeout = setTimeout(() => isUserScrolling = false, 1500);
  });

  function autoScrollGallery() {
    if (!gallery || isUserScrolling) return;

    if (gallery.scrollLeft >= gallery.scrollWidth - gallery.clientWidth - 1) {
      gallery.scrollTo({ left: 0, behavior: 'smooth' });
    } else {
      gallery.scrollBy({ left: scrollAmount, behavior: 'smooth' });
    }
  }

  setInterval(autoScrollGallery, 60); // 20% slower than 50ms
</script> -->
<!--  -->
<!-- TEACHING SECTION -->
<!--  -->

## 👨🏻‍🏫 <strong>Teaching</strong>

<style>
.achievement-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1rem;
  margin-top: 1.5rem;
}

@media (min-width: 768px) {
  .achievement-grid {
    grid-template-columns: 1fr 1fr;
  }
}

.achievement-item {
  background: #161b22; /*linear-gradient(135deg, #161b22, #1e2630);*/
  border-left: 4px solid #FFD700;
  padding: 0.5rem 1rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(255, 215, 0, 0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.achievement-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 14px rgba(255, 215, 0, 0.12);
}

.achievement-title {
  font-weight: 600;
  font-size: 1rem;
  color: #f0f6fc;
  display: block;
  margin-bottom: 0.15rem;
}

.achievement-note {
  font-size: 0.94rem;
  color: #9eb1c6;
  display: block;
}
</style>

<div class="achievement-grid">

  <div class="achievement-item">
    <span class="achievement-title">Deep Learning Teaching Assistant</span>
    <span class="achievement-note">Plaksha University · Aug 2024 – Dec 2024 · Mohali, India · On-site<br>
    Assisted in AI3001/Deep Learning under Dr. Anupam Sobti, guiding students through concepts, assignments, and project work.</span>
  </div>

  <div class="achievement-item">
    <span class="achievement-title">AI Educator</span>
    <span class="achievement-note">Vizuara · Aug 2024 – Jan 2025 · Remote<br>
    Created AI learning materials and mentored students & high school teachers in AI, simplifying complex concepts for diverse learners.</span>
  </div>

  <div class="achievement-item">
    <span class="achievement-title">IOAI Stage 4 & 5 Mentor</span>
    <span class="achievement-note">ACM IOAI Student Mentor · May 2025 · IIIT Hyderabad<br>
    Mentored Stage 4 & 5 International Olympiad in AI 2025 students on NLP and ML problems, guiding them through real-world AI challenges.</span>
  </div>

</div>


<!--  -->
<!-- EXPERIENCE SECTION -->
<!--  -->

## 📊 <strong>Experience</strong>

<style>
.exp-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1rem;
  margin-top: 1.5rem;
}

@media (min-width: 768px) {
  .exp-grid {
    grid-template-columns: 1fr 1fr;
  }
}

.exp-item {
  background: #161b22;
  border-left: 4px solid #00BFFF;
  padding: 0.5rem 1rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 191, 255, 0.08);
  display: flex;
  flex-direction: column;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.exp-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 14px rgba(0, 191, 255, 0.12);
}

/* Header now uses a two-column grid: left (title + desc) and right (date) */
.exp-header {
  display: grid;
  grid-template-columns: 1fr auto;
  align-items: start;
}

.header-left {
  display: flex;
  flex-direction: column;
}

.exp-title {
  font-weight: 600;
  font-size: 1rem;
  color: #f0f6fc;
  margin-bottom: 0.2rem;
}

.exp-desp {
  font-size: 0.95rem;
  color: #9eb1c6;
  font-style: italic;
  font-weight: 500;
}

.exp-date {
  font-size: 0.85rem;
  color: #7f8c9f;
  font-style: italic;
  white-space: nowrap;
  padding-left: 1rem;
  padding-top: 0.15rem;
}
</style>

<div class="exp-grid">

  <!-- Undergraduate Researcher / PreCog Lab - IIIT Hyderabad -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">Research Associate</div>
        <div class="exp-desp">PreCog Lab - IIIT Hyderabad</div>
      </div>
      <div class="exp-date">Jan, 2025 – Present</div>
    </div>
  </div>

  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">AI/ML Engineer</div>
        <div class="exp-desp">Turbo ML(Puch AI) - Remote</div>
      </div>
      <div class="exp-date">Apr - Jun, 2025</div>
    </div>
  </div>

  <!-- AI/ML & Data Science Intern / JM Financial Ltd -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">AI/ML & Data Science Intern</div>
        <div class="exp-desp">JM Financial Ltd, Mumbai, Maharashtra</div>
      </div>
      <div class="exp-date">May – Aug, 2024</div>
    </div>
  </div>

  <!-- Head of Logistics and Operations / Plaksha Consulting Club -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">Head of Logistics & Operations</div>
        <div class="exp-desp">Plaksha Consulting Club</div>
      </div>
      <div class="exp-date">Aug, 2023 – Aug, 2024</div>
    </div>
  </div>

  <!-- AI/ML Engineer / Best Automation -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">AI/ML Engineer</div>
        <div class="exp-desp">Best Automation, Pune/Pimpri-Chinchwad</div>
      </div>
      <div class="exp-date">Jul – Sep, 2023</div>
    </div>
  </div>

  <!-- Entrepreneur / InfoEdge CFE Plaksha University -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">Founder/Entrepreneur - EasyPC</div>
        <div class="exp-desp">InfoEdge CFE - Plaksha University</div>
      </div>
      <div class="exp-date">Apr – Jun, 2023</div>
    </div>
  </div>

  <!-- Tech Business Development Intern / MetaXP -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">Tech Business Development Intern</div>
        <div class="exp-desp">MetaXP</div>
      </div>
      <div class="exp-date">Jul – Sep, 2022</div>
    </div>
  </div>

  <!-- Game Designer / MADIEE Games -->
  <div class="exp-item">
    <div class="exp-header">
      <div class="header-left">
        <div class="exp-title">Game Designer</div>
        <div class="exp-desp">MADIEE Games</div>
      </div>
      <div class="exp-date">Jan – Jun, 2022</div>
    </div>
  </div>

</div>

