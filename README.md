# Fake-job-ads
This dataset contains 18K job descriptions out of which about 800 are fake. 
The goal is to define the text as a real or fake job posting.

Thise date was be used to create classification models like:
- Naive Bayes classifier,
- Random forest,
- Logistic regression.

Data was unbalanced. To decieding this problem was used Resampling Techniques: 
1. Oversample minority class; 
2. Undersample majority class.

First technique got the best result with accuracy score 99% for Random Forest model. Trained Random Forest model was used for prediction on new random data. Random job ads from Duunitori.fi and Monster.fi sites were taken as an example.
