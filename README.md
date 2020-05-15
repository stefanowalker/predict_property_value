# Property Value Predicting
# Previsão de preços de Imóveis

This is a Data App used to display the Machine Learning solution for the Boston property value prediction problem.

The Boston database have is composed by the variables:
- CRIM: Crime rate per capita by city.
- ZN: Proportion of residential land divided by lots over 25,000 square feet.
- INDUS: This is the proportion of hectares of non-commercial businesses per city.
- CHAS: Charles River fictitious variable (= 1 if the section limits the river; 0 otherwise)
- NOX: concentration of nitric oxide (parts per 10 million)
- RM: Average number of rooms between houses in the neighborhood
- AGE: proportion of owner-occupied units built before 1940
- DIS: weighted distances to five job centers in Boston
- RAD: Index of accessibility to radial highways
- TAX: $ 10,000 total property tax rate
- B: 1000 (Bk - 0.63) ², where Bk is the proportion of people of African American descent by city
- PTRATIO: Neighborhoods with a higher proportion of students to teachers (higher value of 'PTRATIO')
- LSTAT: lowest percentage of population status
- MEDV: average value of owner-occupied houses at $ 1000

# Model Building 
Just follow the steps of the code built through Google Colab: testes_models_colab.ipynb.
- First, the base data was explored.
- After data processing.
- Choice of variables that are important to the model.
- Construction of ML models (regression, decision tree, Random Forest).
- The best model was the Radom Forest, which had the lowest mean square error.

At the end, a file (data.csv) was generated with the treated base.
This file is used like input for the application. 

# Application
Built in python 3.7.
Is used the library [streamlit] for making the application.
Besides [Pandas], [Plotly] e [Sklearn].

Run:
```sh
$ streamlit run app.py
```

# Screens

Screen1:
![app1](https://user-images.githubusercontent.com/11994641/82099185-0ee44080-96dd-11ea-9eae-cad7347cf579.jpg)

Screen2:
![app2](https://user-images.githubusercontent.com/11994641/82099203-20c5e380-96dd-11ea-8d87-426a6f93fddc.jpg)



# TODO 
- Revision in features selection step.
- Model Tunning

# CREDITIS
- This application was built through a set of lessons from the week of data science made by the team of [Minerando Dados].
Gratitude to them!


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[streamlit]: <https://www.streamlit.io/>
[pandas]:<https://pandas.pydata.org/>
[plotly]:<plotly.com>
[sklearn]:<https://scikit-learn.org/stable/>
[Minerando Dados]:<https://minerandodados.com.br/>
 
