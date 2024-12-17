---
layout: default
permalink: /news/
title: News
nav: true
nav_order: 4  # Adjust this to place the page in the desired order
---

<h2>Latest News</h2>
<p>Stay up to date with the latest updates and insights on Life Cycle Assessment, Critical Review, and our advisory services.</p>

<div class="news-cards">
  <div class="card">
    <img src="/assets/img/car.jpg" alt="Life Cycle Assessment in Action" />
    <h3>Future carbon footprints of passenger cars</h3>
    <h4>Publication - Feb 2025</h4> <!-- Subtitle -->
    <p>
      Battery electric vehicles consistently show the lowest carbon footprints among passenger cars now and in the future.
    </p>
    <a href="/news/lca-in-action" class="read-more">+</a>
  </div>

  <div class="card">
    <img src="/assets/img/wind.jpg" alt="Critical Review Services Expanded" />
    <h3>New decarbonisation pathways in LCA</h3>
    <h4>Publication - Jan 2025</h4> <!-- Subtitle -->
    <p>
      Decarbonising global electricity reduces carbon emissions and pollution but may increase resource use and land impacts.
    </p>
    <a href="/news/critical-review-expanded" class="read-more">+</a>
  </div>

  <div class="card">
    <img src="/assets/img/setac.jpg" alt="Sustainability Strategy Advisory" />
    <h3>Future carbon footprints of passenger cars</h3>
    <h4>Conference Presentation - Oct 2024</h4> <!-- Subtitle -->
    <p>
      SETAC Europe 26th LCA Symposium, Gothenburg, Sweden.
    </p>
    <a href="/news/sustainability-strategy" class="read-more">+</a>
  </div>

  <div class="card">
    <img src="/assets/img/fpc.jpg" alt="Global Expansion" />
    <h3>Net zero futures in life cycle assessment of passenger cars</h3>
    <h4>Conference Presentation - Feb 2024</h4> <!-- Subtitle -->
    <p>
      Future Propulsion Conference, Solihull, UK.
    </p>
    <a href="/news/global-expansion" class="read-more">+</a>
  </div>
</div>

<style>
  /* Container for the news cards */
  .news-cards {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Ensures two cards per row */
    gap: 20px; /* Space between cards */
    margin-top: 20px;
  }

  /* Individual card styling */
  .card {
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* Smooth hover animation */
  }

  .card img {
    width: 100%;
    height: 150px;
    object-fit: cover; /* Ensures image fills the space while maintaining aspect ratio */
    border-bottom: 3px solid #b8860b; /* Gold accent border below image */
  }

  .card h3 {
    font-size: 1.2rem;
    margin: 10px 0;
    color: #b8860b; /* Gold color for headings */
  }

  .card h4 {
    font-size: 1rem;
    margin: 5px 0 10px 0;
    color: #666; /* Neutral text for subtitles */
    font-style: italic;
  }

  .card p {
    font-size: 0.9rem;
    color: #333; /* Neutral text for description */
    margin: 10px 15px;
  }

  .card:hover {
    transform: translateY(-5px); /* Slight lift on hover */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* Stronger shadow on hover */
  }

  /* Read more link styling */
  .read-more {
    text-decoration: none;
    color: #b8860b; /* Gold color for links */
    font-weight: bold;
    margin-bottom: 10px;
    display: inline-block;
  }

  .read-more:hover {
    text-decoration: underline; /* Underline effect on hover */
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .news-cards {
      grid-template-columns: 1fr; /* One card per row on smaller screens */
    }
  }
</style>
