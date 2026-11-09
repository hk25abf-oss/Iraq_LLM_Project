# README — IMF Iraq 2025 Financial Stability Analysis

## Project Overview
This project develops an LLM-based pipeline to analyse Iraq's 2025 IMF Article IV Consultation Report, extract macroeconomic indicators, generate evidence-grounded summaries, and create a financial stability dashboard.

## Implementation
The project is implemented in Google Colab using Python across 15 notebook cells.

- *Task 1 — PDF Processing & Summarisation:* Extracts, cleans, chunks, and summarises the IMF report with LLM-based quality evaluation.
- *Task 2 — Thematic & Indicator Extraction:* Identifies seven financial stability themes, macroeconomic indicators, strengths, vulnerabilities, and historical trends.
- *Task 3 — RAG Grounding:* Uses MiniLM embeddings and FAISS for semantic retrieval and source-grounded question answering.
- *Task 4 — Data Visualisation:* Produces a four-panel financial stability dashboard using Pandas and Matplotlib.
- *Extra Credit — Multi-Query RAG:* Compares baseline retrieval against quer
