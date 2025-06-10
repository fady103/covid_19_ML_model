# COVID-19 Chest X-ray Classification using CNN

This project implements a convolutional neural network (CNN) to classify chest X-ray images into two categories: **COVID-19** and **Normal**. It aims to provide a simple and effective deep learning pipeline for automated medical image diagnosis.

## 📌 Project Overview

As the world faced the COVID-19 pandemic, early and accurate detection became crucial. This model was built to explore the potential of deep learning in classifying X-ray images for COVID-19 diagnosis.

The notebook contains all steps, including:
- Data preprocessing
- Data augmentation
- CNN model construction
- Training and validation
- Model evaluation

## 🧠 Model Architecture

The model is built using TensorFlow and Keras. It consists of:
- Convolutional layers (`Conv2D`)
- Pooling layers (`MaxPooling2D`)
- Dense layers with `ReLU` activation
- Dropout regularization
- Binary classification output with sigmoid activation

## 📂 Dataset Structure

The dataset is organized in two folders:

dataset/
├── Covid/
└── Normal/

Each folder contains X-ray images labeled accordingly.

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/fady103/covid_19_ML_model.git
cd covid_19_ML_model
```
2. download Dataset
Due to the large size of the dataset, it is not included in this repository.
You can download it manually from Kaggle using the following link: 
```bash
https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
```
Once downloaded, extract only the following two folders and place them in the project folder named covid_19_ML_model/:
```bash
covid_19_ML_model/
├── COVID/
└── Normal/
```
These folders contain chest X-ray images labeled as COVID-19 positive and Normal cases, which are the only two classes used in this project.


2. install requirements
```bash
pip install -r requirements.txt
```
3. Launch the notebook
```bash
jupyter notebook covid2.ipynb
```
