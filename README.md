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

## 📌 How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/DAV-Project.git
