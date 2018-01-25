# Bankruptcy Challenge: predicting which firm is going to go bankrupt

This repository presents the final notebook Ludovic and I used to make our predictions for the data challenge of the class Bankruptcy Challenge, as a part of our scolarity in Option DAD at École Centrale de Lille.
The idea of the challenge was to predict which firm will bankrupt in the next year. We were given a dataset with several accounting features for each firm, taken out of the ledger of the firms. Training data was dated from 2011 and 2012, while testing data was only from 2012.
Our (winning) algorithm used dimensionnality reduction through a well-chosen PCA, subsampling of 2011 data to get a balance between data from 2011 and from 2012, and an ensemble of different XGboost classifiers.
We do not include all the data exploration and intermediary steps that we made in this repository, only the final solution. The data are private. Our team finished first out of 12 teams on the private LeaderBoard.

## Model description

![alt text](https://raw.githubusercontent.com/MaxWab/projectname/branch/path/to/img.png)


## Getting Started

You can just run the notebook once you have installed the different python modules (see below for a list of modules to install). Note that we do not provide the data.

### Prerequisites

You should install the following modules, for instance through pip:

```
pip install --upgrade numpy pandas scipy matplotlib fancyimpute DataManipulation sklearn
```

Note that we also used XGBoost (instructions to download and install can be found here: https://xgboost.readthedocs.io/en/latest/build.html)

## Built With

* Python
* Jupyter Notebook

## Authors

* **Ludovic Darmet** - *Data exploration + algorithm* - https://github.com/ludovicdmt
* **Maxime Wabartha** - *Data exploration + algorithm*


## Acknowledgments

* Option DAD, École Centrale de Lille: http://pierrechainais.ec-lille.fr/Centrale/Option_DAD/Accueil.html