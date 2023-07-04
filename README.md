# Sentence Embeddings for Question Similarity

## Project Description

The goal of this project is to build a Quora question similarity classifier that detects duplicate questions. The purpose is to enhance the user experience on Quora by providing better question suggestions, incorporating functionalities such as grammar check and question auto-complete. 

The project utilizes various machine learning algorithms, including random forests, logistic regression, support vector machines (SVM), as well as deep learning architectures such as Sentence BERT and LSTM. By calculating similarity scores using these algorithms, the question similarity classifier aims to improve the accuracy of identifying duplicate questions.

## Motivation

The motivation behind this project is to enhance the user experience on Quora. Duplicate questions are a common occurrence, and detecting them accurately can help in reducing redundancy and providing more relevant and diverse content to users. By implementing a question similarity classifier, Quora can offer better suggestions, reduce repetitive questions, and enhance the overall quality of the platform.

## Dataset

The project utilizes the Quora Question Pairs dataset, which can be accessed at the following link: [Quora Question Pairs Dataset](https://www.kaggle.com/competitions/quora-question-pairs/data). This dataset consists of question pairs, with labels indicating whether the questions are duplicate or not. It serves as the primary resource for training and evaluating the question similarity classifier.

## Model Performance

The following table presents the performance of different models in terms of accuracy:

| Model              | Accuracy |
| ------------------ | -------- |
| Logistic Regression| 74.9%    |
| SVM                | 72.45%   |
| Random Forest      | 76%      |
| LSTM               | 80%      |
| Sentence BERT      | 85%      |


## Getting Started

To get started with the project, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/your-username/sentence-embeddings-question-similarity.git

```

2. Download the Quora Question Pairs dataset from the provided [link](https://www.kaggle.com/competitions/quora-question-pairs/data) and place it in the `data/` directory.

3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the data analysis, model training, and evaluation processes.

4. Use the provided source code and utility scripts in the `src/` directory to build and customize your own question similarity classifier.
