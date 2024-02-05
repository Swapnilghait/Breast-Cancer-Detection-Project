# Breast-Cancer-Detection-Project

Overview

This project aims to develop a breast cancer detection model using a dataset obtained from USI. The primary objective is to create a robust predictive model capable of accurately identifying breast cancer based on various features.

Project Steps

1. Importing Libraries 
In this step, various libraries were imported to facilitate different aspects of the project:

NumPy and Pandas: Used for data manipulation and analysis.

Matplotlib: Employed for data visualization and generating plots.

Scikit-Learn: Utilized for machine learning tasks, including model training and evaluation.


2. Importing Dataset

It includes essential information such as patient characteristics, diagnostic features, and the target variable indicating the presence or absence of breast cancer.

4. Splitting the Dataset
   
To evaluate the model's performance, the dataset was divided into training and test sets. This step is crucial for assessing how well the model generalizes to new, unseen data. An 80-20 split ratio was adopted, with 80% of the data used for training and 20% for testing.

5. Feature Scaling
   
Feature scaling was applied to ensure that all features contribute equally to the model training process. Commonly used techniques include standardization or normalization. This step enhances the model's convergence and stability.

6. Random Forest Training on Training Set
   
The Random Forest algorithm was chosen for its ability to handle complex datasets and provide robust predictions. The model was trained on the training set, learning patterns and relationships within the features to make accurate predictions regarding breast cancer diagnosis.

7. Confusion Matrix
    
The confusion matrix was employed to evaluate the model's performance. It provides insights into the number of true positives, true negatives, false positives, and false negatives. Metrics such as precision, recall, and accuracy can be derived from the confusion matrix, offering a comprehensive assessment of the model's effectiveness.
