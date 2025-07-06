This project analyzes property prices in Bangalore using the dataset house_price.csv.
##  Objectives

1. Perform **Exploratory Data Analysis (EDA)**.
2. Detect and remove **outliers** in `price per sqft` using:
   - Mean & Standard Deviation
   - Percentile Method
   - Interquartile Range (IQR)
   - Z-score Method
3. Use **box plots** to compare the effectiveness of outlier removal techniques.
4. Check for **normality** of the price/sqft data and apply **transformations** if required.
5. Plot **correlation heatmaps** and **scatter plots** to understand relationships between numerical variables.

### 1. **EDA**
- Summary statistics
- Missing value checks
- Data type identification

### 2. **Outlier Detection**
- **Mean ± 3*Standard Deviation**
- **Percentile Method** (e.g., 1st–99th percentile trimming)
- **IQR Method** (Q1 - 1.5*IQR, Q3 + 1.5*IQR)
- **Z-score Thresholding** (|Z| > 3)
Outliers are removed using:
- Trimming (hard removal)
- Capping (winsorization)
- Imputation (mean/median)

### 3. **Visualization**
- Box plots (before/after outlier removal)
- Histograms & KDE plots
- Heatmap (correlation matrix)
- Scatter plots between numeric features
  
- ### 4. **Normality Checks**
- Skewness & Kurtosis
