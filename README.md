Overview
This project uses a dataset of different types of dates to train machine learning models for classification purposes. We implement two models:

Decision Tree
Random Forest
Both models were trained and tested using scikit-learn. The results are evaluated using accuracy scores and classification reports.

Dataset
The dataset contains features of various types of dates (e.g., BERHI, DEGLET, DOKOL, IRAQI, ROTANA, SAFAVI, SOGAY).

Dataset file: Date_Fruit_Dataset.xlsx

Model Performance
Two models were implemented:

Decision Tree
Random Forest
The models are evaluated using the accuracy score and classification report. Below is an example output:

markdown
Copy code
Decision Tree Accuracy: 0.85
              precision    recall  f1-score   support

       BERHI       0.85      0.90      0.88       100
      DEGLET       0.87      0.82      0.84        90
      ...
Conclusion
This project demonstrates how machine learning models can be applied to classify different types of dates. The Random Forest model slightly outperformed the Decision Tree model in accuracy and precision.
