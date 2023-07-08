# Introduction to Building Q&A Systems with Large Language Models (LLMs)

## Course Objectives
This course aims to equip you with the skills to develop a "Question and Answer" (Q&A) system using Large Language Models (LLMs). The emphasis will be on a widely adopted use-case, which involves Q&A over a Knowledge Base (KB) containing proprietary data. We will delve into the implementation using a prevailing method, the Retrieval-Augmented Generation (RAG). The course will provide insight into the data pipeline, including the pre-processing and ingestion of data into a vector database. Participants will also experience a step-by-step code walkthrough to build a proof-of-concept prototype. Furthermore, we'll delve into design considerations for elevating your PoC to a production-ready solution.

## Target Audience
This course is curated for Software Engineers, ML Engineers, and Data Engineers eager to master the latest strategies for implementing a Q&A system over proprietary data. An ideal participant would be able to leverage these skills to build a PoC prototype in their organizations and exhibit to their internal stakeholders the potential of building an LLM-powered application for internal and external users.

## Course Outline
- The use case: Q&A over documents in a proprietary KB
  - The necessity of Retrieval-Augmented Generation.
  - User identification and UX definition.
  - Setting system expectations.
- Data preparation pipeline for Vector Databases:
  - Data types: documents, conversations, databases.
  - Data pre-processing with open-source solutions (examples: LangChain, Llama Index, BYO)
  - Embedding with state-of-the-art LLMs (examples: OpenAI, Cohere, open-source models)
  - Insertion into Vector Databases (examples: Weviate, Redis, Pinecone)
- Answering Questions via Semantic Search:
  - Question elicitation and embedding.
  - Semantic search and document retrieval.
  - Document-based question answering (examples: ChatGPT, Cohere, open-source models)
  - Summarization techniques and useful tips.
- Proof-of-concept Prototype:
  - Hands-on Python example with MLOps Community Slack Data and Streamlit.
- Production Design Considerations:
  - Exploring emerging architectures for production.
  - Strategies for data preparation.
  - Performance metrics: scalability, latency, costs.
  - PromptOps: versioning, tracking, analysis, evaluation, UAT.
  - User interfaces and feedback loop.

## Prerequisites
- Proficiency in Python programming.
- Experience in building multi-component software applications.
- A high-level understanding of Artificial Intelligence (AI) and the limitations of AI-powered applications.

##  Extras
- [References](references.md)
