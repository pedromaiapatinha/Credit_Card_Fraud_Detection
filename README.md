# Credit Card Fraud Dectection with Machine Learning

## Table of Content
  * [Overview](#Overview)
  * [Business Understanding](#Business-Understanding)
  * [The Challenge](#The-Challenge)
  * [Installation](#Installation)
  * [Directory Tree](#Directory-Tree)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)
  * [Acknowledgements](#Acknowledgements)

## Overview
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Business Understanding
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## The Challenge
Identify fraudulent credit card transactions with a higly class imbalance ratio.

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── Credit Card Fraud Detection.ipynb
└── README.md
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://camo.githubusercontent.com/e5efd9b8f2106722c85415f104a352232a3a9437d765778aca491a2c2a7d5d6c/68747470733a2f2f6465762e70616e6461732e696f2f7374617469632f696d672f70616e6461732e737667" width=200>](https://pandas.pydata.org/) [<img target="_blank" src="https://numpy.org/images/logos/numpy.svg" width=100>](https://numpy.org/) [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=240>](https://seaborn.pydata.org/) [<img target="_blank" src="https://matplotlib.org/_static/logo2_compressed.svg" width=275>](https://matplotlib.org/) 


## Team
<img src="https://img.icons8.com/color/30/000000/linkedin.png"/> [Pedro Patinha](https://www.linkedin.com/in/pedromaiapatinha/)

## Credits
Thanks to kaggle and Machine Learning Group - ULB for making this challenge and dataset available for Machine Learning enthusiasts,
https://www.kaggle.com/mlg-ulb/creditcardfraud
