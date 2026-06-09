# ContextForge

A lightweight personal knowledge-compilation application designed to help developers, students, and open-source contributors capture, organize, and contextually query technical information.

This project is being developed as a learning-focused software engineering project to understand programming fundamentals, semantic vector databases, and real-world application architecture.

## Project Overview

ContextForge allows users to ingest unstructured technical data, automatically extract core components like code snippets, maintain semantic links between concepts, and query their aggregated learning history using natural language.

The goal is to eliminate fragmented documentation and information overload through an intelligent local context engine.

Examples of knowledge ingested:
* API Documentation Snippets
* Error Resolution Logs
* Terminal Command Workflows
* Technical Article Summaries
* Git Workflow Frameworks

## Objectives

* Help developers build a reliable, local engineering memory.
* Provide fast, context-aware retrieval of code and commands.
* Maintain logical relationships between independent frameworks.
* Learn software engineering and AI orchestration through a practical project.

## Features

### Fragment Management
* Ingest text fragments
* View stored fragments
* Update fragment text and custom tags
* Delete legacy fragments

### Semantic Synthesis
* Automated code block isolation
* Key concept extraction
* Automated categorization based on content
* Metadata stamping (creation date, source type)

### Context Querying
* Natural language prompt search
* Historical search ("What did I learn about FastAPI last week?")
* Associated code block retrieval
* Multi-document context merging

## Technology Stack

### Current Version
* Python
* JSON File Storage (Metadata mapping)
* Lightweight Embedding Engine (Local numpy vectors)

### Planned Enhancements
* HTML / Tailwind CSS
* JavaScript
* FastAPI Backend
* ChromaDB / FAISS Vector Database
* Google Gemini API / Hugging Face Inference API

## Programming Concepts Covered

This project is designed to teach crucial software development and AI engineering concepts.

### Variables
Store fragment text and structural data.
```python
fragment_text = "git commit -m 'Initial commit'"
