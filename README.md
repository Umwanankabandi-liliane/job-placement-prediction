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
| Logistic Regression | 0.81 | 0.79 | 0.82 | 0.80 |
| Random Forest (Default) | 0.86 | 0.85 | 0.87 | 0.86 |
| Random Forest (Tuned) | 0.88 | 0.86 | 0.89 | 0.87 |
| Sequential NN (Default) | 0.86 | 0.84 | 0.86 | 0.85 |
| Functional NN (Default) | 0.89 | 0.87 | 0.89 | 0.88 |
| Sequential NN (Deeper) | 0.88 | 0.85 | 0.88 | 0.86 |
| **Functional NN (Higher Dropout)** | **0.90** | **0.88** | **0.90** | **0.89** |



##  Highlights
- Functional Neural Network (Higher Dropout) achieved the best results with **90 % accuracy**.  
- ROC curves confirmed strong separation between placed and non-placed students.  
- Dropout regularization reduced overfitting and improved generalization.



##  Tech Stack
`Python` • `TensorFlow / Keras` • `Scikit-learn` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn`  
Developed and executed in **Google Colab**.



##  Links
-  [Open in Colab](https://colab.research.google.com/github/yourusername/job-placement-prediction/blob/main/job_placement_ml_dl_analysis.ipynb)  
-  [GitHub Repo](https://github.com/yourusername/job-placement-prediction)  
-  [Demo Video](https://youtu.be/your-demo-link)



##  Conclusion
The **Functional Neural Network with Higher Dropout** proved most effective, balancing precision and recall for predicting employability outcomes.  
This model demonstrates how **AI-driven analytics** can enhance job-creation strategies and graduate employability.



**Author:** Liliane Umwanankabandi  
**Institution:** African Leadership University | **Course:** Machine Learning – Model Training & Evaluation  
**Date:** October 2025
