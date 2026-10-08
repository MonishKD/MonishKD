# Hi, I'm Monish Das👋

<img align="right" width="270" alt="" src="https://github.com/user-attachments/assets/14212c1f-33e6-477e-b990-2a3019a62e8e" />

**Software Engineering (Co-op) @ Concordia University**
📍 Montreal, QC

I build backend systems and quantitative tooling, production Spring services during my internships, statistical trading models through my university's quant research club.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/monish-das-md)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:monishdas2003@gmail.com)

<br clear="both" />

### 🔭 Currently

- Building a **live volatility & risk forecasting system** for QUARCC
- Going deeper on **time series modelling** and **distributed systems design**
- Open to **Summer 2027 internships** — data engineering, ai development, quant dev, backend development, data platforms.

---

### 💼 Experience

#### Software Engineer Intern · Ultimate Kronos Group (UKG)
<sub>May 2026 – Aug 2026 · Montreal, QC</sub>

Shipped the Rebalance Live Schedule feature into UKG's core scheduling backend across two Spring repositories, with 13 unit tests covering validation and visibility rules. Built a concurrency test harness for the Rebalancer Engine's async REST control plane, validating sub-300 ms p99 latency, request deduplication, and a 1,000-entry distributed LRU cache across 4 endpoints. Extended a single-threaded TestNG framework into a multi-threaded harness (ExecutorService + CountDownLatch) with p95/p99 reporting, enabling load testing the team previously could not run. Replaced multiple per-region Splunk dashboards with a single tokenized view improving observability across roughly 10 scheduling repositories.

#### Software Test Automation Developer Intern · Intact Financial Corporation
<sub>Sept 2025 – Dec 2025 · Montreal, QC</sub>

Collaborated on building a Java API test automation framework (REST & SOAP) using TestNG, RestAssured, and Maven, replacing a 10+ year old ReadyAPI and Excel based framework. Diagnosed the root cause of 100+ regression test failures and debugged failing scenarios in ReadyAPI. Streamlined automated testing through Jenkins CI/CD pipelines.

#### Quantitative Research Analyst · QUARCC
<sub>Sept 2024 – Present · Concordia University</sub>

Research machine learning models for predicting equity price movement and analyse financial market data alongside a team of student researchers.

---

### 🚀 Projects

#### FX Mean-Reversion Trading Bot
<sub>`Python` · `pandas` · `SciPy` · `NumPy` · `OANDA v20 REST API`</sub>

Live algorithmic trading system covering 6 FX pairs on 15-minute candles. Fits a t-distribution to each pair's deviation from a 60-period moving average and enters when the standardized score exceeds 2. Bid and ask series are fit independently and both must clear entry thresholds, rejecting signals that survive on only one side of the spread and would be unprofitable after transaction costs. The execution loop runs unattended: UTC candle-boundary scheduling, exponential-backoff retries, broker position reconciliation at startup, and notional-normalized order sizing.

#### MealMajor
<sub>`Node.js` · `Express.js` · `PostgreSQL` · `Prisma ORM` · `GitHub Actions`</sub>

Backend and database layer for a full-stack meal-planning application. Modeled users, recipes, and password reset tokens in PostgreSQL via Prisma — schema design, client setup, migration workflow. CI runs install, test, and build checks on every push and pull request to main.

#### Java Blockchain Simulator
<sub>`Java` · `SHA-256` · `Elliptic Curve Cryptography`</sub>

Blockchain built from scratch: block hashing, previous-hash linking, and Proof of Work mining with difficulty adjustment. Integrity validation detects tampering through SHA-256 hash linkage, with transactions signed via ECC key pairs and wallet address verification.

---

### 🛠 Stack

**Languages**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**Frameworks & Libraries**<br>
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)

**Tools & Platforms**<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ-000000?style=flat&logo=intellijidea&logoColor=white)

<sub>**Focus areas** — REST APIs · Distributed Systems · Concurrency & Multithreading · Caching · CI/CD · Observability · Test Automation · Schema Design · Statistical Modeling · Time Series Analysis</sub>

---

### 📊 Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=MonishKD&show_icons=true&hide_border=true&include_all_commits=true&theme=transparent&title_color=0A66C2&icon_color=0A66C2" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MonishKD&layout=compact&hide_border=true&theme=transparent&title_color=0A66C2" alt="Top languages" />
</p>

---

<sub>🌍 English · French · Bangla · Hindi &nbsp;&nbsp;|&nbsp;&nbsp; 📫 [monishdas2003@gmail.com](mailto:monishdas2003@gmail.com)</sub>
