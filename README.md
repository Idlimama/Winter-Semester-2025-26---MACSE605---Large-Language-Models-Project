# Winter-Semester-2025-26---MACSE605---Large-Language-Models-Project
Team Member:
Tarun kumar R(25MML0057)
Ahamed Razi C (25MML0058)
R Amarnath(25MML0051)

Abstract:
Legal research is a fundamental yet time-consuming task in the judicial and legal domains, as it requires analyzing large volumes of judicial judgments and identifying relevant precedents. Traditional legal information retrieval systems mainly rely on keyword-based search techniques, which fail to capture the complex relationships between cases and often lack reasoning and explainability. With the increasing availability of digital legal documents, there is a growing need for intelligent systems that can perform structured, accurate, and explainable legal reasoning.

This project proposes an AI-based legal case reasoning system using Transformer models and Graph-based Retrieval Augmented Generation (GraphRAG). Judicial judgments are processed using Transformer-based natural language processing techniques to extract legal entities, citations, and key concepts. These extracted elements are then organized into a legal knowledge graph, representing precedent relationships among cases. GraphRAG is employed to retrieve relevant subgraphs based on user queries, enabling multi-hop reasoning over judicial precedents. Finally, a Transformer-based language model generates clear and explainable legal responses supported by citation paths.

The proposed system improves the accuracy, transparency, and efficiency of legal research by reducing hallucinations, enabling precedent-aware reasoning, and providing explainable outputs. This approach demonstrates the potential of combining Transformers with structured knowledge graphs for reliable and intelligent legal decision-support systems.

<img width="1076" height="613" alt="image" src="https://github.com/user-attachments/assets/4c652856-ffe9-48da-b068-54731f9d943b" />

<img width="982" height="386" alt="image" src="https://github.com/user-attachments/assets/062861ea-450e-49ff-b219-c762dd1fe887" />

This project proposes an intelligent legal case reasoning system that integrates modern natural language processing techniques with structured knowledge representation. The following components are used in the proposed system:

1️) Transformer-Based Models

Transformer models are used for natural language understanding and text processing. They help in extracting important legal entities, understanding judicial language, and summarizing legal documents. Transformers enable the system to capture long-range dependencies and semantic relationships within legal texts.

2️) Large Language Model (LLM)

A Large Language Model, built on the Transformer architecture, is used to generate human-readable legal reasoning. The LLM interprets the user’s legal query and produces detailed explanations based on the information retrieved from the knowledge graph. The LLM does not work independently; it relies on structured legal data provided through GraphRAG to ensure correctness and explainability.

3️) Graph-Based Retrieval Augmented Generation (GraphRAG)

GraphRAG is employed to retrieve relevant judicial precedents using a legal knowledge graph. Unlike traditional retrieval methods, GraphRAG enables multi-hop reasoning by traversing citation relationships among cases. This approach improves accuracy and provides transparent reasoning paths supported by legal citations.

4️) Legal Knowledge Graph

A legal knowledge graph is constructed to represent judicial cases, legal concepts, and their relationships. Nodes represent entities such as cases, courts, and legal provisions, while edges represent citation and precedent relationships. The knowledge graph serves as the structured memory of the system.

5️) Judicial Judgment Dataset

Publicly available judicial judgments from the Indian Supreme Court are used as the primary dataset. These judgments provide the textual content and citation relationships necessary for building the knowledge graph and supporting legal reasoning.

Dataset link:https://github.com/vanga/indian-supreme-court-judgments/blob/main/opendata/tutorials/README.md

6️) Natural Language Processing (NLP) Techniques

NLP techniques such as named entity recognition, text cleaning, and document segmentation are applied to preprocess legal documents. These techniques enable accurate extraction of legal entities and relationships from unstructured judgment text.

