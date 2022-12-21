
Breast Cancer Prediction Using Machine Learning.

LABORATORY WORK №1

This analysis aims to observe which features are most helpful in predicting malignant or benign cancer and to see general trends that may aid us in model selection and hyper parameter selection. The goal is to classify whether the breast cancer is benign or malignant. To achieve this i have used machine learning classification methods to fit a function that can predict the discrete class of new input.
I was able to identify that out of the 569 persons, 357 are labeled as B (benign) and 212 as M (malignant).

I used pandas’ visualization which is built on top of matplotlib, to find the data distribution of the features.
I used the scatter feature to try determine the relationship between texture and smoothness of the the cancer cells but the data was inconclusive to arrive to a concrete decision.
Further visualisation of the data showed me that the malignant cancer cells showed a higher radius mean, perimeter mean and area mean than benign cancer cells.
Visualisation of the correlation graphs showed that the perimeter mean and the radius mean were the most correlated features of the cells and the least correlated were the fractal dimension mean and radius mean.

With the information I'll be able to now proceed to build different models that will help me predict malignant or benign cancer and choose the most accurate.

LABORATORY WORK №2

In my dataset we have the outcome variable or dependent variable having only two set of values, either M (Malign) or B(Benign). So I used Classification algorithm of supervised learning. I used the following algorithms as my models:

1. Logistic Regression 

2. SVC

3. Decision Tree Algorithm

4. Random Forest Classification

I then proceeded to train the models one by one and showed the classification report of perticular models wise.
To check the accuracy I imported confusion_matrix method of metrics class. The confusion matrix is a way of tabulating the number of mis-classifications, i.e., the number of predicted classes which ended up in a wrong classification bin based on the true classes. I used Classification Accuracy method to find the accuracy of our models. It is the ratio of number of correct predictions to the total number of input samples. From the studies, I obtained the following accuracy scores of my models:

1. RandomForestClassifier-92.55%

2. SVC-91.49%

3. LogisticRegression-90.96%

4. DecisionTreeClassifier-90.96%

The RandomForest model gave me the highest percentage of accuracy so it is the model I am going to implement for the prediction of cancer in patients.

During the whole work I had to take note of the problem of overfitting and underfitting.
