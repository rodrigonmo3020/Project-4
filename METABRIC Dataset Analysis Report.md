# METABRIC Dataset Analysis Report

## Overview of the Analysis
*   This code is made to read and clean a CSV containing the samples of 1904 reast cancer patients.

*  The dataset displays information like Age at Diagnosis, Type of Cancer, Tumor Detailed information about the tumor, including size, stage, and grade. Treatment procedure, Overall Survival Rate and the genetics atributes of -RNA levels z-score for 331 genes, and mutation for 175 genes.

*   The variable that was aimed to predict was the "overall_survival" which is the value that states if a patient with breast cancer has survived 

*   We went through bellow machine learning process as part of this analysis:
    * 1- Read and display the data
    * 2- Clean the data in order to get rid of non relevant infromation.    
    * 3- Split the data into training a testing datasets using the function train_test_split.
    * 5- Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras to create a binary classification model that can predict if a patient diagnosed with breast cancer will have a higher chance of survive or not.
    * 6- Compile and train the model.
    * 7- Evaluate the model’s performance by generating an accuracy score.

## Results
* Data Processing
    * Variable target of the model: "overall_survival"
    * Features of the model: Age at Diagnosis, Type of Cancer, Tumor Detailed information about the tumor, including size, stage, and grade. Treatment procedure, Overall Survival rate and the genetics atributes.
    * Variables removed because they are neither targets nor features: "patient_id", "cancer_type_detailed", "pam50_+_claudin-low_subtype", "tumor_other_histologic_subtype", "integrative_cluster", and the mutation column of the genes with the mutation code.

* Compiling, Training, and Evaluating the Model
    * 1st model attempt:
        layers:  2
        neurons: 15
        activation function: 'relu'
        epochs: 100
        model performance: 0.93 (accuracy)


## Summary
*   The accuracy target resulted of the deep learning model was of 93%. This accuracy level might be considering as aceptable for the breast cancer overal survival prediction however there are many other factors that might influence like the cancer treatment to follow by a patient diagnosed with breast cancer. On the other hand, the result reflects that there is a significant relationship in the information of the genes and the mutations that they experience, being a pattern in people who are diagnosed with malignant tumors.