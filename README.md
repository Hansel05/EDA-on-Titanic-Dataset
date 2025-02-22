# EDA-on-Titanic-Dataset

## Overview
The Titanic disaster remains one of history's most infamous maritime tragedies. This project analyzes the Titanic dataset using Exploratory Data Analysis (EDA) to uncover patterns and trends related to passenger survival.

We explore how different features like class, gender, age, fare, and embarkation point influenced survival chances, providing insights into the socio-economic factors at play during the event.

## Dataset
Description of the dataset.
- `PassengerId`: Unique ID given to each passenger
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Name of the passenger
- `Sex`: Sex of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of Siblings/Spouse aboard
- `Parch`: Number of Parent/Child aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare (Bristish Pound)
- `Cabin`: Cabin alloted to the passenger
- `Embarked`: Passenger from which port (S: Southampton, C: Cherbourg, Q: Queenstown)

## Exploratory Data Analysis (EDA)
### Data Cleaning:
1. Filled missing Age values with the median value.
2. Dropped the Cabin column doe to many missing values.
3. Filled missing Embarked values with the most frequent value.
4. Dropped `PassengerId`, `Name` and `Ticket`.

### Visualization:
#### Univariate Analysis:
Visualized all features to understand distributions.

#### Bivariate Analysis:
- `Survived` vs. all columns.
- `Pclass` vs. all columns.
- `Sex` vs. `Age` & `Fare`.
- `Fare` vs.`Embarked`.

# Insights
- **Sex of the passenger**: The sex of the passenger played a crucial role in survival. Females have a higher cahnce of survival.
- **Fare**: Higher fares were associated with higher survival rates.
- **Passenger Class**: Pclass 1 has more number of survivors due to the fact that the passenger paid a higher fare for a luxurious experience hence were given priority.
- **Age**: Younger passengers had a slightly higher survival rate, while older adults had lower survival chances.
- **Family Size**: Passengers traveling alone had a better survival rate than those in large families.

# Tools and Technologies
- Programming language: Python
- Libraries Used: Pandas, NumPy, Matplotlib, Seaborn, Sklearn

# Future Improvements
- Perform feature engineering to extract more insights.
- Build a machine learning model to predict survival.
