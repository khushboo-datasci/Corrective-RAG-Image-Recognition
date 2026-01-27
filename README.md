# Corrective Retrieval-Augmented Generation (CRAG) System

A Python-based **Corrective Retrieval-Augmented Generation (CRAG)** project that improves traditional RAG by dynamically evaluating retrieved documents and applying corrective logic before generating final responses.

The system retrieves knowledge from research documents, checks relevance, and decides whether to rely on retrieved content or fallback reasoning.

----

## Project Overview

This project demonstrates an **end-to-end CRAG workflow**, including:

- Document loading and preprocessing  
- Text chunking and semantic embedding generation  
- Vector storage using FAISS  
- Query-based document retrieval  
- Relevance evaluation and correction logic  
- Final answer generation  

----

## Problem Statement

Traditional RAG systems may generate incorrect or irrelevant answers if retrieved documents are weak or partially related.

This project addresses that issue by introducing **Corrective Retrieval**, ensuring that:
- Irrelevant documents are filtered  
- Responses are grounded in reliable context  
- Hallucinations are minimized  

----

## Objectives

- Implement a Corrective RAG (CRAG) pipeline  
- Improve response reliability over standard RAG  
- Use document-based knowledge for question answering  
- Demonstrate real-world Generative AI architecture  

----

## Technologies Used

- Python 3.12  
- LangChain (modular packages)  
- Sentence Transformers  
- FAISS Vector Database  
- PyPDF  

----

## Project Workflow

1. Load and preprocess research PDF document  
2. Split document into meaningful text chunks  
3. Generate embeddings using Sentence Transformers  
4. Store embeddings in FAISS vector database  
5. Accept user query  
6. Retrieve relevant document chunks  
7. Evaluate relevance of retrieved content  
8. Apply corrective logic  
9. Generate final refined response  

----

## Visualizations / Outputs

![CRAG Query Output](Corrective-RAG-Image-Recognition.png)


----

## Key Highlights

- Implements **Corrective Retrieval-Augmented Generation (CRAG)**  
- Reduces hallucination in RAG-based systems  
- Fully document-driven approach  
- Suitable for research-based question answering  
- Offline-compatible (no paid APIs required)  

----

## Conclusion

- CRAG enhances traditional RAG by validating retrieved knowledge  
- Improves accuracy and trustworthiness of generated responses  
- Ideal for domain-specific document question answering  
- Demonstrates advanced Generative AI system design  

----

## How to Run the Project

1. Clone the repository

    git clone https://github.com/khushboo-datasci/Corrective-RAG-Image-Recognition

2. Install dependencies  

    pip install -r requirements.txt

3. Open and run the notebook  

    CRAG_Project.ipynb

----

## Author

**Khushboo Kumari**  
Aspiring Data sience 

GitHub: https://github.com/khushboo-datasci
