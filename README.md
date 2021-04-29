##### Project title:

CREDIT CARD DEFAULT PREDICTION AND MODEL INTERPRETATION USING POST- HOC EXPLAINABILITY TECHNIQUES 

##### Motivation:

With the increasing growth in credit card usage comes the challenge of escalating credit card default rate. This research aims to identify risky and non-risky customers by predicting credit card default payments using Taiwan Bank dataset. The aim is to develop an integrated predictive credit card default model to assist financial institutions in addressing at-risk customer profiles and explore the capabilities of various model interpretability techniques to generate explainable insights into prediction model outcomes.

##### Hardware and Software Setup:

    Hardware - Intel Core i5-850U CPU, 1.6 GHz, 4 cores, 8 GB DDR RAM , Windows 10 64-bit OS
    Software - Jupyter Notebook, Anaconda Command Prompt (conda 4.8.4)
    Programming Language - Python 3.7.6

##### Installations:

To run this project, install the below libraries.
    
    pip install lime
    pip install shap
    pip install xgboost
    pip install cufflinks --upgrade
    
The required python libraries are imported in each Notebook separately
    
##### Dataset Source:

    The input dataset 'default_of_credit_card_clients.xls' is included in the same folder as all the Notebooks.
    
This dataset is from UCI repository (https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) to predict whether the credit card holders are defaulters or Non-defaulters. It contains information on default payments, demographic factors, credit data, payment history, and bill statements of credit card clients in Taiwan from April to September of 2005. It consists of 25 attributes and 30,000 observations.

##### Navigation of  iPython Notebooks:

All the codes are organized numerically and placed in a single folder.
Each stage of the project is coded and implemented in separate Notebooks.
All the intermediate files from Notebooks are saved at the end of each book and imported back in the next Notebook.

Run the Python codes in the order specified below:

    1. Data Pre-processing.ipynb
    2. Exploratory Data Analysis.ipynb
    3. Data Transformation.ipynb
    4. Data_Balancing.ipynb
    5. Feature Selection.ipynb
    6. Dimensionality_Reduction.ipynb
    7. Evaluation and Hyperparameter Tuning.ipynb
    8. LIME & SP-LIME.ipynb
    9. Tree SHAP and Linear SHAP.ipynb

##### Note:

Below are the codes that require considerably higher computation time.

    1. "models_comparison" function used in Notebook 4,5,6,7 for comparing model performances
    2. "hyper_params_tree" and "hyper_params_nontree" functions in Notebook 7 to identify suitable hyperparameters for tuning
    3. "shap.TreeExplainer" codes in Notebook 9 for generating SHAP explanations

##### About the author:

SAHANA K
Student ID - 927731
Liverpool John Moores University - Master’s in Data Science 
Batch C5 (NOV 2020)