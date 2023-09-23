# Linear regression model for Fish Length

About the Models

For this task, several models were employed to carry out the analysis.

In the first scenario, a Linear regression model was developed to help predict
the weight of the fish using its lengths, height, and width. In the second scenario,
two different models are used to predict the weight. That is, the Ridge regression model,
and the Lasso regression model. Lastly, is the use of a Logistic regression model
that is modified to two-class and multi-class classification to understand its performance on the iris dataset.
Dataset: In this task, two datasets were used. One, the fish dataset from the Kaggle website and the Iris dataset. The fish dataset contained 158 observations and 7 variables. The iris dataset contained 149 observations and 6 variables.

## Data visualization

In this part, two main visualizations were used: a count plot and a correlation matrix.
Data splitting: In both datasets, the data was split in the ratio of 0.7 for training and 0.3 for testing
Models:

Q1. Linear regression model

i. Coefficients values: [ 58.50297201, 3.22702894, -36.51057731, 25.82354203,
36.66904584]
ii. Standard error: Mean squared error 16062.71181399354
iii. R-squared term (R2): 0.8640949745089501
iv. Dependence between the length and weight of the fish: The correlation between the length1, length2, lenght3,
and weight values are as follows; 0.92, 0.92, and 0.92 respectively. Thus, there is a strong dependence
between the length and weight of the fish.

Q2. Ridge and Lasso Regression Models
Coefficients:

- Ridge Regression Models: [174.57360837, -68.31165568, -79.2515505, 43.64599996, -22.51016906]

- Lasso Regression Models: [11.83187265, 0, 0, 0, 34.84626976]

- The attribute that least impacts the weight of the fish is height with a correlation coefficient of 0.79.

Q3. Logistic regression modification for two-class and multiclass classification.
Surely, there is a significant difference in performance noted when the logistic regression is modified
to a two-class and multi-class classification.
For a two-class classification, the accuracy score of the model is 0.87, whereas for a multi-class classification, the accuracy score is 0.98.
