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
      <h3><a href="https://github.com/pacslab/adapTrain">AdapTrain</a></h3>
      <p>This is a short description of the project. It explains what the repo is about in a few sentences.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/stage.png" alt="Stage">
    <div class="project-card-content">
      <h3><a href="https://github.com/mhnaderi99/Stage">Stage</a></h3>
      <p>This is another project you want to showcase, with a description and GitHub link.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/library.png" alt="Library Management System">
    <div class="project-card-content">
      <h3><a href="https://github.com/mhnaderi99/LibraryManagementSystem">Library Management System</a></h3>
      <p>This is another project you want to showcase, with a description and GitHub link.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/shop.png" alt="Online Shop">
    <div class="project-card-content">
      <h3><a href="https://github.com/mhnaderi99/online-shop">Online Shop</a></h3>
      <p>This is another project you want to showcase, with a description and GitHub link.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/jtanks.png" alt="JTanks">
    <div class="project-card-content">
      <h3><a href="https://github.com/mhnaderi99/jtanks">JTanks</a></h3>
      <p>This is another project you want to showcase, with a description and GitHub link.</p>
    </div>
  </div>

  <div class="project-card">
    <img src="/assets/images/projects/search-engine.png" alt="Search Engine">
    <div class="project-card-content">
      <h3><a href="https://github.com/mhnaderi99/search-engine-c">C-earch Engine</a></h3>
      <p>This is another project you want to showcase, with a description and GitHub link.</p>
    </div>
  </div>
  <!-- Add more cards as needed -->

</div>