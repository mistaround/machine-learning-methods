# SI151-Project----machine-learning-methods
Course Project for SI151 -- Machine Learning and Convex Optimization, Shanghaitech University

Use dataset https://www.kaggle.com/uciml/student-alcohol-consumption?select=student-mat.csv

Environment:

- python 3.6, jupyter notebook
- sklearn, numpy
- matplotlib, pandas, seaborn (only for plotting)



.csv file: modified for different purpose

- student-mat.csv : origin dataset

- grade.csv : G1 score as label

- data_transformed: for plotting

- _lost.csv: for feature value losing

- ...

  

.ipynb: open with jupyter notebook

- Adaboost, Nearest Neighbour(nn), Nueral Network, Gaussian Naive Bayes, SVM

- start with PCA means use PCA to reduce dimension, DimReduction use KBest selection

- svm_ovo means one vs one, ovr one vs rest

- svm_ovo_os means use oversample to solve unbalenced label, SMOTE the same

- svm_ovo_os_mean use mean imputation to fill loss feature value, nn ridge the same

  

translation.txt: how categorical value changed into numerical



**Run inside the ML folder directly!**