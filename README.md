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


ML_Assignment_3-Regression
Regression Assignment Objective: The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset. Dataset: Use the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices. Key Components to be Fulfilled: Loading and Preprocessing (2 marks): Load the California Housing dataset using the fetch_california_housing function from sklearn. Convert the dataset into a pandas DataFrame for easier handling. Handle missing values (if any) and perform necessary feature scaling (e.g., standardization). Explain the preprocessing steps you performed and justify why they are necessary for this dataset. Regression Algorithm Implementation (5 marks): Implement the following regression algorithms: Linear Regression Decision Tree Regressor Random Forest Regressor Gradient Boosting Regressor Support Vector Regressor (SVR) For each algorithm: Provide a brief explanation of how it works. Explain why it might be suitable for this dataset. Model Evaluation and Comparison (2 marks): Evaluate the performance of each algorithm using the following metrics: Mean Squared Error (MSE) Mean Absolute Error (MAE) R-squared Score (R²) Compare the results of all models and identify: The best-performing algorithm with justification. The worst-performing algorithm with reasoning. Timely Submission (1 mark): Submit your code in a Jupyter Notebook format via a GitHub link. Ensure that your code is well-documented and explanations are clear and concise. Submission Guidelines: Use Python and Jupyter Notebook for implementation. Submit the GitHub repository link containing the code and all necessary files. Ensure proper documentation, including code comments and markdown explanations. Total Score: 10



ML-Assignment-4-Classification Problem
Objective: The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset. Dataset: Use the breast cancer dataset available in the sklearn library. Key components to be fulfilled: 1. Loading and Preprocessing (2 marks) Load the breast cancer dataset from sklearn. Preprocess the data to handle any missing values and perform necessary feature scaling. Explain the preprocessing steps you performed and justify why they are necessary for this dataset. 2. Classification Algorithm Implementation (5 marks) Implement the following five classification algorithms: 1. Logistic Regression 2. Decision Tree Classifier 3. Random Forest Classifier 4. Support Vector Machine (SVM) 5. k-Nearest Neighbors (k-NN) For each algorithm, provide a brief description of how it works and why it might be suitable for this dataset. 3. Model Comparison (2 marks) Compare the performance of the five classification algorithms. Which algorithm performed the best and which one performed the worst? 4. Timely Submission (1 mark) Submission Guidelines: Provide your code in a Jupyter Notebook format and submit the GitHub link here. Ensure your explanations and answers are clear and concise. Total Score: 10


ML-Assignment-5-Clustering Algorithm
Objective: The objective of this assessment is to evaluate your understanding and ability to apply clustering techniques to a real-world dataset. Dataset Use the Iris dataset available in the sklearn library. Key components to be fulfilled : 1. Loading and Preprocessing (1 marks) Load the Iris dataset from sklearn. Drop the species column since this is a clustering problem. 2.Clustering Algorithm Implementation (8 marks) Implement the following two clustering algorithms: A) KMeans Clustering (4 marks) Provide a brief description of how KMeans clustering works. Explain why KMeans clustering might be suitable for the Iris dataset. Apply KMeans clustering to the preprocessed Iris dataset and visualize the clusters. B) Hierarchical Clustering (4 marks) Provide a brief description of how Hierarchical clustering works. Explain why Hierarchical clustering might be suitable for the Iris dataset. Apply Hierarchical clustering to the preprocessed Iris dataset and visualize the clusters. 3.Timely Submission (1 mark) Submission Guidelines Provide your code in a Jupyter Notebook format and submit the GitHub link here. Ensure your explanations and answers are clear and concise. Total Score: 10
