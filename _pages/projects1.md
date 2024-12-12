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
      <h3>Minviro | Feb 2025 - Present </h3>
      <p>Measuring and minimising environmental impacts of raw materials and energy technologies.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Minviro</h3>
      <p>
        At present, I am a Senior Sustainability Consultant at Minviro. I work with a specialist team to deliver data-driven, sustainability solutions to world-leading organisations. This primarily focusses on LCA for the raw materials and energy sector. We also develop comprehensive databases, tools, innovation, and research. I have delivered several ISO-compliant LCAs, critical reviews, and innovation advisory.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">Close</a>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-card" id="project2">
    <img src="/assets/img/p_bath.png" alt="Critical Review">
    <div class="card-content">
      <h3>Prospective LCA | Sep 2021 - Jan 2025 </h3>
      <p>Advancing research into future-oriented methods for technologies.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project2')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Prospective LCA | Sep 2021- Jan 2025 </h3>
      <p>
        I completed my PhD at the University of Bath, collaborating with University College London and Paul Scherrer Institut. We developed LCA methods to project the future environmental impacts of batteries, energy systems, and electric vehicles, publishing articles in world-class journals and renowned international conferences.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project2')">Close</a>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-card" id="project3">
    <img src="/assets/img/p_bmi.png" alt="Advisory">
    <div class="card-content">
      <h3>Lithium-ion batteries | Jan 2024 - May 2024 </h3>
      <p> Carbon footprinting of battery manufacturing </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project3')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Advisory</h3>
      <p>
        I worked as a consultant of Benchmark Mineral Intelligence with their sustainability division to deliver an LCA for a global battery manufacturer in anticipation of upcoming EU batteries regulation.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project3')">Close</a>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-card" id="project4">
    <img src="/assets/img/project4.jpg" alt="Project 4">
    <div class="card-content">
      <h3>Project 4</h3>
      <p>A brief description of Project 4 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project4')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 4</h3>
      <p>
        This project focuses on implementing cutting-edge sustainability solutions for industries dealing with high energy consumption. Our goal is to reduce energy use and improve resource efficiency while maintaining the competitiveness of these sectors.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project4')">Close</a>
    </div>
  </div>

  <!-- Project 5 -->
  <div class="project-card" id="project5">
    <img src="/assets/img/project5.jpg" alt="Project 5">
    <div class="card-content">
      <h3>Project 5</h3>
      <p>A brief description of Project 5 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project5')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 5</h3>
      <p>
        This project investigates the impact of new materials in construction and their life cycle. The aim is to find alternatives to traditional materials that can reduce carbon emissions and improve sustainability in the built environment.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project5')">Close</a>
    </div>
  </div>

  <!-- Project 6 -->
  <div class="project-card" id="project6">
    <img src="/assets/img/project6.jpg" alt="Project 6">
    <div class="card-content">
      <h3>Project 6</h3>
      <p>A brief description of Project 6 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project6')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 6</h3>
      <p>
        A comprehensive evaluation of the environmental impacts of recycling processes and materials recovery. This project focuses on optimizing the recycling chain to achieve greater sustainability in waste management.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project6')">Close</a>
    </div>
  </div>

  <!-- Project 7 -->
  <div class="project-card" id="project7">
    <img src="/assets/img/project7.jpg" alt="Project 7">
    <div class="card-content">
      <h3>Project 7</h3>
      <p>A brief description of Project 7 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project7')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 7</h3>
      <p>
        A study on the life cycle of renewable energy technologies, such as solar panels and wind turbines, exploring ways to reduce environmental impacts during their manufacturing, usage, and disposal phases.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project7')">Close</a>
    </div>
  </div>

  <!-- Project 8 -->
  <div class="project-card" id="project8">
    <img src="/assets/img/project8.jpg" alt="Project 8">
    <div class="card-content">
      <h3>Project 8</h3>
      <p>A brief description of Project 8 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project8')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 8</h3>
      <p>
        Focuses on evaluating the environmental impacts of urban development and transportation systems. This project seeks to promote more sustainable city planning and infrastructure development.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project8')">Close</a>
    </div>
  </div>

  <!-- Project 9 -->
  <div class="project-card" id="project9">
    <img src="/assets/img/project9.jpg" alt="Project 9">
    <div class="card-content">
      <h3>Project 9</h3>
      <p>A brief description of Project 9 goes here.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project9')">Learn More</a>
    </div>
    <div class="project-details">
      <h3>Project 9</h3>
      <p>
        A deep dive into sustainable practices in agriculture, focusing on methods that reduce environmental impact while maintaining productivity and profitability for farmers.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project9')">Close</a>
    </div>
  </div>
</div>
