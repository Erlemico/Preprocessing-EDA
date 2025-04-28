# Data Pre-processing, Feature Selection, and Exploratory Data Analysis for Pharmacy Sales Dataset

## 📋 Project Overview
This project focuses on preparing and analyzing a pharmacy sales dataset through proper data pre-processing, feature selection, and exploratory data analysis (EDA).  
The goal is to clean the dataset, select important features, and gain insights that are useful for further predictive modeling or business decision-making.

---

## 📈 Objectives
- Handle missing values and outliers in the dataset.
- Apply data transformations such as standardization, encoding, and binning.
- Perform feature selection using the Filter Method (Variance Threshold).
- Explore data visually using distribution plots, boxplots, heatmaps, and pairplots.
- Derive insights from the cleaned and transformed dataset.

---

## 📂 Dataset
- **Source:** Pharmacy sales transaction data
- **Format:** CSV
- **Size:** ~411,646 rows and multiple columns including transaction details, drug codes, quantities, and therapeutic classes.

---

## 🔧 Methods and Techniques
- **Missing Value Handling:**  
  - Numeric columns: filled with median values  
  - Categorical columns: filled with mode or 'Unknown' for specific columns

- **Outlier Detection and Handling:**  
  - Interquartile Range (IQR) method

- **Data Transformation:**  
  - Standardization (StandardScaler)
  - Label Encoding
  - Binning (`qty` and `hj` into categories)

- **Feature Selection:**  
  - Variance Threshold (Filter Method)

- **Exploratory Data Analysis:**  
  - Distribution plots
  - Boxplots
  - Correlation Heatmap
  - Pairplot (sampled 5000 rows for efficiency)

---

## 📊 Key Findings
- Strong positive correlation between `hna` and `hj` (net price and selling price).
- Distinct patterns in quantity and selling price distributions across different therapeutic classes.
- Successful cleaning and transformation of dataset, ready for further modeling tasks.

---

## 💻 How to Run
1. Clone the repository.
2. Install the required libraries (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn).
3. Open the Jupyter Notebook.
4. Run each cell sequentially to see the cleaning, transformation, and analysis processes.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📚 Project Structure
```plaintext
├── README.md
├── Data Preprocessing and Feature Selection.ipynb
```

---

## 📢 Acknowledgements
- Pharmacy sales data used for educational and analytical purposes.
- Guided by academic materials on Data Pre-processing and Feature Selection.

---