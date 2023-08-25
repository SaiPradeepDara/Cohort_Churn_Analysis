# Cohort_Churn_Analysis
This Dataset mainly deals with Customer data and the plans bought by customers from a telecom company. Here we are applying a classification problem to train the model to predict the label 'Churn' 
Churn is the label that determines whether the customer is continuing the services of the company or not, It has mainly 2 Categorical Variables YES and NO.
If it is YES then the Customer stopped using the Services.

Here, in EDA on the Dataset we got to know that tenure and Total charges played an important role in maintaining the customer.

Model Selection:
As it is a Classification problem, we have to compare the evaluation metrics of different models used for classification tasks
Here we used a Decision Tree, Random Forest Classifier, Adaboost Classifier, and Gradient Boosting Algorithms and compared the metrics like Accuracy, Precision, Recall, and F1 Score from the Confusion Matrix.

Finally, we have observed that Adaboost the is best-suited algorithm for this dataset which gives a high accuracy compared to neighbouring algo's.

The model has been saved to the Pickel file for use in the Front-end Application with the use of Flask.
