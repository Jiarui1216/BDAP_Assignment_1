# Air Quality and Respiratory Health Analysis

This repository contains the code and dataset used for **Assignment 1 Part B and Part C**, focusing on the relationship between **Air Quality Index (AQI)**, air pollutants, and **respiratory health outcomes**.  
The project applies **data analysis** and **machine learning models** to explore the impact of air pollution on health and to predict air quality.


## Repository Structure

AQI_Respiratory_2000_2019.csv              # Dataset (2000–2019 AQI & respiratory health data)
AQI_Respiratory_Analysis_Assignment1B.ipynb # Part B: Data preprocessing, EDA & statistical analysis
PartC_Modelling_Final.ipynb                 # Part C: Machine learning modelling & evaluation
README.md                                   # Project documentation


## Part B: Exploratory Data Analysis (EDA)
- Conducted **data cleaning and preprocessing** for AQI and respiratory health dataset (2000–2019).  
- Performed **descriptive statistics, trend analysis, and correlation analysis**.  
- Visualized long-term patterns in AQI and health indicators.  
- Identified strong associations between **PM2.5, PM10, NO₂** and respiratory-related mortality.


## Part C: Modelling
- Applied **1-at-a-time search algorithm** and multiple ML models for prediction tasks.  
- Evaluated model performance using metrics such as **RMSE, MAE, R²**.  
- Key finding: **Random Forest and Hybrid ML models** demonstrated higher accuracy in predicting air pollution trends and health outcomes compared to linear regression.  
- Showed the advantage of non-linear models in capturing complex air quality-health relationships.


## Requirements
This project is developed in **Python**. Install the following dependencies before running notebooks:
bash
pip install pandas numpy matplotlib seaborn scikit-learn


## How to Run
1. Clone this repository or download the files.  
2. Open the Jupyter notebooks:  
   - Run **AQI_Respiratory_Analysis_Assignment1B.ipynb** for data preprocessing and exploratory analysis.  
   - Run **PartC_Modelling_Final.ipynb** for machine learning modelling and evaluation.  
3. Dataset: **AQI_Respiratory_2000_2019.csv** should be placed in the same directory as the notebooks.


## Results & Insights
- Air pollutants, especially **PM2.5**, significantly correlate with respiratory health issues.  
- Short-term fluctuations and long-term exposure both contribute to increased health risks.  
- Machine learning models provide valuable insights for **forecasting and public health decision-making**.


## References
(Refer to the assignment report for full reference list, formatted in Harvard style.)
