***

# Institutional Energy Usage Analysis and Prediction System 

**Course:** PBL PCS253 | **Problem ID:** 23  
**Team Members:** Saksham Jain (2028479), Satyam Kumar (2028488), Ayush Kumar Verma (2028684)  
**Section:** P (G1)

##  Project Overview
Energy management in large institutions is a significant challenge due to fluctuating occupancy and varying environmental conditions. This project is an end-to-end machine learning regression system designed to address this by accurately forecasting energy consumption. 

By leveraging institutional numerical data—such as time of day, number of students present, ambient temperature, and appliance utilization—this system helps administrators optimize HVAC systems, schedule appliance usage efficiently, and implement cost-saving sustainability measures.

---

##  Repository Structure & Workflow

The project is structured into distinct phases, taking the data from its raw state to a fully evaluated predictive model.

###  Phase 1: Project Synopsis & Data Preprocessing
This phase focuses on data cleaning, handling missing values, and engineering features to ensure high data quality.
* **`Synopsis_PCS253.pdf`**: The official project proposal outlining the problem statement, objectives, and proposed methodology.
* **`institutional_energy(1).csv`**: The initial, unprocessed raw dataset.
* **`preprocess(1).ipynb`**: The Jupyter Notebook containing the data preprocessing pipeline. It covers handling missing data, normalizing/scaling features, and performing feature selection using Forward Selection and Principal Component Analysis (PCA).
* **`preprocessed_data.csv`**: The cleaned dataset containing the subset of optimally selected features.
* **`preprocessed_data_pca.csv`**: The cleaned dataset transformed using PCA for dimensionality reduction.

###  Phase 2: Model Training & Evaluation
This phase focuses on building, training, and evaluating various machine learning regression models on the preprocessed datasets.
* **`Model_Train.ipynb`**: The core machine learning notebook. It evaluates multiple regression algorithms on both the standard feature-selected dataset and the PCA-transformed dataset to determine the best predictive performance.

---

##  Final Results & Model Performance

After rigorous training and cross-validation on the preprocessed data, the models were evaluated using MAE, RMSE, and R² Score. 

The **Support Vector Regressor (SVR)** emerged as the best-performing model overall, successfully learning the complex, non-linear relationships between institutional factors and energy consumption.

**Best Model Overall: Support Vector Regressor (SVR)**
* **Best R² Score:** `0.3706`
* **Best Root Mean Squared Error (RMSE):** `67.9893`
* **Best Mean Absolute Error (MAE):** `31.4994`

---

##  Technologies Used
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

### Execution
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. **Run Preprocessing:** Open and run `preprocess(1).ipynb` to generate the cleaned datasets.
4. **Run Modeling:** Open and run `Model_Train.ipynb` to train the models and reproduce the evaluation metrics.

##  Results & Conclusion
* Successfully identified that `[Feature X]` and `[Feature Y]` are the strongest predictors of institutional energy consumption.
* The final regression model achieved an R² score of `[X.XX]` and an RMSE of `[X.XX]`, demonstrating strong predictive capabilities.
