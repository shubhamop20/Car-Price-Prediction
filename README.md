# Car Price Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset
This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier, etc..
Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others.
Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.

Data Collection: 
[Car Price Prediction](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho) from Kaggle

Website Link: ["https://rainy-brain.herokuapp.com/"](https://rainy-brain.herokuapp.com/)

Testing values

Tech Stack
* Front-End: HTML
* Back-End: Flask
* IDE: Jupyter notebook, Pycharm

How to run this app
* First create a virtual environment by using this command:
* conda create -n myenv python=3.6
* Activate the environment using the below command:
* conda activate myenv
* Then install all the packages by using the following command
* pip install -r requirements.txt
* Now for the final step. Run the app
* python app.py


Workflow
1. Problem Statement and Solution Design 
2. Exploratory Data Analysis 
3. Model Building and Selection 
4. Coding Backend, FLASK API and Testing 
5. Coding Frontend HTML and Testing 
6. Deployment in AWS EC2 with NGINX, Guinicorn, Supervisor 







