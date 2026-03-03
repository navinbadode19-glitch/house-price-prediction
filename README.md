# Housing Price Prediction

##  Overview

This project focuses on predicting housing prices using machine learning techniques on the California housing dataset.
It includes Exploratory Data Analysis (EDA), data preprocessing, and model training using multiple regression algorithms.

---

##  Dataset

* Dataset: California Housing Dataset (from Kaggle)
* Contains features such as median income, housing age, total rooms, population, and location
* Used for predicting median house value

---

##  Technologies Used

* Python 
* Pandas & NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

##  Exploratory Data Analysis (EDA)

* Analyzed feature distributions using histograms
* Studied relationships between features using scatter plots
* Generated correlation matrix and heatmap
* Identified important features affecting house prices
* Detected patterns and trends in the dataset

---

##  Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

---

##  Data Processing

* Stratified sampling using `StratifiedShuffleSplit`
* Handling missing values using `SimpleImputer`
* Feature scaling using `StandardScaler`
* Categorical encoding using `OneHotEncoder`
* Pipeline and ColumnTransformer used for preprocessing

---

##  Model Performance

### 🔹 Linear Regression

* RMSE: **69050.56**
* Cross-validation RMSE (mean): **69204.32**

---

### 🔹 Decision Tree

* RMSE: **0.0** *(overfitting)*
* Cross-validation RMSE (mean): **69081.36**

---

### 🔹 Random Forest ⭐ (Best Model)

* RMSE: **18342.36**
* Cross-validation RMSE (mean): **49432.13**

---

## 📊 Key Insights

* Decision Tree shows overfitting (perfect training score but poor generalization)
* Random Forest significantly improves performance and reduces error
* Linear Regression provides a stable baseline model

---


## 👨‍💻 Author

Navin Badode

---


If you found this project useful, consider giving it a ⭐ on GitHub!
