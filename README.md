# Titanic-Survival-Machine-Learning-Project
![cover](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/0e618524-1aea-428f-98c6-4d822c949d36)

In this machine learning project, the aim is to predict whether passengers aboard the Titanic survived or perished based on various features such as age, gender, ticket class, and family size.

### Dataset Overview
Our dataset contains information about 891 passengers, including:

- Survived:    Binary label (0 for not survived, 1 for survived)
- Pclass:  Ticket class (1st, 2nd, or 3rd)
- Sex: Gender (male or female)
- Age: Passenger age
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Fare: Ticket fare
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Approach
- Data Exploration: We’ll analyze the dataset, handle missing values, and visualize key features.
- Model Selection: Experiment with various classifiers (e.g., logistic regression, decision trees, random forests).
- Model Training and Evaluation: Train models, tune hyperparameters, and evaluate performance using cross-validation.
- Prediction: Apply the best model to predict survival outcomes for the test dataset.

### Process
![libraries and data preview](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/80ba11f6-9428-4e84-bdf9-39c4d9ea5a11)

- The necessary libraries were imported and the first few rows previewed.
- The data was inspected with the .info() method and null values were checked for.

![survivors by gender](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/981ac2d6-7b95-46e0-b46a-7ddd2ce4bc0d)
- On visualizing the survivors by gender, it is observed that more males were deceased and more females survived.

