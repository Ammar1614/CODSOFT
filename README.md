# CODSOFT
This repository contains all the projects completed during my CodSoft Virtual Data Science Internship. Each task demonstrates my understanding of core data science concepts, including data cleaning, exploratory analysis, machine learning, and model evaluation.

CODSOFT – Titanic Survival Prediction

📌 Task Overview

This project focuses on the classic Titanic Survival Prediction problem, a foundational task in machine learning and data science. The goal was to build a robust binary classification model to predict whether a passenger on the Titanic survived 

 📂 What I Did
 
This section details the complete workflow, from data preparation to model evaluation:

Loaded the dataset(`titanicds.zip`) into a Pandas DataFrame.
Data Cleaning and Imputation:
    Handled missing values in `Age` (imputed with the median) and `Embarked` (imputed with the mode).
    * Addressed missing `Fare` value (imputed with the median).
 Feature Engineering:
    * Created the `FamilySize` feature by summing siblings/spouses and parents/children (`SibSp` + `Parch` + 1).
    * Extracted the `Title` feature (e.g., 'Mr', 'Miss') from the `Name` column, as it correlates strongly with age and social status.
  Data Preprocessing:
    * Used a Scikit-learn **`ColumnTransformer`** to apply **One-Hot Encoding** to all categorical features (`Sex`, `Embarked`, `Title`).
  Model Training:
    * Employed a **Random Forest Classifier** as the predictive model, wrapped within a Scikit-learn **`Pipeline`**.
    * Trained the model using an 80/20 train/test split.
  Model Evaluation:
    * Assessed performance using **Accuracy** and a detailed **Classification Report**.

🛠 Technologies Used

The following technologies were essential for developing and executing this machine learning solution:

* Python (Programming language)
* Pandas (Data manipulation and cleaning)
* Scikit-learn (`sklearn`) (Machine learning, pipelines, and evaluation)
* Jupyter Notebook (Interactive development environment)

 📊 Outcome

The trained Random Forest model achieved a high level of performance on unseen test data:

Accuracy:~83.24%

This task provided hands-on experience in:

 Implementing a complete Machine Learning Pipeline.
* Crucial data cleaning and feature engineering techniques.
* Using Scikit-learn tools (`Pipeline`, `ColumnTransformer`, `RandomForestClassifier`) for building robust models.
* Interpreting Classification Report metrics (Precision, Recall, F1-Score).

***

 📁 Files in This Repository

 `titanic.ipynb` – The Jupyter Notebook containing the complete Python code for data processing, training, and evaluation.
 `titanicds.zip` – The dataset used for this project.
`README.md` – This project description.

🤝 Acknowledgement

This project was completed as part of the CODSOFT Data Science Internship.
