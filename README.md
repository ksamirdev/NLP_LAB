# NLP Assignment 1 – Text Preprocessing Pipeline

This repository contains **Assignment 1** for the SEC-D Natural Language Processing (NLP) course. The objective of this project is to implement a complete NLP preprocessing pipeline on a custom paragraph and display the output at each stage to clearly demonstrate how raw text is transformed for computational analysis.

## Project Objective

The assignment focuses on understanding and applying the fundamental steps involved in preparing text data for NLP tasks. Each step highlights how text evolves from an unstructured paragraph into a format suitable for machine learning models.

## NLP Pipeline Steps

### 1. Tokenization

The process of splitting a paragraph into individual words or units called tokens. This allows the model to process text as discrete elements instead of a continuous string.

Example:
"Natural Language Processing" → ["Natural", "Language", "Processing"]

### 2. Stopword Removal

Common words such as "the", "is", "in", "and", which provide little semantic value, are removed to reduce noise and improve efficiency.

Example:
"This is a sample sentence" → ["sample", "sentence"]

### 3. Stemming

Words are reduced to their root form by trimming prefixes or suffixes, often resulting in non-dictionary forms.

Examples:
playing → play
studies → studi

This method is fast but less linguistically accurate.

### 4. Lemmatization

Words are converted to their meaningful base or dictionary form using grammatical rules and context.

Examples:
studies → study
better → good

This method is slower than stemming but produces more accurate results.

## Technologies Used

* Python
* NLTK (Natural Language Toolkit)
* Google Colab
* Jupyter Notebook

## Repository Contents

* **Assignment1.ipynb**
  Jupyter Notebook containing the complete implementation with clear, step-by-step explanations and outputs for each preprocessing stage.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run each cell sequentially to observe the transformations applied to the input text.
3. Review printed outputs after every step to understand the pipeline workflow.

## Learning Outcomes

* Understanding of basic NLP preprocessing concepts
* Practical experience using NLTK
* Insight into how text preparation impacts NLP performance
