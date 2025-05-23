🧾 Predicting Restaurant Tips Using Excel | Data Analytics Project
📌 Project Overview
This project focuses on predicting restaurant tips based on customer and bill characteristics using Microsoft Excel. Through descriptive analytics, data cleaning, transformation, and multiple linear regression, we explore which variables significantly affect the tip amount and how accurately we can model it.

💡 Problem Statement
The goal of this project is to answer the question:
Can we predict the tip amount a customer will give at a restaurant based on data such as total bill, group size, time of day, and customer attributes?
We used a dataset that includes customer details like gender, smoking status, day of the week, meal time, group size, total bill, and tip amount.

✅ Tasks Performed
Imported the dataset into Excel (columns: sex, smoker, day, time, size, total_bill, tip)
Checked for missing values and ensured data cleanliness
Identified independent & dependent variables
Dependent variable: tip
Independent variables: sex, smoker, day, time, size, total_bill
Converted categorical values to numeric using IF conditions for regression
Created Pivot Tables & Charts for:
Gender vs Avg Tip
Smoker vs Avg Tip
Day vs Avg Tip
Time vs Avg Tip
Built Scatter Plots to visualize:
Total Bill vs Tip
Size vs Tip
Applied Multiple Linear Regression using Excel's Data Analysis Toolpak
Predicted Tip values using the regression equation
Calculated Errors and RMSE to measure model performance


📊 Visual Analysis
📌 Pivot Table Insights (Gender, Smoker, Day, Time):
Converted sum to average (mean) for clearer insights.
Observed slight differences in mean tips by gender, smoker status, day, and time.
However, the differences were not statistically significant — may be due to chance.

📈 Scatter Plot Analysis:
Total Bill vs Tip: Positive correlation — higher bills tend to result in higher tips.
Group Size vs Tip: Moderate positive correlation — larger groups often give larger tips.

📉 Regression Analysis
✅ 1. Regression Statistics
Term	              Value	      Meaning
Multiple R	        0.6856	    Strong correlation between predictors and tip
R Square	          0.4701	    Model explains 47% of variation in tips
Adjusted R²	        0.4520	    Adjusted for number of predictors used
Standard Error	    1.02	      Avg. prediction error is ₹1.02
Observations	      244	        Total data points used in model

✅ 2. ANOVA Table
Term	             Value	      Meaning
F	                 26.06	      Model significantly better than random guesses
Significance F	   1.19e-28	    Extremely small — confirms model is meaningful

✅ 3. Coefficients Table
Variable	          Coefficient	  P-value	      Explanation
Intercept	0.846	0.098	Base value (not meaningful alone)
Male	-0.032	0.81 ❌	Gender not significant
Smoker=Yes	-0.086	0.56 ❌	Smoker not significant
Day=Thur	-0.137	0.77 ❌	No strong effect
Day=Fri	0.025	0.94 ❌	No strong effect
Day=Sat	-0.096	0.56 ❌	No strong effect
Time=Dinner	-0.061	0.87 ❌	No strong effect
Size	0.176	0.050 ✅	Larger group = higher tip
Total Bill	0.094	2.34e-19 ✅✅✅	💥 Most impactful predictor of tip amount

🔍 Prediction and RMSE Calculation
Predicted Tip = Intercept + (coefficients × independent variables)

Error = Actual Tip − Predicted Tip

RMSE = √(mean of squared errors)

RMSE helps evaluate how accurate our predictions are on average.

Size	Total Bill	Actual Tip	Predicted Tip	Error	Error²
2	16.99	1.01	2.63	-1.62	2.62
3	10.34	1.66	2.21	-0.55	0.30
3	21.01	3.50	3.19	0.31	0.09

🧠 Key Takeaways
✅ Total Bill is the most important predictor of tips.

✅ Group Size also shows a positive effect.

❌ Gender, Smoking, Day, and Time have weak influence on tip prediction.

✅ RMSE value shows reasonable prediction accuracy.

📤 Conclusion
This project demonstrates how Excel can be used effectively for a complete data analytics cycle — from data cleaning and visualization to regression modeling and prediction accuracy evaluation.

This analysis helps uncover what truly influences tipping behavior and how we can quantify human behavior through data. 💡

🔧 Tools Used
Microsoft Excel

Data Analysis ToolPak

Pivot Tables
IF Conditions for Encoding
Scatter Plot Charts
Regression Modeling
RMSE Calculation

📎 Resources

Dataset: Tips.csv (Add link if available)
Excel File: Tips_Regression_Excel.xlsx (Upload to GitHub repo)



📬 Connect With Me
💼 LinkedIn: https://www.linkedin.com/in/narendrasingh1402/
📺 YouTube: https://www.youtube.com/@Analyst_Hive
🗂️ Portfolio: [(Add your link if available)](https://narendra1402.github.io/)
