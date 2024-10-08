# BABSHA: Behavioral Analysis of Bangladeshi Shoppers in E-Commerce Arena Using TPB, Machine Learning, and Large Language Models

## Overview
This project explores key factors influencing consumer behavior in the rapidly growing e-commerce sector of Bangladesh. By integrating the **Theory of Planned Behavior (TPB)** with machine learning techniques and **Large Language Models (LLMs)**, we aim to identify the attitudes, social norms, and perceived behavioral control that significantly affect online purchase decisions. 

The dataset used in this study was collected through a survey targeting Bangladeshi consumers, focusing on their online shopping behaviors. This project also includes an **ablation study** to evaluate the impact of various behavioral factors on different predictive models. The results show a 93% accuracy using logistic regression models and an 83% accuracy using advanced LLM frameworks such as **Meta's Llama 3.1**.
  
## Results
- **Best Machine Learning Model:** Logistic Regression achieved an accuracy of **93%** and an F1-score of **0.93**.
- **Best LLM Model:** The Llama 3.1 model using Retrieval-Augmented Generation (RAG) achieved an accuracy of **83%** and an F1-score of **0.90**.
- **Explainable AI:** LIME provided insights into key factors influencing purchasing decisions, improving interpretability.

## Dataset
The dataset consists of survey data from **266 participants**, predominantly university students in Bangladesh, collected from March 2024 to May 2024. It includes the following variables:
- **Attitude** (ATTD)
- **Social Norm** (SN)
- **Perceived Behavioral Control** (PBC)
- **Purchase Behavior** (PB)

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/babsha-ecommerce-analysis.git
   cd babsha-ecommerce-analysis

