# AI-Powered Legal Document Analyzer – README

## Project Overview
This project leverages state-of-the-art NLP techniques, particularly transformer models (like BERT), to analyze and extract meaningful insights from legal documents. It automates the process of identifying clauses, classifying document types, and summarizing content, significantly reducing manual effort in legal review processes.

## Key Features
Document classification (e.g., contracts, agreements).

Clause extraction using NLP pipelines.

Summarization using transformer models (BERT/DistilBERT).

Keyword and named entity recognition for legal terms.

Interactive visualizations for entity and clause review.

## Dataset
Source: Legal case files and publicly available contract datasets.

Format: PDF/Word converted to plain text.

Preprocessing: Cleaning, tokenization, stopword removal, and chunking.

## Tech Stack
Language: Python

Libraries: transformers, spaCy, pandas, nltk, matplotlib, streamlit

Model: BERT / DistilBERT

## Results
Achieved >90% accuracy in document type classification.

Real-time clause and keyword extraction in <2 seconds per document.

## Use Cases
Automating legal document review in law firms.

Assisting compliance teams in identifying risky clauses.

Accelerating due diligence in M&A scenarios.

## How to Run
pip install -r requirements.txt
streamlit run app.py
