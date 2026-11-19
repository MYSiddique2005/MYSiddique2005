<!-- Profile README · github.com/MYSiddique2005 -->

<div align="center">

<img src="assets/banner.svg" width="100%" alt="Mohammad Yasin Siddique — Data Analyst | AI & Business Analytics"/>

<a href="https://github.com/MYSiddique2005"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1100&color=2C9CDB&center=true&vCenter=true&width=680&lines=Turning+business+data+into+actionable+insights;EDA+%E2%80%A2+ETL+%E2%80%A2+KPI+Analysis+%E2%80%A2+Forecasting;Built+an+LLM-grounded+ERP+on+231K%2B+sales+lines;LLM+test+accuracy+28%25+%E2%86%92+100%25;Open+to+Data+Analyst+roles+%F0%9F%9A%80" alt="Typing intro"/></a>

<p>
  <a href="https://www.linkedin.com/in/mohammad-yasin-siddique-085b1b316/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:my.siddique2005@gmail.com"><img src="https://img.shields.io/badge/Email-my.siddique2005@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://mysiddique2005.github.io/Byte-Supply-E-Commerce-Business-Analytics/"><img src="https://img.shields.io/badge/Live_Dashboard-Byte_Supply-2E7D32?style=for-the-badge&logo=plotly&logoColor=white" alt="Live dashboard"/></a>
</p>
<p>
  <img src="https://img.shields.io/badge/Open_to-Data_Analyst_roles-7CF5C4?style=flat-square&labelColor=0B1D33" alt="Open to Data Analyst roles"/>
  <img src="https://img.shields.io/badge/Based_in-Nagpur_%F0%9F%87%AE%F0%9F%87%B3_%C2%B7_Malaysia_%F0%9F%87%B2%F0%9F%87%BE-4FC3F7?style=flat-square&labelColor=0B1D33" alt="Location"/>
  <img src="https://komarev.com/ghpvc/?username=MYSiddique2005&style=flat-square&color=1B5E8A&label=Profile+views" alt="Profile views"/>
</p>

<sub>
<a href="#about">About</a> ·
<a href="#impact">Impact</a> ·
<a href="#internship">Internship</a> ·
<a href="#projects">Projects</a> ·
<a href="#skills">Skills</a> ·
<a href="#journey">Journey</a> ·
<a href="#activity">Activity</a> ·
<a href="#connect">Connect</a>
</sub>

</div>

---

<a id="about"></a>
## 👋 About me

Final-year **Computer Science Engineering** student with hands-on experience building end-to-end
**analytics, ERP and machine learning** solutions using **Python and SQL** on datasets of **230,000+ records**.
I'm looking for a **Data Analyst** role to turn business data into actionable insights and support data-driven decisions.

```python
yasin = {
    "role":      "Data Analyst | AI & Business Analytics",
    "education": "B.Tech CSE @ G.H. Raisoni College of Engineering, Nagpur (2027)",
    "now":       ["Research Intern @ INTI International University", "7th-semester Mobility Programme, Malaysia"],
    "focus":     ["EDA", "Data Cleaning", "ETL", "KPI Analysis", "Regression", "Forecasting", "LLM Integration", "RAG"],
    "stack":     ["Python", "SQL", "pandas", "NumPy", "scikit-learn", "FastAPI", "PostgreSQL", "React"],
}
```

<a id="impact"></a>
## 📈 Impact in numbers

<img src="assets/impact.svg" width="100%" alt="Impact: 231,412 sales order lines; LLM test accuracy 28% to 100%; 98–100% evaluation score; ~110,000 products cleaned; RM 2.04M revenue analysed; R² 0.15 to 0.54"/>

---

<a id="internship"></a>
## 💼 Internship

> Click ▶ under any project to expand screenshots, charts and architecture.

### 🧠 [IntelliERP](https://github.com/MYSiddique2005/IntelliERP) — LLM-Grounded Intelligent ERP Decision Support
<sub>**Research Internship · INTI International University · Aug – Dec 2026**</sub>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs_%26_RAG-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

