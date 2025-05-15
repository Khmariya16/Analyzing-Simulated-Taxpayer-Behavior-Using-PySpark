# 🧾 Analyzing Simulated Taxpayer Behavior Using PySpark

This project analyzes and clusters simulated taxpayer profiles based on behavioral and risk-related features using **PySpark**. The objective is to identify patterns that can help tax authorities or analysts in risk segmentation, audit prioritization, or compliance behavior understanding.

---

## 📁 Files Included

- `Taxpayer_Clustering_PySpark.ipynb` – Jupyter notebook with complete PySpark code for preprocessing, clustering, and analysis.
- `simulated_taxpayer_data.csv` – Sample dataset with 100 taxpayer records for testing and development.
- `README.md` – Project overview and instructions.

---

## 🛠️ Tools & Technologies

- **PySpark**
- **Python**
- **SQL (via Spark SQL)**
- **Matplotlib / Seaborn** (for optional visualization)
- **Jupyter Notebook**

---

## 📊 Dataset Features

| Column               | Description                                        |
|----------------------|----------------------------------------------------|
| `taxpayer_id`        | Unique ID of the taxpayer                          |
| `income`             | Annual declared income (in local currency)         |
| `filing_delay_days`  | Number of days late in filing returns              |
| `underreporting_score` | Score (0–1) indicating possible income underreporting |
| `audit_flag`         | Binary flag (1 = audited, 0 = not audited)         |
| `region`             | Geographic region                                  |

---

## 🚀 How to Run

1. **Install Requirements**  
   Make sure you have Python and PySpark installed:
   ```bash
   pip install pyspark matplotlib seaborn
