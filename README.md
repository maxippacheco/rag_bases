# Retrieval Augmented Generation (RAG)

This notebook demonstrates the implementation of Retrieval Augmented Generation (RAG) techniques.

## Overview

Retrieval Augmented Generation (RAG) combines the power of large language models with external knowledge sources to enhance text generation capabilities.

This notebook covers different RAG approaches, including:

- Naive RAG (Keyword search, Cosine similarity)
- Advanced RAG (Vector search, Index-based search)
- Modular RAG

## Usage

1. **Mount your Google Drive:** This notebook requires mounting your Google Drive to access necessary files.
2. **Install libraries:** Ensure you have the required libraries installed. This notebook utilizes libraries like `sklearn`, `nltk`, `spacy`, `openai`.
3. **Set up OpenAI API key:** Provide your OpenAI API key to access the language model.
4. **Run the code:** Execute the notebook cells sequentially.

## Data

The notebook utilizes a sample dataset of records related to RAG. You can replace this data with your own for specific applications.

## Functionality

- The notebook demonstrates functions for calculating cosine similarity, enhanced similarity, and finding the best matching records from the database.
- It showcases how to augment input with retrieved information and generate text using a language model.
- Different RAG approaches are implemented, each with varying levels of complexity.

## Notes

- This notebook provides a basic framework for understanding and applying RAG techniques.
- Consider experimenting with different parameters and data sources to improve performance.

## Acknowledgments

- Inspiration and guidance were taken from various RAG resources and tutorials.
