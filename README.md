# Diabetes Prediction KNN Model

This repository contains a Jupyter Notebook (`Diabetes-Prediction-Model.ipynb`) for building a K-Nearest Neighbors (KNN) model to predict diabetes based on patient data.

## Table of Contents
- Objective
- Data
- Features
- Model
- Benefits
- Getting Started
- Contributing


## Objective
This repository aims to:

- Develop a KNN model to predict diabetes based on patient data.
- Provide a clear and well-structured approach to data exploration, cleaning, preprocessing, model selection, and evaluation using a Jupyter Notebook.
- Serve as a learning resource for anyone interested in KNN for diabetes prediction and machine learning for healthcare applications.


## Data
The project utilizes publicly available product and store data, accessible on Kaggle: <a href="https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database" >Pima Indians Diabetes Database</a>.

The datasets consists of several medical predictor variables and one target variable, `Outcome`. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.



## Features

- **Pregnancies :** Number of times a woman has been pregnant
- **Glucose :** Plasma Glucose concentration of 2 hours in an oral glucose tolerance test
- **BloodPressure :** Diastollic Blood Pressure (mm hg)
- **SkinThickness :** Triceps skin fold thickness(mm)
- **Insulin :** 2 hour serum insulin(mu U/ml)
- **BMI :** Body Mass Index ((weight in kg/height in m)^2)
- **Age :** Age(years)
- **DiabetesPedigreeFunction :** scores likelihood of diabetes based on family history)
- **Outcome :** 0(doesn't have diabetes) or 1 (has diabetes)


## Model

This repository focuses on building and evaluating a KNN model. KNN classifies data points based on their similarity (distance) to labeled data points in the training set. The model considers the "k" nearest neighbors of a new data point (patient) and predicts the class (diabetic or non-diabetic) based on the majority vote of those neighbors.


## Benefits

This diabetes prediction model offers several advantages:

- **Early Detection:** Identify people at high risk for diabetes, enabling earlier intervention.
- **Improved Management:** Help healthcare professionals tailor treatment plans based on risk.
- **Reduced Costs:** Early detection can potentially lower healthcare costs associated with diabetes.
- **Increased Awareness:** Raise awareness about diabetes risk factors and encourage healthier habits.

These models are not meant for sole diagnosis but can be a valuable tool for risk assessment.


## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/amangupta143/Diabetes-Prediction-KNN.git
3. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
5. Run the analysis script:
   ```bash
   jupyter notebook Diabetes-Prediction-Model.ipynb

**Running the Notebook**

- Open a terminal or command prompt and navigate to the directory containing the notebook and the "diabetes.csv" file.
- Start Jupyter Notebook: `jupyter notebook`
- In the Jupyter Notebook interface, open the Diabetes-Prediction-Model.ipynb file.
- Run each code cell (block of code) by pressing `Shift + Enter`. The output of the code will be displayed below the cell.

## Contributing

I welcome contributions to this repository! If you have ideas for improvement, bug fixes, or want to explore different aspects of the model, feel free to create a pull request.


<!--- Animated Line: --->

<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">

Happy coding! 🚀

<!-- Footer Links -->
[![Portfolio](https://img.shields.io/badge/-Portfolio-red?style=flat&logo=appveyor&logoColor=white)](https://github.com/amangupta143)
[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/amangupta143)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amangupta143/)