- **Enterprise data integration** — 5-module ERP (Sales, Inventory, Procurement, Products, Suppliers) with **40+ REST APIs** and **11 PostgreSQL tables**, loaded with **231,412** sales order lines and **227** products
- **AI & business intelligence** — LLM assistant grounded in a **41-passage** knowledge base with **14 role-scoped tools** for **stockout risk, demand forecasting and supplier KPIs**, raising test accuracy from **28% → 100%**
- **Workflow automation** — JWT authentication, **role-based access control for 4 roles**, audit logging and a purchase-order approval workflow with human sign-off; **98–100%** across 3 runs of an 86-question evaluation

<details>
<summary><b>🖼️ Show screenshots &amp; architecture</b></summary>
<br>

| ERP dashboard | AI assistant with evidence |
|:-:|:-:|
| <img src="assets/projects/ui-dashboard.png" width="420" alt="IntelliERP dashboard"/> | <img src="assets/projects/ui-ai-assistant.png" width="420" alt="IntelliERP AI assistant"/> |

<img src="assets/projects/chart-grounding.png" width="640" alt="Grounding results: questions answered correctly with and without the knowledge base"/>

```mermaid
flowchart LR
    U["👤 User<br/>(4 roles, JWT)"] --> FE["⚛️ React + TypeScript"]
    FE --> API["⚡ FastAPI<br/>40+ REST APIs"]
    API --> DB[("🐘 PostgreSQL<br/>11 tables · 231K lines")]
    API --> AI["🧠 LLM assistant"]
    AI -->|14 role-scoped tools| DB
    AI -->|RAG| KB["📚 Knowledge base<br/>41 passages"]
    AI --> V["🔍 Verification<br/>checks every claim"]
    V --> FE
    API --> PO["📝 Draft PO → human approval"]
```

</details>

---

<a id="projects"></a>
## 🚀 Projects

