# KitarMLProject1

This project uses a water quality dataset to see if water is potable or not based on its features.
The first notebook is initial_exploration:
This notebook explores the dataset and checks for missing values. Missing values are filled using the median, and the data is split into training and testing sets.

The second notebook is linear_regression:
This notebook uses linear regression to predict water potability.
First, I used four features: pH, Hardness, Solids, and Sulfate. The training score was 0.002. Then, I used all the features. The training score improved slightly to 0.003, but the test score was -0.0003. The results show that the model did not do a good job predicting water potability.

The third notebook is classification:
This notebook uses Decision Tree and Support Vector Machine (SVM) classifiers to predict water potability. Both models were evaluated using the test dataset with accuracy, precision, sensitivity, and F1 score.

The Decision Tree performed slightly better, achieving an accuracy of 62.2% and a precision of 62.41%. The SVM achieved an accuracy of 61% and a precision of 37.18%. The SVM also failed to identify any class 1 observations, predicting everything as class 0.

Overall, the Decision Tree performed better than the SVM, although both models had relatively low accuracy.
