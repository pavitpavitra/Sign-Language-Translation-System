# Sign-Language-Translation-System
CM 3070 Real Time Sign Language Translation System

This repository contains the code and resources for the Real-Time Sign Language Detection System project. The objective of this project is to develop and deploy a machine learning model that accurately detects and translates sign language gestures, providing an inclusive solution for communication between sign language and non-sign language users.
Project Overview

The project utilises various deep learning models to detect and translate sign language gestures. The best-performing model is exported and applied to an unseen dataset to evaluate its real-world effectiveness.
Contents of the Repository

This repository includes the following files:

    1. Sign_Language_Translation_System_FYP.ipynb:
        This notebook contains the code for preprocessing, training, and evaluating multiple deep learning models (e.g., CNN, CNN-LSTM, ViT) for sign language detection.
        It includes data preparation steps such as image augmentation, model training, and hyperparameter tuning.
        The notebook ends with a comparative analysis of model performance based on various metrics, including accuracy, precision, recall, and F1 score.

    2. Export_and_Apply_Model.ipynb:
        This notebook focuses on exporting the best-performing model and applying it to an unseen dataset.
        It demonstrates the steps required to load the model, preprocess the unseen dataset, and evaluate the model's performance.
        The results from this notebook provide insights into the model's ability to generalise to new, unseen data.
        
    3. Unseen Video Dataset:
        A video dataset of sign language gestures, specifically of the number '9', was prepared to test the model in a real-time setting. This dataset is used in the second notebook to         evaluate the model's practical application and performance.

