 Titanic Dataset Report
1️⃣ Introduction

The RMS Titanic sinking was one of the most tragic maritime disasters in history. The ship sank on April 15, 1912, after hitting an iceberg during its maiden voyage from Southampton to New York City.

The Titanic dataset is widely used in data science and machine learning to predict whether a passenger survived or not based on different features such as age, gender, ticket class, and fare. It is one of the most popular beginner datasets in data analysis and predictive modeling.

2️⃣ Titanic Dataset Overview

The Titanic dataset (popularly used from Kaggle’s Titanic competition) contains information about passengers aboard the Titanic.

 Main Features in the Dataset:

PassengerId – Unique ID of each passenger

Survived – Survival status (0 = No, 1 = Yes)

Pclass – Ticket class (1 = First, 2 = Second, 3 = Third)

Name – Passenger name

Sex – Gender

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Ticket fare

Cabin – Cabin number

Embarked – Port of embarkation

The dataset contains 891 rows and 12 columns in the training dataset.

3️⃣ Methodology

The methodology followed in analyzing the Titanic dataset includes:

Step 1: Data Collection

The dataset is obtained from Kaggle or built-in libraries like seaborn.

Step 2: Data Cleaning

Handling missing values (Age, Cabin, Embarked)

Filling missing Age values using mean/median

Dropping unnecessary columns if required

Step 3: Exploratory Data Analysis (EDA)

Checking survival count

Analyzing survival by gender

Analyzing survival by passenger class

Studying age distribution

Step 4: Statistical & Machine Learning Modeling

Feature selection

Splitting data into training and testing sets

Applying classification algorithms like Logistic Regression

Evaluating model accuracy

4️⃣ Statistical Analysis
🔹 Survival Rate

Around 38% passengers survived

Around 62% passengers did not survive

🔹 Gender Analysis

Female passengers had a much higher survival rate compared to males.

“Women and children first” policy influenced survival chances.

🔹 Passenger Class Analysis

First-class passengers had higher survival rates.

Third-class passengers had lower survival rates.

🔹 Age Analysis

Younger passengers had slightly better survival chances.

Elderly passengers had lower survival probability.

🔹 Fare Analysis

Higher ticket fare passengers had better survival chances.

Fare is positively related to survival probability.

5️⃣ Conclusion

The Titanic dataset clearly shows that survival was strongly influenced by:

Gender

Passenger Class

Age

Fare

Women and first-class passengers had a significantly higher survival rate. This dataset helps understand how real-world data can be analyzed using statistical techniques and machine learning models.

The Titanic dataset remains one of the most important beginner datasets for learning data science concepts such as data cleaning, visualization, and predictive modeling.
