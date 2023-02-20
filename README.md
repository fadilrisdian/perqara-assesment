# Perqara-Assesment

This project is an assessment test for data scientist positions at Perqara.

The following tasks are:
1. Data preparation process
2. Create basic analytics on the nature of the data
3. Providing advanced analytics such as forecast, geoanalysis, outlier, RFM or clustering
4. Generate a model which can be applied to the data based on analytics above (plus value)
5. Documenting all the process and analytics result
6. Submissions must be in reproducible codes in GitHub/GitLab
7. Any language can be used to build the pipeline but Python is preferable and prioritized

# Installation

    git clone https://github.com/fadilrisdian/perqara-assesment.git
    cd perqara-assesment
    pip install requirements.txt

# Dataset

Download the dataset from:

https://drive.google.com/file/d/1U55Axq3zL479fxCPosIEJvlS9AqISeS-/view?usp=sharing

    mkdir data

move data-perqara.zip to data and extract the zip file

# Main Code

main.ipynb

# Model Results

| Model                   | MAE        |RMSE|
| :---                    | ---        |---|
| Random Forest Regressor | 91.87      |11202.21|
| XGB Regressor           | 88.99      |10406.53|
| Linear Regression       | 84.49      |9688.12|
| Auto Arima              | 123.89     |19804.83|