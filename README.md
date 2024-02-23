## About this repository

This repository contains a machine learning model that recommand the right doctor according to the symptoms of the patient.

The training of this model can be found in the python notebook named `model_training.ipynb`

## About the notebook

The notebook contains two parts:

* EDA (Exploratory Data Analysis): Where we perform a statistical analysis of our dataset
* Model training: We select the relevant models for our problem and optimize the hyperparameters of the model

## About the dataset

The dataset is a .xlsx file containing binary variables that represents the symptoms of the patient and the doctor that the patient should consult.

It was found on the site kaggle.com, you can find it [here](https://www.kaggle.com/datasets/ebrahimelgazar/doctor-specialist-recommendation-system)

## How to replicate the results

The dataset can be found in the repository under the name `dataset.xlsx`

To execute the notebook, you need Python 3 and the following libraries:

* matplotlib
* numpy
* pandas
* seaborn
* sklearn

You can install these libraries using the following command:

```shell
pip install requirements.txt
```

requirements.txt is the txt file containing the names of the necessary libraries