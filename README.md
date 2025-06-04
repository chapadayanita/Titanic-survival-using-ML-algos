# 🚢 Titanic Survival Prediction using Decision Tree

This project uses a **Decision Tree Classifier** to predict whether a passenger survived the Titanic disaster based on various features.

## 📁 Dataset

The dataset used is `titanic.csv`, which includes information about the passengers such as:

| Feature     | Description                                |
|-------------|--------------------------------------------|
| `Pclass`    | Ticket class (1st, 2nd, 3rd)               |
| `Sex`       | Gender (male/female)                       |
| `Age`       | Age of the passenger                       |
| `SibSp`     | Number of siblings/spouses aboard          |
| `Parch`     | Number of parents/children aboard          |
| `Fare`      | Fare paid for the ticket                   |
| `Survived`  | Target variable (0 = No, 1 = Yes)          |

## 🛠️ Technologies Used

- Python
- Pandas
- scikit-learn
- Matplotlib

## 🔍 Workflow

1. **Load and preprocess** the Titanic dataset
2. Handle missing values for `Age` and `Fare`
3. Convert categorical column `Sex` to numeric
4. Select key features for training
5. Split data into training and testing sets
6. Train a **Decision Tree Classifier**
7. Make predictions and evaluate the model
8. Predict the survival of a **new hypothetical passenger**
9. Plot a scatter graph of actual vs predicted values

## 📊 Features Used for Model

- `Pclass` (Ticket class)
- `Sex` (Converted to binary: male = 0, female = 1)
- `Age`
- `SibSp`
- `Parch`
- `Fare`

## 📈 Output

- Accuracy of the model on the test set
- Survival prediction for a new passenger with the following details:
  - Pclass: 2
  - Sex: female (1)
  - Age: 30
  - SibSp: 0
  - Parch: 0
  - Fare: 10
- A scatter plot comparing actual and predicted survival values
