# 🏥 Health Insurance Charges Prediction

## 📖 Overview

Healthcare costs vary widely depending on personal and lifestyle factors. This project builds a machine learning model that predicts individual medical insurance charges using demographic and health-related data.

The project walks through a complete data science pipeline, starting from raw data exploration to building and evaluating predictive regression models.

The objective is to understand which factors most influence insurance costs and to develop an accurate prediction model using real-world data.



## 🎯 Problem Statement

Insurance providers determine premium charges using multiple risk indicators. Accurately predicting these costs can help:
	•	Insurance companies estimate pricing risks
	•	Individuals understand factors affecting healthcare expenses
	•	Analysts gain insights into healthcare cost drivers

This project predicts insurance charges based on personal and lifestyle attributes.



## 📊 Dataset Information

The dataset contains records of individuals and their corresponding medical insurance charges.

### Features Used


| Feature | Description | Data Type |
| :--- | :--- | :--- |
| **Age** | Age of the insured individual | Integer |
| **Sex** | Gender of the individual (Male/Female) | Categorical |
| **BMI** | Body Mass Index ($kg/m^2$) | Float |
| **Children** | Number of dependents covered by insurance | Integer |
| **Smoker** | Smoking status (Yes/No) | Categorical |
| **Region** | Geographic residential area in the US | Categorical |
| **Charges** | Medical insurance cost (**Target Variable**) | Float |


## Project Workflow

1. Data Exploration

	•	Loaded and inspected dataset
	•	Checked data types and missing values
	•	Generated descriptive statistical summaries

2. Data Preprocessing
	•	Encoded categorical variables
	•	Prepared feature variables and target variable
	•	Split data into training and testing sets

3. Exploratory Data Analysis
	•	Visualized relationships between features and insurance charges
	•	Identified key cost drivers
	•	Analyzed correlations between variables

4. Model Development

Regression models were trained to predict insurance charges using structured data.

5. Model Evaluation

Models were evaluated using:
	•	Mean Absolute Error (MAE) , Mean Squared Error (MSE) and R² Score



## 🧠 Tools and Technologies
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn
	•	Jupyter Notebook



## 📈 Key Insights
	•	Smoking status has the strongest impact on insurance charges.
	•	Higher BMI values tend to increase medical costs.
	•	Insurance costs generally rise with age.
	•	Lifestyle and health indicators collectively influence pricing.



## 🚀 How to Run the Project

Clone the Repository
````
https://github.com/chighislian/health-insurance-prediction.git
````
Install Dependencies 
````
pip install pandas numpy matplotlib seaborn scikit-learn notebook
````
Launch Notebook
````
Health_Insurance_Charges_Prediction.ipynb
````
open the notebook file and run  all cells
## 📂 Project Structure
````
health-insurance-prediction/
│
├── Health_Insurance_Charges_Prediction.ipynb
├── insurance.csv
└── README.md
````
## 🏆 Skills Demonstrated
	•	Data Cleaning and Preparation
	•	Exploratory Data Analysis
	•	Feature Engineering
	•	Regression Modeling
	•	Model Performance Evaluation
	•	Data Visualization



## 🔮 Future Improvements
	•	Deploy model as a web application
	•	Test additional machine learning algorithms
	•	Perform hyperparameter tuning
	•	Add automated prediction interface



## 📚 Educational Purpose

This project was developed as part of hands-on machine learning practice using healthcare cost prediction as a real-world use case.



## 🤝 Contributions

Suggestions and improvements are welcome. Feel free to fork the repository and submit pull requests.