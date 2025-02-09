# IdentifyPhishingURL

For our project, we used an AI-driven approach to identify phishing URLs by attempting to extract patterns and key characteristics of both legitimate and malicious links. Using the Data Science Lifecycle, along with the SMART approach, we will process and analyze a large dataset from PhiUSIL to distinguish phishing links from legitimate ones. 

The dataset used can be found here: https://www.kaggle.com/datasets/ndarvind/phiusiil-phishing-url-dataset

After cleaning the data, conducting EDA and feature engineering, we formed 3 models: Logistic Regression, Random forest and SVM. Random forest was the most accurate model as it did not have any false positives. Logistic regression was the second most accurate with 6 false positives. SVM was rather inaccurate with 175 false positives. Thus, we successfully created a reliable model (Random Forest) to predict whether a given link was a phishing link or not. 
