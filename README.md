# Multimodal Sentiment Classification System

## Overview

This project is a multimodal sentiment classification system that predicts sentiment from both text and images. It classifies inputs into three categories: positive, negative, and neutral.

The system combines classical machine learning, deep learning, and transformer-based models to improve performance and robustness compared to single-modality approaches.

---

## Problem Statement

Sentiment analysis using only text or only images often fails to capture complete context. This project addresses this limitation by combining both modalities to improve prediction accuracy and stability.

---

## Approach

The system processes text and image inputs separately and then combines their outputs for final prediction.

### Text Modality
- Classical machine learning models such as Logistic Regression or SVM using TF-IDF features
- A fine-tuned BERT model for contextual text understanding

### Image Modality
- A ResNet-based convolutional neural network for feature extraction and classification

### Fusion Strategy
- Late fusion is used to combine predictions from both modalities
- Final output is determined based on combined model predictions

---

## Architecture

Text Input → BERT / Classical ML →  
                                     → Final Prediction  
Image Input → ResNet CNN →

---

## Features

- Multimodal sentiment analysis using text and images
- Combination of classical ML and deep learning approaches
- Fine-tuned BERT for contextual language understanding
- ResNet-based CNN for image classification
- Late fusion strategy for improved robustness
- Outputs sentiment as positive, negative, or neutral

---

## Tech Stack

- Python
- PyTorch / TensorFlow
- Hugging Face Transformers (BERT)
- Scikit-learn
- OpenCV / PIL
- ResNet CNN


## Project Structure
