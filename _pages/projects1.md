---
layout: default
permalink: /projects/
title: Projects
nav: true
nav_order: 2  # Adjust this to place the page in the desired order
---

<style>
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin: 40px 0;
  }

  .project-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    background: #fff;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    position: relative;
  }

  .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
  }

  .project-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }

  .project-card .card-content {
    padding: 15px;
  }

  .project-card h3 {
    margin: 0 0 10px;
    font-size: 1.25rem;
    color: #333;
  }

  .project-card p {
    margin: 0;
    color: #555;
    line-height: 1.6;
  }

  .project-card a {
    display: block;
    margin-top: 10px;
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
  }

  .project-card a:hover {
    text-decoration: underline;
  }

  .project-details {
    display: none;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.95);
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    overflow-y: auto;
  }

  .project-card.expanded .project-details {
    display: block;
  }
</style>

<script>
  function toggleDetails(cardId) {
    const card = document.getElementById(cardId);
    card.classList.toggle('expanded');
  }
</script>

<h1>Our Projects</h1>
<p>Explore our exciting projects below. Click on any project to learn more!</p>

<div class="project-grid">
  <!-- Project 1 -->
  <div class="project-card" id="project1">
    <img src="/assets/img/p_minviro.png" alt="Minviro">
    <div class="card-content">
      <h3>Minviro</h3>
      <p>Measuring and minimising environmental impacts of raw materials and energy technologies</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Life Cycle Assessment - Details</h3>
      <p>
        Life Cycle Assessment (LCA) is a comprehensive method to evaluate the environmental impacts of products and services across their entire life cycle—from raw material extraction, manufacturing, distribution, use, to disposal or recycling. We provide tailored LCA solutions to help organizations minimize their environmental footprint and achieve sustainability goals.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">Close</a>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-card">
    <img src="/assets/img/project2.jpg" alt="Critical Review">
    <div class="card-content">
      <h3>Critical Review</h3>
      <p>Ensure your LCA studies meet ISO standards and accurately reflect impacts.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-card">
    <img src="/assets/img/project3.jpg" alt="Advisory">
    <div class="card-content">
      <h3>Advisory</h3>
      <p>Get expert guidance on reducing environmental impacts and improving efficiency.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-card">
    <img src="/assets/img/project4.jpg" alt="Project 4">
    <div class="card-content">
      <h3>Project 4</h3>
      <p>A brief description of Project 4 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 5 -->
  <div class="project-card">
    <img src="/assets/img/project5.jpg" alt="Project 5">
    <div class="card-content">
      <h3>Project 5</h3>
      <p>A brief description of Project 5 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 6 -->
  <div class="project-card">
    <img src="/assets/img/project6.jpg" alt="Project 6">
    <div class="card-content">
      <h3>Project 6</h3>
      <p>A brief description of Project 6 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 7 -->
  <div class="project-card">
    <img src="/assets/img/project7.jpg" alt="Project 7">
    <div class="card-content">
      <h3>Project 7</h3>
      <p>A brief description of Project 7 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 8 -->
  <div class="project-card">
    <img src="/assets/img/project8.jpg" alt="Project 8">
    <div class="card-content">
      <h3>Project 8</h3>
      <p>A brief description of Project 8 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>

  <!-- Project 9 -->
  <div class="project-card">
    <img src="/assets/img/project9.jpg" alt="Project 9">
    <div class="card-content">
      <h3>Project 9</h3>
      <p>A brief description of Project 9 goes here.</p>
      <a href="#">Learn More</a>
    </div>
  </div>
</div>
