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

  .lca-box {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
    background-color: #f9f9f9;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
  }

  .lca-box:hover {
    transform: scale(1.02);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
    background-color: #fff8e1; /* Super light gold color */
  }

  .lca-box h3 {
    margin-top: 0;
    color: #333;
    font-size: 1.25em;
  }

  .lca-box p {
    margin: 10px 0;
    color: #555;
    font-size: 1em;
    line-height: 1.6;
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
    <div class="lca-box">
      <h3>Compliance LCA</h3>
      <p>Designed to meet the highest standards (e.g., ISO 14040/14044) and regulations (e.g., EU product carbon footprint). This includes strict data requirements, comprehensive reporting, and external critical review by experts. Ideal for meeting regulatory requirements, public disclosure, and making comparative assertions.</p>
    </div>

    <div class="lca-box">
      <h3>Operational LCA</h3>
      <p>Provides flexibility for data requirements and reporting while following top standards and frameworks. No external critical review, enabling faster delivery. Ideal for internal purposes, environmental insights, and as a foundation for Compliance LCA if needed.</p>
    </div>

    <div class="lca-box">
      <h3>Advanced Analysis and Tools</h3>
      <p>Bespoke carbon and environmental impact tools, tailored to your needs. Examples include simple spreadsheet-based calculators or advanced Python tools for product, supply-chain, and scenario analysis, such as carbon calculators based on product dimensions, transport modes, end-of-life treatments, and decarbonisation scenarios. </p>
    </div>

    <div class="lca-box">
      <h3>Environmental Impact Methods</h3>
      <p>Various impact methods from carbon footprinting (following the latest IPCC methodologies) to other impacts such as resource consumption, air pollution, toxicity, and land use.</p>
    </div>

    <div class="lca-box">
      <h3>Products and Services</h3>
      <p>LCAs can be conducted for a wide range of contexts, including consumer goods (e.g., t-shirts, chemical products), energy technologies (e.g., batteries, solar panels), construction materials, agricultural products (e.g., fertilizers), and more.</p>
    </div>
  </div>

  <!-- Service 2: Critical Review -->
  <div class="service">
    <img src="/assets/img/review.png" alt="Critical Review" />
    <h2>Critical Review</h2>
    <p>An independent and objective evaluation of LCA studies to ensure they meet ISO standards and accurately reflect the product or service's environmental impacts. I offer services to review and verify your LCA and methodology for internal or reporting purposes, and enhance the credibility and reliability of your results.</p>
  </div>

  <!-- Service 3: Advisory -->
  <div class="service">
    <img src="/assets/img/guide.png" alt="Advisory Services" />
    <h2>Advisory</h2>
    <p>I provide expert guidance on LCA and sustainability, offering support from initial steps to ongoing assistance after implementation. This applies not only to product and service sustainability but also to organization-wide strategies tailored to your business needs and software development.</p>
  </div>
</div>

<!-- Get in Touch Button -->
<div class="get-in-touch">
  <a href="/contact/">Get in Touch</a>
</div>
