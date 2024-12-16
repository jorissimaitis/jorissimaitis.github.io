---
layout: about
title: Home
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
    <a href="/services">
      <h3>Life Cycle Assessment</h3>
    </a>
  </div>

  <div class="box" id="review">
    <a href="/services">
      <h3>Critical Review</h3>
    </a>
  </div>

  <div class="box" id="advisory">
    <a href="/services">
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
    <img src="logo_pathways.png" alt="Pathways" />
    <img src="logo_carbongraph.png" alt="CG" />
    <img src="logo_relondon.png" alt="ReLondon" />
    <img src="logo_earthly.png" alt="Earthly" />
    <img src="logo_scholartribe.png" alt="ST" />
    <img src="logo_razbio.png" alt="Razbio" />
    <img src="logo_gc.png" alt="GW" />
    <img src="logo_banes.png" alt="Banes" />
  </div>
</div>

<!-- Metrics Section -->
<div class="metrics-section">
  <div class="metric">
    <h3>+15</h3>
    <p>Projects Delivered</p>
  </div>
  <div class="metric">
    <h3>+20</h3>
    <p>Partners</p>
  </div>
</div>


<style>
/* Styling the subtitle */
.custom-subtitle {
  color: #B8860B;  /* Example color (gold) */
}

/* Metrics Section Styling */
.metrics-section {
  display: flex; /* Keep metrics horizontally aligned */
  justify-content: space-around; /* Spread the metrics evenly */
  margin-top: 40px; /* Add more space above the metrics */
  margin-bottom: 20px; /* Add more space below if needed */
  text-align: center;
}

.metrics-section .metric {
  flex: 1; /* Ensure both metrics take equal width */
  margin: 0 10px; /* Space between metrics */
}

.metrics-section .metric h3 {
  margin: 0;
  font-size: 2.5rem; /* Slightly smaller than before */
  color: #B8860B; /* Gold color for emphasis */
  font-weight: bold; /* Make the number bold */
}

.metrics-section .metric p {
  margin: 5px 0 0;
  font-size: 1.5rem;
  color: #333; /* Neutral text color */
  font-weight: 600; /* Make the description semibold */
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
  background-color: #e0e0e0;  /* light gray background */
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
  background-color: #F7F1E1;  /* change background on hover */ 
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
    transform: translateX(-300%);  /* End off-screen */
  }
}
</style>
