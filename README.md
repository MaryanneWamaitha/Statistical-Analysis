# Statistical-Analysis
**Telco Customer Churn Analysis**
_Overview_
This project analyzes a telecommunications company's customer churn data to identify factors that influence customer retention. Using R, I performed descriptive and inferential statistical analyses and visualized key relationships between customer attributes and churn behavior. I also fitted a Logistic Regression model to model the probability of churn. Finally, I used K-means to cluster cutomers in segments and various visualizations to show distribution of variables across clusters.

_Key Findings_
Descriptive Statistics: The dataset includes key metrics such as Tenure, MonthlyCharges and TotalCharges. Summary statistics reveal the general distribution of the data. 
Inferential Statistics: A t-test was conducted to compare the mean of MonthlyCharges from churned vs non-churned customers. The Null Hypothesis, that the difference in mean between the 2 groups is equal to zero, was rejected at a 95% confidence interval. The t-test showed that at a 95% confidence interval the average tenure of churned customers ranges from 17.09 months to 18.86 months. It also showed that the relation betweeen contract period and tenure is significantly low.
 I used a logistic regression model to model the probability of churn, I split my data 0.7:0.3 for training and test sets. The area under the curve AUC of the model was 0.8429 showing the model's ability to distinguish between classes.

_Viewing the Report_
To view the detailed analysis, including all visualizations and results, please access the HTML report available in this repository. 
