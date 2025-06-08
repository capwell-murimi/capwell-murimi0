---
layout: collection
permalink: /projects/
title: Projects
collection: projects # You'll need to create a _projects collection in your root directory
author_profile: true
---

Browse through my projects below.

<style>
.project-card {
  display: flex;
  align-items: center;
  gap: 20px;
  border: 1px solid #eee;
  border-radius: 12px;
  margin-bottom: 32px;
  padding: 18px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.04);
  transition: transform 0.2s, box-shadow 0.2s;
  background: #fafbfc;
}
.project-card:hover {
  transform: scale(1.03) translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.10);
  background: #f0f8ff;
}
.project-preview {
  width: 120px;
  height: 80px;
  object-fit: cover;
  border-radius: 8px;
  transition: box-shadow 0.2s;
  box-shadow: 0 1px 4px rgba(0,0,0,0.08);
}
.project-info {
  flex: 1;
}
.project-title {
  margin: 0;
  font-size: 1.2em;
  font-weight: bold;
}
.project-link {
  display: inline-block;
  margin-top: 8px;
  color: #2678c8;
  text-decoration: underline;
  font-weight: 500;
  transition: color 0.2s;
}
.project-link:hover {
  color: #d65a31;
}
</style>

<div class="project-card">
  <img class="project-preview" src="https://placehold.co/120x80?text=Scraping" alt="Data Scraping Preview">
  <div class="project-info">
    <p class="project-title">Data Scraping Project</p>
    <p>My first project involved scraping data from a single web page.</p>
    <p><strong>Technologies:</strong> Beautiful Soup, Requests, Pandas</p>
    <a class="project-link" href="https://github.com/yourusername/data-scraping-project" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://placehold.co/120x80?text=Wrangling" alt="Data Wrangling Preview">
  <div class="project-info">
    <p class="project-title">Data Wrangling Project</p>
    <p>My second project focused on cleaning and transforming data using Python.</p>
    <p><strong>Technologies:</strong> Python</p>
    <a class="project-link" href="https://github.com/yourusername/data-wrangling-project" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://placehold.co/120x80?text=EDA" alt="EDA Preview">
  <div class="project-info">
    <p class="project-title">Exploratory Data Analysis (EDA) Project</p>
    <p>My third project was performing exploratory data analysis using Python.</p>
    <p><strong>Technologies:</strong> Python</p>
    <a class="project-link" href="https://github.com/yourusername/eda-project" target="_blank">View Code</a>
  </div>
</div>
