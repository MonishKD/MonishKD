# Hi, I'm Monish 👋

**Software Engineering (Co-op) student at Concordia University** · Montreal, QC

I build backend systems and quantitative tooling. Most of my work lives at the point where distributed systems meet financial data: production Spring services during my internships, statistical trading models through my university's quant research club.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/monish-das-md)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:monishdas2003@gmail.com)

---

## 🔭 What I'm working on

- **Volatility and risk forecasting system** for QUARCC, building live forecasting infrastructure from the ground up
- Deepening my grounding in **time series modelling** and **distributed systems design**
- Open to **Summer 2027 internships** in backend engineering, quantitative development, and data platforms

## 🚀 Projects

### FX Mean-Reversion Trading Bot
`Python` `pandas` `SciPy` `NumPy` `OANDA v20 REST API`

Live algorithmic trading system covering 6 FX pairs on 15-minute candles. Fits a t-distribution to each pair's deviation from a 60-period moving average and enters when the standardized score exceeds 2. Bid and ask series are fit independently and both must clear entry thresholds, which rejects signals surviving on only one side of the spread that would be unprofitable after transaction costs. The execution loop runs unattended: UTC candle-boundary scheduling, exponential-backoff retries on API failures, broker position reconciliation at startup, and notional-normalized order sizing across USD-base and USD-quote pairs.

### MealMajor
`Node.js` `Express.js` `PostgreSQL` `Prisma ORM` `GitHub Actions`

Backend and database layer for a full-stack meal-planning application. Modeled users, recipes, and password reset tokens in PostgreSQL via Prisma, covering schema design, client setup, and migration workflow. CI pipeline runs install, test, and build checks on every push and pull request to main.

### Java Blockchain Simulator
`Java` `SHA-256` `Elliptic Curve Cryptography`

Blockchain built from scratch: block hashing, previous-hash linking, and Proof of Work mining with difficulty adjustment. Integrity validation detects tampering through SHA-256 hash linkage, with transaction support via ECC key pairs, digital signatures, and wallet address verification.

## 🛠 Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Erlang](https://img.shields.io/badge/Erlang-A90533?style=flat&logo=erlang&logoColor=white)
![Clojure](https://img.shields.io/badge/Clojure-5881D8?style=flat&logo=clojure&logoColor=white)

**Frameworks & Libraries**

![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ-000000?style=flat&logo=intellijidea&logoColor=white)

**Areas**

REST APIs · Backend Development · Distributed Systems · Concurrency & Multithreading · Caching · CI/CD · Observability · Test Automation · Database Schema Design · Statistical Modeling · Time Series Analysis

## 📊 GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MonishKD&show_icons=true&hide_border=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MonishKD&layout=compact&hide_border=true" alt="Top languages" />
</p>

## 🌍 Languages

English · French · Bangla · Hindi

---

📫 **Reach me at** [monishdas2003@gmail.com](mailto:monishdas2003@gmail.com)
<img width="480" height="270" alt="giphy" src="https://github.com/user-attachments/assets/14212c1f-33e6-477e-b990-2a3019a62e8e" />

