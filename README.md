<div align="center">

# Marcelo Chávez

### Data Scientist · Statistical Engineer · Data Engineering

**Python · Machine Learning · Apache Airflow · PostgreSQL · R**

<br>

<table>
<tr>
<td align="center"><b>📍 Ubicación</b><br>Quito · Ecuador</td>
<td align="center"><b>📄 Perfil Profesional</b><br><a href="documentos/CV_MARCELO_CHAVEZ.pdf">Hoja de Vida</a></td>
<td align="center"><b>🌐 LinkedIn</b><br><a href="https://www.linkedin.com/in/marcelochavezec/">marcelochavezec</a></td>
<td align="center"><b>✉️ Contacto</b><br><a href="mailto:marcelo_chavez_ec@outlook.com">Email</a></td>
</tr>
</table>

</div>

---

<img align="right" alt="Data Analytics" width="43%" src="documentos/banner.png">

## 👨‍💻 Sobre mí

Soy **Ingeniero en Estadística Informática** especializado en **Ciencia de Datos, Machine Learning, Estadística Aplicada e Ingeniería de Datos**.

Mi principal ecosistema de trabajo es **Python**, utilizado para desarrollar procesos de análisis, transformación de datos, modelos de Machine Learning, automatizaciones y pipelines ETL.

La ejecución y calendarización de procesos de datos se complementa con **Apache Airflow**, mientras que **PostgreSQL** constituye una de las principales tecnologías utilizadas para almacenamiento, procesamiento e integración de información.

**R** complementa este ecosistema principalmente para modelamiento estadístico, métodos multivariantes, análisis exploratorio y desarrollo de aplicaciones analíticas con Shiny.

<br>

* 🐍 **Python** para Data Science, Machine Learning y Data Engineering
* 🤖 Modelamiento predictivo y aprendizaje automático
* ⚙️ Procesos ETL automatizados
* 🌬️ Orquestación de workflows con **Apache Airflow**
* 🗄️ PostgreSQL y SQL
* 🐳 Docker y ambientes reproducibles
* 📐 Estadística aplicada y métodos multivariantes
* 📊 Aplicaciones analíticas con R + Shiny
* 🏥 Analítica de datos e indicadores de salud

<br clear="both">

---

# 🧠 Data Science Ecosystem

<div align="center">

<table>

<tr>

<td align="center" width="220">
<img src="documentos/python_logo.png" width="110" alt="Python"/>
<br><br>
<b>PYTHON</b>
<br>
<sub>Data Science · ML · ETL</sub>
</td>

<td align="center" width="220">
<b>🌬️</b>
<br><br>
<b>APACHE AIRFLOW</b>
<br>
<sub>Workflow Orchestration</sub>
</td>

<td align="center" width="220">
<b>🗄️</b>
<br><br>
<b>POSTGRESQL</b>
<br>
<sub>Data Storage · SQL</sub>
</td>

</tr>

<tr>

<td align="center">
<img src="documentos/Rlogo.png" width="75" alt="R"/>
<br><br>
<b>R</b>
<br>
<sub>Statistical Computing</sub>
</td>

<td align="center">
<img src="documentos/shiny.png" width="95" alt="Shiny"/>
<br><br>
<b>SHINY</b>
<br>
<sub>Analytical Applications</sub>
</td>

<td align="center">
<b>🐳</b>
<br><br>
<b>DOCKER</b>
<br>
<sub>Reproducible Environments</sub>
</td>

</tr>

</table>

</div>

---

# 🐍 Python for Data Science

<div align="center">

### `Python · Pandas · NumPy · Scikit-learn · Matplotlib · SQLAlchemy`

</div>

Python constituye el **núcleo tecnológico** de mi trabajo para:

<table>

<tr>
<td width="50%" valign="top">

### Data Science

* Data Wrangling
* Análisis exploratorio
* Transformación de datos
* Feature Engineering
* Análisis estadístico
* Visualización

</td>

<td width="50%" valign="top">

### Machine Learning

* Clasificación
* Regresión
* Clustering
* Selección de variables
* Entrenamiento de modelos
* Evaluación de modelos

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Data Engineering

* ETL / ELT
* Integración de fuentes
* PostgreSQL
* SQL
* Procesamiento de datos
* Automatización

</td>

<td width="50%" valign="top">

### Orchestration

* Apache Airflow
* DAGs
* Scheduling
* Dependencias
* Monitoreo de procesos
* Pipelines reproducibles

