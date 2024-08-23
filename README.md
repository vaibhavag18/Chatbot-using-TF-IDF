# Chatbot Using TF-IDF

Welcome to the Chatbot Using TF-IDF project! This project demonstrates a simple yet effective chatbot that uses TF-IDF (Term Frequency-Inverse Document Frequency) to process and match user queries with predefined questions and answers. The chatbot leverages Natural Language Processing (NLP) techniques to understand and respond to user inputs.

## Project Overview

The chatbot is designed to handle user queries by comparing them to a set of predefined questions. It uses TF-IDF for text representation and cosine similarity for finding the most relevant answers. The project involves text preprocessing, feature extraction, and similarity measurement.

### Features

- **Text Preprocessing:** Utilizes tokenization, lemmatization, and stemming to prepare text data for analysis.
- **TF-IDF Vectorization:** Converts text into numerical vectors based on term frequency and inverse document frequency.
- **Cosine Similarity:** Measures the similarity between user input and predefined questions to find the most relevant response.
- **Customizable:** Easily update the questions and answers to tailor the chatbot to specific use cases.

## Requirements

To run this project, you need the following Python packages:

- `pandas`
- `nltk`
- `numpy`
- `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas nltk numpy scikit-learn
