# Churn_prediction_model
This repository contains code for predicting Customer Churn on Telecommunication company using various machine learning algorithms. The dataset is loaded using Python libraries like NumPy, Pandas, Seaborn, and Matplotlib. The analysis includes data visualization, data preprocessing, feature engineering, and model training. The models used for prediction are:
1. Categorical Boost Classifier
2. Random Forest Classifier
3. SMOTETomek technique
5. Tomeklinks

# What have I done?
1. I have preprocessed the data to handle missing and categorical values, and prepare it for analysis.
2. Performed EDA(you can find in the EDA file).
3. Visualized the key findings and also reported in the pdf report attached.
4. Implemented Feature engineering for predicting churn.

# What is Churn?
Churn prediction involves identifying customers who might cancel a service based on their usage patterns. This prediction holds significant importance for businesses as retaining existing customers is more cost-effective than acquiring new ones. Detecting at-risk customers enables tailored marketing strategies, allowing businesses to take specific actions for each customer, ultimately increasing the likelihood of customer retention. 

# Steps involved in Model Deployment:
1. Data Analysis (EDA)
2. Data Preprocessing.
3. Feature Engineering.
4. Feature Selection (SelectKBest)
5. Fit into Algorithm (ML Algorithm)

# Objective of the model
1. To determine the percentage of customers who churn and those who remain active
3. To analyze the data to identify features influencing customer churn, and
4. To identify the most suitable machine learning model for accurately classifying churn and non-churn customers.

# EDA insights
1. Contract-categorization 

![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/e17b497d-e955-4e1b-899f-36a1aa23be59)

2. Payment-tenure relation 

![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/5581afa3-582d-414b-a5ad-adde765de38b)

3. Heatmaap
   
![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/e65ac089-6417-4508-b845-70241857d465)

4. Grouping shows Non-senior Citizen are more churners
   
![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/76a62979-0076-495d-a3a1-e1b8ec48865d)

5. Corelation of Churn to other features
   
![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/510d8ac8-2d28-4bc3-8526-ae0eb2af9546)

# Modeling 
I tried the model to work on two machine learning models: 
1. Categorical Boost with SMOTETomek( Higher Accuracy and F1 Score)
2. Random Forest Classifier
   
Both models were trained on a dataset containing various customer features( ‘Age’, ‘Martial Status’, ‘Monthly Charges’, ‘Gender’) and with the Kaggle dataset provided in the Google Form. Here is the model Comparison for the Both - 

# Model Comparison 
1. The Random Forest Classifier was one of the models I tested. It works by combining many decision trees to predict whether customers might leave. In my tests, it showed good accuracy(0.82) and a fair F1 score, indicating it's decent at predicting customer churn in our dataset.

Observations: While Random Forest showed acceptable performance, it fell short in addressing class imbalance issues inherent in the dataset.

![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/ff5c8322-fd62-4858-9e6a-10bab56f0689)

2. During my evaluation, I tried Categorical Boost with SMOTETomek. Categorical Boost builds models step by step, focusing on areas where previous models had trouble. This approach is great for fixing mistakes and works well with imbalanced data like in churn prediction. SMOTETomek, the trick I added, balances out the uneven data by adjusting how many examples it uses from each group.

Observations: Categorical Boost, particularly when coupled with SMOTETomek for handling imbalanced data, outperformed Random Forest in handling the class imbalance and predicting churn accurately.

![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/34f14ff3-c0d1-4c17-b8b2-e50b62087cd7)

![image](https://github.com/Shashankforcode2408/Churn_prediction_model/assets/126846732/0b394316-fab9-4ead-95e1-87594491305c)

# Find More detailed report and analysis in the Report file and RAID document. 
















