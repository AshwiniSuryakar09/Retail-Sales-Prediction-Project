# ML-Retail-Sales-Prediction-Project--
> **AlmaBetter Verified Project** - [**Credentials**]()


 ![rossman store](https://github.com/AshwiniSuryakar09/Retail-Sales-Prediction-Project/blob/main/Rossmann%20image.png)

 >Click on the following link to check out the video presentation and the colab file.

 >[Video]()

 >[Colab](https://colab.research.google.com/drive/1ZRG16TMEz3RhMklFcxhRvBBjM2nZdjYL?usp=sharing)
 
📊 This repository contains the code and documentation for the Rossman Sales Prediction project. 🛍️ The goal of this project is to forecast the daily sales of Rossmann stores up to six weeks in advance.
📈 By accurately predicting sales, store managers can make informed decisions regarding promotions, competition, holidays, and other factors that influence sales performance. 📅

># Problem Statement:

Rossmann operates over 3,000 drug stores in 7 European Countries. Rossmann store managers are currently tasked with predicting their daily sales up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the 'Sales' column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment

># Project Summary:
The Rossman Sales Prediction project involved extensive data analysis, feature engineering, and model selection to forecast sales accurately. Here is a brief overview of the project steps and key findings:
 ### 1. Data collection and Cleaning
  * Collected historical sales data for Rossmann stores, including competitor details, holiday details, customer details, and daily sales detail
  * Cleaned and prepared the dataset for analysis ensuring data integrity
  * Handled missing values and outliers to improve the quality of the data.
### 2. Exploratory Data Analysis (EDA)
* Conducted in-depth EDA to extract valuable insights from the data set by exploring univariate, bivariate, and multivariate relationships.
* Generated insightful visualizations to uncover patterns and trends in the data.
* Extracted meaningful insights to inform future decision-making in the machine learning pipeline.
### 3. Feature Engineering and Preprocessing
* Engineered new features, including PromoDuration and Competition Distance, to capture essential information.
* Addressed multicollinearity among independent variables using variance inflation factor (VIF) analysis.
* Detected and managed outliers using the Interquartile Range (IQR) technique.
* Applied One-Hot Encoding to categorical variables for compatibility with machine learning algorithms.
* Employed various transformation techniques to achieve a normal distribution of data.
### 4. Model Selection and Training
* Split the preprocessed data into training and testing sets to evaluate model performance.
* Implement multiple machine learning algorithms, including linear regression, decision trees, and random forest with regression techniques
* Evaluated model performance using metrics such as R-squared score, means square error, and root mean square error
* Employed regularization techniques, including Lasso, Ridge, and Elastic Net, to enhance model performance.
### 5. Conclusion
* After thorough experimentation with various machine learning The XGBoost model emerged as the top-performing model for sales prediction.
* It achieved an impressive R2 score of around 98%** on the training data and maintained 97% on the test dataset.
* The model displayed lower Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) values compared to other models, indicating superior predictive accuracy.
* Consistent performance across multiple evaluation metrics, including R2 score, MSE, and RMSE, suggests robust generalization.
* Residuals analysis revealed well-behaved residuals with mean and median values close to zero, affirming the model's ability to capture underlying data patterns effectively

This project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. 
The insights from the analysis provide valuable information for decision-making within the retail industry.

> ## Author
[Ashwini Suryakar](https://www.linkedin.com/in/ashwini-suryakar-b4b68523a/)
