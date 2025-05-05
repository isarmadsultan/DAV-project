# Data Analysis and Visualization Project - DAV 🌟

This is a course project for the **Data Analysis and Visualization (DAV)** subject at Namal University. The goal is to apply real-world data analysis techniques using a dataset of interest, and generate meaningful insights through visualizations and preprocessing.

---

## 📁 Dataset

- **File:** `combined_dataset.csv`
- **Description:** The dataset includes production-related information such as:
  - `team`, `department`, `targeted_productivity`, `smv`, `wip`, `over_time`, `incentive`, `idle_time`, `idle_men`, `no_of_style_change`, `no_of_workers`, and `actual_productivity`
  - Time-related fields like `date`, `quarter`, and `day`

---

## ✅ Completed Phases

### 🔍 Phase 2: Exploratory Data Analysis (EDA)
- Loaded and explored the dataset
- Identified data types and missing values
- Visualized:
  - Histograms for distribution
  - Boxplots to check outliers
  - Correlation heatmap
- **Initial Insights:**
  - `wip` has ~42% missing values
  - Outliers are present in `over_time`, `incentive`, and `idle_time`
  - Strong correlation seen between `targeted_productivity` and `actual_productivity`

---

## 🔜 Upcoming Phases

- **Phase 3:** Data Preprocessing
  - Handle missing values and outliers
  - Transform features as needed
- **Phase 4:** Correlation Analysis + Modeling

---

📦 Phase 3: Data Preprocessing
In this phase, the dataset was cleaned and transformed to prepare it for modeling:

✅ Missing Values
The column wip was removed due to over 42% missing values.

Remaining missing values were handled by dropping incomplete rows.

✅ Duplicate Records
Duplicate entries were checked and removed.

✅ Outlier Handling
Outliers in incentive, over_time, and idle_time were removed using the IQR method.

✅ Data Transformation
Categorical variables (day, quarter, department, team) were encoded using Label Encoding.

Numerical features were scaled using Min-Max Scaling.

This completed the data cleaning pipeline and ensured consistency, normality, and model-readiness of the dataset.

---
## 📈 Conclusion Summary

- Features like targeted productivity and quarter show strong correlation with actual productivity.
- Linear Regression achieved an R² score of __ and RMSE of __.
- Classification model predicted productivity levels with an accuracy of __%.
- Further improvement could be achieved by feature engineering, tuning, or using ensemble methods.
