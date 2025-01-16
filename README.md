# Breast-Cancer-Classification-Decision-Tree-
Objective:

    Make a proper decision tree for classifying the data to give status as “Alive” or “Dead”.
    Fit the data to your decision tree model and show the validation loss and accuracy  plot varying the epoch (iteration) value from 1 to 20.

Dataset:

This dataset of breast cancer patients was sourced from the SEER Program's November 2017 update, which offers population-based cancer statistics. It includes data on female patients diagnosed between 2006 and 2010 with infiltrating duct and lobular carcinoma of the breast (histology codes 8522/3 according to SEER primary site recode NOS).

Input variables with their descriptions:

    Age
    Age of the patient.
    Race
    Patient's race. Other categories: American Indian/AK Native, Asian/Pacific Islander.
    Marital Status
    Marital status of the patient.
    T Stage
    Adjusted AJCC 6th T stage classification for the tumor.
    N Stage
    Adjusted AJCC 6th N stage classification for regional lymph nodes.
    6th Stage
    Breast cancer adjusted AJCC 6th stage classification.
    Differentiate
    The degree of differentiation of the tumor.
    Grade
    The grade of the tumor, indicating its aggressiveness.
    A Stage
        Regional: Neoplasm that has extended.
        Distant: Neoplasm that has spread to remote parts of the body either through direct extension or metastasis.
    Tumor Size
    Exact size of the tumor, measured in millimeters.
    Estrogen Status
    Status of estrogen receptor in the tumor.
    Progesterone Status
    Status of progesterone receptor in the tumor.
    Regional Node Examined
    Number of regional lymph nodes examined.
    Regional Node Positive
    Number of regional lymph nodes positive for cancer.
    Survival Months
    Number of months the patient survived after diagnosis.

Output variable: Status: Dead/Alive

Method:

    For making the decision tree apply “gini impurity” approach.
