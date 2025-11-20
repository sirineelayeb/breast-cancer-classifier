# Breast Cancer Classifier

## Dataset
The project uses a breast cancer dataset with features extracted from tumor samples, including measurements like cell size, texture, and smoothness.  

## Description
This project uses a neural network to predict whether breast tumors are **malignant** or **benign** based on features from a dataset.   
It is implemented using **Python**, **TensorFlow/Keras**, and **Pandas**.

- `diagnosis(1=m, 0=b)` → 1 = malignant, 0 = benign

---

## Features
- Fully connected neural network with two hidden layers of 256 neurons each.  
- Sigmoid activation for hidden and output layers (binary classification).  
- Trained using **binary crossentropy loss** and **Adam optimizer**.  

---

## Usage
1. Clone this repository:

```bash
git clone https://github.com/sirineelayeb/breast-cancer-classifier.git

**Dataset download link:**  
[Breast Cancer Dataset (real)](https://drive.google.com/file/d/1y5D6lxSCq7udr8Gq42oXfFAgDsd-cmES/view?usp=sharing)
