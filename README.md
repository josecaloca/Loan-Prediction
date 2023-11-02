# SGH Warsaw School of Economics - Application of Business Intelligence in financial sector analyses

This repository contains the materials for the lecture on **The use of predictive models in credit risk management** at SGH Warsaw School of Economics, for the course **Application of Business Intelligence in financial sector analyses** [234390-0090].

The repository consists of:

1. loan_prediction_scorecard.ipynb - Jupyter notenook used for the creation of a credit scorecard.
2. data folder - contains all input files
3. logistic_reg_model.sav - final exported logistic regression model
4. scorecard.xlsx - final scorecard (human readable format)
5. SGH_loan_prediction.pptx - PPT presentation used during the lecture 

## Requirements
To run the Jupyter notebooks, make sure to install the required libraries listed in the requirements.txt file.

Firstly, we will create a conda environment called *my_env*
```
conda create -n my_env python=3.11.5
```

Secondly, we will activate the *my_env* environment that was recently created.

```
conda activate my_env
```

###  Clone this GitHub repo

```
git clone https://github.com/josecaloca/Loan-Prediction.git
```

###  Pip install all required libraries

```
pip install -r requirements.txt
```

## Usage
To use the repository, clone or download the repository to your local machine. Then, navigate to the directory containing the notebooks and open them using Jupyter Notebook or JupyterLab.
