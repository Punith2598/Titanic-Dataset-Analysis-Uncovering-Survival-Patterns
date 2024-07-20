# Titanic Dataset Analysis: Uncovering Survival Patterns

## Overview
This project applies machine learning techniques to predict the survival of passengers on the Titanic using the Titanic dataset. The objective is to uncover survival patterns based on various passenger attributes. This repository includes the complete workflow from data loading, preprocessing, model building, evaluation, to final predictions.

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data Exploration and Preprocessing](#data-exploration-and-preprocessing)
6. [Model Building and Evaluation](#model-building-and-evaluation)
7. [Predictions](#predictions)
8. [Conclusion](#conclusion)
9. [References](#references)

## Introduction
This project presents a detailed analysis and modeling process for predicting the survival of Titanic passengers using machine learning algorithms. The process involves data exploration, preprocessing, visualization, model building, evaluation, and tuning to achieve optimal prediction performance.

## Data
The dataset used is the Titanic dataset, which includes various attributes of the passengers such as age, gender, class, etc.

Files included:
- `train.csv`: The training dataset.
- `test.csv`: The test dataset.
- `gender_submission.csv`: Example of a submission file.
- `submission.csv`: The final predictions made by the best model.

## Files
- **`Titanic - Machine Learning from Disaster.ipynb`**: Jupyter Notebook with analysis and model training.
- **`Titanic Disaster.pdf`**: Detailed project report.
- **`Titanic-Dataset-Analysis-Uncovering-Survival-Patterns.pptx`**: Presentation summarizing the findings.
- **`requirements.txt`**: List of Python packages required.

## Installation
To run this project, you need to have Python installed along with the following libraries:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn jupyter
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Punith2598/Titanic-Dataset-Analysis-Uncovering-Survival-Patterns.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Titanic-Dataset-Analysis-Uncovering-Survival-Patterns
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook 'Titanic - Machine Learning from Disaster.ipynb'
   ```

## Data Exploration and Preprocessing
1. **Data Loading and Inspection**: The dataset contains passenger information such as age, gender, ticket class, etc.
2. **Missing Value Analysis**: Identified and handled missing values in columns such as 'Age' and 'Cabin'.
3. **Feature Engineering**: Created new features such as 'FamilySize' and 'IsAlone' to capture additional information.
4. **Target Variable Encoding**: The 'Sex' column was encoded to binary values (male: 0, female: 1).

## Model Building and Evaluation
1. **Model Selection**: Evaluated several models including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Machine (SVM).
2. **Training Process**: Models were trained using an 80-20 train-validation split.
3. **Evaluation Metrics**: Models were evaluated using accuracy, precision, recall, and F1 score. Random Forest and Gradient Boosting achieved the highest F1 scores.

## Predictions
- Predictions were made on the test set.
- The submission file `submission.csv` was prepared for submission to the competition or further analysis.

## Conclusion
This machine learning model demonstrates high accuracy in predicting the survival of Titanic passengers, potentially aiding in uncovering survival patterns. Future work could involve further optimization and continuous improvement with new data.

## References
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

This README covers all the essential aspects of your project and provides clear instructions and explanations for users to follow and understand your work.
