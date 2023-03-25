
# Insurance Premium Prediction

The goal of this project is to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather han the ineffective part.


## Dataset :
The dataset is collected from Kaggle

Data source : https://www.kaggle.com/datasets/noordeen/insurance-premium-prediction
## Approach :

Performed various machine learning tasks like Data Pre-processing, Data Visualization, Feature Engineering, Model Building, Model Testing etc. to build a solution that should able to predict the premium of the personal for health insurance.

The following approach explains the project lifecycle :

1) Data Preprocessing : Exploring the data using pandas, numpy & identifying null values, missing values and outliers present in the dataset.
2) Data Visualization : Visualize the data through matplotlib, seaborn for finding insights of the variables present the dataset.
3) Feature Engineering : Cleaning the data to select and transform the most relevant variables from raw data.
4) Model Building : For model building we split the data into train and test. Then we train our model on different machine learning algorithms like :

    i.   Linear Regression
    ii.  Support Vector Regressor
    iii. Random Forest Regressor
    iv.  Gradient Boosting Regressor

5) Model Testing : We use test data to get the predicted values and the model with best r2_score and lowest MAE is selected. The best model is saved for predictions.
6) Tuning : Performed Hyperparameter tuning using RandomizedSearchCV and GridSearchCV to get the best parameters.
7) Webpage : A web application is created for the user to easily enter the necessary inputs and get the predictions.
8) Deployment : The project is deployed on Heroku Platform.
## Web Deploement
Checkout the webapp by clicking the link below.

Link : https://atharva-git-code-insurance-premium-prediction-app-gol7nq.streamlit.app/
Link : http://rocky-savannah-26447.herokuapp.com

## High Level Design :

URL: https://docs.google.com/document/d/1czzpeU5Cev99vwXIrdmDIbyNmYvQxmIxJSNU-aLGD7s/edit?usp=share_link
## Low Level Design :

URL : https://docs.google.com/document/d/13aeREAXKkGBJ8hmG7F_Gqp5p60lEwWjxzLowk0qaJgU/edit?usp=share_link
## Architecture Design :

URL: https://docs.google.com/document/d/17IIPw5_kiW6Z9yemBHX_WGPSXNTiXx4piybU7k6KcLI/edit?usp=share_link
## Wireframe Document :

URL:https://docs.google.com/document/d/11ZcKv_1vpHRjRbpFsv2C3TnfkVMefr_gIQPRkC31vbo/edit?usp=share_link

## Detailed Project Report :

URL:https://drive.google.com/file/d/19L5j23m9UmTQPzqNFNG2zDCXz40fvI1K/view?usp=share_link
## Project Demo Video :

   URL:

## Tools and Technologies Used :

    1) Jupyter Notebook is used as IDE.
    2) For creating webapp Streamlit framework is used.
    3) Heroku is used for Model Deployment
## Author

Atharva Fulmamdikar (Linkedin : https://www.linkedin.com/in/atharva2706/)
