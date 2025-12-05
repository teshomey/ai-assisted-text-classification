**By:** Teshome Kebede Deressa

**Date:** 08-Dec-2025  

---

## Overview
This README outlines the complete workflow for processing, enriching, and classifying research publications as **Regional** or **Not Regional** using metadata enhancement and AI-assisted text analysis. All scripts and procedures can be found in the `Data Analyst.ipynb` notebook. The analysis starts with three `.txt` datasets from Web of Science (WoS), which are cleaned and linked to corresponding records in OpenAlex for additional metadata. Finally, publications are categorized using an AI classification model (GPT-5.1), based on their geographic focus and research context.

---

## 📂 Project Workflow

### 0️⃣ Install Dependencies
The notebook automatically installs necessary Python packages required for:
- Data processing (e.g., pandas)
- API communication (OpenAlex)
- Data modeling

---

### 1️⃣ Data Structuring — Data Model Design
- Load necessary packages
- Import three `.txt` publication datasets  
- Initial data inspection  
- Combinig datasets  
- Column normalization/renaming for readability  
- Handling missing values & data cleaning  
- Python `dataclass` used for a clear data model (`PublicationRecord`)

---

### 2️⃣ Record Linking — OpenAlex Enrichment
- API configuration  
- Helper functions to query OpenAlex  
- Matching & retrieving enriched metadata  

---

### 3️⃣ Record Classification — AI-Assisted
- Configuration parameters  
- Helper functions for classification  
- Execution of rule-based or model-based classification

---

### 4️⃣ Data Sa
- Convert enriched and classified records into a clean CSV format  
- Ready for further analysis

---

## 🚀 How to Run This Notebook

1. Install Python 3.9+ and Jupyter Notebook
2. Open this notebook in Jupyter: `Data Analyst.ipynp`
