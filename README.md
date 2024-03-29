Lead Scoring and Conversion Optimization

Overview
This repository presents a comprehensive lead scoring analysis using a logistic regression model to enhance conversion rates for an education company. The analysis aims to identify key factors influencing lead conversion, providing valuable insights for strategic decision-making.

Key Findings
Imbalanced Data Columns:

Data in most columns, except 'A free copy of Mastering The Interview,' is highly imbalanced, justifying their exclusion.
The variable 'A free copy of Mastering The Interview' is redundant and will be dropped.
Lead Generation Sources:

Maximum leads are generated by Google and Direct Traffic.
Reference leads and Welinkgak Website leads exhibit a notably high conversion rate.
Occupation and Conversion:

The majority of leads are unemployed, with a conversion rate exceeding 50%.
Working professionals show a significantly high conversion rate.
Last Activity and Conversion:

Leads with the last activity as 'Email opened' have a high probability of conversion.
SMS sent as the last activity is associated with a noteworthy conversion rate.
Website Engagement:

Leads spending more time on the website are more likely to convert.
Suggestion to enhance website engagement for improved conversion rates.
Model Performance:

ROC curve value of 0.86 indicates robust model performance.
Train Data Metrics: Accuracy 77.05%, Sensitivity 82.89%, Specificity 73.49%.
Test Data Metrics: Accuracy 77.52%, Sensitivity 83.01%, Specificity 74.13%.
Conclusion:

An optimal model is achieved by considering sensitivity and specificity for final predictions.
Test set metrics of approximately 77% accuracy, 83% sensitivity, and 74% specificity demonstrate the model's effectiveness.
Lead Score Insights:

The lead score on the trained set indicates a conversion rate around 80%.
Important features contributing to a good conversion rate include 'Lead Origin_Lead Add Form,' 'What is your current occupation_Working Professional,' and 'Total Time Spent on Website.'
Recommendations
Improve customer engagement through emails and calls, targeting leads opening emails.
Implement SMS communication to further enhance conversion probabilities.
Focus on website enhancements for increased lead interaction and conversions.
Consider compulsory selection in key data columns for improved data quality.
Tailor marketing strategies to cater to the unemployed leads, given their higher conversion rates.
Model Validation
The logistic regression model demonstrates reliability with a ROC curve value of 0.86 and aligned train and test metrics. The overall performance indicates the model's effectiveness in predicting lead conversions.

How to Use
Clone the repository to your local machine.
Review the Jupyter notebook for detailed insights and code implementation.
Explore the visualizations and key findings in the presentation file.
Check the summary report for a concise overview of the analysis approach and recommendations.
Feel free to reach out for any further clarification or collaboration opportunities. Happy exploring!






