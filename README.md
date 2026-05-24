# Climate Change RAG Chatbot

**Generative AI | Large Language Models | Retrieval-Augmented Generation | Gradio | Climate Change**

## Project Overview

This project was developed as part of the **Generative AI** chapter of the WBS Data Science & Machine Learning course.

The goal of the project is to build an interactive chatbot about **climate change** using Large Language Models and Retrieval-Augmented Generation (RAG). Instead of relying only on the general knowledge of a pre-trained language model, the chatbot retrieves relevant information from climate-related source documents and uses this context to generate more focused and informative answers.

The project combines concepts from Generative AI, embeddings, vector search, prompt engineering, conversational memory, and Gradio-based deployment.

---

## Project Goal

The main goal of this project is to explore how Generative AI can be used to create a helpful chatbot for climate change topics.

The chatbot is designed to answer questions about topics such as:

- causes of climate change
- greenhouse gas emissions
- impacts of global warming
- mitigation strategies
- adaptation measures
- renewable energy
- sustainability
- climate policy and public awareness

The project is not intended to replace scientific experts. Instead, it demonstrates how a RAG-based chatbot can support learning, communication, and access to climate-related information.

---

## Why RAG?

Large Language Models can generate fluent and useful text, but they may also produce outdated, incomplete, or incorrect answers.

Retrieval-Augmented Generation helps reduce this problem by adding an external knowledge source to the chatbot workflow.

In this project, RAG is used to:

- retrieve relevant climate change information from documents
- provide additional context to the language model
- improve the relevance of chatbot responses
- make the chatbot more domain-specific
- reduce the risk of unsupported answers

---

## How the Chatbot Works

The chatbot follows a simple RAG workflow:

1. A user asks a question about climate change.
2. The question is transformed into an embedding.
3. The system searches for similar text chunks in the climate knowledge base.
4. The most relevant chunks are retrieved.
5. The retrieved context is passed to the Large Language Model.
6. The model generates an answer based on the user question and the retrieved information.
7. The answer is displayed in a Gradio chatbot interface.

---

## Main Features

- Climate change question-answering chatbot
- Retrieval-Augmented Generation workflow
- Use of embeddings and vector similarity search
- Domain-specific responses based on climate-related documents
- Conversational interface using Gradio
- Simple prototype for non-technical users
- Focus on responsible use of Generative AI

---

## Key Concepts Practised

This project helped me practise and understand the following concepts:

- Generative AI
- Large Language Models
- Transformers
- Embeddings and vector representations
- Retrieval-Augmented Generation
- Prompt engineering
- Conversational memory
- Gradio interface development
- Data privacy and ethical considerations
- Bias and limitations in AI systems

---

## Technologies Used

- Python
- Google Colab
- Gradio
- Large Language Models
- Embeddings
- Vector search
- Retrieval-Augmented Generation
- Prompt engineering

Depending on the implementation, the project may also use libraries such as:

- LlamaIndex
- LangChain
- sentence-transformers
- Hugging Face models
- OpenAI or other LLM APIs
- pandas
- numpy

---

## Repository Structure

```text
wbs-climate-change-rag-chatbot/
│
├── data/
│   └── climate-related source documents
│
├── notebooks/
│   └── Experiments and development notebooks
│
├── app/
│   └── Gradio chatbot application
│
├── requirements.txt
└── README.md

