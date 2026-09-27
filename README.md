# Data Engineering

> A structured and practical repository for learning, building, and documenting **Data Engineering** concepts, tools, technologies, and real-world projects.

---

## 📌 About This Repository

This repository is my learning and development space for **Data Engineering**, combining theoretical knowledge with hands-on implementation.

It contains:

* 📚 Learning materials and technical notes
* 🧪 Hands-on exercises and labs
* 🛠️ Practical Data Engineering projects
* 🗄️ SQL and database practice
* 🔄 ETL / ELT pipelines
* 🏗️ Data Warehousing concepts and implementations
* ⚡ Big Data technologies
* 🌊 Data streaming and event-driven systems
* 🐳 Containerized data applications
* ☁️ Cloud and modern data platforms
* 📊 Datasets and data-processing workflows

The goal is to continuously transform concepts into **practical, production-oriented implementations**.

---

## 🗺️ Data Engineering Roadmap

The repository follows a progressive learning path:

```text
Python
   │
   ▼
SQL & Databases
   │
   ▼
Data Processing
   │
   ▼
ETL / ELT
   │
   ▼
Data Warehousing
   │
   ▼
Data Pipelines
   │
   ├──────────────► Apache Airflow
   │
   ├──────────────► Apache Spark
   │
   └──────────────► Apache Kafka
   │
   ▼
Docker & Containerization
   │
   ▼
Cloud Platforms
   │
   ▼
Production Data Engineering
```

---

## 📂 Repository Structure

```text
data-engineering/
│
├── 01-python/
│   ├── notes/
│   ├── exercises/
│   └── projects/
│
├── 02-sql/
│   ├── notes/
│   ├── queries/
│   └── exercises/
│
├── 03-databases/
│   ├── relational/
│   ├── nosql/
│   └── database-design/
│
├── 04-data-processing/
│   ├── pandas/
│   ├── numpy/
│   └── data-cleaning/
│
├── 05-etl-elt/
│   ├── pipelines/
│   ├── extraction/
│   ├── transformation/
│   └── loading/
│
├── 06-data-warehousing/
│   ├── dimensional-modeling/
│   ├── star-schema/
│   └── projects/
│
├── 07-apache-airflow/
│   ├── dags/
│   ├── operators/
│   └── projects/
│
├── 08-apache-spark/
│   ├── pyspark/
│   ├── spark-sql/
│   └── projects/
│
├── 09-apache-kafka/
│   ├── producers/
│   ├── consumers/
│   └── streaming-projects/
│
├── 10-docker/
│   ├── dockerfiles/
│   └── docker-compose/
│
├── 11-cloud/
│   ├── aws/
│   ├── azure/
│   └── gcp/
│
├── projects/
│   ├── project-01/
│   ├── project-02/
│   └── project-03/
│
├── datasets/
│
├── resources/
│
└── README.md
```

---

## 🧰 Technologies & Tools

### Programming & Query Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)

### Data Processing

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

### Data Engineering

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge\&logo=apacheairflow\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge\&logo=apachekafka\&logoColor=white)

### DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

### Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge\&logo=googlecloud\&logoColor=white)

---

## 📚 Core Topics

### 1. Python for Data Engineering

* Python fundamentals
* Object-Oriented Programming
* File handling
* Exception handling
* APIs
* JSON / CSV processing
* Logging
* Virtual environments
* Package management

### 2. SQL

* SELECT / WHERE / GROUP BY
* JOINs
* Subqueries
* CTEs
* Window Functions
* Aggregations
* Indexing
* Query optimization
* Database transactions

### 3. Databases

* Relational databases
* NoSQL databases
* Database design
* Normalization
* Indexing
* Transactions
* Data modeling

### 4. ETL & ELT

```text
Source
  │
  ▼
Extract
  │
  ▼
Transform
  │
  ▼
Load
  │
  ▼
Data Warehouse
  │
  ▼
Analytics
```

Topics include:

* Data extraction
* Data transformation
* Data validation
* Data cleaning
* Data loading
* Batch processing
* Incremental loading
* ETL vs ELT

### 5. Data Warehousing

* OLTP vs OLAP
* Dimensional modeling
* Fact tables
* Dimension tables
* Star schema
* Snowflake schema
* Slowly Changing Dimensions
* Data marts

### 6. Data Pipelines

* Batch pipelines
* Streaming pipelines
* Pipeline orchestration
* Scheduling
* Monitoring
* Logging
* Error handling
* Data quality

