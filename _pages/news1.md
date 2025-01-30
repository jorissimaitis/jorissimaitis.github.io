---
layout: default
permalink: /news/
title: Communications
nav: true
nav_order: 4
---

<h2>Latest News</h2>
<p>Publications, conferences, talks, and more</p>

<div class="news-cards">

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/wind.jpg" alt="New decarbonisation pathways in LCA" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Introducing global decarbonisation pathways to LCA</h3>
      <h4>Publication - Jan 2025</h4>
      <p>We published a study in Renewable and Sustainable Energy Reviews (IF 16.8). Future decarbonisation scenarios from an integrated assessment model – TIAM-UCL – are introduced into Premise, a software helping to conduct prospective LCA (pLCA). The study conducts a pLCA on scenarios decarbonising the global electricity supply, finding several environmental co-benefits and trade-offs. Full link: https://doi.org/10.1016/j.rser.2024.115298</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/setac.jpg" alt="SETAC Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Future carbon footprints of passenger cars</h3>
      <h4>Conference Presentation - Oct 2024</h4>
      <p>I presented research from an upcoming study at SETAC Europe 26th LCA Symposium, Gothenburg, Sweden. Early findings reveal that across many types of passenger cars, battery electric vehicles consistently deliver the lowest carbon footprints, now and in the future. This is because projected electricity decarbonisation significantly outweighs the decarbonisation of alternatives such as liquid fuels and hydrogen.</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/ev.jpg" alt="SETAC Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>EU batteries carbon footprint methodology</h3>
      <h4>Public feedback - April 2024</h4>
      <p> I provided feedback on the EU battery carbon footprint methodology, recommending clearer guidelines, standardized reporting, and improved lifecycle assessment processes. It highlights issues with data sources, energy use, recycling assumptions, and potential policy impacts on battery manufacturing and sustainability. Full link: https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/13877-Batteries-for-electric-vehicles-carbon-footprint-methodology/F3466688_en
</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/fpc.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Net zero futures in life cycle assessment of passenger cars</h3>
      <h4>Conference Presentation - Feb 2024</h4>
      <p>I presented research from an upcoming study at the Future Propulsion Conference, Solihull, UK. Initial results indicate that among various passenger car types, battery electric vehicles (BEVs) consistently exhibit the smallest carbon footprint in current and future systems. This advantage stems from the expected shift towards cleaner electricity, which outpaces emission reductions in hydrogen and liquid fuel alternatives.</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/banes.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Pioneering net zero construction policy in Bath & North East Somerset</h3>
      <h4>Publication - Oct 2023</h4>
      <p>We published a report that examines the impact of local net-zero construction policy on industry. Findings show mixed compliance, challenges in renewable energy integration, cost concerns, and the need for clearer guidance. The study highlights lessons for future sustainable construction policies. Full link: 10.15125/BATHRO-297388880</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/leiden.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Future environmental impacts of passenger vehicles</h3>
      <h4>Conference Presentation - Jul 2023</h4>
      <p>I presented early research results at the 11th International Conference on Industrial Ecology, Leiden, Netherlands. This focussed on showing novel prospective LCA methods for passenger cars that time-adjusted for various future scenarios in energy development.</p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/battery.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Are future recycling benefits misleading? Prospective life cycle assessment of lithium‐ion batteries.</h3>
      <h4>Publication - June 2023</h4>
      <p>We published a research article in the Journal of Industrial Ecology (IF 7.0). A prospective LCA considered future electricity scenarios to assess current and future carbon footprints of lithium-ion battery production and recycling. A key finding was that future recycling benefits can overestimated, highlighting that decarbonizing production is most crucial for reducing environmental impacts. Full link: https://doi.org/10.1111/jiec.13413 </p>
    </div>
  </div>

  <div class="news-item">
    <div class="news-image">
      <img src="/assets/img/iet.jpg" alt="Net Zero Futures Conference" onclick="expandImage(this)" />
    </div>
    <div class="news-text">
      <h3>Are electric vehicles as green as we think?</h3>
      <h4>Key note lecture - November 2022</h4>
      <p>I was invited to give a key note lecture by the Institute of Engineering and Technology, Bath, UK, on the sustainability of electric vehicles. The full lecture can be found here: https://www.youtube.com/watch?v=OT3wfBBoMAU&t=871s</p>
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
  /* General news container */
  .news-cards {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Space between news items */
    margin-top: 20px;
  }

  /* Individual news item */
  .news-item {
    display: flex;
    align-items: flex-start;
    gap: 20px; /* Space between image and text */
  }

  .news-image img {
      width: 100%;
      max-width: 300px; /* Set consistent width */
      aspect-ratio: 3 / 2; /* Enforces a 3:2 landscape ratio */
      object-fit: cover; /* Crops images to fit the ratio */
      cursor: pointer;
      border-radius: 8px; /* Slightly rounded corners */
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Small shadow */
      transition: box-shadow 0.3s ease, transform 0.3s ease; /* Smooth transition */
  }

  .news-image img:hover {
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* Deeper shadow on hover */
      transform: translateY(-2px); /* Slight lift effect on hover */
  }

  /* Text content styling */
  .news-text {
    flex: 1; /* Take remaining space */
    text-align: left;
  }

  .news-text h3 {
    font-size: 1.2rem;
    margin: 0 0 5px 0;
    color: #b8860b; /* Gold color for headings */
  }

  .news-text h4 {
    font-size: 1rem;
    margin: 0 0 10px 0;
    color: #666;
    font-style: italic;
  }

  .news-text p {
    font-size: 0.9rem;
    color: #333;
    margin: 0;
  }

  /* Overlay for expanded images */
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
    z-index: 9999;
  }

  .overlay img {
    max-width: 90%;
    max-height: 90%;
  }

  /* Mobile responsiveness */
  @media (max-width: 768px) {
    .news-item {
      flex-direction: column;
      align-items: center;
    }

    .news-image img {
      max-width: 100%; /* Full width for smaller screens */
    }
  }
</style>
