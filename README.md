# Module_12_challenge
My submission for the GWU Fintech Bootcamp Module 12 challenge. For this challenge I used the sklearn and imblearn libraries to create two logistic regression models that I used to predict the classification of a loan as healthy or high-risk based on the data provided in a .csv file. 

In order to make sure that I created a model that made the most accurate predictions, I created two models: one was based on the regularly sampled data, the other was based on oversampled data created using the RandomOverSampler module from the imblearn library.

The results from my models showed that the model based on the oversampled data was slightly less precise compared to the regularly sampled model, but was more accurate and had a higher recall for both its healthy loan and high-risk loan predictions than the model based on regularly sampled data. 

For this reason, I would recommend that the oversampled model be used in production, as higher accuracy and recall are important 


