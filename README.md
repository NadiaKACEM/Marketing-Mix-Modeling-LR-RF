**1. Summerize **  :

In this analysis, I aimed to develop a market mix model (MMM) to optimize advertising spend and predict sales for a consumer goods company. My objectives were to improve the accuracy of sales predictions and identify the key drivers influencing sales.

I began by preprocessing the data, which involved cleaning, handling missing values, and addressing outliers. Feature engineering was also performed, including the extraction of temporal features from the calendar week. I used one-hot encoding to transform the categorical variable "Division" into a format suitable for modeling.

To build the predictive model, I initially employed a linear regression model. However, after evaluating its performance, I decided to explore Random Forest regression due to its ability to capture non-linear relationships in the data. Hyperparameter tuning led to significant improvements in model performance.

**2. Model Deployment and Conclusions:**

Insights gained from the model's feature importance analysis provide actionable recommendations:

- Google Impressions have the highest importance, suggesting that increasing the company's online presence through Google advertising could have a substantial impact on sales.

- Email Impressions and Facebook Impressions are also significant contributors.

- Affiliate Impressions play a role in influencing sales, albeit to a lesser extent.

- Organic Views and Paid Views both contribute positively to sales, emphasizing the importance of both organic and paid views of Youtube.

If It was a real-life scenario, I would strongly recommend increasing investment in Google ads, but even more crucially, in email and Facebook advertising. This recommendation is substantiated by the robust correlations we observed between Google, email, and Facebook ad impressions. These correlations may signify that potential customers, having been exposed to ads on Facebook and through email, subsequently turn to Google for further information or engagement.


**3. Limitations:**

While My analysis has yielded promising results, several limitations should be acknowledged:

The dataset is limited, and it may not capture long-term trends or seasonality effectively.
The model's predictive accuracy still can be improved.

**4. References:**

Kaggle Dataset: Sample Media Spends Data

**5. Final Thoughts:**

The Random Forest model, with its feature importance analysis, offers a practical tool for guiding marketing strategies.
I welcome any feedback or suggestions for further improvement.