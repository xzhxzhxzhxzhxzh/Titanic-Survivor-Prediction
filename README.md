# Titanic-Survivor-Prediction
Kaggle competition: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

This is a famous competition on Kaggle. The propose of this competition is to create a model to predict which passengers survived the Titanic shipwreck, where **feature engineering** is the most important and challenge part. This project was completed with **[scikit-learn](https://scikit-learn.org/stable/)** and the model reached **80%** accuracy in the test data.

## Dataset Introduction
On April 15, 1912, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. Translated 32% survival rate. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class. The goal is to predict the survival of 418 passengers using the information from other 891 passengers.

The feature description is shown here.
* Name: Name of the passenger
* Pclass: Ticket class
* Sex: Sex of the passenger
* Age: Age in years
* SibSp: Number of siblings and spouses aboard
* Parch: Number of parents and children aboard
* Ticket: Ticket number
* Fare: Passenger fare
* Cabin: Cabin number
* Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## File Description
* `data` : The default folder to save downloaded datasets.
* `data_preparation` : The folder consists of Python files to acquire data and generate transformed dataset.
* `logs` : The default folder to save logs.
* `models` : The folder consists of different models. 
* `outputs` : The default folder to save trained models.
* `training_and_testing` : The folder consists of Python files to define a training/testing process.
* `utilities` : The folder consists of tools to generate logs, to visualize training results etc.

&emsp;
* `main.py` : Specify which datasets you want to learn, then you can start training.
* `cifar10.ipynb` : A IPython Notebook to train models on CIFAR10.
* `mnist.ipynb` : A IPython Notebook to train models on MNIST.

## Result evaluation
