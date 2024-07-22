# Sentiment Analysis with Embeddings

This project implements a sentiment analysis model using sentence embeddings for feature extraction. The model classifies tweets into three sentiment categories: positive, negative, and neutral. It employs a neural network built with PyTorch and uses the SentenceTransformers library to obtain sentence embeddings.

## Overview

This repository provides a comprehensive pipeline for sentiment analysis:

1. **Data Preparation**: Load and preprocess tweet data.
2. **Feature Extraction**: Use SentenceTransformers to convert tweets into embeddings.
3. **Model Training**: Train a neural network to classify sentiments.
4. **Evaluation**: Assess model performance using accuracy metrics.

## Installation

To run this code, you'll need to install the required packages. You can use pip to install the necessary libraries:

```bash
pip install numpy pandas torch sentence-transformers seaborn scikit-learn