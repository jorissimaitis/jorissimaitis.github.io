---
layout: about
title: about
permalink: /
subtitle: <strong>LCA Consultant - PhD, PIEMA, REnvP</strong> #<a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: lright
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

<p style="font-size: 1.1rem;">Tailored solutions to measure and minimise the environmental impacts of products and services across their entire life cycle.</p>

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

<style>
/* Styling the boxes */
.expertise-boxes {
  display: flex;
  justify-content: space-between;
  gap: 20px;  /* space between the boxes */
  margin-top: 30px; /* space from the paragraph */
}

.expertise-boxes .box {
  background-color: #f5f5f5;  /* light gray background */
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  flex: 1;  /* make boxes expand equally */
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;  /* smooth transition for hover effect */
}

.expertise-boxes .box a {
  text-decoration: none;
  color: #333;  /* dark text */
  font-size: 1.2rem;  /* slightly larger font size */
  font-weight: bold;
}

.expertise-boxes .box:hover {
  background-color: #e0e0e0;  /* change background on hover */
  box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.2);  /* enhance shadow on hover */
}

.expertise-boxes .box h3 {
  margin: 0;
  font-size: 1.5rem;  /* make the text larger */
  color: #333;  /* dark text color */
  font-weight: bold;
}

@media (max-width: 768px) {
  /* Stack the boxes on mobile */
  .expertise-boxes {
    display: grid;
    grid-template-columns: 1fr;  /* make it one column on small screens */
  }
}
</style>
