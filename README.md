Project Title: Breast tumor Prediction
Team Members:

Mary nourel meriem
Project Overview:

This project aims to create a model that predicts whether a tumor is cancerous (malignant) or not (benign) using information from a dataset.
Dataset:

    Training Dataset: This dataset has examples of tumors with features like size and texture, along with labels showing whether they are malignant or benign.
    Testing Dataset: This dataset has the same features but does not include labels. It is used to test the model’s performance.

Steps Taken:

    Data Loading: We loaded the datasets using pandas.
    Data Preprocessing:
        Checked for missing values and handled them.
        Scaled the data to make sure all features are similar in size for better training.
    Feature Selection: We separated the labels (diagnosis) from the features (tumor characteristics).
    Data Splitting: The data was divided into training and validation sets to test the model.
    Model Training:
        We used a logistic regression model to train on the training data.
        The model was set to run for a maximum of 500 iterations to ensure it learned well.
    Model Evaluation: We checked the model’s accuracy using the validation set, and it achieved an accuracy of 98.75%.

Conclusion:

The model showed that it could accurately predict breast cancer diagnoses based on tumor features. This project highlights how important it is to prepare data and evaluate models effectively.
