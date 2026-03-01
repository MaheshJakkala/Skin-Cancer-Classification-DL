# Skin Cancer Classification using Deep Learning & ML

## Overview
This project presents a comprehensive skin lesion classification system
built on the HAM10000 dataset. Multiple modeling approaches are explored,
including custom CNNs, transfer learning architectures, and traditional
machine learning pipelines.

## Dataset
HAM10000 (Human Against Machine with 10000 training images)

## Models Implemented
- Custom CNN (baseline)
- Custom CNN with class balancing & augmentation
- EfficientNetB0 (transfer learning)
- MobileNetV2 (lightweight model)
- Traditional ML: SVM, Random Forest, KNN, Logistic Regression

## Results (Key Highlight)
- **CNN with augmented balanced data: 97.6% accuracy**
- EfficientNetB0: 81.2% accuracy
- Classical ML models: ~69% accuracy

## Key Learnings
- Severe class imbalance significantly affects medical datasets
- Data augmentation is more impactful than deeper models
- Transfer learning improves generalization but requires careful tuning

## Tech Stack
Python, TensorFlow, Keras, Scikit-learn, OpenCV, Plotly, NumPy, Pandas

## Disclaimer
For educational and research purposes only. Not intended for clinical use.