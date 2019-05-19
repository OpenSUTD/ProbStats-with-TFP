# Prob&Stats with TensorFlow Probability

![GitHub contributors](https://img.shields.io/github/contributors/OpenSUTD/ProbStats-with-TFP.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/OpenSUTD/ProbStats-with-TFP.svg) ![GitHub](https://img.shields.io/github/license/OpenSUTD/ProbStats-with-TFP.svg)

This project is conceptualised to supplement ISTD [50.034 (Introduction to Probability and Statistics)](https://istd.sutd.edu.sg/undergraduate/courses/50034-introduction-to-probability-and-statistics) with some nice visualisations and code things to play with. It does not, and is not intended to, cover all the subject areas of 50.034.

This repository contains [**Jupyter Notebooks**](https://jupyter.org/) that are designed to run on [**Google Colaboratory**](https://colab.research.google.com/), a free Jupyter environment that runs in the cloud. This means that there's nothing to install on your computer!

Most of the code here will utilise the [**TensorFlow Probability**](https://www.tensorflow.org/probability) library. If you're viewing the Notebook on Colab, there's nothing you have to worry about! Everything you need is already configured.

## Contents

| S/N | Notebook Title                       | Link |
| --- | ------------------------------------ | ---- |
| 01  | Introduction and Normal Distribution | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OpenSUTD/ProbStats-with-TFP/blob/master/01_Intro_Normal_Distributions.ipynb)  |
| 02  | Special Distributions                | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OpenSUTD/ProbStats-with-TFP/blob/master/02_Special_Distributions.ipynb)|
| 03  | Bayesian Approach to Coin-flip       | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OpenSUTD/ProbStats-with-TFP/blob/master/03_Bayesian_Coin_Flip.ipynb)|
| 04  | WIP                                  | WIP|

**Local Install**

If you want to run the notebooks locally (not recommended if you don't already have a TensorFlow environment set up):

```bash
git clone https://github.com/OpenSUTD/ProbStats-with-TFP
cd ProbStats-with-TFP

# install dependencies
pip install tensorflow
pip install -r requirements.txt

# run Jupyter Notebook (or JupyterLab)
jupyter notebook
```

## Contributing

Any relevant contributions are welcome! Feel free to open a pull request. 

**Simple Requirements**

1. Only use "common" libraries
2. Design to run on Google Colaboratory
3. Make an effort to keep code simple and understandable

**Core Maintainer**

Timothy Liu / [@tlkh](https://github.com/tlkh)
