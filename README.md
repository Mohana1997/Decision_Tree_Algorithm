This repository showcases my work on predicting Claimants who come with attorney, using a claimants dataset. The project flow involves,

Data Collection and Exploratory Data Analysis (EDA): I started by gathering the dataset and performing EDA to understand the data’s structure and key features.

Model Building model with Decision Tree Algorithm: I built model using Decision Tree Algorithm through train-test split. Here I encountered a problem
of low bias and high variance. To overcome this problem, I used "Hyperparameter tweaking"(max_depth).

Evaluation Metrics: After building the model, I evaluated their performance using metrics like confusion matrix, accuracy score, 
classification report, ROC Curve. Finally obtained a generalized model with accuracy of 75% for training data
and 72% for test data and understood how my model would behave in real-time

GridSearchCV: Also tried "GridSearch Cross Validation" method to find optimal value for "max_depth" and to find the best metric for "criterion".

Ensemble Techniques: Also worked on ensemble techniques like bagging, boosting and stacking using RandomForest Algorithm, Adaboost Algorithm
and knn,logistic and decision tree for stacking

Model Validation: Model validation was done using KFoldCV and LOOCV to obtain the accuracy and standard deviation.  
