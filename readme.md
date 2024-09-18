# AI-Driven Historical Knowledge Generation

This repository contains the code and workflows for a project focused on using large language models (LLMs) to generate new historical knowledge from a large corpus of historical texts and related metadata. By leveraging a Retrieval-Augmented Generation (RAG) pipeline and various machine learning techniques, the project aims to iteratively build, analyze, and refine machine-generated models of the texts.

## Project Goals

The goal is to explore how LLMs can contribute to historical research by:

1. **Corpus Analysis Using LLM Agents**: Employing LLM agents in a RAG pipeline to work on a large corpus of texts and their library metadata.
  
2. **Building ML Models at Various Granularities**: Producing models of the corpus using techniques such as:
   - **Network Analysis**
   - **Latent Dirichlet Allocation (LDA) Topic Modeling**

3. **Recursive Exploration and Knowledge Generation**:
   - Rather than interpreting these models in the traditional historical research sense, LLM agents will use these models iteratively.
   - LLMs will generate new prompts and exploratory questions informed by the machine-generated models, recursively acting on new insights and improving their understanding of the corpus.

## Approach

1. **RAG Pipeline**: 
   - Using a RAG pipeline, LLM agents will retrieve and analyze segments of the corpus. This will allow for more contextual and focused exploration of the material.
   
2. **Multi-Level Model Creation**:
   - At different levels of granularity (e.g., sentence, paragraph, chapter), machine-learning models will be applied to extract patterns and structures within the text.
   
3. **Recursive Integration**:
   - AI agents will utilize the outputs from these models (e.g., topic modeling clusters) to iteratively refine their understanding of the corpus.
   - Agents will generate new questions and exploratory paths based on overlapping models and insights, dynamically advancing their knowledge of the corpus.

## Planned Features

- **Text and Metadata Analysis**: Analyzing both the content of texts and the associated metadata (e.g., author, publication date, subject) for a richer understanding.
  
- **Machine Learning Models**:
  - **Network Analysis**: To understand relationships between key entities, events, and ideas.
  - **Topic Modeling**: To cluster texts around key themes and topics, using LDA or similar algorithms.

- **Recursive Learning and Prompt Generation**: AI agents will iteratively refine their models and explore the corpus through recursive interactions, potentially identifying new questions or hypotheses that drive deeper exploration of the texts.

