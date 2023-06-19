# Final project: CS-UY 4563 Machine Learning 

In this project, we focused on using machine learning models to predict whether the
client will subscribe to a term deposit product in the bank. The client dataset was taken from
OpenML and included 16 input variables. Some of them are related to clients: age, job, marital
status, education level, default credit, average yearly balance, housing loan, and personal loan.
Some of them are related to the contact information: contact communication type, last contact
duration, number of contacts performed during this campaign and for this client, number of
contacts performed before this campaign and for this client, and outcome of the previous
marketing campaign.

There are 54211 rows of data in total. We randomly selected 10000 samples from the
dataset and split them into 7000 training samples and 3000 testing samples.
We use supervised analysis (logistic regression, support vector machines, and neural
networks) in classifying clients and making predictions. All three models were run multiple
times using different regularization, feature transformation, and normalization, and we evaluated
each model’s result.
