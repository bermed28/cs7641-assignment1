# CS 7641 - Assignment 1: Supervised Learning 

This repository contains the experiments made to analyze and complete assignment 1 of the CS7641 - Machine Learning course from the Georgia Institute of Technology.

The main purpose of this assignment is to analyze 5 supervised learning algorithms:
* Decision Trees
* Neural Networks
* K-Nearest Neighbors
* Boosting (using Decision Trees)
* Support Vector Machines

with 2 datasets using Scikit-learn and compare/contrast their performance.

----

### Setup Virtual Environment

In the root directory of the project, do one of the following two

#### Conda

```shell
$ conda create --name myenv python=3.8
$ conda activate myenv
$ pip install -r requirements.txt
```

#### PipEnv

```shell
$ python -m venv /venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

### Run Script

Open up `Main.ipynb` in VS Code (or your preferred editor/jupyter server), select your virtual environment (in this example `myenv`) as your kernel and run the code cells one by one. Note that final classifier results may vary from report numbers depending on computer specs.

----

## Note: If you are a GT Student taking CS7641 **_DO NOT_** proceed looking at this repository in order to not violate the GT Academic Honor Code