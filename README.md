# England Water Quality: Predictive Modelling & Database Integration
Project focus: Predictive Modeling, Environmental Monitoring, Geospatial Data Science.

![alt text](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![alt text](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![alt text](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![alt text](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![alt text](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![alt text](https://img.shields.io/badge/Geopandas-44A833?style=for-the-badge&logo=pandas&logoColor=white) ![alt text](https://img.shields.io/badge/ML-Predictive_Modeling-blueviolet?style=for-the-badge)

## 📌 Project Overview
This project utilizes Machine Learning to identify patterns in water quality across England, analyzing chemical concentrations and environmental factors to predict health levels of river systems.

## 🚀 Key Features
- **Scalable Data Pipeline:** Migrated static environmental data into an **SQLite** database for efficient retrieval.
- **Unsupervised Learning:** Applied **K-Means Clustering** to identify 3 distinct water quality profiles (Healthy, Stressed, and Severely Polluted).
- **Supervised Classification:** Developed a **Random Forest Classifier** to predict "Poor" water quality with **90% accuracy** and a **0.95 AUC score**.
- **Feature Importance:** Identified Phosphate as the primary driver of water quality degradation.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Database:** SQLite3
- **Environment:** Jupyter Notebook

## 📊 Results
- Identified specific "Severely Polluted" clusters characterized by high Ammonia and Phosphate.
- The predictive model can identify 86% of true pollution events using only chemical proxies, reducing the need for expensive continuous toxic agent monitoring.
