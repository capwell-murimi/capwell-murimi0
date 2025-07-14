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
.project-section {
  margin: 0.45em 0;
  line-height: 1.5;
}
.project-label {
  font-weight: bold;
  border-radius: 4px;
  padding: 0.1em 0.5em;
  margin-right: 0.45em;
}
.problem-label { background: #1a7cff33; color: #00e8c4; }
.approach-label { background: #36a7ff33; color: #36a7ff; }
.tools-label { background: #ffba0833; color: #ffba08; }
.result-label { background: #ff5e5b22; color: #ff5e5b; }
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
  <img class="project-preview" src="https://images.unsplash.com/photo-1504639725590-34d0984388bd?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="MLOps Project preview" />
  <div class="project-info">
    <p class="project-title">MLOps: KNN Model Deployment</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Bridging the gap between model development and scalable, production-ready deployment for machine learning solutions.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Developed a KNN classification model and deployed it as a RESTful API using best practices in MLOps, enabling seamless integration with production systems.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Python, scikit-learn, Flask, Google Colab, Docker, GitHub Actions</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>End-to-end workflow: from model training (<a href="https://colab.research.google.com/drive/1VAutBx5ju4_x3qj0ofB7wVvS4kbrI1vI?usp=sharing" target="_blank">Colab Notebook</a>) to API deployment (<a href="https://github.com/capwell-murimi/KNN_model_API.git" target="_blank">API Code</a>), showcasing automation and reproducibility.</div>
    <a class="project-link" href="https://github.com/capwell-murimi/KNN_model_API.git" target="_blank">View API Code</a>
    <a class="project-link" href="https://colab.research.google.com/drive/1VAutBx5ju4_x3qj0ofB7wVvS4kbrI1vI?usp=sharing" target="_blank">View Model Notebook</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1674476459435-92fa2ab3ac04?q=80&w=880&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Linear Regression Project preview" />
  <div class="project-info">
    <p class="project-title">Linear Regression Analysis</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Need to predict numerical values and understand relationships between variables in a dataset.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Applied linear regression modeling to real-world data, visualizing trends and evaluating model performance using statistical metrics.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Python, scikit-learn, Pandas, Matplotlib</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Built an interpretable predictive model and generated visual insights, demonstrating foundational data science techniques.</div>
    <a class="project-link" href="https://colab.research.google.com/drive/10PQGfLbKVuuhbbq-aHdtEhQtVaof-GM4?usp=sharing" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1523961131990-5ea7c61b2107?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Data Scraping Project preview" />
  <div class="project-info">
    <p class="project-title">Data Scraping Project</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Manual data collection from websites was time-consuming and error-prone.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Built Python scripts using Beautiful Soup and Requests to automate extraction of tabular web data, saving to structured CSV files for analysis.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Beautiful Soup, Requests, Pandas</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Reduced data collection time by 80%; datasets were ready for immediate analytics use.</div>
    <a class="project-link" href="https://colab.research.google.com/drive/1O6ZkB5XcXt1ALwwNA4dhEw2FwGZbnoLx?usp=sharing" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1621955964441-c173e01c135b?q=80&w=2086&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Data Wrangling Project preview" />
  <div class="project-info">
    <p class="project-title">Data Wrangling Project (Netflix Dataset)</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Raw Netflix data was inconsistent, messy, and unsuitable for analysis.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Designed data cleaning and transformation pipelines to handle missing values, normalize columns, and validate data integrity.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Python</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Produced a high-quality dataset ready for exploratory and predictive analytics, improving downstream data project outcomes.</div>
    <a class="project-link" href="https://www.kaggle.com/code/capwellmurimi/data-wrangling-netflix" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1561625116-df74735458a5?q=80&w=2074&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Titanic EDA Project preview" />
  <div class="project-info">
    <p class="project-title">Exploratory Data Analysis Project (Titanic Dataset)</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Lack of actionable insights from historical passenger data limited business strategy formation.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Used Pandas, Matplotlib, and Seaborn to visualize distributions, correlations, and survival factors, uncovering trends in the dataset.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Pandas, Matplotlib, Seaborn</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Identified key predictors of survival and presented actionable recommendations for similar transport scenarios.</div>
    <a class="project-link" href="https://www.kaggle.com/code/capwellmurimi/titanic-eda" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="/assets/images/dashboard.png" alt="Power BI Hotel Dashboard Project preview" />
  <div class="project-info">
    <p class="project-title">Power BI Hotel Dashboard</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Hotel managers needed real-time visibility into key business metrics but were bogged down by static reports.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Designed and implemented an interactive Power BI dashboard to visualize occupancy, revenue, and guest trends.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Power BI</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Enabled data-driven decisions and increased operational efficiency for hotel management.</div>
    <a class="project-link" href="https://drive.google.com/drive/folders/1QJVILO4gPyY9POEoFYBTBFj_tmWnvzRx" target="_blank">View Code</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="/assets/images/HR.png" alt="Tableau HR Dashboard preview" />
  <div class="project-info">
    <p class="project-title">Tableau HR Dashboard</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>HR teams struggled to visualize and track employee metrics, leading to inefficient decision-making.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Developed an interactive Tableau dashboard displaying employee demographics, turnover rates, and key HR KPIs for actionable insights.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Tableau</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Empowered HR departments with real-time analytics and improved workforce planning.</div>
    <a class="project-link" href="https://public.tableau.com/views/HRDashboard_17500918044660/HRSummary?:language=en-US&publish=yes&:sid=1FD192C878D84B8EB2FF575B28ED0DA2-0:0&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank">View Dashboard</a>
  </div>
</div>

<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1974&auto=format&fit=crop" alt="Kai and Karo Scraper Project preview" />
  <div class="project-info">
    <p class="project-title">Kai & Karo Vehicle Scraper</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Vehicle data on the Kai and Karo website was not easily accessible in bulk for analysis.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Automated web scraping to extract vehicle listings, including price, make, year, and transmission, across multiple pages.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Python, Beautiful Soup, Requests, Pandas</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Collected a complete dataset for analysis and market research, demonstrating scalable scraping techniques.</div>
    <a class="project-link" href="https://colab.research.google.com/drive/1Q56xu_3H9Kcf8lYfCl7lnPK9nLeYA3uY?usp=sharing" target="_blank">View Code</a>
  </div>
</div>



<div class="project-card">
  <img class="project-preview" src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?q=80&w=465&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Classification Models Project preview" />
  <div class="project-info">
    <p class="project-title">Classification Models</p>
    <div class="project-section"><span class="project-label problem-label">Problem:</span>Needed to accurately categorize data points into distinct classes for predictive analysis.</div>
    <div class="project-section"><span class="project-label approach-label">Approach:</span>Developed and compared multiple classification algorithms (e.g., Logistic Regression, Decision Trees, Random Forests) to determine the most effective model.</div>
    <div class="project-section"><span class="project-label tools-label">Tools:</span>Python, scikit-learn, Pandas, Matplotlib</div>
    <div class="project-section"><span class="project-label result-label">Result:</span>Achieved high accuracy in classifying data and provided interpretable results for further decision-making.</div>
    <a class="project-link" href="https://colab.research.google.com/drive/18mNog6qU3IxcGB3kyS6U-L1BU5Ps5y_C?usp=sharing" target="_blank">View Code</a>
  </div>
</div>

</div>
