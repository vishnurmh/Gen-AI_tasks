🤖 Generative AI Tasks & Practical Implementations

Welcome to Gen-AI Tasks, a collection of practical implementations and learning exercises focused on Generative AI, NLP, Embeddings, Vector Databases, RAG, and AI-powered applications.

This repository contains hands-on experiments, notebooks, assessments, workflow documentation, and practical implementations developed while learning and applying modern Generative AI concepts.

👨‍💻 Author

VEMULA VISHNU

Registration Number: 99230040452
Email: 99230040452@klu.ac.in
Department: CSE – AI & ML
Institution: Kalasalingam Academy of Research and Education

📌 About This Repository

The purpose of this repository is to document practical work and experiments related to Generative AI and Large Language Model (LLM) technologies.

The repository covers concepts from fundamental text representations to more advanced AI workflows such as:

Word Embeddings
Hugging Face Embeddings
Cosine Similarity
Vector Databases
ChromaDB
CRUD Operations in ChromaDB
Retrieval-Augmented Generation (RAG)
Document Loading
Document Chunking
AI Chatbots
GATE-focused AI Chatbot
AI Workflow Design
Generative AI Assessments
🧠 Topics Covered
1. Word Embeddings

Exploration of how text can be represented as numerical vectors for machine learning and natural language processing applications.

Concepts include:

Text representation
Word vectors
Semantic relationships
Vector space representation
Similarity between words
2. Hugging Face Embeddings

Practical implementation and experimentation with embedding models using the Hugging Face ecosystem.

The implementation progresses from basic concepts toward intermediate-level embedding applications.

Topics include:

Loading embedding models
Generating text embeddings
Converting text into vectors
Comparing vector representations
Understanding semantic similarity
3. Cosine Similarity

Implementation of Cosine Similarity to measure the similarity between vector representations.

The repository includes both:

Mathematical calculation of cosine similarity
Programmatic implementation

Cosine similarity is particularly useful in:

Semantic search
Document similarity
Recommendation systems
Retrieval-Augmented Generation
Vector databases
4. Vector Databases

Introduction to the concept of vector databases and their importance in modern Generative AI applications.

The repository explores ChromaDB for storing and retrieving vector embeddings.

Key concepts:

Vector storage
Embeddings
Similarity search
Metadata
Document retrieval
Semantic search
5. ChromaDB CRUD Operations

Practical implementation of CRUD operations using ChromaDB.

CRUD stands for:

Operation	Description
Create	Add documents and embeddings
Read	Retrieve stored documents
Update	Modify stored information
Delete	Remove documents

This demonstrates how vector databases can be managed programmatically.

6. RAG – Retrieval-Augmented Generation

The repository includes practical work related to Retrieval-Augmented Generation (RAG).

RAG combines information retrieval with generative AI.

Basic RAG Workflow
Documents
    ↓
Document Loading
    ↓
Text Splitting / Chunking
    ↓
Embedding Generation
    ↓
Vector Database
    ↓
Similarity Search
    ↓
Relevant Context
    ↓
LLM
    ↓
Generated Answer

RAG helps AI systems generate responses based on retrieved information rather than relying only on the model's internal knowledge.

7. Document Loading & Chunking

The repository contains practical work on preparing documents for RAG systems.

Important stages include:

Loading documents
Extracting text
Cleaning text
Splitting documents into chunks
Generating embeddings
Storing embeddings
Retrieving relevant chunks

Effective chunking is important because it directly affects retrieval quality.

8. AI Chatbot – GATE Preparation

The repository also includes a GATE-focused AI chatbot task.

The chatbot demonstrates how Generative AI concepts can be applied to an educational use case.

The project focuses on:

