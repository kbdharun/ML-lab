# ML-lab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kbdharun/ML-Lab)
[![CodeFactor](https://www.codefactor.io/repository/github/kbdharun/ml-lab/badge)](https://www.codefactor.io/repository/github/kbdharun/ml-lab)

This repository contains the programs that I worked out in Machine Learning Laboratory.

## Index

- Lab 1: Introduction to EDA
  - [Introduction to Matplotlib and Seaborn packages](https://github.com/kbdharun/ML-Lab/blob/main/Lab1/EDA_Matplotlib_&_Seaborn.ipynb)
  - [Introduction to Numpy and Pandas package](https://github.com/kbdharun/ML-Lab/blob/main/Lab1/Numpy_&_Pandas.ipynb)
  - [Insurance Data Analysis](https://github.com/kbdharun/ML-Lab/blob/main/Lab1/ML_Lab1_Insurance.ipynb)
  - [Iris Data Analysis](https://github.com/kbdharun/ML-Lab/blob/main/Lab1/ML_Lab1_Iris.ipynb)
- Lab 2: Principal Component Analysis
  - [About PCA](https://github.com/kbdharun/ML-Lab/blob/main/Lab2/README.md)
  - [PCA based dimensionality reduction on Wine dataset](https://github.com/kbdharun/ML-Lab/blob/main/Lab2/PCA-DR-Wine.ipynb)
  - [PCA using algorithm steps without `sklearn`](https://github.com/kbdharun/ML-Lab/blob/main/Lab2/PCA-using-alg-without-sk.ipynb)
  - [PCA using `sklearn` on Iris dataset](https://github.com/kbdharun/ML-Lab/blob/main/Lab2/PCA-using-sklearn-Iris.ipynb)
  - [PCA - Wine Quality Classification](https://github.com/kbdharun/ML-Lab/blob/main/Lab2/PCA-Wine-quality-classification.ipynb)
- Lab 3: K-Nearest Neighbors
  - [About KNN](https://github.com/kbdharun/ML-Lab/blob/main/Lab3/README.md)
  - [KNN using Iris dataset](https://github.com/kbdharun/ML-Lab/blob/main/Lab3/KNN-using-Iris.ipynb)
- Lab 4: Linear Discriminant Analysis and Linear Regression
  - [About LDA and LR](https://github.com/kbdharun/ML-Lab/blob/main/Lab4/README.md)
  - [LDA on Iris dataset](https://github.com/kbdharun/ML-Lab/blob/main/Lab4/LDA.ipynb)
  - [LR on Single Dataset (Iris)](https://github.com/kbdharun/ML-Lab/blob/main/Lab4/LR-on-single-dataset.ipynb)
  - [LR on Multiple Datasets (Iris, Wine)](https://github.com/kbdharun/ML-Lab/blob/main/Lab4/LR-on-multiple-datasets.ipynb)

---

## Prerequisites

Python and packages in `requirements.txt` file installed.

> [!NOTE]
> You can install all the packages in the file using the command `pip install -r requirements.txt`.

### Container Image

Alternatively, you can use the [container image](https://github.com/kbdharun/ML-Lab/pkgs/container/ml-lab-image) I created with all the packages preinstalled.

You can install it in [Distrobox](https://github.com/89luca89/distrobox) with the command `distrobox create -i ghcr.io/kbdharun/ml-lab-image:latest -n ml` and use it with the command `distrobox enter ml`.

Additionally, you can verify the authenticity of the container image using [`cosign`](https://github.com/sigstore/cosign) (download the `cosign.pub` file from [here](https://github.com/kbdharun/ML-Lab/blob/main/cosign.pub) and execute the following command):

```zsh
cosign verify --key cosign.pub ghcr.io/kbdharun/ml-lab-image:latest
```
