# End-to-End-Supply-Chain-Data-Pipeline
A production-grade Medallion Architecture (Bronze/Silver/Gold) using Azure Databricks, PySpark, and Delta Lake, visualized in Power BI.

# 📊 Supply Chain Data Engineering Project

## 🏗️ Architecture
Ingested 180k+ rows of Supply Chain data from Azure Data Lake Gen2 into a Medallion Architecture.

* **Bronze**: Raw CSV Ingestion.
* **Silver**: PySpark cleaning, deduplication, and Delta Lake conversion.
* **Gold**: SQL aggregations for business KPIs.

## 🛠️ Tech Stack
* **Cloud**: Azure (ADLS Gen2, Entra ID)
* **Processing**: Databricks (PySpark, Spark SQL)
* **Storage**: Delta Lake
* **Visualization**: Power BI (DirectQuery)

## 💡 Key Business Insight
Identified that the 'Fan Shop' category generated the highest revenue, allowing for targeted inventory optimization.

## 🛡️ Security
* Credentials managed via **Databricks Secret Scopes**.
* Placeholder configurations used for public code safety.

* ![Dashboard Preview](dashboard_preview.png)
