# Objective
Demonstrate abilities using python's pandas, plotly, & scikit-learn packages
View rendered notebook [here](https://nbviewer.org/github/NoahVelez/oil_price_prediction_model/blob/0f003a0ed0d0bc1384a1f5bb9137e6e2532ca10e/Crude%20Oil%20Price%20Prediction%20Model.ipynb)

# 🔍 Project Insight: Predicting Crude Oil Prices
I'm excited to share a recent project where I've developed a Linear Regression Model to predict the Cushing, OK WTI Spot Price FOB. This work combines data analysis and energy economics, providing insights into the future of crude oil prices.

# 📊 Behind the Scenes:
The model leverages data from the U.S. Energy Information Administration, focusing on weekly U.S. crude oil supply. My approach involved using Pandas for data manipulation, Plotly Express for visualization, and Scikit-learn for building the regression model.

# 🧩 Modeling and Analysis:
After thorough data cleaning and preparation, I focused on identifying key features that influence crude oil prices. The model's performance, indicated by an R-squared of 0.85, shows a strong correlation between the features and the target price.

# 📈 Results and Reflections:
The visualizations created help in understanding the model's predictions compared to actual prices. The insights from the regression coefficients were particularly interesting, shedding light on the impact of different variables on oil pricing.

# Results
**Note:** GitHub cannot render Plotly plots in a Notebook so they have been added below.
## Cushing, OK WTI Spot Price FOB (Dollars per Barrel)
![1702949813077](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/c7659bee-3be0-4850-85ef-5fa84aaff22a)
## Actual vs Predicted Results
The "Actual vs Predicted Results" plot visually compares the real-world crude oil prices with those forecasted by the linear regression model. Deviations from the diagonal line, which represents perfect prediction, indicate the areas where the model overestimates or underestimates the actual prices.
![1702949775831](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/34601623-b3f8-4e29-a70a-2def7c8b1a5b)
## Residuals vs Predicted Prices
The "Residuals vs Predicted Prices" plot in this context visually represents the differences (residuals) between the actual and predicted crude oil prices. This plot helps in identifying patterns in the prediction errors, indicating whether the model consistently overestimates or underestimates at certain price levels.
![1702949862832](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/ae6cb724-2b7d-41f1-8fce-e4e04e1e66bb)
