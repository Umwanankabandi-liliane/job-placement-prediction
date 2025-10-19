# Job Placement Prediction using ML & DL

This repository contains the final submission for the **Model Training & Evaluation Summative Assignment**.  
The project predicts whether students will be placed (employed) after graduation using **Machine Learning (ML)** and **Deep Learning (DL)** models.



##  Overview
We explore how academic, personal, and employability factors influence job placement outcomes.  
Models were trained on the *Placement_Data_Full_Class.csv* dataset using Scikit-learn and TensorFlow.

**Goal:** Compare traditional ML and DL approaches to find the most accurate and generalizable model.



##  Models Tested
1️⃣ Logistic Regression  
2️⃣ Random Forest (Default)  
3️⃣ Random Forest (Tuned – 300 trees, depth = 8)  
4️⃣ Sequential NN (Default)  
5️⃣ Functional NN (Default)  
6️⃣ Sequential NN (Deeper)  
7️⃣ Functional NN (Higher Dropout)



##  Performance Summary

| **Model** | **Accuracy** | **Precision** | **Recall** | **F1** |
|:--|:--:|:--:|:--:|:--:|
| Logistic Regression | 0.88 | 0.90 | 0.93 | 0.92 |
| Random Forest (Default) | 0.79 | 0.82 | 0.90 | 0.86 |
| Random Forest (Tuned) | 0.79 | 0.80 | 0.93 | 0.86 |
| Sequential NN (Default) | 0.83 | 0.87 | 0.90 | 0.88 |
| Functional NN (Default) | 0.83 | 0.87 | 0.90 | 0.88 |
| Sequential NN (Deeper) | 0.83 | 0.87 | 0.90 | 0.88 |
| **Functional NN (Higher Dropout)** | **0.81** | **0.87** | **0.87** | **0.87** |



Highlights

Logistic Regression achieved the best performance with an accuracy of ≈ 88 %, outperforming more complex models.

Random Forest and Neural Network models showed competitive but slightly lower accuracy (≈ 79–84 %), indicating that simpler models can generalize better on smaller datasets.

ROC analysis confirmed that Logistic Regression had the highest discrimination power between placed and non-placed students.

Regularization and dropout in deep models helped control overfitting, but dataset size limited their full potential.



##  Tech Stack
`Python` • `TensorFlow / Keras` • `Scikit-learn` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn`  
Developed and executed in **Google Colab**.





The Logistic Regression model proved most effective overall, achieving the highest accuracy (≈ 88 %) and strong balance between precision and recall.
This result shows that even simple, interpretable machine-learning models can outperform deeper architectures when data are limited and relationships are mostly linear.
While deep-learning models such as the Functional Neural Network with Dropout showed promising generalization, their full potential would require larger, more diverse datasets.
Overall, the project confirms that AI-driven analytics—whether classical or deep—can provide powerful tools for improving graduate employability forecasting and supporting data-driven job-creation strategies.

**Author:** Liliane Umwanankabandi  
**Institution:** African Leadership University | **Course:** Machine Learning – Model Training & Evaluation  
**Date:** October 2025
