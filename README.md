# LLAMA 2 Retrieval-Augmented Generation with LlamaIndex Framework

## Introduction
This project employs the LLAMA 2 model in conjunction with the LlamaIndex Framework to create a retrieval-augmented generation system. It is designed to answer queries based on the content of two influential papers: "Attention Is All You Need" and "You Only Look Once (YOLO)".

## Overview
Retrieval-augmented generation (RAG) enhances language models by integrating external document retrieval into the response generation process. This project uses the LlamaIndex Framework, a leading data framework for building applications with large language models (LLMs), along with Hugging Face and Langchain embeddings.

## Model Training
The LLAMA 2 Large Language Model (LLM) has been trained on the PDFs of the aforementioned papers. The LlamaIndex Framework facilitates the indexing of these documents, making them accessible for the model to retrieve information during the generation process.

## Prompting and Retrieval
The trained model can be prompted with questions related to the papers' content. It retrieves the most pertinent information from the indexed documents to generate accurate and contextually relevant answers.

## Technologies Used
- **LlamaIndex Framework**: Provides the infrastructure for indexing and retrieving data for LLM applications.
- **Hugging Face**: A platform for machine learning models, particularly focused on pre-trained models.
- **Langchain**: A library that enables the creation of applications with language models.

## Conclusions
This project illustrates the integration of retrieval mechanisms with LLMs to improve the quality and relevance of generated responses. By training the LLAMA 2 model with the LlamaIndex Framework, we achieve a sophisticated system capable of providing informed answers based on specific scholarly works.