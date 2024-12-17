---
layout: default
permalink: /news/
title: News
nav: true
nav_order: 4
---

<h2>Latest News</h2>
<p>Stay up to date with the latest updates and insights on Life Cycle Assessment, Critical Review, and our advisory services.</p>

<div class="news-cards">
  <div class="card">
    <div class="card-content">
      <div class="card-image">
        <img src="/assets/img/car.jpg" alt="Life Cycle Assessment in Action" onclick="expandImage(this)" />
      </div>
      <div class="card-text">
        <h3>Future carbon footprints of passenger cars</h3>
        <h4>Publication - Feb 2025</h4>
        <p>Battery electric vehicles consistently show the lowest carbon footprints among passenger cars now and in the future.</p>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-content">
      <div class="card-image">
        <img src="/assets/img/wind.jpg" alt="New decarbonisation pathways in LCA" onclick="expandImage(this)" />
      </div>
      <div class="card-text">
        <h3>New decarbonisation pathways in LCA</h3>
        <h4>Publication - Jan 2025</h4>
        <p>Decarbonising global electricity reduces carbon emissions and pollution but may increase resource use and land impacts.</p>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-content">
      <div class="card-image">
        <img src="/assets/img/setac.jpg" alt="SETAC Conference" onclick="expandImage(this)" />
      </div>
      <div class="card-text">
        <h3>Future carbon footprints of passenger cars</h3>
        <h4>Conference Presentation - Oct 2024</h4>
        <p>SETAC Europe 26th LCA Symposium, Gothenburg, Sweden.</p>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="card-content">
      <div class="card-image">
        <img src="/assets/img/fpc.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
      </div>
      <div class="card-text">
        <h3>Net zero futures in life cycle assessment of passenger cars</h3>
        <h4>Conference Presentation - Feb 2024</h4>
        <p>Future Propulsion Conference, Solihull, UK.</p>
      </div>
    </div>
  </div>
</div>

<!-- Optional JavaScript for Image Expansion -->
<script>
  function expandImage(img) {
    const expandedImg = document.createElement('div');
    expandedImg.innerHTML = `
      <div class="overlay" onclick="this.remove()">
        <img src="${img.src}" alt="Expanded Image" />
      </div>
    `;
    document.body.appendChild(expandedImg);
  }
</script>

<style>
  /* General container for news cards */
  .news-cards {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Spacing between rows */
    margin-top: 20px;
  }

  /* Card structure */
  .card {
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    overflow: hidden;
    display: flex;
    align-items: center;
    transition: box-shadow 0.3s ease;
  }

  .card:hover {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }

  /* Image container */
  .card-image {
    flex: 1;
    cursor: pointer;
  }

  .card-image img {
    width: 100%;
    height: 150px;
    object-fit: cover;
  }

  /* Text container */
  .card-text {
    flex: 2;
    padding: 15px;
    text-align: left;
  }

  .card h3 {
    font-size: 1.2rem;
    margin: 0 0 5px 0;
    color: #b8860b; /* Gold color */
  }

  .card h4 {
    font-size: 1rem;
    margin: 0 0 10px 0;
    color: #666;
    font-style: italic;
  }

  .card p {
    font-size: 0.9rem;
    color: #333;
    margin: 0;
  }

  /* Expanded image overlay */
  .overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
  }

  .overlay img {
    max-width: 90%;
    max-height: 90%;
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .card {
      flex-direction: column;
      align-items: flex-start;
    }

    .card-image img {
      height: 120px;
    }
  }
</style>
