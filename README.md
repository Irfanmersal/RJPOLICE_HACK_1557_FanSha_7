**Step 01. Data Description:** In this first section the data will be collected and studied. The missing values will be threated or removed. Finally, a initial data description will carried out to know the data. Therefore some calculations of descriptive statistics will be made, such as kurtosis, skewness, media, fashion, median and standard desviation.

**Step 02. Feature Engineering:** In this section, a mind map will be created to assist the creation of the hypothesis and the creation of new features. These assumptions will help in exploratory data analysis and may improve the model scores.

**Step 03. Data Filtering:** Data filtering is used to remove columns or rows that are not part of the business. For example, columns with customer ID, hash code or rows with age that does not consist of human age.

**Step 04. Exploratory Data Analysis:** The exploratory data analysis section consists of univariate analysis, bivariate analysis and multivariate analysis to assist in understanding of the database. The hypothesis created in step 02 will be tested in the bivariate analysis.

**Step 05. Data Preparation:** In this fifth section, the data will be prepared for machine learning modeling. Therefore, they will be transformed to improve the learning of the machine learning model, thus they can be encoded, oversampled, subsampled or rescaled.

**Step 06. Feature Selection:** After the data preparation in this section algorithms, like Boruta, will select the best columns to be used for the training of the machine learning model. This reduces the dimensionality of the database and decreases the chances of overfiting.

**Step 07. Machine Learning Modeling:** Step 07 aims to train the machine learning algorithms and how they can predict the data. For validation the model is trained, validated and applied to cross validation to know the learning capacity of the model.

**Step 08. Hyparameter Fine Tuning:** Firstly selected the best model to be applied in the project, it's important to make a fine tuning of the parameters to improve its scores. The same model performance methods apllied in the step 07 are used.

**Step 09. Conclusions:** This is a conclusion stage which the generation capacity model is tested using unseen data. In addition, some business questions are answered to show the applicability of the model in the business context.

**Step 10. Model Deploy:** This is the final step of the data science project. So, in this step the flask api is created and the model and the functions are saved to be implemented in the api.






 5.0 Machine Learning Applied

Here's all cross validation results of the machine learning models with their default parameters. The cross validation method is important to show the capacity of the model to learn.

#### Dummy Model

| Balanced Accuracy |  Precision  |    Recall   |      F1     |      Kappa     |
|:-----------------:|:-----------:|:-----------:|:-----------:|:--------------:|
|   0.499 +/- 0.0   | 0.0 +/- 0.0 | 0.0 +/- 0.0 | 0.0 +/- 0.0 | -0.001 +/- 0.0 |

#### Logistic Regression

| Balanced Accuracy |  Precision  |      Recall     |        F1       |      Kappa      |
|:-----------------:|:-----------:|:---------------:|:---------------:|:---------------:|
|  0.565 +/- 0.009  | 1.0 +/- 0.0 | 0.129 +/- 0.017 | 0.229 +/- 0.027 | 0.228 +/- 0.027 |

#### K Nearest Neighbors

| Balanced Accuracy |    Precision    |      Recall     |        F1       |      Kappa      |
|:-----------------:|:---------------:|:---------------:|:---------------:|:---------------:|
|  0.705 +/- 0.037  | 0.942 +/- 0.022 | 0.409 +/- 0.074 | 0.568 +/- 0.073 | 0.567 +/- 0.073 |

#### Support Vector Machine

| Balanced Accuracy |  Precision  |     Recall     |        F1        |      Kappa      |
|:-----------------:|:-----------:|:--------------:|:----------------:|:---------------:|
|  0.595 +/- 0.013  | 1.0 +/- 0.0 | 0.19 +/- 0.026 | 0.319 +/- 0.0373 | 0.319 +/- 0.037 |

#### Random Forest

| Balanced Accuracy |    Precision    |      Recall     |        F1       |      Kappa      |
|:-----------------:|:---------------:|:---------------:|:---------------:|:---------------:|
|  0.865 +/- 0.017  | 0.972 +/- 0.014 | 0.731 +/- 0.033 | 0.834 +/- 0.022 | 0.833 +/- 0.022 |

#### XGBoost

| Balanced Accuracy |    Precision    |      Recall     |       F1       |      Kappa     |
|:-----------------:|:---------------:|:---------------:|:--------------:|:--------------:|
|   0.88 +/- 0.016  | 0.963 +/- 0.008 | 0.761 +/- 0.033 | 0.85 +/- 0.023 | 0.85 +/- 0.023 |

#### LightGBM

| Balanced Accuracy |   Precision  |      Recall     |        F1       |      Kappa      |
|:-----------------:|:------------:|:---------------:|:---------------:|:---------------:|
|  0.701 +/- 0.089  | 0.18 +/- 0.1 | 0.407 +/- 0.175 | 0.241 +/- 0.128 | 0.239 +/- 0.129 |
