# Titanic Survival Prediction

This project aims to predict whether a passenger survived the Titanic disaster based on various attributes using Logistic Regression.

## Table of Contents

Introduction
Dataset
Attributes
Installation
Usage
Results
Contributing
License
Introduction

The Titanic Survival Prediction project utilizes Logistic Regression to predict the survival of passengers on the Titanic. The dataset includes several attributes that describe each passenger's demographic and travel information.

## Dataset

The dataset consists of passenger information, including their survival status, ticket class, sex, age, and other related attributes. The dataset used for this project can be found on seaborn website.

## Attributes

The dataset includes the following attributes:

survived: Survival (0 = No, 1 = Yes)
pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
sex: Sex of the passenger
age: Age of the passenger in years
sibsp: Number of siblings/spouses aboard the Titanic
parch: Number of parents/children aboard the Titanic
fare: Passenger fare
embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
class: Ticket class (First, Second, Third)
who: Gender and age group (man, woman, child)
adult_male: Whether the passenger is an adult male (True/False)
deck: Deck on which the passenger was staying
embark_town: Town where the passenger boarded the ship
alive: Survival status (yes/no)
alone: Whether the passenger was alone (True/False)

## Installation

To get started with the project, clone the repository and install the necessary dependencies.

'''ruby
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
'''

## Usage

Follow these steps to use the Titanic Survival Prediction model:

Prepare the Data: Ensure the dataset is in the correct format and preprocessed. This may involve handling missing values, encoding categorical variables, and scaling numerical features.

Train the Model: Run the script to train the logistic regression model.

'''ruby
python train_model.py
'''
Make Predictions: Use the trained model to make predictions on new data.
'''ruby
python predict.py --input data/new_passengers.csv
'''
## Results

The logistic regression model provides a prediction for each passenger's survival. The model's performance can be evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
