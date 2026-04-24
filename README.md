# Python_PBL
This repo contains phase wise work of Python PBL(PCS253) of TeamId:PY-PT17 with members:
Saksham Jain(17)-Team Leader 
Satyam Kumar(22) 
Ayush Kumar Verma(36).



***

# Institutional Energy Usage Prediction ⚡

## 📖 Project Overview
This project is an end-to-end machine learning regression system designed to analyze and predict energy usage within an institutional setting. By leveraging numerical data such as the time of day, occupancy, ambient temperature, and appliance utilization, this system aims to accurately forecast energy demands. 

The project demonstrates a complete machine learning lifecycle, from raw data acquisition and preprocessing to advanced feature selection and predictive modeling.

## ✨ Key Features & Workflow

### 1. Data Collection & Preprocessing
* **Dataset:** Utilizes a numerical dataset focused on institutional energy metrics (time of day, number of students present, ambient temperature, and appliance usage).
* **Data Cleaning:** Handles missing values and removes inconsistencies to ensure high data quality.
* **Normalization & Transformation:** Applies scaling and transformation techniques so features are uniformly processed by the machine learning algorithms.

### 2. Exploratory Data Analysis (EDA)
* **Pattern Recognition:** Analyzes daily and seasonal energy consumption trends.
* **Outlier Detection:** Identifies and handles anomalous energy spikes or drops.
* **Visualizations:** Utilizes line plots for time-series trends, histograms for distribution analysis, and correlation heatmaps to understand feature relationships.

### 3. Feature Engineering & Selection
Based on insights gathered during EDA, the following techniques are used to reduce dimensionality and improve model performance:
* **Principal Component Analysis (PCA)**
* **Forward Feature Selection**
* **Backward Feature Elimination**

### 4. Predictive Modeling
* **Algorithm:** Implements a robust machine learning regression model (e.g., Linear Regression, Random Forest, or Gradient Boosting).
* **Evaluation:** The model is rigorously evaluated using standard regression metrics (such as RMSE, MAE, and R² Score) to ensure accurate and reliable energy predictions.

---

## 🛠️ Technologies Used
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

##  Getting Started

### Prerequisites
Make sure you have Python installed. You can install the required dependencies using the following command:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```



##  Results & Conclusion
**(You can update this section once your model is trained)* *
* Successfully identified that `[Feature X]` and `[Feature Y]` are the strongest predictors of institutional energy consumption.
* The final regression model achieved an R² score of `[X.XX]` and an RMSE of `[X.XX]`, demonstrating strong predictive capabilities.
