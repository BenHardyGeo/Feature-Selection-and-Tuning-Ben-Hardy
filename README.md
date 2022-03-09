# Feature-Selection-and-Tuning-Ben-Hardy

Keywords: Ensemble Methods, hyperparameter tuning, GridSearchCV, RandomSearchCV, Supervised Learning, Classification, Over sampling, Under sampling

This notebook was prepared for the fifth project of the Post Graduate Program in Artificial Intelligence and Machine Learning: Business Applications from the McCombs School of Business at The University of Texas. The data was provided in a .csv file.

The focus of this project was on tuning and feature selection. The task was to classify bank customers likely to “churn” i.e. cancel their credit card with the bank. Data on customer info and banking habits was provided. Target data was provided so it was a supervised learning task.

This project introduced the idea of using Pipeline to ensure that input parameters were properly conditioned and that no data leakage occurred during the process. Various classification methods were employed LogisticRegression, AdaBoostClassifier, GradientBoostingClassifier, RandomForestClassifier, BaggingClassifer, DecisionTreeClassifer and XGBoostGlassifer. All models were tested, only the best 3 were then extensively tuned.

The target class: Attrited Customers accounted for 16% of the data. So, the target variable was very unbalanced. For this reason, over sampling (SMOTE) and under sampling (RandomUnderSampler) methods were tested when training the models.

Given that the focus of the project was on tuning both Random Search and Grid Search were employed. I found the best result when using Random Search to quickly obtain a high performing set of parameters, followed by a focused Grid Search around the highest performing parameters to find the final parameter set.

While this project was done as part of a school project. I believe it indicates the quality of work that I’m capable of in real-world applications. I was the top student in my cohort with a final course weighted average of 99.39%.
