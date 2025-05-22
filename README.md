# EEE486---Statistical-Foundations-of-Natural-Language-Processing
Bilkent EEE486 Spring 2025
# EEE486/586 - Statistical Foundations of Natural Language Processing

This repository contains the implementations, reports, and related files for the homework assignments in the course **EEE486- Statistical Foundations of Natural Language Processing** at Bilkent University.

## Contents

- Assignment 1 - The Hunt for Collocations
- Assignment 2 - Fine-tuning BERT for Text Classification
- Assignment 3 - Transformer Architecture for Dialogue Summarization

---

## Assignment 1: The Hunt for Collocations

Identify collocations from a given Jane Austen corpus using three statistical hypothesis testing methods:
- Student’s t-test
- Chi-square test
- Likelihood ratio test

**Tools Used:**
- Python (with nltk)
- POS tagging and lemmatization
- Manual statistical computations 

**Procedure:**
- POS-tagged and lemmatized the corpus.
- Extracted noun-noun and adjective-noun bigrams.
- Filtered stopwords and low-frequency pairs.
- Computed test scores and sorted top candidates.
- Evaluated and discussed results for specific bigrams 

---

## Assignment 2: Fine-tuning BERT for Text Classification

Fine-tune a BERT model on the **RTE** dataset from GLUE Benchmark for a textual entailment task.

**Tools Used:**
- HuggingFace transformers
- Optuna for hyperparameter tuning
- PyTorch

**Tasks:**
- Used `BertForSequenceClassification` with [CLS] token for Part 1.
- Experimented with:
  - Learning rate
  - Number of epochs
  - Input sequence length
  - Dropout rate
- Pushed the best model to HuggingFace Hub.
- Part 2 involved implementing and evaluating a custom classification strategy different from the [CLS]-based method.

**Evaluation:**
- Accuracy and loss metrics
- Visual plots for comparison
- Discussion of hyperparameter impacts

---

## Assignment 3: Transformer for Dialogue Summarization

**Objective:**  
Build a transformer model **from scratch** (including attention mechanisms) for summarizing dialogues using the **DialogSum** dataset.

**Tools Used:**
- Python + NumPy + TensorFlow
- Custom implementation of:
  - Scaled dot-product attention
  - Multi-head attention
  - Encoder and Decoder blocks
  - Full Transformer architecture

**Structure:**
- Part A: Theory, implementation, and unit testing of all components.
- Part B: Model training, loss visualization, sample outputs, and BERTScore evaluation.

**Evaluation:**
- Performance on sample summaries from training and test sets.



