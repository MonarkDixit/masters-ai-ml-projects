# Forest Cover Type Prediction using Machine Learning

This project develops an end-to-end machine learning pipeline to classify forest cover types using cartographic and environmental variables such as elevation, slope, soil type, wilderness areas, and distances to natural features.

The objective is to demonstrate how data exploration, statistical reasoning, feature engineering, and machine learning models can be combined to solve a real-world ecological classification problem efficiently.

---

## 📌 Problem Overview

Accurately identifying forest cover types is important for environmental monitoring, conservation planning, and resource management. Traditional field surveys are time-consuming and expensive, making machine learning a scalable alternative.

This project predicts forest cover categories based purely on terrain and geographic measurements.

---

## 📊 Dataset

Source: UCI Machine Learning Repository – Forest Cover Type Dataset  

- 55 cartographic and environmental features  
- 7 forest cover classes  
- Includes continuous variables and binary wilderness/soil indicators  

Key features include:
- Elevation, slope, and hillshade values  
- Distance to roads, water bodies, and fire points  
- Wilderness area indicators  
- Soil type classifications  

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes:

- Distribution analysis of continuous features  
- Correlation analysis between environmental variables  
- Identification of skewed features  
- Visualization of feature importance patterns  

Insights such as elevation being strongly linked to forest type were validated through data analysis.

---

## 🧪 Feature Engineering & Preprocessing

- Log transformations applied to skewed variables  
- Scaling and normalization where required  
- Feature selection using model-based importance  
- Dimensionality reduction experiments using PCA  

This helped improve model stability and performance.

---

## 🤖 Machine Learning Models Implemented

- Random Forest Classifier (primary high-performance model)  
- Extra Trees Classifier  
- Histogram-based Gradient Boosting  
- Logistic Regression (baseline comparison)  

Hyperparameter tuning was applied to improve predictive accuracy.

---

## 📈 Model Performance

- Achieved approximately **95% test accuracy** using Random Forest  
- Strong class-wise performance across forest types  
- Feature importance revealed elevation as the most predictive variable  

Evaluation methods used:
- Accuracy score  
- Confusion matrix  
- Classification report  

---

## 📌 Key Insights

- Terrain elevation plays a dominant role in determining forest cover type  
- Environmental proximity variables significantly influence classification  
- Tree-based ensemble models outperform linear approaches for this dataset  

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 📂 Project Files

- `forest_cover_ml_pipeline.ipynb` — complete notebook with code, explanations, and results  

---

## 🎯 Conclusion

This project demonstrates how machine learning can accurately classify ecological environments using only geographic and cartographic data. The approach enables scalable environmental monitoring and provides insights into the most influential environmental factors affecting forest composition.

---

## 👤 Author

**Monark Dixit**  
Master’s Student in Applied Machine Learning  
University of Maryland – College Park
