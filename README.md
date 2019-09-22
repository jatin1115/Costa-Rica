# Costa-Rica
Using python to implement Machine Learning for Costa-Rica poverty analysis

The file is a set of household characteristics from a representative sample of Costa Rican Households. The dataset has observations for each member of the household but the classification is done at the household level. That is, households cannot have two different classifications. Data is not presented at the household level so that participants can create their own household features from individual data.

#### SOLUTION STEPS:-

->Import Required libraries

->Standard Scaling (numeric data / Data Preparation)

->Visualization

->PCA (to reduce number of columns)

->Pipeline

->Use PCA to reduce number of columns

->Apply following modeling techniques:

->RandomForest (Use cross-validation and Bayes Optimization for values of Hyper Parameters)

->XGBoost (Use cross-validation and Bayes Optimization for values of Hyper Parameters)

->LightGBM (Use cross-validation and Bayes Optimization for values of Hyper Parameters)


#### REFERENCES :-

->Scaling the data using SciKit:
https://www.analyticsvidhya.com/blog/2016/07/practical-guide-data-preprocessing-python-scikit-learn/

->Splitting to Train & Test using SciKit:
https://medium.com/@contactsunny/how-to-split-your-dataset-to-train-and-test-datasets-using-scikit-learn-e7cf6eb5e0d

->Cross Validation:
https://scikit-learn.org/stable/modules/cross_validation.html

->K Nearest Neighbors
https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/

->How to get started with Machine Learning
http://www.freecodecamp.org

->Feature Engineering
https://www.kaggle.com/willkoehrsen/a-complete-introduction-and-walkthrough

->Value Error
https://datascience.stackexchange.com/questions/11928/valueerror-input-contains-nan-infinity-or-a-value-too-large-for-dtypefloat32

->Random Forest: Hyperpameter Tuning
https://towardsdatascience.com/random-forest-in-python-24d0893d51c0
https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74

