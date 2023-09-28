Diabetes Prediction Project
Overview

This project aims to predict whether a person has diabetes based on various health metrics. Using the National Institute of Diabetes and Digestive and Kidney Diseases dataset, we built and compared different machine learning models to find the best one.
Dataset

    Source: National Institute of Diabetes and Digestive and Kidney Diseases.
    Columns: The dataset includes multiple features like glucose levels, blood pressure, age, BMI, and more.


Steps Followed

    Exploratory Data Analysis (EDA):
        Checked for missing values.
        Analyzed the relationships between features and the outcome.
        Studied feature distributions and correlations.

    Data Preprocessing:
        Fixed odd values (like a glucose level of zero).
        Scaled features so they're in the same range.
        Used oversampling to balance out the dataset.

    Model Training:
        Trained two models: Logistic Regression and Random Forest.
        Compared their performance based on accuracy, precision, recall, etc.

    Model Evaluation:
        Used various metrics to evaluate the performance of the models on a separate test set.

Results

    Logistic Regression turned out to be a simple and effective choice for this task, providing interpretable results and consistent predictions.

Usage

    Load your data.
    Split the data into training and testing sets.
    Use the provided Python code to preprocess your data.
    Train the model using the training set.
    Evaluate the model using the testing set.

Conclusion

The project highlights the importance of understanding and preprocessing data before training machine learning models. The chosen model, Logistic Regression, offers a balance between simplicity, speed, and performance.
