# Supervised_Machine_Learning
Supervised machine learning assignment

Prediction Write-up

Based on the data as is, we should see better performance with scaled data than with unscaled data. Scaling data prior to training will normalize it by removing any units associated with the data. Normalizing the data will also take away any assumptions that the larger numbers within the dataset will have more weight or have more significant "value;" for example, in this dataset the machine learning model will not see a significant difference between the principal "loan amount" value and the value presented in the dataset for the person's credit limit value.

In addition, we should also see better performance in our Random Forest Classifier than the Logistical Regression model. The Random Forest Classifier looks at the data as "1's" or "0's" whereas the Logistical Regression model is based on probability of the "observation falling into a category." The two datasets are in the same format and report relatively the same type of data. However, because we are looking to determine the best predictor for loans based on various categories; by randomly choosing the categories for our training set, our test prediction should show better performance using the Random Forest Classifier model. The Logistical Regression Model works best in weighted datasets, in which our dataset is better suited not to be weighted for better predictive performance.

Therefore, in this dataset, we should see better performance with the scaled dataset as to unscaled dataset.
