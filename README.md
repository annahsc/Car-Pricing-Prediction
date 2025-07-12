##  Car Price Prediction

This project predicts the sale prices of second-hand vehicles using regression-based machine learning models. The dataset includes 10,000 car listings and features over 35 variables, including numeric features like mileage, engine size, and horsepower, as well as categorical features such as body type, transmission, and fuel type.

The project begins with exploratory data analysis and visualization to understand pricing trends and identify key variables. Missing values—found in both numerical and categorical fields—are handled thoughtfully to avoid data leakage and improve model performance. Feature categorization and encoding are performed, followed by correlation analysis and variable selection.

Multiple regression models are tested, with performance evaluated using Mean Absolute Percentage Error (MAPE). Insights are drawn for different stakeholders: buyers can better evaluate value, sellers can set competitive prices, and dealers and insurers can use pricing forecasts to inform business strategies.

Notably, we discovered that many vehicles had zero mileage, suggesting a high volume of demo or display cars being sold. The market also shows fast turnover, with a median of just 36 days on market.

Tools used: Python, Pandas, Scikit-learn, Seaborn, Matplotlib  
Techniques: Regression, Feature Engineering, EDA, Data Cleaning
