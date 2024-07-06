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
- We can infer from this visual that preference was given to females when it came to handing out life jackets and life boats


![survivors by Pclass](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/d3110ecc-5c96-4a14-8181-2631620652b2)
- An intriguing insight is seen here where majority of the deceased were in the third class whilst majority of the survivors were rich people in the first class.

- Other interesting insights are seen below together with the machine learning models.
- Download the notebook for a full view of the project

![Age distribution](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/6910ffc6-a818-4ea6-bc1d-bbcd7cc4f07b)

![Siblings and spouses](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/4e56448e-5180-4ad8-bf47-d9f7d394505e)

![Survival by parentschild](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/41c48823-e1f2-4718-aeae-344ded6b3340)

![fares distribution](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/2761b991-138d-404d-8b96-8346dae09e43)

![ML imports](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/75f2ca00-1caa-426e-a5f1-4bc12b496b22)

![logistc reg 2](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/1d4adf90-46e0-4b1c-b387-fb877169e911)

![random forest](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/1e7374fa-2baf-49e7-9716-aefadcaba15a)

![decision tree](https://github.com/joelkaku/Titanic-Survival-Machine-Learning-Project/assets/131392907/a55d69b6-547e-4a7b-add5-89784f6c0601)

