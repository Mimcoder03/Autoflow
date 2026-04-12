# **ProdigyFlow — Intelligent Data Analytics Agent**

*A Capstone Project for the Kaggle Agents Intensive Program*

<img width="900" height="550" alt="main thumbnai" src="https://github.com/user-attachments/assets/34db2c20-72e7-463f-8aff-ad6f65d977ea" />

---

## **Overview**

**ProdigyFlow** is a fully autonomous, multi-agent data analytics pipeline designed to transform raw, unstructured data into clean datasets, meaningful insights, and ready-to-use visualizations — without manual intervention. Created for the **Kaggle Agents Intensive Capstone Project**, this system demonstrates how intelligent agents can streamline and accelerate traditional analytics workflows.

Instead of writing repetitive cleaning scripts or manually generating plots, ProdigyFlow shows how an agentic architecture can automate **data preparation, exploratory analysis, insight extraction, reporting, and visualization generation** in one coordinated flow.

The result is a modern, efficient, and scalable analytics pipeline that reflects real-world industry processes and the future direction of automated data intelligence.

---


## 🎯 **Why We Chose This Project**

We selected this project because **agent-driven analytics represents the next major shift in business intelligence and data engineering**. Data teams spend a large portion of time on manual cleaning, repetitive EDA, and visualization tasks. We wanted to build a system that:

* Simulates an industry-grade analytics pipeline
* Shows how agents can automate real analytics tasks
* Demonstrates practical use of Python, automation, visualization, and system design
* Reduces manual overhead and speeds up insight generation

This project also aligns with emerging trends such as:

* AI-powered data preparation
* Autonomous EDA
* Multi-agent coordination
* Unified data workflows
* Intelligent reporting systems

Our goal was to create something academically strong, professionally relevant, and future-ready.

---

## **Project Goals**

ProdigyFlow automates the core components of the analytics lifecycle:

1. **Data Ingestion & Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Insight Generation & Summary Reporting**
4. **Visualization & Dashboard Preparation**

---

## **System Architecture**

ProdigyFlow is built as a multi-agent system, with each agent responsible for a single stage of the pipeline:

* **Cleaning Agent** — Parses and cleans raw data
* **Analysis Agent** — Performs structured EDA and auto-summaries
* **Visualization Agent** — Generates charts and visual insights
* **Main Agent** — Orchestrates the entire pipeline end-to-end

It uses a tools layer (MCP utilities) for data handling, visualization, logging, and reporting.

<img width="700" height="900" alt="PRODIGYFLOW ARCH" src="https://github.com/user-attachments/assets/5b92719b-6088-414f-94ee-4d1838701918" />

---

## **Repository Structure**

```
ProdigyFlow/
│
├── data/               
│   ├── raw/
│   └── cleaned/
├── agents/              
│   ├── main_agent.py
│   ├── cleaning_agent.py
│   ├── analysis_agent.py
│   └── visualization_agent.py
├── tools/               
│   ├── data_tools.py
│   ├── logging_tools.py
│   └── viz_tools.py
├── reports/             
│   ├── Executive_Report.pdf
│   ├── Findings.md
│   └── Architecture_Diagram.png
├── dashboard/          
├── prodigyflow-kaggle-notebook.ipynb
├── test_gemini.py     
├── README.md
├── requirements.txt
└── LICENSE
```

---

## **Our Core Agents**

| **Agent Name**              | **Role**                  | **Key Responsibilities**                                                                   | **Outputs**                                          |
| --------------------------- | ------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------- |
| **Cleaning Agent**          | Data Preparation          | Missing values, type fixing, duplicate removal, basic transformations                      | Cleaned dataset (`data/cleaned/`)                    |
| **Analysis Agent**          | Exploratory Data Analysis | Summary stats, correlations, patterns, anomaly signals, AI-generated summaries             | Insight dictionaries + summary text (`/reports`)     |
| **Visualization Agent**     | Data Visualization        | Generates charts, comparison plots, trend graphs, and export-ready visuals                 | PNG/JPG visual assets in `/reports` and `/dashboard` |
| **Main Orchestrator Agent** | Workflow Automation       | Runs the full pipeline, manages logging, triggers all agents, handles errors and reporting | Final HTML/PDF report + logs + consolidated outputs  |

---

## **Dashboard**

The dashboard includes:

* High-level overview metrics
* Subject-wise performance trends
* Distribution and comparison charts
* Correlation insights
* Summary sections for fast interpretation

---

## **Technologies Used**

* **Python** — Pandas, NumPy, Matplotlib
* **Agentic Automation** (multi-agent pipeline)
* **MCP Tools** — for modular utilities & orchestration
* **Jupyter Notebook** — Kaggle-friendly analysis environment

---

## **What We Learned**

### **Technical Learnings**

* Designing and coordinating multi-agent workflows
* Structuring scalable and modular Python projects
* Cleaning and transforming real-world datasets
* Automating EDA and summarization
* Creating detailed visualizations and exporting them
* Building HTML reports and tracking logs
* Managing experiments and reproducibility

### **Conceptual Learnings**

* How to convert raw business problems into actionable pipelines
* Importance of systematic cleaning and traceability
* How automation can reduce repetitive tasks
* How to maintain readability and structure in multi-file projects
* Working collaboratively with GitHub and version control

This project deepened our understanding of modern analytics pipelines and how automation can enhance efficiency.

---

## **How to Run**

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/ProdigyFlow.git
cd ProdigyFlow
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Main Agent**

```bash
python agents/main_agent.py
```

4. View outputs in:

* `/data/cleaned/` — cleaned dataset
* `/reports/` — summaries, logs, report.html
* `/dashboard/` — visual assets

---

## **License**

Licensed under the MIT License. See `LICENSE` for details.

---

## **Acknowledgements**

This project was developed as part of the **Kaggle Agents Intensive Capstone Project**.
Huge thanks to the mentors, Kaggle community, and all contributors who supported our learning journey.

---
