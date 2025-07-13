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

ML_Assignment_2_EDA_and_Preprocessing
Objective: The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning. Dataset: https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing Key Components to be fulfilled: Data Exploration: (Score : 2) Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns. Data Cleaning: (Score : 2) Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers. Replace the value 0 in age as NaN Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode) Data Analysis: (Score : 2) Filter the data with age >40 and salary<5000 Plot the chart with age and salary Count the number of people from each place and represent it visually Data Encoding: (Score : 2) Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms. Feature Scaling: (Score : 2) After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler. Total Score : 10


