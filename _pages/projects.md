---
layout: collection
permalink: /projects/
title: Projects
collection: projects
author_profile: true
---

<style>
.projects-container {
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
  justify-content: flex-start;
}
.project-card {
  background: #181818;
  color: #f2f2f2;
  border-radius: 18px;
  box-shadow: 0 2px 12px #222;
  width: 350px;
  overflow: hidden;
  transition: transform 0.25s cubic-bezier(.4,2,.6,.8), box-shadow 0.25s;
  margin-bottom: 1.8em;
  display: flex;
  flex-direction: column;
}
.project-card:hover {
  transform: scale(1.045) rotate(-1deg);
  box-shadow: 0 8px 28px #0af6ff44;
}
.project-preview {
  width: 100%;
  height: 185px;
  object-fit: cover;
  border-bottom: 2px solid #36a7ff;
  transition: filter 0.25s;
}
.project-card:hover .project-preview {
  filter: brightness(1.12) contrast(1.1) saturate(1.2);
}
.project-info {
  padding: 1.2em 1.4em 1.4em 1.4em;
  flex: 1;
}
.project-title {
  font-size: 1.25em;
  font-weight: bold;
  color: #36a7ff;
  margin-bottom: 0.25em;
}
.project-link {
  display: inline-block;
  margin-top: 0.7em;
  color: #181818;
  background: linear-gradient(90deg, #36a7ff, #00e8c4);
  padding: 0.42em 1.05em;
  border-radius: 6px;
  font-weight: bold;
  text-decoration: none;
  transition: background 0.25s, color 0.25s;
}
.project-link:hover {
  background: #00e8c4;
  color: #181818;
}
@media (max-width: 800px) {
  .projects-container { flex-direction: column; align-items: center; }
  .project-card { width: 98vw; }
}
</style>

Browse through my projects below.

<div class="projects-container">

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1523961131990-5ea7c61b2107?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Data Scraping Project preview" />
  <div class="project-info">
    <p class="project-title">Data Scraping Project</p>
    <p>Automated extraction of tabular web data into structured formats for fast analysis, using Python’s web scraping stack.</p>
    <p><strong>Technologies:</strong> Beautiful Soup, Requests, Pandas</p>
    <a class="project-link" href="https://github.com/capwell-murimi/data-scraping-project" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1621955964441-c173e01c135b?q=80&w=2086&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Data Wrangling Project preview" />
  <div class="project-info">
    <p class="project-title">Data Wrangling Project</p>
    <p>Cleaned, transformed, and validated raw data sets to prepare for analysis—ensuring data quality and consistency for downstream tasks.</p>
    <p><strong>Technologies:</strong> Python</p>
    <a class="project-link" href="https://github.com/capwell-murimi/data-wrangling-project" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://plus.unsplash.com/premium_photo-1720091339077-d0f56397a0c9?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="EDA Project preview" />
  <div class="project-info">
    <p class="project-title">Exploratory Data Analysis Project</p>
    <p>Explored complex data sets using visualization and statistics to uncover actionable insights and trends for business strategies.</p>
    <p><strong>Technologies:</strong> Pandas, Matplotlib, Seaborn</p>
    <a class="project-link" href="https://github.com/capwell-murimi/eda-project" target="_blank">View Code</a>
  </div>
</div>

</div>
