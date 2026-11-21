<img align="right" width="150" src="assets/profile.png" alt="Sravan Gogineni" />

# Sravan Gogineni

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=1000&color=1F6FEB&vCenter=true&width=600&lines=Engineer+%26+big-data+enthusiast;Streaming+%7C+Airflow+%7C+Spark+%7C+BigQuery;Building+reliable+data+systems+end+to+end)](https://github.com/Sravan-Gogineni)

**Engineer** · tech enthusiast with a deep interest in big data systems.

I build software end to end — from distributed ingestion and real-time streaming to warehouse migrations, orchestration, analytics, and applied ML/LLM systems. I'm happiest around large-scale data: how it moves, where it lives, and how to make it fast. M.S. in Data Science, always chasing the next thing to learn and build.

*Currently exploring — streaming architectures, data-lakehouse design, and LLM/RAG systems.*

📍 Scottsdale, AZ · 📨 [sravangogineni19@gmail.com](mailto:sravangogineni19@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/sravan-gogineni)

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

- **Languages** — Python, SQL, Java, R
- **Data & Orchestration** — Apache Airflow, Spark, Dataflow, Pub/Sub, MQTT
- **Cloud** — AWS (S3, Lambda, EC2, Glue, EMR, RDS), GCP (BigQuery, Dataflow, Pub/Sub)
- **Databases** — PostgreSQL, MySQL, MongoDB
- **Analytics & ML** — Power BI, Tableau, TensorFlow, RAG / LLM pipelines

---

## Featured Projects

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/Sravan-Gogineni/Helsinki-Publi-Transport-App">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sravan-Gogineni&repo=Helsinki-Publi-Transport-App&theme=github_dark&hide_border=true" alt="Helsinki Real-Time Transit Streaming" />
      </a>
    </td>
    <td width="50%">
      <a href="https://github.com/Sravan-Gogineni/HFP-Backend-Microservice">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sravan-Gogineni&repo=HFP-Backend-Microservice&theme=github_dark&hide_border=true" alt="HFP Backend Microservice" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <a href="https://github.com/Sravan-Gogineni/job_insights">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sravan-Gogineni&repo=job_insights&theme=github_dark&hide_border=true" alt="Job Market Insights" />
      </a>
    </td>
    <td width="50%"></td>
  </tr>
</table>

**🚍 Helsinki Real-Time Transit Streaming** — live public-transport pipeline on GCP: a Java microservice on **Dataflow** streams high-frequency vehicle positions from a public **MQTT** broker into **Pub/Sub** for downstream processing.
`Java · Dataflow · Pub/Sub · MQTT`

**🔎 Job Market Insights** — scrapes and analyzes job-posting data for market trends, paired with an email-based application tracker.
`Python · Scraping · Analytics`

Also built (private): **RAG systems** (research-paper retrieval + a grad-app chatbot), an **Airflow visa-analytics pipeline**, and a **university course-recommendation engine**.

---

## How I Build Data Pipelines

```mermaid
flowchart LR
    A[Events / IoT] --> B[(MQTT Broker)]
    B --> C[Microservice<br/>on Dataflow]
    C --> D[(Pub/Sub)]
    D --> E[Stream Processing]
    E --> Q{Data Quality}
    Q -->|pass| F[(Lakehouse<br/>Bronze → Silver → Gold)]
    Q -->|fail| X[(Dead-letter)]
    F --> G[Transforms / dbt]
    G --> H[(BigQuery)]
    H --> I[Dashboards & ML]
    AF[[Airflow]] -. orchestrates .-> E
    AF -. orchestrates .-> G
```

---

## Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sravan-Gogineni/Sravan-Gogineni/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sravan-Gogineni/Sravan-Gogineni/output/github-contribution-grid-snake.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/Sravan-Gogineni/Sravan-Gogineni/output/github-contribution-grid-snake.svg" />
</picture>

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sravan-gogineni)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sravangogineni19@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/u/Sravan_chowdary/)

Always happy to talk data engineering, streaming systems, and applied ML — feel free to reach out.
