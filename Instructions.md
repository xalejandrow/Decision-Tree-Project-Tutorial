Decision Tree Project Tutorial
Edit on Github

    The goal of this project is to classify patients having diabetes or no, based on their diagnostics.
    Make some basic exploratory analysis and prepare the data for modeling.
    Use decision trees and hypertune your model. This folder has a solution guide in case you get stuck.
    Don't forget that you are creating software, so build pipelines in the app.py

🌱 How to start this project

You will not be forking this time, please take some time to read this instructions:

    Create a new repository based on machine learning project by clicking here.
    Open the recently created repostiroy on Gitpod by using the Gitpod button extension.
    Once Gitpod VSCode has finished opening you start your project following the Instructions below.

🚛 How to deliver this project

Once you are finished creating your decision tree model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.
📝 Instructions

Predicting Diabetes:

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

Data Dictionary:

    Pregnancies: Number of times pregnant

    Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test

    BloodPressure: Diastolic blood pressure (mm Hg)

    SkinThickness: Triceps skin fold thickness (mm)

    Insulin: 2-Hour serum insulin (mu U/ml)

    BMI: Body mass index (weight in kg/(height in m)^2)

    DiabetesPedigreeFunction: Diabetes pedigree function

    Age: Age (years)

    Outcome: Class variable (0 or 1), Class Distribution: (class value 1 is interpreted as "tested positive for diabetes")

Source:

(a) Original owners: National Institute of Diabetes and Digestive and Kidney Diseases (b) Donor of database: Vincent Sigillito (vgs@aplcen.apl.jhu.edu) Research Center, RMI Group Leader Applied Physics Laboratory The Johns Hopkins University

Step 1:

Go to the following online dataset (https://raw.githubusercontent.com/4GeeksAcademy/decision-tree-project-tutorial/main/diabetes.csv) and download the data. Save it yor in your project's 'data/raw' folder. Time to work on it!

Step 2:

Use the explore.ipynb notebook to find patterns and valuable information that will help on your cleaning process.

Don't forget to write your observations.

Use the app.py to create your cleaning pipeline. Save your clean data in the 'data/processed' folder.

Step 3:

Now that you have a better knowledge of the data, in your exploratory notebook create a first decision tree model with your clean data.

Step 4:

Change your decision tree to use 'entropy' as criterion.

Step 5:

Hypertune your model using GridSearch to find the best hyperparameters.

Train your model with the optimal hyperparameters.

Again use the app.py to create your final machine learning model.

Save your final model in the 'models' folder.

In your README file write a brief summary of your cleaning and modeling process.
