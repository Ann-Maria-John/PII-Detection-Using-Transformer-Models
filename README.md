# PII-Detection-Using-Transformer-Models

This repository contains the code and resources for a project focused on identifying Personally Identifiable Information (PII) using advanced transformer models. The project involves data preprocessing, exploratory data analysis (EDA), and training multiple models including DeBERTa and Longformer.

### Goal
The goal of this project is to identify Personally Identifiable Information (PII) within text using Named Entity Recognition (NER) tasks and token classification approaches.

### Data Sources
Original Dataset: Kaggle competition-provided dataset

Generated Data: Mistral, ChatGPT, Gemma

### Models Used
DeBERTa:
Baseline model
Trained with original, Mistral, and ChatGPT data
Trained with original and Gemma data

Longformer:
Optimized for long documents

### Results
DeBERTa + Gemma Data: F-beta score of 0.988

DeBERTa + Mistral + ChatGPT Data: F-beta score of 0.99

Longformer (best configuration): F-beta score of 0.958