Question answering
Retrieval-based responses
AI-assisted learning
Domain-specific knowledge
RAG-based chatbot concepts
📂 Repository Contents
File	Description
Word_Embeddings_VNU.ipynb.txt	Practical work on word embeddings
HuggingFace_Embedding_Scratch_to_Intermediate_VNU.ipynb.txt	Hugging Face embedding experiments
Calculating_Cosine_Similarity_Mathematically_VNU.ipynb.txt	Mathematical and programmatic cosine similarity
Intro_to_Vector_Databases_ChromaDBipynb_VNU.ipynb.txt	Introduction to vector databases and ChromaDB
CRUD_Operations_ChromaDB_VNX.ipynb.txt	CRUD operations using ChromaDB
Step1_RAG_Document_Loading_and_Chunking_Strategies_VNU.ipynb.txt	RAG document processing and chunking
VNU_Rag_Practice.ipynb.txt	RAG practical implementation
VEMULA_VISHNU_99230040452_GATE_Chatbot_Task_Final_Revised14.pdf	GATE chatbot task documentation
VEMULA_VISHNU_99230040452_Mini_Assessment13.pdf	Mini assessment
VEMULA_VISHNU_Assessment_Final_With_Live_Evidence11.pdf	Final assessment with evidence
VEMULA_VISHNU_Assessment_MultiStep_AI_Workflow12.pdf	Multi-step AI workflow assessment
Campus_Micro_Experiment_AI_Workflow_Vishnu15.pdf	AI workflow experiment documentation

The repository currently contains these practical notebooks/text exports and supporting PDF documentation.

🛠️ Technologies & Tools

The major technologies and concepts explored in this repository include:

Programming
Python
Jupyter Notebook
Google Colab
Generative AI
Large Language Models
Prompt Engineering
Retrieval-Augmented Generation
AI Chatbots
NLP
Word Embeddings
Text Embeddings
Semantic Similarity
Natural Language Processing
Vector Search
ChromaDB
Vector Databases
Similarity Search
Cosine Similarity
AI Ecosystem
Hugging Face
Embedding Models
RAG Pipelines
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/vishnurmh/Gen-AI_tasks.git
2. Navigate to the Repository
cd Gen-AI_tasks
3. Use Google Colab

Most of the practical implementations are notebook-based and can be executed using Google Colab.

You can upload the notebook or open the corresponding notebook file and execute the cells sequentially.

📚 Learning Path

A recommended order for understanding the concepts in this repository is:

1. Word Embeddings
       ↓
2. Hugging Face Embeddings
       ↓
3. Cosine Similarity
       ↓
4. Vector Databases
       ↓
5. ChromaDB
       ↓
6. ChromaDB CRUD Operations
       ↓
7. Document Loading
       ↓
8. Document Chunking
       ↓
9. RAG
       ↓
10. AI Chatbot

This progression moves from the fundamentals of representing text as vectors toward practical Generative AI applications.

🎯 Learning Objectives

Through these implementations, the following skills are developed:

Understanding text embeddings
Generating vector representations
Measuring semantic similarity
Working with vector databases
Performing CRUD operations on vector stores
Preparing documents for RAG
Implementing document chunking strategies
Understanding retrieval pipelines
Building domain-specific AI applications
Applying Generative AI concepts to real-world problems
🔍 RAG Architecture

A simplified architecture explored through the repository is:

                 ┌─────────────────┐
                 │    Documents    │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Document Loader │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │    Chunking     │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │   Embeddings    │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │   ChromaDB      │
                 │ Vector Database │
                 └────────┬────────┘
                          ↓
                    User Query
                          ↓
                 ┌─────────────────┐
                 │ Similarity      │
                 │ Search          │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Relevant Context│
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │      LLM        │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ AI Generated    │
                 │ Response        │
                 └─────────────────┘
📈 Future Improvements

Future versions of this repository may include:

Advanced RAG pipelines
Hybrid search
Metadata filtering
Reranking techniques
Evaluation of RAG systems
Advanced vector database operations
LLM integration
Multimodal RAG
Agentic AI workflows
Production-ready AI applications
Streamlit/React-based AI interfaces
📜 Repository Purpose

This repository serves as a practical learning portfolio for Generative AI and demonstrates the progression from fundamental concepts such as embeddings and vector similarity to advanced applications such as RAG and AI chatbots.

It can also be used as a reference for students and developers who are beginning their journey into Generative AI, Vector Databases, and Retrieval-Augmented Generation.

👤 Author

VEMULA VISHNU
B.Tech – Computer Science & Engineering (AI & ML)
Kalasalingam Academy of Research and Education

Registration Number: 99230040452
Email: 99230040452@klu.ac.in

⭐ Acknowledgement

This repository was developed as part of practical learning and experimentation in Generative AI, NLP, Embeddings, Vector Databases, ChromaDB, and RAG technologies.

⭐ If you find this repository useful, consider giving it a star!

Repository:
https://github.com/vishnurmh/Gen-AI_tasks
