# CNN image classification & sentiment analysis

## Author

Milena Morawska

GitHub: https://github.com/MilenaMorawska

---

## Overview

This project covers two tasks: image classification using a custom convolutional neural network (CNN) trained from scratch, and sentiment analysis using pretrained transformer models. It provides tools for training and evaluating an image classifier across 10 categories, and for comparing baseline, zero-shot, and few-shot approaches to sentiment classification.

---

## Features

Task 1:
- Custom CNN built from scratch for 10-class image classification (no pretrained weights)
- Data augmentation pipeline 
- Regularisation techniques including SpatialDropout2D, standard Dropout, batch normalisation, and L2 regularisation
- Training callbacks (EarlyStopping, ModelCheckpoint) for efficient, overfitting-resistant training
- Full evaluation suite: accuracy, precision, recall, F1-score, macro F1-score, and confusion matrices

Task 2:
- Three-class sentiment analysis (negative / neutral / positive) using:
  - A fine-tuned baseline transformer (nlptown/bert-base-multilingual-uncased-sentiment)
  - Zero-shot classification (MoritzLaurer/DeBERTa-v3-base-mnli-fever-anli)
  - Few-shot prompting (google/flan-t5-large)
- Full evaluation suite: accuracy, precision, recall, F1-score, macro F1-score, and confusion matrices


Full evaluation suite: accuracy, precision, recall, F1-score, macro F1-score, and confusion matrices
Error handling for missing datasets and invalid inputs

## Data

The image dataset used for Task 1 is provided by the COP528 module (Loughborough University)
and is not included in this repository due to file size and licensing restrictions.
