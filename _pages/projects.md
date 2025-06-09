---
layout: collection
permalink: /projects/
title: Projects
collection: projects
author_profile: true
---

<style>
/* Responsive, centered grid with spacious cards */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
  gap: 2em;
  margin: 2em auto;
  max-width: 1250px;
  padding: 0 2vw;
}

.project-card {
  background: #181818;
  color: #f2f2f2;
  border-radius: 18px;
  box-shadow: 0 2px 12px #222;
  overflow: hidden;
  transition: transform 0.25s cubic-bezier(.4,2,.6,.8), box-shadow 0.25s;
  display: flex;
  flex-direction: column;
  min-width: 0;
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
  display: flex;
  flex-direction: column;
  justify-content: space-between;
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

@media (max-width: 900px) {
  .projects-grid {
    grid-template-columns: 1fr 1fr;
    max-width: 98vw;
    padding: 0 1vw;
  }
}
@media (max-width: 600px) {
  .projects-grid {
    grid-template-columns: 1fr;
    max-width: 98vw;
    padding: 0 1vw;
  }
}
</style>

Browse through my projects below.

<div class="projects-grid">

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

<div class="project-card">
  <img class="project-preview" src="assets/images/dashboard.png" alt="Power BI Hotel Dashboard Project preview" />
  <div class="project-info">
    <p class="project-title">Power BI Hotel Dashboard</p>
    <p>Designed an interactive Business Intelligence dashboard for hotel management, delivering real-time insights on occupancy, revenue, and guest trends. Empowered hotel managers to make data-driven decisions with engaging visual analytics.</p>
    <p><strong>Technologies:</strong> Power BI</p>
     <a class="project-link" href="https://github.com/capwell-murimi/kai-karo-vehicle-scraper" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1974&auto=format&fit=crop" alt="Kai and Karo Scraper Project preview" />
  <div class="project-info">
    <p class="project-title">Kai & Karo Vehicle Scraper</p>
    <p>Scraped all vehicles listed on the Kai and Karo website, extracting price, make, year, and transmission mode (automatic/manual) for each vehicle. Learned to automate scraping across multiple pages for comprehensive data collection and market analysis.</p>
    <p><strong>Technologies:</strong> Python, Beautiful Soup, Requests, Pandas</p>
    <a class="project-link" href="https://github.com/capwell-murimi/kai-karo-vehicle-scraper" target="_blank">View Code</a>
  </div>
</div>
