# Objective
Demonstrate abilities using python's pandas, plotly, & scikit-learn packages
View rendered notebook in nbviewer [here](https://nbviewer.org/github/NoahVelez/oil_price_prediction_model/blob/0f003a0ed0d0bc1384a1f5bb9137e6e2532ca10e/Crude%20Oil%20Price%20Prediction%20Model.ipynb)

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
![newplot](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/2a6a315b-c9a8-4697-919d-3fb5066f940e)
## Actual vs Predicted Results
The "Actual vs Predicted Results" plot visually compares the real-world crude oil prices with those forecasted by the linear regression model. Deviations from the diagonal line, which represents perfect prediction, indicate the areas where the model overestimates or underestimates the actual prices.

![newplot (1)](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/7b87dfe4-a80f-40d6-adb6-2e0a736d4a09)
## Residuals vs Predicted Prices
The "Residuals vs Predicted Prices" plot in this context visually represents the differences (residuals) between the actual and predicted crude oil prices. This plot helps in identifying patterns in the prediction errors, indicating whether the model consistently overestimates or underestimates at certain price levels.

![newplot (2)](https://github.com/NoahVelez/oil_price_prediction_model/assets/60712051/9f7ab6af-987c-4502-8a90-b4075cc3086d)
