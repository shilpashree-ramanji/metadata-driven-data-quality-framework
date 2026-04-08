# 📊 Metadata-Driven Data Quality Framework

## 🚀 Overview

This project implements a **metadata-driven data quality validation framework** designed for media/marketing datasets (Meta, LinkedIn, TikTok).

The framework automates data validation checks such as:

* Schema validation
* Completeness checks
* Metric validation (CTR, spend, impressions)
* Volume and freshness checks

---

## 🎯 Key Features

* Metadata-driven (no hardcoding)
* Reusable validation rules
* Scalable for multiple datasets
* PySpark-based execution
* Supports business and metric validations

---

## 🏗️ Architecture

```
Raw Data → Validation Engine → Results → Pass/Fail Decision
```

---

## 📂 Project Structure

* `config/` → Excel-based rule definitions
* `src/validation/` → Core validation engine
* `notebooks/` → Demo execution
* `data/` → Sample datasets

---

## ⚙️ Technologies Used

* PySpark
* Azure Databricks
* Delta Lake
* Python

---

## 📊 Sample Validations

* Null checks
* Spend ≥ 0
* Impressions ≥ Clicks
* CTR validation
* Record count deviation

---

## 🚀 Future Enhancements

* UI-based rule configuration
* Dashboard for validation monitoring
* Integration with Unity Catalog

---

## 👩‍💻 Author

Shilpa – Data Engineer
