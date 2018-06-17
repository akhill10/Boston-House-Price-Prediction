# Boston-House-Price-Prediction
In this NoteBook I detail the machine learning (ML) models I implemented to accurately predict the housing prices in Boston suburbs. The dataset for this experiment is accessed from the UCI Machine Learning repository via https://archive.ics.uci.edu/ml/datasets/Housing. The ipython Notebook is organized in such a way as to demonstrate the entire process right from getting and cleaning the data, to exploratory analysis of the dataset to understand the distribution and importance of various features in influencing the algorithm, to coming with a hypothesis, training ML models, evaluation of the models, etc.

The dataset (Boston Housing Price) was taken from the StatLib library which is maintained at Carnegie Mellon University and is freely available for download from the UCI Machine Learning Repository. The dataset consists of 506 observations of 14 attributes. The median value of house price in $1000s, denoted by MEDV, is the outcome or the dependent variable in our model. Below is a brief description of each feature and the outcome in our dataset:

CRIM     – per capita crime rate by town
ZN     – proportion of residential land zoned for lots over 25,000 sq.ft
INDUS     – proportion of non-retail business acres per town
CHAS     – Charles River dummy variable (1 if tract bounds river; else 0)
NOX     – nitric oxides concentration (parts per 10 million)
RM     – average number of rooms per dwelling
AGE     – proportion of owner-occupied units built prior to 1940
DIS     – weighted distances to five Boston employment centres
RAD     – index of accessibility to radial highways
TAX     – full-value property-tax rate per $10,000
PTRATIO     – pupil-teacher ratio by town
B     – 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT     – % lower status of the population
MEDV     – Median value of owner-occupied homes in $1000’s

