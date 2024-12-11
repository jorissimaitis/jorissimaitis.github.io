---
layout: about
title: About
permalink: /
subtitle: <strong class="custom-subtitle">LCA Consultant - PhD, PIEMA, REnvP</strong> #<a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
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
    <img src="1.png" alt="Logo 1" />
    <img src="logo2.png" alt="Logo 2" />
    <img src="logo3.png" alt="Logo 3" />
    <img src="logo4.png" alt="Logo 4" />
    <!-- Add more logos here -->
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
  animation: scroll 15s linear infinite;  /* Scroll animation */
}

.logo-container img {
  width: 150px;  /* Adjust logo size */
  margin-right: 50px;  /* Space between logos */
}

/* Keyframes for the scrolling
