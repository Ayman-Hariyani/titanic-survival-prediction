Titanic Survival Prediction 🚢 

📌 Overview

```markdown
The Titanic dataset contains records of 891 passengers aboard 
the RMS Titanic, which sank in April 1912. The dataset includes 
features such as passenger class, gender, age, fare paid, and 
port of embarkation.

The goal of this project is to predict whether a passenger 
survived or not based on these features.

```

📊 Dataset

* Source: Kaggle Titanic Dataset
* Features include age, gender, ticket class, fare, etc.

⚙️ Approach
* Data Cleaning:
   * Handled missing values (Age, Embarked)
   * Dropped Cabin due to excessive nulls
* Exploratory Data Analysis:
   * Survival trends based on gender, class, and age
* Feature Selection:
   * Selected relevant predictors
* Models Used:
   * Logistic Regression
   * Random Forest
  
📈 Results
* Logistic Regression Accuracy: 77%
* Random Forest Accuracy: 82.5%

🚀 Future Improvements
* Add feature engineering (Family Size, Titles)
* Use cross-validation
* Hyperparameter tuning
* Improve evaluation metrics (F1-score, Recall)

 🛠️ Tech Stack
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

 🔍 Key Insights
- 38.38% survival rate — dataset is imbalanced
- Sex is the strongest predictor — females survived at dramatically higher rates
- 1st class passengers survived most, 3rd class died most
- Fare is a moderate predictor — survivors paid more than double the fare
- Age alone is a weak predictor of survival
