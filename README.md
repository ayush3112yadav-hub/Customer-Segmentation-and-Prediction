# 🛒 Customer Segmentation & Predictive Modelling Pipeline

An end-to-end machine learning project built in Python that segments insurance customers using unsupervised learning and predicts future premium amounts using supervised regression.

---

## 🚀 Project Overview
This project processes a robust customer dataset to:
1. **Clean & Format Data:** Handle duplicates, format dates, and verify data integrity.
2. **Engineer Features:** Calculate customer tenure, financial ratios (premium-to-coverage), and age cohorts.
3. **Customer Segmentation:** Apply **K-Means Clustering** (optimized via the Elbow Method) to group customers into 4 distinct behavioural tribes.
4. **Predictive Modelling:** Train a **Random Forest Regressor** to forecast customer premium amounts with high accuracy.
5. **Evaluation & Insights:** Evaluate model performance (RMSE & R² Score) and derive targeted marketing strategies.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`StandardScaler`, `KMeans`, `RandomForestRegressor`, `train_test_split`)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** VS Code

---

## 📂 Repository Structure
```text
├── customer_analysis.py                  # Main Python script (Tasks 1-6)
├── customer_segmentation_data.csv        # Raw dataset
├── customer_segmented_predictions.csv    # Final processed output with clusters & predictions
├── elbow_curve.png                       # Elbow method visualization for K-Means
├── Customer_Segmentation_Project_Summary.docx # Detailed project journey & executive summary
└── README.md                             # Project documentation
```

## 💻 How to Run the Code

### 1. Clone this repository or download the files into your local directory.

### 2. Install the required dependencies in your terminal:
```
Bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
### 3. Run the main analysis script:
```
Bash
python customer_analysis.py
```
