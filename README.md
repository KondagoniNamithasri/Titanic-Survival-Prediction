# Titanic Survival Prediction

## *Overview*
This project predicts the survival of passengers aboard the Titanic using machine learning models. By analyzing demographic and socio-economic data, we identify patterns and insights that influenced passenger survival.

## *Key Features*
- *Data Preprocessing*: Handling missing values, encoding categorical variables, and scaling numerical features.
- *Exploratory Data Analysis (EDA)*: Visualizing data to uncover trends and relationships.
- *Feature Engineering*: Creating and optimizing features for better model performance.
- *Model Building*: Training and evaluating machine learning models such as Logistic Regression, Decision Trees, and Random Forests.
- *Performance Evaluation*: Using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to assess model effectiveness.

## *Dataset*
The dataset is sourced from [Kaggle's Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) and includes the following key columns:
- *PassengerId*: Unique identifier for each passenger.
- *Survived*: Target variable (0 = No, 1 = Yes).
- *Pclass*: Ticket class (1st, 2nd, or 3rd).
- *Name*: Name of the passenger.
- *Sex*: Gender of the passenger.
- *Age*: Age of the passenger.
- *SibSp*: Number of siblings/spouses aboard.
- *Parch*: Number of parents/children aboard.
- *Fare*: Ticket fare.
- *Embarked*: Port of embarkation (C, Q, S).

## *Technologies Used*
- *Programming Language*: Python
- *Libraries*: pandas, numpy, matplotlib, seaborn, scikit-learn
  
## *How to Run*
1. Clone the repository:
   bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   
2. Install the required dependencies:
   bash
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook or Python script:
   bash
   jupyter notebook Titanic_Survival_Prediction.ipynb
   
## *Results*
The machine learning models achieved the following performance metrics:
- *Logistic Regression*: Accuracy = 80%
- *Random Forest*: Accuracy = 85%

## *License*
This project is licensed under the [MIT License](LICENSE).

## *Contributing*
Contributions are welcome! Please fork the repository and submit a pull request.

## *Acknowledgements*
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- Open-source libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
