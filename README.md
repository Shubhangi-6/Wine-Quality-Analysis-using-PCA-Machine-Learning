# Wine-Quality-Analysis-using-PCA---Machine-Learning




**Project Title: PCA Wine Analysis with Logistic Regression**

**Introduction:**
- This project leverages AI and machine learning techniques to analyze and classify wine data using Principal Component Analysis (PCA) and Logistic Regression.

**Steps:**

1. **Data Gathering:**
   - The dataset, sourced from a local file, provides comprehensive information about various wine attributes.
     
2. **Principal Component Analysis (PCA):**
   - Standard Scaling was applied to the dataset to standardize the features.
   - PCA was employed to reduce the dimensionality of the dataset while maintaining a high percentage of explained variance.
   - The explained variance ratios for principal components were analyzed, revealing the most influential features contributing to the variance in the dataset.

2. **Exploratory Data Analysis (EDA):**
   - Conducted an initial exploration of the dataset, including its shape, information, and summary statistics.
   - No missing values were found, ensuring the integrity of the dataset.

3. **Feature Engineering:**
   - Identified outliers in specific columns using the Interquartile Range (IQR) method.
   - Implemented a custom function to replace outliers, enhancing data quality.

4. **Outliers handling:**
   - Outliers in key wine attributes (e.g., Malic.acid, Ash, Acl, Mg, Proanth, Color.int, Hue) were identified and replaced, ensuring a more robust and reliable 
    dataset for analysis.

4. **Principal Component Analysis (PCA):**
   - Applied Standard Scaling to standardize the dataset.
   - Utilized PCA to reduce the dimensionality of the dataset while preserving its variance.

5. **Model Training:**
   - Split the dataset into training and testing sets for model evaluation.
   - Trained a Logistic Regression model, a widely used algorithm in machine learning.

6. **Model Evaluation (Training Set):**
   - Assessed model performance on the training set using accuracy, confusion matrix, and visualized results through a scatter plot.

7. **Model Evaluation (Testing Set):**
   - Extended the evaluation to the testing set, ensuring robustness and generalization of the model.

**Results:**
- The Logistic Regression model demonstrated significant accuracy on both training and testing sets.
- Principal Component Analysis revealed the most influential features in the dataset.


AI, Machine Learning, Logistic Regression, Principal Component Analysis (PCA), Feature Engineering, Outlier Detection, Model Training, Model Evaluation, Data Analysis, Wine Dataset.

