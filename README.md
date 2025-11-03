# 🚗 AI-PriceOptima-SpringBoard

# 🎯 Project Objective:
To design and implement a machine learning–driven dynamic pricing system that adjusts prices in real-time or periodically to maximize revenue and maintain competitiveness. The system will use historical sales and inventory data to predict optimal prices using advanced ML techniques. By ensuring adaptability and transparency, the platform aims to help businesses increase profitability while preserving customer trust.

# Milestone 1: Requirements & Data Preparation

# Data Set
https://www.kaggle.com/datasets/arashnic/dynamic-pricing-dataset/data
   # Objective: Define KPIs and collect datasets.

🔁 kpis
# KPI: https://pub.towardsai.net/key-performance-indicators-kpis-in-machine-learning-69d8a59ec8c1
In ML, KPIs are metrics that tell us how well the model or project is performing — both technically and from a business point of view.

🔹🔹🔹why we need to use kpis for this project?
“In this project, we use KPIs to understand both the data and the business performance. Technical KPIs, like missing values or duplicate rows, ensure the data is clean and reliable. Business KPIs, like average ride cost, ride duration, and customer ratings, show how the ride service is performing and help identify patterns in customer behavior. Overall, KPIs provide clear, measurable insights that guide decisions and make it easier to track improvements over time.”

🔹🔹KPIs:
🔹Revenue Lift (%) = ((New – Old) / Old) × 100

🔹Profit Margin (%) = ((Revenue – Cost) / Revenue) × 100

🔹Conversion Rate (%) = (Completed / Total) × 100

🔹Required Python Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, scipy, xgboost, lightgbm,  joblib

## Milestone 2: Data Ingestion Pipeline

🔹Pipeline:
A pipeline means a series of steps or stages that data passes through —
from raw input → cleaned data → processed data → final output (like a trained ML model or report).
It’s called a “pipeline” because data flows through it step by step —
just like water flows through connected pipes 🚰.


🔹🔹🔹Data Ingestion Pipeline:

A data ingestion pipeline is a specific type of pipeline that focuses on collecting, transforming, and loading data from various sources into a target system, such as a data warehouse, database, or data lake. The primary goal of a data ingestion pipeline is to move data from its source to a destination, often in a format that's suitable for analysis or processing.

🔹load_data is the data ingestion component, which loads the data into a pandas DataFrame.
🔹 clean_data is the data cleaning component, which removes rows with missing values.
🔹transform_data is the data transformation component, which adds a new column 'Cost_Category' based on the 'Historical_Cost_of_Ride' column.
🔹filter_data is the data filtering component, which filters rows where 'Number_of_Riders' is greater than 50.
🔹output_data is the data output component, which prints the final transformed data.
🔹The pipeline function runs the entire pipeline, from data ingestion to data output.

# Milestone 3: Exploratory Data Analysis (EDA)

🔹Check data quality (nulls, duplicates, types)

🔹Generate summary statistics (.describe())

🔹Visualize distributions and detect outliers (IQR method, boxplots)

🔹Analyze correlations using a heatmap

🔹Explore feature relationships using scatter plots

🔹Handle categorical variables encoding


# Milestone 4: Baseline Pricing Engine

# Baseline Pricing Engine
🔹🔹🔹Baseline pricing is a pricing strategy that establishes a standard price for a product or service based on certain criteria, such as costs, market conditions, or target profit margins. This baseline price serves as a reference point for future pricing decisions and can be adjusted based on various factors like demand, competition, or inventory level

# dynamic pricing 
Dynamic pricing means adjusting the price of a product or service in real time (or frequently) based on factors like demand, supply, time, competition, or customer behavior.
The price changes automatically depending on the situation.

 # Time-Based Pricing Rules:
 
Time-based pricing rules involve adjusting prices based on the time of day, day of the week, or other temporal factors. This approach recognizes that demand for ride-hailing services varies over time and that prices can be optimized to reflect these fluctuations.


# Inventory-Based Pricing Rules:

Inventory-based pricing rules involve adjusting prices based on the availability of drivers or vehicles. This approach recognizes that the supply of drivers and vehicles can impact the quality and speed of service.
Objectives:

Key Achievements:

🔹Rule-based pricing engine implemented
🔹Time Based Pricing: Morning (378), Afternoon(3800),Evening (364), Night (367)
🔹 Inventory adjustments based on demand-supply ratio
🔹 Simulated Revenue lift achieved:  Static Revenue  ($372502.62 ), Dynamic Revenue ($454695.61), Revenue Lift (22.07%)
🔹 Total baseline revenue: 372.502



## Milestone 5: Advanced Model Development

# Objectives:

- Train ML models (XGBoost & LightGBM) for dynamic pricing
- Advanced feature engineering
- Hyperparameter optimization
-  backtesting with historical data
-  Simulated Revenue lift validation

🔹 Two ML models trained and evaluated(XGBoost & LightGBM)
🔹 Advanced feature engineering 
🔹 Hyperparameter optimization implemented
🔹 Standard Scaler model improvements 
🔹  backtesting with historical data completed
🔹 Simulated revenue lift achieved and validated

 🛠️ Tools Used

Languages & Libraries:Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn
Development Environment: Jupyter Notebook, VS Code

👩‍💻 About the Developer
Developed by: K.Priyanka

🏷️ Repository Details
Branch: AI_Price_Optima_PRIYANKA
Status: 🚧 Ongoing Development
