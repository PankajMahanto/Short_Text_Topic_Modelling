# Enhanced Topic Modeling for Short Text Using Embeddings

## Overview
This project focuses on **topic modeling** for short texts using advanced embedding techniques. Traditional topic modeling methods often struggle with short texts due to the lack of word co-occurrence information. To address this, we leverage embeddings to enhance topic coherence and ensure better representation of text data.

## Features
- Utilizes **word embeddings** (e.g., Word2Vec, GloVe, or BERT) to capture semantic meaning.
- Implements **dimensionality reduction** techniques like PCA or t-SNE to cluster embeddings effectively.
- Employs **clustering algorithms** (e.g., K-Means, DBSCAN) to generate topics.
- Provides an enhanced evaluation framework for assessing topic coherence and diversity.

## Motivation
Short text data is prevalent in various fields, such as social media, news headlines, and customer reviews. Traditional approaches like **Latent Dirichlet Allocation (LDA)** fail to perform effectively due to data sparsity. This project aims to overcome these limitations by incorporating embedding-based representations.

## Requirements
To run the project, you need the following Python libraries:

- `numpy`
- `pandas`
- `sklearn`
- `gensim`
- `nltk`
- `spacy`
- `matplotlib`
- `seaborn`
- `transformers` (for contextual embeddings like BERT)

Install the dependencies using:

```bash
pip install -r requirements.txt

## Image file

![demo](https://github.com/user-attachments/assets/5d3d43ba-5420-448b-b780-ce194c9a36e1)
