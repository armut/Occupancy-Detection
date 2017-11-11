# Occupancy Detection

The aim of this project is to detect human presence in the room using real world IoT data.

Using the provided data, supervised machine learning classification algorithms have been trained on training data set and tested against two test sets. The first test set consists of the data that has been collected mostly the door closed. Contrarily, the other one has been collected mostly the door open.

The original paper is [“Accurate occupancy detection of an office room from light, temperature, humidity and
CO2 measurements using statistical learning models”](http://www.sciencedirect.com/science/article/pii/S0378778815304357) from Luis M. Candanedo and Véronique Feldheim.

You can read the final report in the `report` folder or donwload the jupyter notebook and run it yourself. You can find the python requirements in `requirements.pip` and if using pip, you can get them in one command passing the requirements file as a parameter like this:

```
pip install -r requirements.pip
```

The algorithms trained and tested on this project are,

* Logistic Regression
* Naïve Bayes
* K-Nearest Neighbors
* Decision Tree
* Random Forest
* Gradient Boosting Machine
* Kernelized Support Vector Machine

For every algorithm, a table has been presented with several parameters and different feature combinations. At the end, there is a table that shows every algorithm with their best parameters and feature combinations alongside their scores for this project.


