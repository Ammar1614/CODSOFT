🎬 CODSOFT – Movie Rating Prediction**

This repository contains one of the major projects completed during my CodSoft Virtual Data Science Internship. This task focuses on building a machine learning model that predicts movie ratings based on key features such as genre, director, cast, and other attributes.

The project demonstrates strong understanding of data preprocessing, feature engineering, exploratory data analysis, and regression modeling.

---

📌 Task Overview

The objective of this project is to predict the rating of a movie using historical movie data. This involves analyzing movie characteristics and building a regression model capable of estimating ratings accurately.

This end-to-end workflow includes:

* Data loading & cleaning
* Handling missing values
* Encoding categorical features
* Feature engineering
* Model training
* Model evaluation

---

🔹 1. Loaded the Dataset

Imported the `movies2.csv` file into a Pandas DataFrame for analysis.

---

🔹 2. Data Cleaning & Imputation

Performed essential cleaning steps:

* Handled missing values using:
* Median for numerical features
* Mode for categorical features
* Ensured correct encoding for special characters
* Removed irrelevant or duplicate columns (if any)

---

🔹 3. Feature Engineering

To improve model performance, additional useful features were created:

* title_word_count – number of words in a movie title
* genre_count – number of genres associated with a movie
* Label Encoding applied to categorical columns:

  * Genre
  * Director
  * Actors
  * Language
  * Country
  * And others present in the dataset

---

🔹 4. Data Preprocessing

* Converted all encoded categorical features to numeric format
* Prepared the feature matrix X and target variable y (movie rating)

---

 🔹 5. Model Training

Trained multiple regression models to predict the movie rating, including:

* Linear Regression
* Random Forest Regressr
* Gradient Boosting Regressor

Used an 80/20 train-test split for evaluation.

---

🔹 6. Model Evaluation

Evaluation metrics used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score (Coefficient of Determination)

The Random Forest Regressor achieved the best performance on test data, delivering strong accuracy and low prediction error.

Technologies Used
The following tools and libraries were used in this project:
* Python
* Pandas – Data manipulation and cleaning
* Matplotlib / Seaborn– Data visualization
* Scikit-learn – Feature encoding, model building & evaluation
* Jupyter Notebook – Interactive development



📊 Outcome

This project provided hands-on experience with:

* Working on real-world movie datasets
* Encoding categorical features for regression tasks
* Building and comparing multiple regression models
* Improving predictions with feature engineering
* Interpreting key regression metrics

The final model successfully predicts movie ratings based on movie properties with high accuracy.


 📁 Files in This Repository

  movie123.ipynb – Jupyter Notebook with the full implementation
  movies2.csv– Movie dataset used
  README2.md – Project documentation

---

 🤝 Acknowledgement

This project was completed as part of the CODSOFT Data Science Internship Program, helping me build strong foundational skills in data preprocessing, machine learning, and project structuring.

