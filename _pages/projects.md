---
title: "Projects"
layout: single
permalink: /projects/
author_profile: true
classes: wide
---

Here are some of the projects I've worked on:

<style>
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 24px;
    margin-top: 30px;
  }

  .project-card {
    display: flex;
    flex-direction: column;
    background-color: var(--card-bg, #1e1e1e);
    color: var(--card-text, #e0e0e0);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0,0,0,0.5);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .project-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.7);
  }

  .project-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    /* background-color: #000; */
  }

  .project-card-content {
    padding: 16px;
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .project-card h3 {
    margin: 0;
    font-size: 1.2em;
  }

  .project-card a {
    text-decoration: none;
    color: var(--card-link, #8ab4f8);
  }

  .project-card a:hover {
    color: var(--card-link-hover, #4f9df8);
  }

  .project-card p {
    font-size: 0.95em;
    margin: 0;
    color: var(--card-desc, #ccc);
  }
</style>

<div class="project-grid">

  <div class="project-card">
    <img src="https://github.com/pacslab/adapTrain/raw/main/docs/adaptrain-logo.webp" alt="AdapTrain">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/adaptive-ist">AdapTrain</a></h3>
      <p>An adaptive lightweight framework for heterogeneity-aware independent subnet training (IST)</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/stage.png" alt="Stage">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/Stage">Stage</a></h3>
      <p>An Android social platform for movie and series enthusiasts written in Kotlin</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/library.png" alt="Library Management System">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/LibraryManagementSystem">Library Management System</a></h3>
      <p>A backend for managing library operations using ExpressJS and PostgreSQL.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/shop.png" alt="Online Shop">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/online-shop">Online Shop</a></h3>
      <p>A full-stack e-commerce platform with product browsing, cart, and checkout features.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/jtanks.png" alt="JTanks">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/jtanks">JTanks</a></h3>
      <p>A multiplayer 2D tank battle game written in Java.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/search-engine.png" alt="Search Engine">
    <div class="project-card-content">
      <h3><a href="https://github.com/mh-naderi/search-engine-c">C-earch Engine</a></h3>
      <p>A query processing tool for searching logical term combinations across text files written in C.</p>
    </div>
  </div>
  <!-- Add more cards as needed -->

</div>