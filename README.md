Project Overview
This project focuses on analyzing the key drivers of health insurance costs and building a predictive model to estimate premiums. 
Using a dataset of over 1,300 individuals, I performed exploratory data analysis (EDA) and engineered a regression model that captures 78% of the variance in insurance charges

Key ResultsModel Performance: Achieved an $R^2$ score of 0.78, indicating a high level of predictive reliability.Primary Cost Drivers: Smoking status, BMI, and Age were identified as the most significant predictors of high insurance premiums.Actionable Insight: Non-smokers with a BMI under 30 paid significantly lower premiums, suggesting clear targets for preventative health incentives.

Tech StackLanguage: PythonLibraries: Pandas, NumPy, Scikit-Learn, Matplotlib, SeabornEnvironment: Jupyter Notebook / Google Colab


Analysis WorkflowData Cleaning: Handled missing values and encoded categorical variables (Sex, Region, Smoker).EDA: Created correlation heatmaps and distribution plots to visualize the relationship between variables.Feature Engineering: Analyzed the interaction between BMI and Smoking status.Modeling: Implemented [Linear Regression / Random Forest] and evaluated performance using Mean Absolute Error (MAE) and R-squared metrics.
