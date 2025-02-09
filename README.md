# IdentifyPhishingURL

For our project, we used an AI-driven approach to identify phishing URLs by attempting to extract patterns and key characteristics of both legitimate and malicious links. Using the Data Science Lifecycle, along with the SMART approach, we will process and analyze a large dataset from PhiUSIL to distinguish phishing links from legitimate ones. 

The dataset used can be found here: https://www.kaggle.com/datasets/ndarvind/phiusiil-phishing-url-dataset

After cleaning the data, conducting EDA and feature engineering, we formed 3 models: Logistic Regression, Random forest and SVM. Random forest was the most accurate model as it did not have any false positives. Logistic regression was the second most accurate with 6 false positives. SVM was rather inaccurate with 175 false positives. Thus, we successfully created a reliable model (Random Forest) to predict whether a given link was a phishing link or not. 

To answer our problem statement “How can we identify malicious phishing links by examining patterns between legitimate and phishing URLs?”, we should look at 11 different features. They are:  
1.	How similar the URL is to a legitimate URL
2.	Presence of social media
3.	Presence of copyright information
4.	The number of self-referral links
5.	Presence of description
6.	Image ratio
7.	Presence of complicated, unpredictable or random URLs
8.	Use of HTTPs
9.	Domain title similarity
10.	Presence of a submit button
11.	Responsivity of the webpage
    
These features allowed us to create a reliable mechanism to detect phishing URLs.
