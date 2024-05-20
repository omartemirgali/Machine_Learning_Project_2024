# Machine Learning Project - BIPxTech and Teamsystem  
## EXEMPTION CODE MAPPER
This project is done by LUISS University students studying in Data Science and Management taking Machine Learning course given by Guiseppe Italiano, Fabio Angeletti and Davide Torre.  
Students' names worked on the project: Omar Temirgali, Ayazhan Allayarova and Dmitrii Treschev.  

## Introduction 
The goal of this project is to develop a model capable of predicting the exemption VAT code (found in the dataset column "IvaM") for each invoice line. This prediction will be made using information from various other fields within the invoice line. The work done here is trying two approaches. First is removing the null values and testing the models, second is replacing the null values with the frequent categorical variables. 

## Installation
To successfully build and evaluate the model that predicts the exemption VAT code, you will need to install several Python libraries. Below is a list of the required libraries and instructions on how to install them:

Required Libraries
* scikit-learn: A powerful library for machine learning in Python.
* pandas: Essential for data manipulation and analysis.
* numpy: Provides support for large, multi-dimensional arrays and matrices.
* matplotlib: Used for creating static, animated, and interactive visualizations.
* seaborn: A library for making statistical graphics.

### Installation Instructions
You can install these libraries using pip. Open your terminal or command prompt and run the following commands:

```bash
pip install scikit-learn pandas numpy matplotlib seaborn
```

### Additional Libraries
Jupyter Notebook: While not strictly necessary, it is highly recommended for interactive development and testing. Install it using:
```bash
pip install notebook
```

By following these steps, you will set up the necessary environment to develop and evaluate your model for predicting the exemption VAT code based on invoice line attributes.

## Usage
To use the model refer to these lines of code which shows best results among the other models. Also all lines of codes were commented appropriately if there are any issues please contact us (See Contacts section below). 

```bash
#defining RadnomForest model and fitting in train dataset
model_rf = RandomForestClassifier(n_estimators=100, random_state=42)
model_rf.fit(X_train, y_train)
```

```bash
#defining RadnomForest model and fitting in train dataset
rf = RandomForestClassifier(n_estimators=100)
rf.fit(X_train, y_train)
```

## Acknowledgement
We want to say thanks to the company for challenging us with interesting task with collaboration of teaching staff.

## Contacts
* omar.temirgali@studenti.luiss.it
* ayazhan.allayarova@studenti.luiss.it
* d.treschev@studenti.luiss.it 
