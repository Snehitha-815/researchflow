# ResearchFlow: Autonomous AI Research Assistant

ResearchFlow is an AI powered assistant that helps researchers and analysts work with long technical documents. It can read large PDF collections, plan its own steps, search across them, extract key information, and produce clean summaries and structured reports.

The goal is to show how modern LLMs, retrieval augmented generation, and agentic workflows can support real research teams in labs, hospitals, institutes, and engineering organizations.

## What it can do

- Ingest and index long documents such as reports, guidelines, or research papers
- Use a planner agent to decide the steps needed to answer a complex request
- Search relevant sections using a vector database
- Extract key findings, recommendations, and important sentences
- Generate a human friendly summary and a structured JSON or table output
- Keep an audit trail of the steps and sources it used

## Tech stack

- Python
- FastAPI
- LangChain or LangGraph
- OpenAI or Azure OpenAI for LLMs and embeddings
- Chroma or Qdrant as a vector store
- Streamlit or React for a simple user interface

## Planned architecture

- **Planner agent** that breaks a high level request into smaller tasks
- **Retriever agent** that performs RAG over document embeddings
- **Extraction agent** that pulls out concrete facts or recommendations
- **Summarizer agent** that writes clear summaries
- **Validator agent** that checks for consistency and basic quality

All of this will be exposed through a FastAPI backend with a simple UI to upload documents, choose an analysis mode, and view reports.

## Goals

This project is designed to look and behave like a real system that a research lab or AI team would use. It combines:

- LLM applications and agents
- Retrieval augmented generation
- Backend engineering
- Simple frontend integration
- Clear documentation

It is also part of my portfolio as an AI Engineer focused on LLMs, RAG, and production ready ML systems.

## Status

Project setup in progress. Core components to be implemented:

- [ ] Document ingestion and chunking
- [ ] Embedding and vector store pipeline
- [ ] Planner and retriever agents
- [ ] Extraction and summarization agents
- [ ] Validator agent and audit logging
- [ ] FastAPI endpoints
- [ ] Basic UI