</td>
</tr>

</table>

---

# ⚙️ Arquitectura de Procesamiento de Datos

```mermaid
flowchart LR

    subgraph FUENTES["01 · DATA SOURCES"]
        A1["Bases de Datos"]
        A2["Archivos"]
        A3["APIs"]
    end

    subgraph INGESTA["02 · INGESTION"]
        B1["Python"]
        B2["SQL"]
    end

    subgraph PROCESO["03 · PROCESSING"]
        C1["Pandas"]
        C2["NumPy"]
        C3["Validación"]
        C4["Transformación"]
    end

    subgraph ORQUESTACION["04 · ORCHESTRATION"]
        D1["Apache Airflow"]
        D2["DAGs"]
        D3["Scheduling"]
    end

    subgraph STORAGE["05 · DATA STORAGE"]
        E1["PostgreSQL"]
    end

    subgraph PRODUCTOS["06 · ANALYTICS"]
        F1["Machine Learning"]
        F2["Indicadores"]
        F3["Data Products"]
    end

    A1 --> B1
    A2 --> B1
    A3 --> B1

    B1 --> C1
    B2 --> C1

    C1 --> C2
    C2 --> C3
    C3 --> C4

    D1 -. controla .-> B1
    D1 -. orquesta .-> C1
    D1 -. ejecuta .-> C4
    D1 --> D2
    D2 --> D3

    C4 --> E1

    E1 --> F1
    E1 --> F2
    E1 --> F3

    classDef source fill:#172554,stroke:#60a5fa,color:#ffffff,stroke-width:1px;
    classDef python fill:#0f3d57,stroke:#38bdf8,color:#ffffff,stroke-width:2px;
    classDef process fill:#164e63,stroke:#67e8f9,color:#ffffff;
    classDef airflow fill:#7c2d12,stroke:#fb923c,color:#ffffff,stroke-width:2px;
    classDef database fill:#312e81,stroke:#818cf8,color:#ffffff,stroke-width:2px;
    classDef analytics fill:#14532d,stroke:#4ade80,color:#ffffff;

    class A1,A2,A3 source;
    class B1,B2 python;
    class C1,C2,C3,C4 process;
    class D1,D2,D3 airflow;
    class E1 database;
    class F1,F2,F3 analytics;
```

---

# 🌬️ Apache Airflow + Python ETL

La automatización de procesos se estructura mediante **DAGs de Apache Airflow**, utilizando Python como lenguaje principal para extracción, transformación, validación y carga de información.

```mermaid
flowchart TB

    AIRFLOW["🌬️ APACHE AIRFLOW"]

    AIRFLOW --> DAG["DAG"]

    DAG --> T1["01 · Extract"]
    T1 --> T2["02 · Transform"]
    T2 --> T3["03 · Validate"]
    T3 --> T4["04 · Load"]
    T4 --> T5["05 · Quality Check"]

    T1 --> PY1["Python"]
    T2 --> PY2["Pandas"]
    T3 --> PY3["Python Rules"]
    T4 --> DB["PostgreSQL"]
    T5 --> RESULT["Dataset Disponible"]

    classDef airflow fill:#7c2d12,stroke:#fb923c,color:#ffffff,stroke-width:3px;
    classDef task fill:#172554,stroke:#60a5fa,color:#ffffff,stroke-width:2px;
    classDef python fill:#0c4a6e,stroke:#38bdf8,color:#ffffff;
    classDef database fill:#312e81,stroke:#818cf8,color:#ffffff;
    classDef result fill:#14532d,stroke:#4ade80,color:#ffffff,stroke-width:2px;

    class AIRFLOW,DAG airflow;
    class T1,T2,T3,T4,T5 task;
    class PY1,PY2,PY3 python;
    class DB database;
    class RESULT result;
```

---

# 🤖 Machine Learning Pipeline

