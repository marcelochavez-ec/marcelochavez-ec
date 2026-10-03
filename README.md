<div align="center">

# Marcelo Chávez

### Analytical Process Automation Specialist

**Python · Django · Apache Superset · Apache Airflow**

<br>

<table>
<tr>
<td align="center"><b>📍 Location</b><br>Quito · Ecuador</td>
<td align="center"><b>📄 Professional Profile</b><br><a href="documentos/CV_MARCELO_CHAVEZ.pdf">Curriculum Vitae</a></td>
<td align="center"><b>🌐 LinkedIn</b><br><a href="https://www.linkedin.com/in/marcelochavezec/">marcelochavezec</a></td>
<td align="center"><b>✉️ Contact</b><br><a href="mailto:marcelo_chavez_ec@outlook.com">Email</a></td>
</tr>
</table>

</div>

---

<img align="right" alt="Data Analytics" width="43%" src="documentos/banner.png">

## 👨‍💻 About Me

I am a **Data Consultant specialized in the automation of analytical and statistical processes**, covering the design, implementation, and integration of **data ecosystems and analytical solutions**.

My work focuses on the creation and innovation of **end-to-end analytical solutions** that combine automated data processing, statistical methods, data engineering, workflow orchestration, visualization, and analytical software development to transform data into reliable and timely information for decision-making.

I develop **data products using Python-based technologies**, with an emphasis on scalability, documentation, and reproducibility.

I am particularly interested in the application of **Machine Learning methods** and their integration into modern data workflows and applications.

<br clear="both">

---

# 💻 Technology Stack

<div align="center">

| Area | Technologies |
|---|---|
| 🐍 **Core Programming** | Python |
| 🌐 **Analytical Applications** | Django |
| 📊 **Business Intelligence & Analytics** | Apache Superset |
| 🌬️ **Workflow Orchestration** | Apache Airflow |
| 🗄️ **Databases** | PostgreSQL|
| 🧠 **Data Analysis** | Pandas · NumPy |
| 🤖 **Machine Learning** | Scikit-learn |
| 📈 **Visualization** | Matplotlib · Seaborn |
| 🐳 **Infrastructure** | Docker · Linux · Git |

</div>

---

# 🐍 Python for Data Analytics

<div align="center">

### `Python · Pandas · NumPy · Scikit-learn · Matplotlib · SQLAlchemy`

</div>

Python is the **core technology of my analytical ecosystem**, supporting the complete data lifecycle from ingestion and processing to analysis, modeling, automation, and delivery of data products.

<table>

<tr>

<td width="50%" valign="top">

### Data Processing

- Data ingestion
- Data cleaning
- Data transformation
- Data validation
- Data integration
- Data wrangling
- Automated processing

</td>

<td width="50%" valign="top">

### Statistical Analytics

- Exploratory Data Analysis
- Descriptive statistics
- Statistical methods
- Statistical indicators
- Data quality assessment
- Analytical validation

</td>

</tr>

<tr>

<td width="50%" valign="top">

### Machine Learning

- Regression
- Classification
- Clustering
- Feature Engineering
- Train / Test workflows
- Model evaluation

</td>

<td width="50%" valign="top">

### Data Engineering

- ETL / ELT
- Data pipelines
- PostgreSQL
- SQL
- Data integration
- Workflow automation

</td>

</tr>

</table>

---

# ⚙️ Analytical Process Automation

My analytical workflows integrate **Python, Apache Airflow, PostgreSQL, Apache Superset, and Django** to automate the complete lifecycle of data processing and analytical information delivery.

```mermaid
flowchart LR

    subgraph SOURCES["01 · DATA SOURCES"]
        A1["Databases"]
        A2["Files"]
        A3["APIs"]
    end

    subgraph INGESTION["02 · INGESTION"]
        B1["Python"]
        B2["SQL"]
    end

    subgraph PROCESSING["03 · PROCESSING"]
        C1["Pandas"]
        C2["NumPy"]
        C3["Validation"]
        C4["Transformation"]
    end

    subgraph ORCHESTRATION["04 · ORCHESTRATION"]
        D1["Apache Airflow"]
        D2["DAGs"]
        D3["Scheduling"]
    end

    subgraph STORAGE["05 · DATA STORAGE"]
        E1["PostgreSQL"]
    end

    subgraph ANALYTICS["06 · ANALYTICS"]
        F1["Machine Learning"]
        F2["Statistical Indicators"]
        F3["Apache Superset"]
    end

    subgraph PRODUCTS["07 · DATA PRODUCTS"]
        G1["Django"]
        G2["Analytical Applications"]
        G3["Decision Support"]
    end

    A1 --> B1
    A2 --> B1
    A3 --> B1

    B1 --> C1
    B2 --> C1

    C1 --> C2
    C2 --> C3
    C3 --> C4

    D1 -. orchestrates .-> B1
    D1 -. controls .-> C1
    D1 -. executes .-> C4
    D1 --> D2
    D2 --> D3

    C4 --> E1

    E1 --> F1
    E1 --> F2
    E1 --> F3

    F1 --> G1
    F2 --> G1
    F3 --> G1

    G1 --> G2
    G2 --> G3
