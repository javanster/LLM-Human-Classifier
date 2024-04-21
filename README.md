## Identification of LLM-generated and human-written texts

TDT4310 project, NTNU, Spring 2024
Max Gunhamn & Jarl Sterkenburg

---

This repository contains code for training machine learning models to perform binary text classification, where the target classes are LLM-generated and human-written.

#### The code is structured in Jupyter notebooks:
- [Data exploration](/data_exploration.ipynb)
- [Data preprocessing](/preprocessing.ipynb)
- [Model training and testing](/models/)

#### Data and trained AutoGluon model

As the data files and the trained AutoGlon model files are too large for this repository, they can be dowloaded from here:

https://drive.google.com/drive/folders/1fX7FYr5DdERnd18agrT4UmVpczD0lGfz?usp=sharing

Create a new folder in the root folder named *data*, and place the downloaded data files inside of it. The downloaded *AutogluonModels* folder must be placed inside the *[models folder](/models/)*. 

#### Data sources:

- DAIGT-V4-TRAIN-DATASET: https://www.kaggle.com/datasets/thedrcat/daigt-v4-train-dataset (retrieved April 5, 2024).
- LLM - Detect AI Datamix: https://www.kaggle.com/datasets/conjuring92/ai-mix-v26?rvi=1   (retrieved April 5, 2024).