### 7. Big Data

* Apache Spark
* PySpark
* Distributed processing
* Spark SQL
* DataFrames
* Partitioning
* Transformations and actions

### 8. Streaming

* Apache Kafka
* Producers
* Consumers
* Topics
* Partitions
* Consumer groups
* Event-driven pipelines

---

## 🚀 Projects

Practical projects are an important part of this repository.

Each project aims to follow a realistic Data Engineering workflow:

```text
Data Source
     │
     ▼
Extraction
     │
     ▼
Validation
     │
     ▼
Transformation
     │
     ▼
Storage
     │
     ▼
Orchestration
     │
     ▼
Analytics / Reporting
```

### Project Documentation

Each project may include:

* 📋 Project overview
* 🎯 Objectives
* 🏗️ Architecture
* 🔄 Data pipeline
* 🗄️ Database design
* 🧹 Data transformations
* 🧪 Data validation
* 🐳 Docker configuration
* ⚙️ Configuration
* 📊 Results
* 📸 Screenshots
* 📖 Documentation

---

## 🧪 Hands-on Labs

The repository also contains smaller labs and experiments designed to practice individual concepts.

Examples:

```text
SQL Queries
Python Data Processing
API Data Extraction
CSV Processing
Database Integration
ETL Pipelines
Airflow DAGs
Spark Jobs
Kafka Streaming
Dockerized Pipelines
```

---

## 📊 Data Engineering Principles

Throughout the repository, the focus is on developing solutions that are:

* **Reliable**
* **Scalable**
* **Maintainable**
* **Testable**
* **Observable**
* **Reproducible**
* **Well documented**

---

## 🔍 Data Quality

Data quality is treated as an essential part of every pipeline.

Examples of validation include:

* Missing values
* Duplicate records
* Invalid data types
* Schema validation
* Referential integrity
* Range validation
* Null checks
* Business-rule validation

---

## ⚙️ Engineering Practices

Projects aim to follow common software engineering practices:

* Clean and modular code
* Environment variables
* Configuration management
* Logging
* Error handling
* Testing
* Git version control
* Documentation
* Reproducible environments
* Containerization where appropriate

---

## 🐳 Docker

Docker is used where appropriate to create reproducible development environments.

Typical architecture:

```text
┌──────────────────────────┐
│        Application       │
├──────────────────────────┤
│        Airflow           │
├──────────────────────────┤
│       PostgreSQL         │
├──────────────────────────┤
│          Kafka           │
├──────────────────────────┤
│         Spark            │
└──────────────────────────┘
```

---

## 📈 Learning Progress

| Area             |     Status     |
| ---------------- | :------------: |
| Python           | 🟡 In Progress |
| SQL              | 🟡 In Progress |
| Databases        | 🟡 In Progress |
| Data Processing  | 🟡 In Progress |
| ETL / ELT        | 🟡 In Progress |
| Data Warehousing | 🟡 In Progress |
| Apache Airflow   |    ⚪ Planned   |
| Apache Spark     |    ⚪ Planned   |
| Apache Kafka     |    ⚪ Planned   |
| Docker           |    ⚪ Planned   |
| Cloud            |    ⚪ Planned   |

> This section will be updated as the repository evolves.

---

## 📖 Resources

Additional learning resources, references, documentation, and useful materials are collected in the `resources/` directory.

---

## 🔄 Continuous Development

This repository is continuously evolving as new concepts, technologies, experiments, and projects are added.

The focus is not only on learning **what** Data Engineering tools do, but also on understanding **why**, **when**, and **how** to use them in practical systems.

---

## 🎯 Goals

The main goals of this repository are to:

1. Build a strong foundation in Data Engineering.
2. Understand modern data architectures.
3. Develop practical data pipelines.
4. Work with real-world datasets.
5. Practice distributed data processing.
6. Understand orchestration and automation.
7. Build production-oriented projects.
8. Document the learning process and engineering decisions.

---

## 🤝 Contributions

This repository is primarily a personal learning and project space.

Suggestions, discussions, and improvements are welcome.

If you find an issue or have a useful suggestion, feel free to open an **Issue** or **Pull Request**.

---

## 📜 License

This project is licensed under the **MIT License** unless otherwise specified.

---

## ⭐ Repository Status

**🚧 Actively maintained and continuously evolving.**

> Learn → Build → Test → Document → Improve
