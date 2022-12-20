# test-studies
Breast Cancer Prediction Using Machine Learning.

This analysis aims to observe which features are most helpful in predicting malignant or benign cancer and to see general trends that may aid us in model selection and hyper parameter selection. The goal is to classify whether the breast cancer is benign or malignant. To achieve this i have used machine learning classification methods to fit a function that can predict the discrete class of new input.
I was able to identify that out of the 569 persons, 357 are labeled as B (benign) and 212 as M (malignant).

I used pandas’ visualization which is built on top of matplotlib, to find the data distribution of the features.
I used the scatter feature to try determine the relationship between texture and smoothness of the the cancer cells but the data was inconclusive to arrive to a concrete decision.
Further visualisation of the data showed me that the malignant cancer cells showed a higher radius mean, perimeter mean and area mean than benign cancer cells.
Visualisation of the correlation graphs showed that the perimeter mean and the raduis mean were the most correlated features of the cells and the least correlated were the fractal dimension mean and radius mean.

With the information i'll be able to now proceed to build different models that will help me predict malignant or benign cancer and choose the most accurate.
