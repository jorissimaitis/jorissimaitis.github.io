---
layout: about
title: About
permalink: /
subtitle: <strong class="custom-subtitle">Life Cycle Assessment Consultant - PhD, PIEMA, REnvP</strong> #<a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic1.png
  image_circular: false # crops the image to make it circular
  more_info:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
latest_posts: false
---

<p style="font-size: 1.2rem;">Tailored solutions to measure and minimise the environmental impacts of products and services across their entire life cycle.</p>

<div class="expertise-boxes">
  <div class="box" id="lca">
    <a href="#lca">
      <h3>Life Cycle Assessment</h3>
    </a>
  </div>

  <div class="box" id="review">
    <a href="#review">
      <h3>Critical Review</h3>
    </a>
  </div>

  <div class="box" id="advisory">
    <a href="#advisory">
      <h3>Advisory</h3>
    </a>
  </div>
</div>

<!-- Scrolling logos container -->
<div class="scrolling-logos">
  <div class="logo-container">
    <img src="logo_minviro.png" alt="Minviro" />
    <img src="logo_anthesis.png" alt="Anthesis" />
    <img src="logo_eightversa.png" alt="Eight Versa" />
    <img src="logo_ccc.png" alt="CCC" />
    <img src="logo_bmi.png" alt="BMI" />
    <img src="logo_ucl.png" alt="UCL" />
    <img src="logo_bath.png" alt="Bath" />
    <img src="logo_emf.png" alt="EMF" />
    <img src="logo_nursem.png" alt="Nursem" />
    <img src="logo_relondon.png" alt="ReLondon" />
    <img src="logo_earthly.png" alt="Earthly" />
    <img src="logo_scholartribe.png" alt="ST" />
    <img src="logo_razbio.png" alt="Razbio" />
    <img src="logo_gc.png" alt="GW" />
    <img src="logo_banes.png" alt="Banes" />
  </div>
</div>

<style>
/* Styling the subtitle */
.custom-subtitle {
  color: #B8860B;  /* Example color (blue) #4A90E2 */
}

/* Styling the boxes */
.expertise-boxes {
  display: flex;
  flex-direction: column;  /* Stack the boxes vertically */
  gap: 15px;  /* space between the boxes */
  margin-top: 20px; /* space from the paragraph */
  align-items: right;  /* Center the boxes horizontally */
}

.expertise-boxes .box {
  background-color: #f5f5f5;  /* light gray background */
  padding: 15px;
  border-radius: 8px;
  text-align: left;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;  /* smooth transition for hover effect */
  width: 90%;  /* Set a percentage width (or adjust based on desired size) */
  max-width: 300px;  /* Limit the maximum width of the box */
}

.expertise-boxes .box a {
  text-decoration: none;
  color: #B8860B;  /* dark text */
  font-size: 1.0rem;  /* slightly smaller font size */
  font-weight: 300;  /* semi-bold font weight */
}

.expertise-boxes .box:hover {
  background-color: #e0e0e0;  /* change background on hover */
  box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.2);  /* enhance shadow on hover */
}

.expertise-boxes .box h3 {
  margin: 0;
  font-size: 1.1rem;  /* slightly smaller font size */
  color: #333;  /* dark text color */
  font-weight: 400;  /* semi-bold font weight */
}

/* Styling the scrolling logos */
.scrolling-logos {
  width: 100%;
  overflow: hidden;  /* Hide the overflow */
  margin-top: 50px;  /* Space from the boxes */
}

.logo-container {
  display: flex;
  animation: scroll 35s linear infinite;  /* Slower scrolling animation */
}

.logo-container img {
  max-width: 150px; /* Set the maximum width for all logos */
  max-height: 100px; /* Set the maximum height for all logos */
  margin-right: 50px; /* Space between logos */
  object-fit: contain; /* Maintain aspect ratio and ensure logos fit */
}

/* Keyframes for the scrolling */
@keyframes scroll {
  0% {
    transform: translateX(30%);  /* Start off-screen */
  }
  100% {
    transform: translateX(-250%);  /* End off-screen */
  }
}
</style>

<!-- Career Timeline/Milestones Section -->
<div class="career-timeline">
  <h2>Career Milestones</h2>
  <div class="timeline-item">
    <div class="timeline-date">2024</div>
    <div class="timeline-content">
      <h3>Founded Environmental Consulting Firm</h3>
      <p>Established a consultancy specializing in Life Cycle Assessment and environmental advisory services.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2020</div>
    <div class="timeline-content">
      <h3>Earned PhD in Environmental Science</h3>
      <p>Completed a doctorate focusing on sustainable product systems and LCA methodologies.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2015</div>
    <div class="timeline-content">
      <h3>Became a Registered Environmental Practitioner</h3>
      <p>Recognized as a professional with expertise in environmental planning and strategy.</p>
    </div>
  </div>
</div>

<style>
/* Styling the Career Timeline */
.career-timeline {
  margin-top: 50px;
  padding: 20px;
  background-color: #f9f9f9;
  border-radius: 8px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
}

.career-timeline h2 {
  text-align: center;
  color: #B8860B; /* Matches your dark gold theme */
  margin-bottom: 20px;
}

.timeline-item {
  display: flex;
  margin-bottom: 20px;
}

.timeline-date {
  font-size: 1.2rem;
  font-weight: bold;
  color: #4A90E2; /* Matches your blue-green theme */
  margin-right: 20px;
  flex-shrink: 0;
}

.timeline-content {
  background-color: #ffffff;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
}

.timeline-content h3 {
  margin: 0 0 10px;
  font-size: 1.1rem;
  color: #333;
}

.timeline-content p {
  margin: 0;
  font-size: 0.95rem;
  color: #555;
}
</style>

