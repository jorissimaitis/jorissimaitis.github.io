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
      <h3>Raw materials and energy technologies</h3>
      <p>Measuring and minimising environmental impacts of world-leading organisations.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">+</a>
    </div>
    <div class="project-details">
      <h3>Feb 2025 - Present </h3>
      <p>
        At present, I am a Senior Sustainability Consultant at Minviro. I work with a specialist team to deliver data-driven, sustainability solutions to world-leading organisations. This primarily focusses on LCA for the raw materials and energy sector. We also develop comprehensive databases, tools, innovation, and research. I have delivered several ISO-compliant LCAs, critical reviews, and innovation advisory.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project1')">-</a>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-card" id="project2">
    <img src="/assets/img/p_bath.png" alt="Critical Review">
    <div class="card-content">
      <h3>Prospective LCA</h3>
      <p>Advancing research into future-oriented methods for energy and transport technologies.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project2')">+</a>
    </div>
    <div class="project-details">
      <h3>Sep 2021- Jan 2025 </h3>
      <p>
        I completed my PhD at the University of Bath, collaborating with University College London and Paul Scherrer Institut. We developed LCA methods to project the future environmental impacts of batteries, energy systems, and electric vehicles, publishing articles in world-class journals and renowned international conferences.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project2')">-</a>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-card" id="project3">
    <img src="/assets/img/p_bmi.png" alt="Advisory">
    <div class="card-content">
      <h3>Lithium-ion batteries</h3>
      <p> LCA of lithium-ion battery manufacturing for EU regulations. </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project3')">+</a>
    </div>
    <div class="project-details">
      <h3>Jan 2024 - May 2024</h3>
      <p>
        I worked as a consultant of Benchmark Mineral Intelligence with their sustainability division to deliver an LCA for a global battery manufacturer in anticipation of upcoming EU batteries regulation.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project3')">-</a>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-card" id="project4">
    <img src="/assets/img/p_pathways.png" alt="Project 4">
    <div class="card-content">
      <h3>Software Advisory</h3>
      <p>Decarbonising construction by LCA automation and environmental product declarations</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project4')">+</a>
    </div>
    <div class="project-details">
      <h3>Jan 2024 - Aug 2025</h3>
      <p>
        I helped advise the development of a start-up Pathways on LCA principles and methodology, for deploying an automated and integrated software for construction product impacts and environmental product declaration generation.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project4')">-</a>
    </div>
  </div>

  <!-- Project 5 -->
  <div class="project-card" id="project5">
    <img src="/assets/img/p_ccc.png" alt="Project 5">
    <div class="card-content">
      <h3>UK's Seventh Carbon Budget</h3>
      <p>Advising the UK government on industry and waste greenhouse gas emissions</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project5')">+</a>
    </div>
    <div class="project-details">
      <h3>Feb 2024 - Apr 2024 </h3>
      <p>
        I completed a policy fellowship with the UK's Climate Change Committee, contributing to the Seventh Carbon Budget on decarbonising industry and waste systems.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project5')">-</a>
    </div>
  </div>

  <!-- Project 6 -->
  <div class="project-card" id="project6">
    <img src="/assets/img/p_anthesis.png" alt="Project 6">
    <div class="card-content">
      <h3>Critical Review of Packaging</h3>
      <p>Panel reviewer of Anthesis for consumer goods packaging products</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project6')">+</a>
    </div>
    <div class="project-details">
      <h3>Feb 2024 - Sep 2024</h3>
      <p>
        I conduct critical reviews for Anthesis LCA projects which have focussed on packaging materials and consumer goods.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project6')">-</a>
    </div>
  </div>

  <!-- Project 7 -->
  <div class="project-card" id="project7">
    <img src="/assets/img/p_eightversa.png" alt="Project 7">
    <div class="card-content">
      <h3>Carbon Certification Methods</h3>
      <p>Advisory on LCA methodology for certification development.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project7')">+</a>
    </div>
    <div class="project-details">
      <h3>May 2022</h3>
      <p>
        I advised and reviewed Eight Versa's proposals for a carbon certification scheme using LCA methodology.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project7')">-</a>
    </div>
  </div>

  <!-- Project 8 -->
  <div class="project-card" id="project8">
    <img src="/assets/img/p_carbongraph.png" alt="Project 8">
    <div class="card-content">
      <h3>Software Advisory</h3>
      <p>Accessible LCA using AI</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project8')">+</a>
    </div>
    <div class="project-details">
      <h3>Jun 2024 - Sep 2024</h3>
      <p>
        I advised and reviewed LCA software developed by CarbonGraph that makes LCA accessible driven by AI.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project8')">-</a>
    </div>
  </div>

  <!-- Project 9 -->
  <div class="project-card" id="project9">
    <img src="/assets/img/p_banes.png" alt="Project 9">
    <div class="card-content">
      <h3>Zero Carbon Construction Policy</h3>
      <p>Local policy investigation into decarbonising construction</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project9')">+</a>
    </div>
    <div class="project-details">
      <h3>Jan 2023 - Sep 2023</h3>
      <p>
        I worked as a leading researcher with University of Bath team to investigate the effectiveness of zero carbon construction policy for the Bath & Northeast Somerset Council.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project9')">-</a>
    </div>
  </div>

  <!-- Project 10 -->
  <div class="project-card" id="project10">
    <img src="/assets/img/p_razbio.png" alt="Produce Carbon Calculator">
    <div class="card-content">
      <h3>Produce Carbon Calculator</h3>
      <p>LCA tool for organic broccoli production and transport scenarios.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project10')">+</a>
    </div>
    <div class="project-details">
      <h3>May 2024 - Sept 2024</h3>
      <p>
      For consultancy project with Razbio, I developed a simple and accessible sheet-based LCA tool to estimate the carbon footprint of organic broccoli production vs. commercial methods.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project10')">-</a>
    </div>
  </div>

  <!-- Project 11 -->
  <div class="project-card" id="project11">
    <img src="/assets/img/p_rocket.png" alt="Garment Products">
    <div class="card-content">
      <h3>Garment Products</h3>
      <p>LCA of t-shirts, vests, and cycling jerseys.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project11')">+</a>
    </div>
    <div class="project-details">
      <h3>Jun 2022 - Dec 2022</h3>
      <p>
        Consulting for Rocket Charities and Earthly, I conducted a cradle-to-grave ISO-based LCA of garment products such as t-shirts, vests, and cycling jerseys.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project11')">-</a>
    </div>
  </div>

  <!-- Project 12 -->
  <div class="project-card" id="project12">
    <img src="/assets/img/p_nursem.png" alt="Skincare Products">
    <div class="card-content">
      <h3>Skincare Products</h3>
      <p>LCA of medical skincare products and circular economy strategies</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project12')">+</a>
    </div>
    <div class="project-details">
      <h3>Jan 2022 - Jun 2022</h3>
      <p>
        In consultation with Nursem, I delivered a cradle-to-gave ISO-based LCA of several skin care products including scenarios for circular economy strategies such as refill and reuse packaging.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project12')">-</a>
    </div>
  </div>

  <!-- Project 13 -->
  <div class="project-card" id="project13">
    <img src="/assets/img/p_relondon.png" alt="Carbon Calculator">
    <div class="card-content">
      <h3>Carbon Calculator</h3>
      <p>Advisory and review of carbon footprint calculator.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project13')">+</a>
    </div>
    <div class="project-details">
      <h3>May 2022</h3>
      <p>
        I consulted with ReLondon to review and feedback on their existing product carbon footprint calculator.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project13')">-</a>
    </div>
  </div>

  <!-- Project 14 -->
  <div class="project-card" id="project14">
    <img src="/assets/img/p_gw.png" alt="Reuse Packaging Supply Chain">
    <div class="card-content">
      <h3>Reusable Wine Packaging</h3>
      <p>Project proposal for implementing a reuse packaging supply-chain</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project14')">+</a>
    </div>
    <div class="project-details">
      <h3>Jan 2021 - Jun 2021</h3>
      <p>
        As part of the "From Linear to Circular Programme 2021" run by the Ellen MacArthur Foundation, I led a consulting team for Garcon Wines to propose supply-chain for reusable wine packaging.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project14')">-</a>
    </div>
  </div>

  <!-- Project 15 -->
  <div class="project-card" id="project15">
    <img src="/assets/img/p_ucl.png" alt="Biofertilizer Products">
    <div class="card-content">
      <h3>Biofertilizer Products</h3>
      <p>LCA of biofertilizer products based on EU circular bioeconomy technologies.</p>
      <a href="javascript:void(0);" onclick="toggleDetails('project15')">+</a>
    </div>
    <div class="project-details">
      <h3>May 2020 - Sep 2020</h3>
      <p>
        As part of my MSc dissertation at UCL, I conducted an LCA of biofertilizer products from Project NOMAD - An EU Horizon 2020 funded project.
      </p>
      <a href="javascript:void(0);" onclick="toggleDetails('project15')">-</a>
    </div>
  </div>


</div>

<style>
  /* Existing styles... */

  /* Style for the + and - buttons */
  .project-card a {
    display: block;
    margin-top: 10px;
    color: #d4af37; /* Gold color */
    text-decoration: none;
    font-weight: bold;
    font-size: 1.5rem; /* Slightly larger for emphasis */
    text-align: center;
  }

  .project-card a:hover {
    text-decoration: underline;
    color: #b8860b; /* Slightly darker gold on hover */
  }
</style>
