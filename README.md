# titanic-ml-project
A beginner-friendly machine learning project using the Titanic dataset to predict passenger survival, built without tutorials and fully understood line-by-line.

Titanic Survival Prediction (ML Project)

This project is a machine learning model that predicts whether a passenger survived the Titanic shipwreck based on various features like age, sex, class, etc. It was built from scratch as a personal learning milestone — without blindly following any tutorial.

Project Highlights
- End-to-end classification using the Titanic dataset.
- Models used: Logistic Regression, Random Forest, K-Nearest Neighbors, and more.
- Feature importance visualization.
- Hyperparameter tuning with GridSearchCV.
- Evaluation using confusion matrix, accuracy, and cross-validation.

Files Included
- `titanic_model.ipynb` – Jupyter Notebook with all code and explanation.
- `cleaned_titanic.csv` – Dataset used (from Kaggle Titanic competition).
- `README.md` – This file.

Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Features Used
- `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`
- Dropped unnecessary columns like `Name`, `Ticket`, `Cabin`, and `PassengerId`.

Models Trained
- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

Evaluation
- Accuracy Score
- Confusion Matrix
- Cross-Validation
- Feature Importance Visualization

Future Improvements
- Add more preprocessing steps (e.g., feature engineering).
- Test with more advanced models like XGBoost or SVM.
- Convert into a web app using Flask.

How to Run
1. Open `titanic_model.ipynb` in Jupyter Notebook.
2. Make sure the Titanic dataset (`cleaned_titanic.csv`) is in the same directory.
3. Run cells step-by-step to see data cleaning, model training, and evaluation.

---