### 📊 [Byte Supply — E-Commerce Business Analytics](https://github.com/MYSiddique2005/Byte-Supply-E-Commerce-Business-Analytics)
<sub>**Individual project · Oct 2026** · [🌐 Live interactive dashboard](https://mysiddique2005.github.io/Byte-Supply-E-Commerce-Business-Analytics/)</sub>

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

- **Exploratory data analysis** — analysed **24,991** transactions (**RM 2.04M** revenue over 5 years): **36.5%** gross margin, **89.6%** on-time delivery; mega-sale days earned **25.1%** margin vs **36.8%** otherwise
- **Predictive modelling** — linear vs polynomial regression on a chronological 80/20 split; polynomial model cut **MAE by 21.5%** and raised **R² from 0.15 to 0.54** for a 12-month revenue forecast
- **Data visualisation** — 10 Seaborn and Matplotlib charts showing late deliveries cut average rating from **4.20 to 2.99** and that **Q4 generates 29.2%** of annual revenue

<details>
<summary><b>📉 Show charts</b></summary>
<br>

<img src="assets/projects/11_forecast.png" width="720" alt="12-month revenue forecast"/>

| Late-delivery impact on ratings | Seasonality heatmap |
|:-:|:-:|
| <img src="assets/projects/08_late_delivery_impact.png" width="420" alt="Late delivery impact"/> | <img src="assets/projects/04_seasonality_heatmap.png" width="420" alt="Seasonality heatmap"/> |

</details>

---

### 🛒 [Supply Chain Big Data Analytics](https://github.com/MYSiddique2005/SupplyChain-BigDataAnalytics)
<sub>**Team project (5 members) · Sep – Oct 2026**</sub>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-2C5364?style=flat-square)
![Data Engineering](https://img.shields.io/badge/Data_Engineering-2C5364?style=flat-square)

- **Data acquisition** — processed **~110,000** product records from **Amazon, Flipkart, Shopee and Lazada** for multi-platform e-commerce dataset preparation
- **ETL & data quality** — extraction, transformation, schema standardisation, deduplication, missing-value assessment and validation across heterogeneous CSV datasets
- **Team collaboration** — coordinated preprocessing, quality checks and documentation within a five-member team, applying communication, problem-solving and analytical thinking

<details>
<summary><b>🔧 Show the ETL pipeline</b></summary>
<br>

```mermaid
flowchart LR
    A["🇮🇳 Flipkart<br/>20K"] --> E["⚙️ preprocess.py<br/>extract · transform · validate"]
    B["🇺🇸 Amazon<br/>30K"] --> E
    C["🇹🇼 Shopee<br/>30K"] --> E
    D["🌏 Lazada<br/>30K"] --> E
    E --> F["🏷️ Shared schema"] --> G["🧹 109,998 clean rows<br/>0 duplicate IDs"] --> H["📈 Analytics & ML"]
```

</details>

---

<a id="skills"></a>
## 🛠️ Technical skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,postgres,ts,fastapi,react,sklearn,git,vscode&perline=8" alt="Python, PostgreSQL, TypeScript, FastAPI, React, scikit-learn, Git, VS Code"/>
</p>

<table>
<tr><td><b>Languages</b></td><td>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</td></tr>
<tr><td><b>Data Analysis &amp; ML</b></td><td>

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</td></tr>
<tr><td><b>Backend &amp; Databases</b></td><td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA539?style=for-the-badge&logo=python&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</td></tr>
<tr><td><b>Concepts</b></td><td>

`EDA` · `Data Cleaning` · `Data Preprocessing` · `ETL` · `Statistical Analysis` · `Regression` · `Forecasting` · `KPI Analysis` · `Data Visualization` · `LLM Integration` · `RAG`

</td></tr>
</table>

---

<a id="journey"></a>
## 🧭 Journey

```mermaid
timeline
    2021 : SSC (CBSE) — East Point School, Nagpur
    2023 : HSC — St. Paul Junior College, Nagpur
         : Started B.Tech CSE — G.H. Raisoni College of Engineering
    2024 : 3rd semester at IIIT Nagpur (Credit Transfer Scheme)
    2025 : Technotsav 2.0 — Centres of Excellence, GHRCE
    2026 : Mobility Programme — INTI International University, Malaysia
         : Research Intern — IntelliERP (Aug–Dec)
         : ICIT2026 international conference, INTI
    2027 : B.Tech CSE graduation (expected)
```

<details>
<summary><b>🎓 Education details</b></summary>
<br>

| Programme | Institution | Year |
|---|---|:-:|
| **B.Tech, Computer Science Engineering** | G.H. Raisoni College of Engineering, Nagpur | 2027 (expected) |
| 7th Semester Mobility Programme | INTI International University, Malaysia | 2026 |
| 3rd Semester, Credit Transfer Scheme | IIIT Nagpur | — |
| Higher Secondary Certificate (HSC) | St. Paul Junior College, Nagpur | 2023 |
| Secondary School Certificate (SSC, CBSE) | East Point School, Nagpur | 2021 |

</details>

<details>
<summary><b>🏅 Events &amp; conferences</b></summary>
<br>

- **ICIT2026** — 9th International Conference on Innovation and Technopreneurship, INTI International University, Malaysia (10 Sep 2026)
- **Technotsav 2.0** — technical festival by the Centres of Excellence, G.H. Raisoni College of Engineering, Nagpur (21–22 Mar 2025)

</details>

---

<a id="activity"></a>
## 📊 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=MYSiddique2005&show_icons=true&hide_border=true&theme=tokyonight&count_private=true&rank_icon=github" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MYSiddique2005&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>

<img height="165" src="https://streak-stats.demolab.com?user=MYSiddique2005&theme=tokyonight&hide_border=true" alt="Contribution streak"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=MYSiddique2005&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph"/>

</div>

---

<div align="center">

<a id="connect"></a>
### 🤝 Let's connect

Open to **Data Analyst** and **Business / AI Analytics** opportunities.

<a href="https://www.linkedin.com/in/mohammad-yasin-siddique-085b1b316/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:my.siddique2005@gmail.com"><img src="https://img.shields.io/badge/Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>
