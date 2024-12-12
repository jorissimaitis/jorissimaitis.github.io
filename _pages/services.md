---
layout: default
permalink: /services/
title: Services
nav: true
nav_order: 1  # Adjust this to place the page in the desired order
---

<style>
  .service {
    margin: 40px 0;
    padding: 20px 0;
    border-bottom: 1px solid #ddd;
    text-align: center;
  }

  .service img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .service img:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
  }

  .service h2 {
    margin: 10px 0;
    color: #333;
    font-size: 1.5em;
  }

  .service p {
    margin: 10px 0 0;
    line-height: 1.6;
    color: #555;
    font-size: 1em;
  }

  .get-in-touch {
    margin: 50px 0 20px;
    text-align: center;
  }

  .get-in-touch a {
    display: inline-block;
    padding: 15px 30px;
    font-size: 1.2em;
    font-weight: bold;
    text-decoration: none;
    color: #fff;
    background-color: #007BFF; /* Bootstrap Primary Blue */
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: background-color 0.3s ease, box-shadow 0.3s ease;
  }

  .get-in-touch a:hover {
    background-color: #0056b3; /* Darker Blue on Hover */
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
  }
</style>

<div class="services">
  <!-- Service 1: Life Cycle Assessment -->
  <div class="service">
    <img src="/assets/img/lca.png" alt="Life Cycle Assessment" />
    <h2>Life Cycle Assessment</h2>
    <p>
      Life Cycle Assessment (LCA) is a comprehensive method to evaluate the environmental impacts of products and services across their entire life cycle—from raw material extraction, manufacturing, distribution, use, to disposal or recycling. We provide tailored LCA solutions to help organizations minimize their environmental footprint and achieve sustainability goals.
    </p>
  </div>

  <!-- Service 2: Critical Review -->
  <div class="service">
    <img src="/assets/img/review.png" alt="Critical Review" />
    <h2>Critical Review</h2>
    <p>
      Critical Review is an independent and objective evaluation of LCA studies to ensure they meet ISO standards and accurately reflect the product or service's environmental impacts. Our expert team offers critical review services to enhance the credibility and reliability of your LCA results.
    </p>
  </div>

  <!-- Service 3: Advisory -->
  <div class="service">
    <img src="/assets/img/guide.png" alt="Advisory Services" />
    <h2>Advisory</h2>
    <p>
      Our advisory services are designed to guide organizations in making informed decisions on sustainability. Whether you're looking to reduce your environmental impacts, improve efficiency, or navigate environmental regulations, we provide expert advice tailored to your business's needs.
    </p>
  </div>
</div>

<!-- Get in Touch Button -->
<div class="get-in-touch">
  <a href="/contact/">Get in Touch</a>
</div>
