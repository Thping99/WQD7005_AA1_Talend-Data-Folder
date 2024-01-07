#PROJECT OVERVIEW (README)

The case study titled "E-Commerce Platform Customer Churn Prediction" delves into the intricate task of foreseeing customer churn within the framework of an online retail platform. Positioned as a pivotal objective, the project utilizes a dataset embodying 12 distinct customer attributes, including critical information such as age, gender, location (specifically in Malaysia), membership tier (ranging from Bronze to Platinum), total purchases, total spent, favorite category, last purchase date, occupation, website visits per month, and a binary churn indicator (1 denoting churned, 0 signifying active customers). The primary aim of this endeavor is to construct a predictive model, employing SAS e-Miner, that discerns potential churn patterns and equips the e-commerce platform with actionable insights for targeted customer retention strategies. 

In conjunction with SAS e-Miner, the project integrates Talend Data Integration and Talend Data Prep to ensure a seamless and comprehensive analytical pipeline. Talend Data Prep takes center stage in the preliminary stages, acting as the vanguard for data preprocessing and cleansing. It addresses data quality concerns, handles missing values, and facilitates feature engineering to refine the dataset for subsequent analysis. Simultaneously, Talend Data Integration comes into play, orchestrating the harmonious integration and transformation of data from diverse sources. However, we only use it for filtering out missing values for this report. The tool streamlines the data pipeline, guaranteeing a coherent flow of information between the analytics-driven SAS e-Miner and the preparatory Talend Data Prep. 

SAS e-Miner, as the crux of advanced analytics, undertakes the development and evaluation of the churn prediction model. It plays a crucial role in assessing model accuracy, precision, recall, and other pertinent metrics. In this report, we have executed SAS Enterprise Miner for Decision Tree Model, Random Forest (Bagging) and Gradient Boosting Model for model comparison. Moreover, SAS e-Miner's exploratory data analysis capabilities unravel insights into customer behavior, allowing for the identification of key factors influencing churn and a nuanced understanding of customer engagement dynamics. 

The description for all the CSV and Excel File attached: 

#Dataset_WQD7005_AA1.csv (Own generated dataset) 

#Dataset_WQD7005_AA1_DataPrep_v1.xlsx (Cleaned dataset after cleaning in Talend Data Prep) 

#output1.csv (Output after filtering out missing values through Talend Data Integration) 

#output2.csv (Output from Rejected case: Missing Values) 
