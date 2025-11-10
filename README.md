# Deep-Learning-Assignment-2
PyTorch models for legal clause similarity detection using BiLSTM with Attention and CNN multi-scale features. Includes training, evaluation metrics, and visualizations for semantic similarity classification on real-world legal text.
Legal Clause Similarity Detection

This repository implements legal clause similarity detection using PyTorch, featuring two deep learning models:

BiLSTM with Attention

CNN with Multi-Scale Convolutions

The models classify whether two legal clauses are semantically similar.

Features

Preprocessing pipeline for legal text

Custom tokenizer for legal clauses

BiLSTM with attention mechanism

CNN multi-scale model for semantic similarity

Training with early stopping and learning rate scheduling

Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, PR-AUC

Training history and confusion matrix visualization

Installation
git clone <repo-url>
cd <repo-folder>
pip install -r requirements.txt


Requirements:

Python >= 3.8

PyTorch >= 2.0

pandas, numpy, scikit-learn, matplotlib, seaborn

Usage

Place your dataset in the folder ./legal_data/legalclausedataset/

Each CSV represents a clause category

Run the main script:

python main.py


This will train both models, evaluate on a test set, and generate metrics and visualizations.

Evaluation

The models are evaluated using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC & PR-AUC

Sample output is printed, and training history plots are generated.

Example Output
BiLSTM Metrics: {'accuracy': 0.50, 'precision': 0.0, 'recall': 0.0, 'f1_score': 0.0, 'roc_auc': 0.67, 'pr_auc': 0.70}
CNN Metrics: {'accuracy': 0.86, 'precision': 0.86, 'recall': 0.85, 'f1_score': 0.86, 'roc_auc': 0.94, 'pr_auc': 0.94}

License

MIT License © 2025

If you want, I can also write a super compact 1-page version of the README that’s perfect for GitHub repos, keeping it under ~250 words, which looks really clean for viewers.
