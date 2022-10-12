---
layout: post
title: IEEE Big Data 2019 Tutorial
---

# Taming Unstructured Big Data: Automated Information Extraction from Massive Text

Xuan Wang, Yu Zhang, Qi Li, Jiawei Han

Department of Computer Science, University of Illinois at Urbana-Champaign, Urbana, IL, USA

Time: **10:05am-12:10pm, Wednesday, December 11, 2019**

Location: **Los Angeles, CA, USA**


## Slides: 
Our tutorial slides can be downloaded [here](http://hanj.cs.illinois.edu/pdf/bigdata19tuto_slides.pdf).


## Abstract:
Text data is a powerful information source that covers almost every aspect of our life. Automated information extraction has attracted considerable attention with various approaches developed to mine structured knowledge from unstructured text. In this tutorial, we present an organized picture of automated information extraction from massive text to answer the need of a systematic review and comparison of the techniques. We first introduce major tasks of information extraction such as named entity recognition and relation extraction. Then we introduce downstream applications such as heterogeneous information network construction and claim mining that utilize the extracted information. Specifically, we focus on the methods that are scalable, effective, minimum supervised and working on various kinds of text (e.g., news and biomedical science). We also demonstrate on a real-world dataset, PubMed that includes over 29 million biomedical literature, how the heterogeneous information network can be constructed and how the scientific claims can be automatically retrieved based on automated information extraction. The covered topics will be interesting to both advanced researchers and beginners in data mining, text mining, natural language processing and machine learning.


## Outline:
- Introduction
  - Motivations
  - Overview of automatic information extraction from massive text
  - Application of utilizing the extracted information
- Named Entity Recognition
  - What is Named Entity Recognition (NER)?
  - Traditional Supervised Methods
    - CorNLL03 Shared Task
    - Sequence Labeling Framework
    - Conditional Random Fields (CRFs) 
    - Handcrafted Features
  - Modern Neural Models
    - Bidirectional Long Short-term Memory (BiLSTM)-based Models
    - Language Model and Contextualized Representations
    - End-to-end Neural Models
  - Distantly Supervised Methods
    - Entity Typing
    - Learning from Domain-Specific Dictionaries
- Relation Extraction
  - What is Relation Extraction (RE)? – Supervised Methods
    - Multi-relational Embedding
    - Position-aware Neural Models
    - Dependency-path-based Neural Models
  - Pattern-based Methods
    - Sequential Textual Patterns
    - Patterns with Linguistic Features
    - Synonym Pattern Grouping
  - Open-domain Approaches
    - How to exploit local structure?
    - How to exploit global consistency? 
    - High-arity OpenIE
  - Weakly-supervised Methods
    - Bootstrapping Methods
    - Pattern-enhanced Embedding Learning
- Heterogeneous Information Network Construction
  - What is a Heterogenous Information Network (HIN)?
  - Network-based Document Summarization
    - What is a concept map?
    - Constructing Concept Maps from Text
  - Factual Network Construction and Exploration
    - Network Construction
    - Factual Knowledge Exploration
- Claim Mining
  - What is a claim?
  - Comparison between Opinion Mining, Argument Mining and Claim Mining
  - Context-independent claim mining
    - What is context-independent claim mining?
    - Supervised Machine Learning Methods
  - Context-dependent claim mining
    - What is a topic and a context-dependent claim? 
    - Supervised Machine Learning Methods
    - Weakly/Distantly-supervised Methods
    - Unsupervised Claim Mining
- System Demos
  - Named Entity Recognition & APIs
  - Open Relation Extraction & APIs 
  - Scientific Claim Mining & APIs 
  - BioText Mining Demo
- Summary and Future Directions
  - Summary
    - Principles and Techniques
    - Advantages and Limitations
    - How to choose a method based on your application?
  - Future Directions

