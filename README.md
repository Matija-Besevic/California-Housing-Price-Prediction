# California Housing Market Analysis & Price Prediction 🏡📊

An end-to-end Data Science and Machine Learning project focused on analyzing census data to understand housing trends and predict median house values in California.

---

## 📑 Project Overview
This project targets a core real estate problem: **predicting housing prices based on location, demographics, and structural features.** 

The pipeline includes automated data ingestion, thorough Exploratory Data Analysis (EDA), feature engineering, and predictive modeling. It serves as a production-ready template for handling external datasets cleanly and efficiently.

## 🛠️ Tech Stack & Libraries
- **Data Engineering:** `urllib`, `tarfile`, `os`
- **Data Analysis:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`

---

## 📁 Repository Structure
```text
├── datasets/                    # Created automatically (ignored by Git)
│   └── housing/housing.csv      # The extracted dataset
├── fetch_data.py                # Automated data ingestion script
├── California_Housing_Analysis.ipynb  # Jupyter Notebook for EDA & Modeling
├── .gitignore                   # Prevents uploading large data files
└── README.md                    # Project documentation
