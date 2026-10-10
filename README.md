# KitarMLProject1
This project uses a water quality dataset to see if water is potable or not based on its features.
The first notebook is initial_exploration:
This notebook explores the dataset and checks for missing values. Missing values are filled using the median, and the data is split into training and testing sets.

The second notebook is linear_regression:
This notebook uses linear regression to predict water potability.
First, I used four features: pH, Hardness, Solids, and Sulfate. The training score was 0.002. Then, I used all the features. The training score improved slightly to 0.003, but the test score was -0.0003. The results show that the model did not do a good job predicting water potability.
