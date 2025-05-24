---
layout: default
title: Home
---

<!-- Marquee Banner -->
<style>
.marquee-container {
  width: 100%;
  overflow: hidden;
  white-space: nowrap;
  background-color: #0077cc;
  color: white;
  padding: 1rem 0;
  font-size: 1.5rem;
  font-weight: bold;
  border-radius: 0 0 10px 10px;
}

.marquee-text {
  display: inline-block;
  padding-left: 100%;
  animation: marquee 10s linear infinite;
}

@keyframes marquee {
  0% { transform: translateX(0); }
  100% { transform: translateX(-100%); }
}

.hero {
  text-align: center;
  margin-top: 3rem;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.3rem;
  font-weight: 700;
}

.hero h2 {
  font-size: 2rem;
  color: #555;
  margin-top: 0;
  font-weight: 400;
}
</style>

<div class="marquee-container">
  <div class="marquee-text">Welcome to My Professional Portfolio</div>
</div>

<div class="hero">
  <h1>HELLO, I'm RAMESH THANGAMANI</h1>
  <h2>TECHNICAL WRITER</h2>
  <p><em>A passionate technical writer specializing in clear, concise documentation that helps users succeed</em></p>
</div>

<div style="text-align: center; margin-top: 2rem;">
  <img src="images/TW_illurstration.jpg" alt="Technical Writer Illustration"
       style="max-width: 90%; height: auto; max-height: 400px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>

