# Diabetes Prediction

## Introduction

Diabetes is a chronic disease that occurs when the pancreas is no longer able to make insulin, or when the body cannot effectively use the insulin it produces. Insulin is a hormone that regulates the body's use of glucose (sugar), the body's main source of fuel. Glucose comes from the foods we eat and is the main source of energy needed to fuel the body's cells and tissues. Insulin helps glucose to get into the cells to be used for energy. When glucose builds up in the blood instead of going into the cells, the condition is called high blood glucose (hyperglycemia). Over time, high blood glucose can lead to serious health problems.

## Dataset

The dataset used for this project is the Pima Indians Diabetes Database. The dataset consists of 768 observations of 9 variables. The variables are as follows:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

## Methodology

The dataset is split into training and testing sets. The training set is used to train the model and the testing set is used to test the model. The model used for this project is a Decision Tree Classifier. The model is trained using the training set and then tested using the testing set. The model is evaluated using the accuracy score and confusion matrix.

## Results

The accuracy score of the model is 0.7359 and the confusion matrix is as follows:

| | Predicted 0 | Predicted 1 |
| --- | --- | --- |
| Actual 0 | 128 | 30 |
| Actual 1 | 36 | 46 |

## Conclusion

The accuracy score of the model is 0.7359. This means that the model is 73.59% accurate. The confusion matrix shows that the model correctly predicted 174 out of 231 observations. The model incorrectly predicted 60 out of 231 observations. The model correctly predicted 46 out of 82 observations of people who do not have diabetes. The model incorrectly predicted 36 out of 82 observations of people who do not have diabetes. The model correctly predicted 128 out of 158 observations of people who have diabetes. The model incorrectly predicted 30 out of 158 observations of people who have diabetes. The model can be improved by using a different model or by using a different dataset.

## References

- [Diabetes](https://www.cdc.gov/diabetes/basics/diabetes.html)
- [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
- [Accuracy Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html)
- [Confusion Matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