```mermaid
flowchart LR

    subgraph DATA["DATA"]
        A["Raw Data"]
    end

    subgraph PREPARACION["PREPARATION"]
        B["Cleaning"]
        C["EDA"]
        D["Feature Engineering"]
    end

    subgraph MODELADO["MODELING"]
        E["Train / Test"]
        F["Model Training"]
        G["Hyperparameters"]
    end

    subgraph EVALUACION["EVALUATION"]
        H["Metrics"]
        I["Model Comparison"]
    end

    subgraph RESULTADO["OUTPUT"]
        J["Predictions"]
        K["Analytical Insights"]
    end

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
    I --> K

    classDef data fill:#172554,stroke:#60a5fa,color:#ffffff;
    classDef prep fill:#164e63,stroke:#67e8f9,color:#ffffff;
    classDef model fill:#581c87,stroke:#c084fc,color:#ffffff;
    classDef evaluation fill:#78350f,stroke:#fbbf24,color:#ffffff;
    classDef output fill:#14532d,stroke:#4ade80,color:#ffffff;

    class A data;
    class B,C,D prep;
    class E,F,G model;
    class H,I evaluation;
    class J,K output;
```

---

# 📐 Statistical Science

La formación estadística constituye la base metodológica de los procesos de Ciencia de Datos y Machine Learning.

<table>

<tr>

<td width="50%" valign="top">

### Estadística

* Estadística descriptiva
* Inferencia estadística
* Modelamiento estadístico
* Análisis exploratorio
* Indicadores estadísticos

</td>

<td width="50%" valign="top">

### Métodos Multivariantes

* Análisis de Componentes Principales
* Métodos de reducción dimensional
* Clasificación
* Agrupamiento
* Análisis de relaciones multivariantes

</td>

</tr>

</table>

---

# 📊 R & Statistical Computing

<div align="center">

<img src="documentos/Rlogo.png" width="75" alt="R">
&nbsp;&nbsp;&nbsp;&nbsp;
<img src="documentos/shiny.png" width="95" alt="Shiny">

<br><br>

**R · Tidyverse · Shiny · ggplot2 · data.table · RPostgres**

</div>

R complementa el ecosistema Python principalmente en:

* Modelamiento estadístico
* Métodos multivariantes
* Visualización estadística
* Análisis exploratorio
* Construcción de indicadores
* Aplicaciones analíticas mediante Shiny

---

# 🛠️ Technology Stack

<div align="center">

<table>

<tr>
<td align="center"><b>🐍 Programming</b></td>
<td align="center">Python · R · SQL</td>
</tr>

<tr>
<td align="center"><b>🧠 Data Science</b></td>
<td align="center">Pandas · NumPy · Scikit-learn</td>
</tr>

<tr>
<td align="center"><b>🤖 Machine Learning</b></td>
<td align="center">Classification · Regression · Clustering</td>
</tr>

<tr>
<td align="center"><b>⚙️ Data Engineering</b></td>
<td align="center">Python · ETL · PostgreSQL · SQL</td>
</tr>

<tr>
<td align="center"><b>🌬️ Orchestration</b></td>
<td align="center">Apache Airflow · DAGs · Scheduling</td>
</tr>

<tr>
<td align="center"><b>🐳 Infrastructure</b></td>
<td align="center">Docker · Linux · Git</td>
</tr>

<tr>
<td align="center"><b>📊 Analytics</b></td>
<td align="center">Shiny · Matplotlib · ggplot2</td>
</tr>

</table>

</div>

---

# 🎯 Professional Focus

<div align="center">

### Python

↓

### Data Science + Machine Learning

↓

### Apache Airflow + Data Engineering

↓

### PostgreSQL

↓

### Statistical & Analytical Products

</div>

Mi enfoque profesional integra **Python, Estadística y Data Engineering** para construir procesos analíticos automatizados, reproducibles y orientados a transformar datos en información útil para la toma de decisiones.

---

<div align="center">

## Contacto

<table>

<tr>
<td align="center" width="170">
<b>📄 HOJA DE VIDA</b>
<br><br>
<a href="documentos/CV_MARCELO_CHAVEZ.pdf">Ver CV</a>
</td>

<td align="center" width="170">
<b>🌐 LINKEDIN</b>
<br><br>
<a href="https://www.linkedin.com/in/marcelochavezec/">Ver Perfil</a>
</td>

<td align="center" width="220">
<b>✉️ EMAIL</b>
<br><br>
<a href="mailto:marcelo_chavez_ec@outlook.com">marcelo_chavez_ec@outlook.com</a>
</td>

<td align="center" width="150">
<b>📍 UBICACIÓN</b>
<br><br>
Quito · Ecuador
</td>
</tr>

</table>

<br>

### Data Scientist · Statistical Engineer

**Python · Machine Learning · Apache Airflow · Data Engineering**

<sub>Building reproducible data-driven analytical systems.</sub>

</div>
