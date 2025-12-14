# Eye Cancer Patient Segmentation Using Clustering

This project applies **unsupervised machine learning techniques** to analyze and segment eye cancer patient data. It involves extensive exploratory data analysis (EDA), data preprocessing, dimensionality reduction using PCA, and clustering using multiple algorithms to uncover meaningful patient groups.

## Project Objectives
- Perform **exploratory data analysis (EDA)** on eye cancer patient data
- Preprocess and encode categorical and numerical features
- Apply **feature scaling and PCA** to reduce dimensionality
- Segment patients using **clustering algorithms**
- Compare clustering techniques for medical data interpretation

## Tech Stack
- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and preprocessing

## 🧪 Project Workflow
#### Exploratory Data Analysis (EDA)
- Checked data types, missing values, and duplicates
- Analyzed categorical and numerical distributions
- Visualized correlations and feature relationships

#### Data Preprocessing
- Dropped non-informative columns (`Patient_ID`, `Date_of_Diagnosis`)
- Ordinal encoding for cancer stage
- One-hot encoding for categorical variables
- Converted binary indicators to integer format

#### Feature Scaling & Dimensionality Reduction
- Applied **StandardScaler** to normalize features
- Used **PCA (95% variance retained)** to reduce dimensionality and improve clustering performance


## 📊 Results & Insights

- PCA significantly reduced dimensionality while preserving key information
- KMeans produced stable and interpretable patient segments
- Hierarchical clustering provided additional insights into cluster structure
- The segmented clusters can help in understanding patient subgroups based on treatment patterns and outcomes


## Note on DBSCAN

DBSCAN was explored but not finalized, as density-based clustering did not naturally produce stable clusters for this medical dataset. Centroid-based methods were found to be more suitable.

## 📌 Conclusion

This project demonstrates how **unsupervised learning** can be effectively used in the healthcare domain to segment patients and extract meaningful patterns from complex medical data.

