# Capstone-Advanced-Data-Science-Project

## Description
This project aims to predict car prices based on various features such as mileage, engine volume, number of cylinders, and others. The dataset used for this project is sourced from "capstone.csv".

## Table of Contents
1. [Importing Data](#importing-data)
2. [Preprocessing](#preprocessing)
3. [Normalize the Data](#normalize-the-data)
4. [Training](#training)
5. [Hyperparameter Tuning](#hyperparameter-tuning)
6. [Results Visualization](#results-visualization)
7. [Conclusion](#conclusion)
8. [Dependencies](#dependencies)
9. [Setup Instructions](#setup-instructions)
10. [Usage](#usage)

## Importing Data
The dataset is imported using pandas from "capstone.csv".

## Preprocessing
- Missing values in the 'Levy' column are replaced with NaN and then filled with 0.
- The 'Engine volume' and 'Mileage' columns are converted to numeric values.
- Categorical columns are one-hot encoded.
- Irrelevant columns are dropped.
- The preprocessed data is saved to "mydata.csv".

## Normalize the Data
The data is normalized using sklearn's `normalize` function.

## Training
The dataset is split into training and testing sets, and a linear regression model is trained.

## Hyperparameter Tuning
Various regression models are evaluated using GridSearchCV for hyperparameter tuning.

## Results Visualization
A scatter plot is created to visualize the actual vs. predicted prices.

![image](https://github.com/Yashchaudhari29/Capstone-Advanced-Data-Science-Project/assets/119956179/2221557f-37a9-405a-a5f3-fb2456785317)


## Conclusion
The project successfully predicts car prices using regression techniques and gained **99.99% accuracy**.

![image](https://github.com/Yashchaudhari29/Capstone-Advanced-Data-Science-Project/assets/119956179/711b980e-07c5-49c4-8f57-f5c6b2597892)

## Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib

## Setup Instructions
1. Clone this repository.
2. Install the required dependencies using pip:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```
3. Run the Jupyter notebook.

## Usage
- Run the cells in the Jupyter notebook sequentially to execute the entire pipeline.
- Modify the preprocessing steps or model hyperparameters as needed.

