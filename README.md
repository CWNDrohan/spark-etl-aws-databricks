# AWS S3 + Spark ETL with Databricks

This project demonstrates an end-to-end ETL pipeline using PySpark on Databricks with data ingested directly from an AWS S3 bucket. Built as the final project for DATA603 (Big Data Processing), it showcases secure credential handling, external cloud storage integration, and scalable processing of structured data in a Spark environment.

---

## 🔍 Problem Statement

The objective of this project was to process and analyze large CSV datasets stored in an AWS S3 bucket using PySpark. Tasks included securely accessing the data, loading it into Spark DataFrames, performing basic transformations and analyses, and visualizing the results within Databricks.

---

## 📈 Data Access & Technologies

* **Storage:** Amazon S3 (mounted in Databricks)
* **Cluster:** Databricks Community Edition (single node)
* **Tools:**

  * PySpark (`pyspark.sql.functions`, `types`)
  * AWS access via programmatic keys
  * `dbutils.fs` for file access and mounting
  * `matplotlib` for basic visualizations

---

## 📅 Pipeline Steps

1. Access AWS credentials from a private CSV (mounted internally)
2. Parse and encode credentials securely using `urllib`
3. Mount S3 bucket using Databricks utilities
4. Read CSV into Spark DataFrame
5. Display file metadata and verify structure
6. (Optional) Clean, transform, and visualize data

---

## 🎓 Learning Outcomes

* Hands-on use of PySpark and Databricks with real S3 integration
* Implemented a programmatic credential workflow without hardcoding
* Practiced scalable data loading, schema handling, and display tools within a Spark environment

---

## 📁 Repo Structure

```
spark-etl-aws-databricks/
├── notebooks/
│   └── latest.ipynb              # Final cleaned Databricks notebook
├── data/                            # AWS credential notes or sample (excluded)
├── thumbnail.png                    # GitHub/LinkedIn visual
└── README.md
```

---

## 📇 Credits

Final project for DATA603: Big Data Processing
University of Maryland, Baltimore County (UMBC) – MPS in Data Science
Author: Craig Drohan
