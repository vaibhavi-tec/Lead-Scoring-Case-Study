# Customer Conversion Analysis for X Education

## Overview
This project aims to analyze customer behavior and improve conversion rates for X Education using machine learning techniques. The primary focus is on identifying key factors that influence enrollments and optimizing prediction models.

## Dataset and Processing
- The dataset includes user interaction data such as visit duration, lead source, and last activity.
- Missing values were handled by creating new categories for unknowns instead of dropping data.
- Categorical variables were grouped and dummy encoded for better model performance.

## Exploratory Data Analysis (EDA)
- Univariate and multivariate analyses were performed using count plots, histograms, and correlation heatmaps.
- Insights were derived regarding key behavioral trends impacting conversions.

## Model Development
- **Logistic Regression** was implemented to predict conversion likelihood.
- **Feature Selection** was done using RFE and VIF to retain the most relevant variables.
- The **Train-Test split (70-30)** and **MinMax Scaling** were applied for standardization.

## Model Performance
- Initial predictions yielded an accuracy of ~93%.
- The **ROC curve** was used to optimize the classification threshold, improving precision and recall by 2-5%.
- Key metrics such as specificity (94%) and sensitivity (90%) indicated strong model reliability.

## Key Takeaways
- **Website engagement (total duration & visits) significantly influences conversion.**
- **Lead source and last activity (Google, direct traffic, SMS, chat) are major predictors.**
- **Working professionals have a higher likelihood of enrollment.**

## Conclusion
By leveraging these insights, X Education can enhance targeted marketing efforts, optimize lead management, and boost enrollment rates.

## Dependencies
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, Statsmodels

## How to Use
1. Load the dataset and preprocess it.
2. Perform EDA to explore patterns.
3. Train the logistic regression model using the provided feature set.
4. Evaluate and optimize the model using ROC and classification metrics.

## Author
Sushmitha,Taha,Vaibhavi

