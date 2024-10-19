# Linear-regression-Co2-Emission-prediction

This project and dataset is related to the Co2 emission of different cars. The dataset includes Engine size, Cylinders, Fuel Consumption
and Co2 emissions for various car models. The project is to predict the Co2 emission of a car given this dataset, using another field, such as Engine size?

Quite simply, yes! We can use linear regression to predict a
continuous value such as Co2 Emission, by using other variables.
Linear regression is the approximation of a linear model used to describe the relationship between two or more variables. In simple linear regression, there are two variables: a dependent variable and an independent variable.

The key point in the linear regression is that our dependent value should be continuous and cannot be a discreet value. However, the independent variable(s) can be measured on either a categorical or continuous measurement scale.

There are two types of linear regression models. They are: simple regression and multiple regression.

Simple linear regression is when one independent variable is used to estimate
a dependent variable. For example, predicting Co2 emission using
the EngineSize variable. When more than one independent variable is
present, the process is called multiple linear regression.For example, predicting Co2 emission using EngineSize and Cylinders of cars.

However, the focus here is on simple linear regression.
Now, let’s see how linear regression works. 
Looking at the dataset again to understand linear regression, we can plot our variables. We show Engine size as an independent variable, and Emission as the target value that we would like to predict. A scatterplot clearly shows the relation between variables where changes in one variable "explain" or possibly "cause" changes in the other variable.

Also, it indicates that these variables are linearly related.
With linear regression you can fit a line through the data.
For instance, as the EngineSize increases, so do the emissions.
With linear regression, you can model the relationship of these variables.
A good model can be used to predict what the approximate emission of each car is.
------------------------------------------------------------------------------------------------------------------------------------------------
## Understanding the Data

### `FuelConsumption.csv`:

We have downloaded a fuel consumption dataset, **`FuelConsumption.csv`**, which contains model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles for retail sale in Canada. [Dataset source](http://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)

- **MODELYEAR** e.g. 2014
- **MAKE** e.g. Acura
- **MODEL** e.g. ILX
- **VEHICLE CLASS** e.g. SUV
- **ENGINE SIZE** e.g. 4.7
- **CYLINDERS** e.g 6
- **TRANSMISSION** e.g. A6
- **FUEL CONSUMPTION in CITY(L/100 km)** e.g. 9.9
- **FUEL CONSUMPTION in HWY (L/100 km)** e.g. 8.9
- **FUEL CONSUMPTION COMB (L/100 km)** e.g. 9.2
- **CO2 EMISSIONS (g/km)** e.g. 182   --> low --> 0
----------------------------------------------------------------------------------------------------------------------------
**Objectives**

The Objective of this project are to:

- Use scikit-learn to implement simple Linear Regression
- Create a model, train it, test it and use the model
------------------------------------------------------------------------------------------------------------------------------------------------
**Requirements**
- scikit-learn
- matplotlib
- import
- pylab
- numpy
------------------------------------------------------------------------------------------------------------------------------------------------
