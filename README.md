# Gas & Electricity Utility Customer Churn Analysis
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## Project Overview
analyze and predict customer churn for a gas and electricity utility company.

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

### Features
1. **Data Cleaning**
  -	Check missing values
2. **Exploratory Data Analysis (EDA)**
  -	Statistical Summaries: mean, median, variance, and standard deviation
  -	Correlation Analysis: heatmap correlations
  -	Distribution Plots: histograms, scatter plots, boxplots, line plots, bar plots
3. **Machine Learning Models**
  -	Feature Engineering: Label Encoder
  -	Classifier Algorithms: Randon Forest
  -	Model Evaluation: accuracy score, classification report, confusion matrix
  -	Predictive Modeling: Randon Forest
4. **Interactive Visualizations**
  -	null

## Tools used
1. **Programming Language** 
  - Python
2. **Libraries**
  - pandas, numpy, scikit-learn, matplotlib
3. **Visualization Tools**
  - plotly, seaborn
