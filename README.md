ANALYZING SAARC CAPITAL STOCK DATA AND WORKING POPULATION FOR THEIR IMPACT ON GDP

Objective:
This analysis explores how private and public investment (P_stock & G_stock) interact with a working population(work_popn), which is the factor of productions in standard Cobb-Douglas Equation, influences GDP. We use different models and compare their results.

Log-linear regression for reflecting CoBB-Douglas Production Function.
Log-linear regression with Country and Decade Parameters for time and country effect ( but not using Panel data analysis).
Random Forest Regression for predictive modeling and SHAP values to interpret feature importance.
Key Research Questions:
Does private investment drive GDP more than government investment?
Do public-private investments complement each other or substitute each other?
Dataset: SAARC economic indicators dataset from IMF CAPITAL STOCK DATASET 2017 and World Bank for Population Data. 5 countries with the highest ABSOLUTE GDP in the SAARC Region for 46 years (1970 -2015

From this analysis, we found that private capital stock is the most important determinant of GDP followed by Government Capital stock, 
This is complemented by the earlier, which shows significant changes in SHAP values when private stock is greater than 5 and closely followed by government stock.

Among the models, Random Forest has the best Rsquare value, and we can see the residuals are near normal distribution. Also, All three factors of production have significant values only in this model.
