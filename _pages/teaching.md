---
layout: default
permalink: /lcacourse/
title: Online Course
description: Master the principles of Life Cycle Assessment (LCA) with this hands-on course and build your first LCA model using basic tools.
nav: true
nav_order: 5
---

<div style="max-width: 800px; margin: 0 auto; text-align: left;">
  <h1 style="font-size: 2rem;">Life Cycle Assessment (LCA): From Zero to Hero</h1>
  <p style="font-size: 1.2rem;">Master LCA principles, practice with case-studies, and build your first LCA model without expensive software!</p>
  
  <div class="project-grid">
    <!-- Thumbnail Image -->
    <div class="project-card" id="lcacourse">
      <img src="/assets/img/thumbnail.jpg" alt="Life Cycle Assessment Course" class="thumbnail" onclick="expandImage(this)">
    </div>
  
    <!-- Course Description -->
    <div class="course-description">
      <h3>Course Description</h3>
      <p>In this hands-on course, you'll learn core LCA principles aligned with ISO standards. You'll gain practical experience by building your first LCA model with Microsoft Excel or Google Sheets. This course includes case studies and quizzes to help reinforce your learning and prepare you for real-world LCA practice. You can access this course on Udemy using the link below.</p>

    <p>https://www.udemy.com/course/life-cycle-assessment-lca-from-zero-to-hero/?referralCode=A0235E47FBC523F74CED </p>
    </div>
  </div>
</div>

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
  .project-grid {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
  }

  .thumbnail {
    width: 100%;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    cursor: pointer;
    transition: box-shadow 0.3s ease, transform 0.3s ease;
  }

  .thumbnail:hover {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
    transform: scale(1.05);
  }

  .course-description {
    margin-top: 20px;
    font-size: 1rem;
    text-align: left;
  }

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
</style>