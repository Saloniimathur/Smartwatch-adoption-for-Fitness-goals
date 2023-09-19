# Smartwatch-adoption-for-Fitness-goals


![Uploading image.png…]()

## Overview

This project explores the relationship between user attributes and smartwatch data to predict fitness goals, specifically the number of steps a user should aim for. It utilizes machine learning models, including linear regression and random forest regression, to make these predictions based on user characteristics.

## Dataset

We used a dataset obtained from Kaggle, which includes various user attributes and smartwatch data. The dataset contains the following columns:

- `Age`: User's age.
- `Activity Level (Steps)`: User's current activity level measured in steps.
- `Sleep (round off Hours)`: User's average sleep duration, rounded to the nearest hour.
- `Heart Rate (BPM)`: User's average heart rate in beats per minute.
- `Weight (kg)`: User's weight in kilograms.
- `Height (cm)`: User's height in centimeters.
- `Fitness Goals (Steps)`: The target variable we aim to predict, representing the user's fitness goal in terms of daily steps.

## Model Training

We've employed two regression models for this project:

1. **Linear Regression**: A straightforward linear model that establishes a relationship between the input features and fitness goals.

2. **Random Forest Regressor**: An ensemble learning model that combines multiple decision trees to provide more accurate predictions.

Both models have been trained and evaluated to predict fitness goals based on the provided user attributes.

## Usage

1. Clone the repository
2. Install the required Python libraries
3. Run the prediction script
4. 
4. Input your values for the following user attributes when prompted:
- Age
- Activity Level (Steps)
- Sleep (round off Hours)
- Heart Rate (BPM)
- Weight (kg)
- Height (cm)

5. The script will then use the trained model to predict your fitness goals (daily steps) based on the provided attributes.

## Model Persistence

We've saved the trained model as a `.pkl` file. You can easily load this model and use it for predictions in your own applications.

## Contributing

We welcome contributions to this project. If you have ideas for improvements or bug fixes, please open an issue or submit a pull request. 


## Acknowledgments

- Kaggle for providing the dataset.
- Scikit-learn for the machine learning libraries used in this project.

Feel free to reach out with any questions or feedback!


