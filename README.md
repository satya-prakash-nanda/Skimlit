# SkimLit NLP Project 📄🔥

This project is an NLP-driven effort to classify sentences within medical research abstracts, allowing users to "skim" literature quickly. Inspired by the 2017 [PubMed 200k RCT dataset](https://arxiv.org/abs/1710.06071), the model classifies each sentence of a Randomized Controlled Trial (RCT) abstract by its role (e.g., Objective, Methods, Results, etc.). The project is inspired by Daniel Bourke's NLP course on TensorFlow and deep learning.

![Model Input-Output](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/images/09-skimlit-overview-input-and-output.png)

## ✨ Overview

**Goal:** Build an NLP model to classify sentences in abstracts to assist researchers in quickly understanding medical papers without reading through extensive text.

- **Dataset**: [PubMed 200k RCT dataset](https://github.com/Franck-Dernoncourt/pubmed-rct), featuring 200,000 abstracts for RCTs.
- **Model Input**: Raw abstract text, tokenized for preprocessing.
- **Model Output**: Sentence-level classification of sections like Objective, Methods, and Results.

---

## 📋 Table of Contents

1. [Project Setup](#project-setup)
2. [Dataset Preparation](#dataset-preparation)
3. [Modeling Pipeline](#modeling-pipeline)
4. [Results](#results)
5. [Future Work](#future-work)

---

## 🛠️ Project Setup

### Dependencies

Install the required libraries:

```bash
pip install tensorflow pandas numpy
```


## 📂 Dataset Preparation
Download Data: Clone the dataset using:

```bash
git clone https://github.com/Franck-Dernoncourt/pubmed-rct.git
```

Data Inspection: Use the PubMed_20k_RCT_numbers_replaced_with_at_sign subset, which has numbers replaced with @ for consistency across samples.



