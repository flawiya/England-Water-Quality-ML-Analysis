# England Water Quality: Predictive Modelling & Database Integration

## 📌 Project Overview
This project develops a data-driven system for monitoring and predicting water quality across England. By integrating relational databases (SQLite) with machine learning, the project identifies hidden pollution patterns and builds an early-warning system for ecological degradation.

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
