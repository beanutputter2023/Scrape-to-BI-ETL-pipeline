# 💼 Scrape-to-BI: RemoteOK Jobs Data  

## 📌 Project Description  
This project demonstrates an **end-to-end data pipeline** built using Databricks.  

- Collected job posting data from the **RemoteOK API**.  
- Loaded raw data into the **Bronze layer**.  
- Applied cleaning and enrichment transformations in the **Silver layer**.  
- Aggregated and structured the data into the **Gold layer**, making it BI-ready.  
- Built a **Power BI dashboard** for interactive visualization and insights.  

---

## 📊 Dashboard Screenshots  
<img width="747" height="414" alt="image" src="https://github.com/user-attachments/assets/8188a2a1-5f17-4f79-9ea5-55d3766b595f" />
<img width="751" height="425" alt="image" src="https://github.com/user-attachments/assets/5682b3e4-3dd1-4c15-8a0b-60a468da3ad3" />

  

---

## 🛠 Tools Used  
- **Python** – for API calls & data ingestion  
- **PySpark** – for scalable transformations  
- **Databricks** – for data processing & Delta Lake management  
- **Power BI** – for dashboarding & visualization  

---

## 🔄 Data Flow  

```mermaid
flowchart TD
    A[RemoteOK API] --> B[Bronze: Raw Ingestion]
    B --> C[Silver: Cleaned & Enriched Data]
    C --> D[Gold: Aggregated Tables]
    D --> E[Power BI Dashboard]
