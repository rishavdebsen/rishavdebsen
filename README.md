![Rishav Deb Sen - Data Analyst. Data into decisions.](1-profile-banner.svg)

# Hi, I'm Rishav Deb Sen

### Data Analyst | SQL · Python · Power BI · Excel | AI & ML Projects

I build dashboards, automate reporting, and turn data into clear answers to business questions. My portfolio also explores machine learning and retrieval-based document Q&A.

Based in Bengaluru. Previously a Data Associate at Wipro. Open to Data Analyst, BI Analyst, and junior AI roles. Available to join immediately.

[Connect on LinkedIn](https://www.linkedin.com/in/rishav-d-824a392a1)

---

## Professional experience

**Data Associate · Wipro | Jan 2025 - Feb 2026**

Supported reporting and dashboards for a multinational transportation client.

- Automated reporting workflows with Excel VBA and Python, reducing report turnaround by 30%.
- Built Power BI dashboards for cross-functional and global stakeholders.
- Applied controls validation and documented reconciliation rules to improve reporting quality.

## How I approach a project

**Business question → Data checks → Analysis → Dashboard or application → Findings and limitations**

I aim to make each repository easy to review: explain the problem, show the result, document how to run it, and be clear about what has and has not been tested.

---

## Explore my projects

[Investor Intelligence](#ai-powered-investor-intelligence-platform) · [Invoice ML](#vendor-invoice-intelligence) · [Power BI Dashboard](#blinkit-grocery-sales-dashboard)

Select a project, open the code, or try the deployed Investor demo. Click the expandable sections for implementation details.

### [AI-Powered Investor Intelligence Platform](https://github.com/rishavdebsen/AI-Powered-Investor-Intelligence-Platform)

A RAG-style document Q&A and financial KPI dashboard for exploring company filings.

[![Open repository](https://img.shields.io/badge/OPEN-CODE-173B50?style=for-the-badge&logo=github)](https://github.com/rishavdebsen/AI-Powered-Investor-Intelligence-Platform) [![Try demo](https://img.shields.io/badge/TRY-STREAMLIT%20DEMO-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://investor-intelligence-platform.streamlit.app)

[![Investor dashboard preview](2-investor-dashboard.png)](https://investor-intelligence-platform.streamlit.app)

*Free-hosted demo may be asleep. Use the wake button on Streamlit if prompted. Screenshot shows the project interface, not live market data.*

<details>
<summary><b>See retrieval pipeline, tools, and implementation scope</b></summary>


- Ingests PDF, Markdown, and text filings with structure-aware chunking.
- Returns retrieved excerpts with source citations and extracts headline financial KPIs.
- Combines a FastAPI backend with a Streamlit interface and Mixpanel funnel tracking.

**Tools:** Python · FastAPI · Streamlit · SQLite · RAG architecture · TF-IDF · Mixpanel

**RAG implementation scope:** Document ingestion, chunking, TF-IDF retrieval, and source-cited excerpts are implemented. The default answer is extractive, not LLM-generated. The optional OpenAI/Azure generation path is unverified.

</details>

---

### [Vendor Invoice Intelligence](https://github.com/rishavdebsen/Invoice-Intelligence-Freight-Cost-Prediction-Invoice-Risk-Flagging-Machine-Learning-sql-python)

A machine learning project for estimating freight costs and flagging invoices for manual review.

[![Explore SQL and ML code](https://img.shields.io/badge/EXPLORE-SQL%20%2B%20ML%20CODE-F7931E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rishavdebsen/Invoice-Intelligence-Freight-Cost-Prediction-Invoice-Risk-Flagging-Machine-Learning-sql-python)

[![Vendor Invoice Intelligence app screenshot](3-invoice-app.png)](https://github.com/rishavdebsen/Invoice-Intelligence-Freight-Cost-Prediction-Invoice-Risk-Flagging-Machine-Learning-sql-python)

*Real screenshot of the repository app running locally with its default example inputs. UI impact statements describe intended uses, not measured business results. This is not a hosted demo or a verified prediction result.*

**Invoice data → SQL features → Regression and classification → Streamlit predictions**

<details>
<summary><b>See models, evaluation, and app details</b></summary>


- Uses SQL joins and aggregations to create features from vendor invoice and purchase data.
- Compares Linear Regression, Decision Tree, and Random Forest models for freight prediction.
- Tunes a Random Forest classifier with GridSearchCV and 5-fold cross-validation; evaluates precision, recall, F1, and the confusion matrix.
- Separates training and inference into reusable scripts, with predictions available through a Streamlit app.

**Tools:** SQL · SQLite · Python · pandas · scikit-learn · Streamlit

**Scope:** Invoice flags are based on business-rule labels, not independently verified fraud outcomes.

</details>

---

### [Blinkit Grocery Sales Dashboard](https://github.com/rishavdebsen/blinkit-grocery-sales-dashboard)

An interactive Power BI dashboard for exploring sales by product category, outlet size, and location tier.

[![View Power BI project](https://img.shields.io/badge/VIEW-POWER%20BI%20PROJECT-F2C811?style=for-the-badge)](https://github.com/rishavdebsen/blinkit-grocery-sales-dashboard)

[![Blinkit Power BI dashboard preview](4-blinkit-dashboard.jpg)](https://github.com/rishavdebsen/blinkit-grocery-sales-dashboard)

<details>
<summary><b>See dashboard features, tools, and dataset credit</b></summary>


- Presents sales, item counts, average sales, and ratings with interactive filters.
- Includes a companion pandas script for checking dataset summaries.
- Built following the Data Tutorials walkthrough using its practice dataset, with credit in the repository.

**Tools:** Power BI · DAX · Python · pandas

</details>

---

## About me

- In my projects, I use SQL and Python to prepare data, compare models, and build interactive tools.
- My interests sit at the intersection of business intelligence, automation, and practical AI applications.

## Tools I use

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge)
![RAG projects](https://img.shields.io/badge/RAG%20Projects-245C73?style=for-the-badge)
![Machine learning](https://img.shields.io/badge/Machine%20Learning-6B4E9B?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

| Area | Tools and methods |
| --- | --- |
| Analysis | SQL joins, CTEs, window functions, aggregations; Python, pandas, NumPy |
| Dashboards and reporting | Power BI, DAX, Power Query, Excel VBA, Tableau |
| Project databases | MySQL, SQLite |
| AI and document retrieval | RAG-style document Q&A, TF-IDF retrieval, structure-aware chunking, source citations, financial KPI extraction |
| Machine learning | scikit-learn, Linear Regression, Decision Trees, Random Forest, feature engineering, GridSearchCV, cross-validation, model evaluation |
| Application projects | FastAPI, Streamlit, retrieval-based document Q&A, Mixpanel event tracking |

**Project focus:** document retrieval and RAG architecture in Investor Intelligence; regression, classification, and model evaluation in Vendor Invoice Intelligence. These are portfolio projects, separate from my Wipro experience.

## Connect

[LinkedIn](https://www.linkedin.com/in/rishav-d-824a392a1) · [GitHub](https://github.com/rishavdebsen)
