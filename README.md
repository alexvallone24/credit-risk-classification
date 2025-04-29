Overview:

The purpose of this analysis was to design and evaluate machine learning models to predict the credit risk of loans. In this assignment, I classified loans as either healthy (label 0) or high-risk (label 1). This helps financial institutions to assess which applicants may pose a higher risk compared to others. 

The dataset consisted of financial and demographic information about loan applicants. When focusing on the "loan_status" column, 0 represented a healthy loan and 1 represented a high-risk loan. As I analyzed the data as a whole, I found significantly more healthy loans accounted for when compared to high-risk ones.

I followed the standarg stages in the supervised machine learning process, including:
Data preprocessing/cleaning,
scaling,
train-test split,
model selection and training using LogisticRegression, and
model evaluation using a confusion matrix and classification report.

Machine Learning Model Results:

Accuracy Score: 0.99

Precision Score (class 0): 1.00

Precision Score (class 1): 0.84

Recall Score (class 0): 0.99

Recall Score (class 1): 0.94


Summary:

The logistic regression model concluded to be 99% accurate, showing excellent performance in classifying loan risk. Specifically, it was highly effective at identifying high-risk loans with a recall of 0.94. The precision score of 0.84 means that it was correct 84% of the time when predicting if a loan was high-risk.  

Since the model has a high recall of identifying high-risk loans, this makes it very useful in a real-world scenario as it decreases the chance of creating false negatives. Therefore, I would strongly recommend this logistic regression model as its high accuracy and recall performance makes it a reliable source to turn to. 
