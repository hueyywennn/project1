# Gas & Electricity Utility Customer Churn Analysis
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Project Overview
This project focuses on customer churn analysis for a gas and electricity utility provider. The goal is to identify key factors contributing to client churn and develop a strategic investigative framework. By leveraging Python (Pandas and NumPy) for data analysis and visualization techniques for trend interpretation, the project aims to engineer and optimize a Random Forest model to enhance churn prediction accuracy, with a target of achieving 85%. The findings are summarized in an executive report for the Associate Director, providing actionable insights to support decision-making.

### Dataset - Client 
|   Name                           |    Description                                                                   |
|-------------------------------------|---------------------------------------------------------------------------------|
| `id`                                | Client company identifier                                                       |
| `activity_new`                      | Category of the company’s activity                                              |
| `channel_sales`                     | Code of the sales channel                                                       |
| `cons_12m`                          | Electricity consumption of the past 12 months                                    |
| `cons_gas_12m`                      | Gas consumption of the past 12 months                                           |
| `cons_last_month`                   | Electricity consumption of the last month                                        |
| `date_activ`                        | Date of activation of the contract                                              |
| `date_end`                          | Registered date of the end of the contract                                      |
| `date_modif_prod`                   | Date of the last modification of the product                                    |
| `date_renewal`                      | Date of the next contract renewal                                               |
| `forecast_cons_12m`                 | Forecasted electricity consumption for next 12 months                           |
| `forecast_cons_year`                | Forecasted electricity consumption for the next calendar year                   |
| `forecast_discount_energy`          | Forecasted value of current discount                                           |
| `forecast_meter_rent_12m`           | Forecasted bill of meter rental for the next 12 months                          |
| `forecast_price_energy_off_peak`    | Forecasted energy price for 1st period (off peak)                               |
| `forecast_price_energy_peak`        | Forecasted energy price for 2nd period (peak)                                   |
| `forecast_price_pow_off_peak`       | Forecasted power price for 1st period (off peak)                                |
| `has_gas`                           | Indicates if the client is also a gas client                                    |
| `imp_cons`                          | Current paid consumption                                                        |
| `margin_gross_pow_ele`              | Gross margin on power subscription                                              |
| `margin_net_pow_ele`                | Net margin on power subscription                                                |
| `nb_prod_act`                       | Number of active products and services                                          |
| `net_margin`                        | Total net margin                                                                |
| `num_years_antig`                   | Antiquity of the client (in number of years)                                    |
| `origin_up`                         | Code of the electricity campaign the customer first subscribed to               |
| `pow_max`                           | Subscribed power                                                                |
| `churn`                             | Indicates if the client churned over the next 3 months                          |

### Dataset - Price 
| Name            | Description                                                       |
|------------------------|-------------------------------------------------------------------------|
| `id`                   | Client company identifier                                               |
| `price_date`           | Reference date for the pricing data                                     |
| `price_off_peak_var`   | Price of energy for the 1st period (off peak)                           |
| `price_peak_var`       | Price of energy for the 2nd period (peak)                               |
| `price_mid_peak_var`   | Price of energy for the 3rd period (mid peak)                           |
| `price_off_peak_fix`   | Price of power for the 1st period (off peak)                            |
| `price_peak_fix`       | Price of power for the 2nd period (peak)                                |
| `price_mid_peak_fix`   | Price of power for the 3rd period (mid peak)                            |

## Project Objectives
1. **Data Cleaning & Preprocessing**
   - Handle missing values and inconsistencies in data.
   - Convert date fields into meaningful time-based features.
   - Normalize categorical data for machine learning models.

2. **Exploratory Data Analysis (EDA)**
   - Perform statistical summaries: mean, median, variance, standard deviation.
   - Conduct correlation analysis using heatmaps.
   - Visualize data distribution through histograms, scatter plots, box plots, and line plots.

3. **Machine Learning Models**
   - **Feature Engineering**: Encode categorical variables using Label Encoding.
   - **Churn Prediction**: Train a Random Forest classifier to predict customer churn.
   - **Model Evaluation**: Use accuracy score, classification report, and confusion matrix to assess performance.
   - **Optimization**: Tune hyperparameters to achieve an 85% prediction accuracy target.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib
- **Data Visualization Tools**: seaborn, plotly

## Project Workflow
1. **Data Collection**: Import and inspect datasets.
2. **Data Cleaning & Preprocessing**: Handle missing values, transform features, and encode categorical variables.
3. **Exploratory Data Analysis (EDA)**: Generate statistical summaries and data visualizations.
4. **Feature Engineering**: Create new features to improve model performance.
5. **Model Training**: Train and optimize the Random Forest classifier for churn prediction.
6. **Model Evaluation**: Assess prediction performance using classification metrics.
7. **Results Interpretation**: Provide actionable insights for business decisions.
