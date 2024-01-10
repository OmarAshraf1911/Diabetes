# Diabetes Prediction using Machine Learning

## About Dataset

This dataset is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases via Kaggle. The objective is to predict whether a patient has diabetes based on various diagnostic measurements. The dataset comprises medical predictor variables such as the number of pregnancies, BMI, insulin level, age, and more. It is important to note that all patients in this dataset are females at least 21 years old and of Pima Indian heritage.

### Acknowledgements

Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.

## Project Overview

This project aims to build a machine learning model that predicts the onset of diabetes in patients. The following preprocessing steps were undertaken:

- Removal of missing values
- Encoding categorical variables
- Data splitting for model training and testing

### Techniques and Models Used

The project utilizes various machine learning algorithms for prediction, including:

- VotingClassifier
- SVC (Support Vector Classifier)
- LogisticRegression
- DecisionTreeClassifier
- AdaBoostClassifier
- BaggingClassifier
- GradientBoostingClassifier
- RandomForestClassifier
- ExtraTreesClassifier
- KNeighborsClassifier

GridSearchCV was employed for fine-tuning parameters in GradientBoostingClassifier, RandomForestClassifier, and ExtraTreesClassifier models to enhance their predictive performance.

## Execution in Kaggle Notebook

To reproduce this project:

1. Access the Kaggle platform and open a notebook.
2. Import the dataset from the provided source on Kaggle.
3. Create a new notebook and import the dataset.
4. Implement the machine learning models listed above.
5. Utilize Confusion Matrix to evaluate the models' performance.

Please note that the provided code snippets are for demonstration purposes and may need adjustments based on your specific dataset and requirements.

Feel free to adapt and expand upon this code to explore and implement various models and evaluation techniques within your Kaggle notebook.
