# Business Cases with Data Science Case 4

## Predict hotel booking cancellations and optimize revenue for Hotel Chain C

### Problem:
Hotel Chain C was facing increasing cancellation rates, leading to lost revenue. Cancellations are unpredictable, making it difficult to implement effective overbooking policies. The hotel aimed to develop models to forecast net demand from bookings and identify high-cancellation-risk bookings. This would enable measures to minimize cancellations and optimize revenue.

![image](https://github.com/yousefebrahimi0/Business-Cases-with-Data-Science-Case-4/blob/main/pic1.png)

### Steps:
+ Explored and analyzed data to understand cancellation patterns and customer characteristics
+ Cleaned, preprocessed, and transformed data to ensure quality and model performance
+ Tested multiple models including XGB, Random Forest, and Bagging Classifiers
+ Selected best-performing XGB model and tuned hyperparameters using a grid search
+ Trained final model on full dataset and tested on the holdout set
+ Evaluated model on accuracy, precision, recall, and F1 score

![image](https://github.com/yousefebrahimi0/Business-Cases-with-Data-Science-Case-4/blob/main/pic2.png)

### Key results:

+ The model achieved >0.85 accuracies, precision, recall, and F1 score on the test set
+ Provided actionable insights into customer segments using clustering
+ Identified high cancellation risk bookings to enable preventive measures
+ Enabled data-driven pricing strategies and overbooking policies
+ Reduced cancellation rate to help maximize hotel revenue
+ Implemented a monitoring system to ensure continued model performance
