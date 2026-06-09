# KnowSphere

## Project Overview

KnowSphere is an intelligent personal knowledge management system that helps users organize, connect, and retrieve information from multiple sources such as PDFs, articles, YouTube videos, and personal notes.

The system acts as a "Second Brain" by automatically extracting key insights, generating summaries, building relationships between concepts, and enabling users to search and interact with their knowledge using natural language.

This project aims to improve learning, research, and knowledge retention through AI-powered organization and retrieval.

---

## Objectives

- Centralize knowledge from multiple sources.
- Generate AI-powered summaries.
- Build meaningful connections between concepts.
- Enable semantic search across stored information.
- Help users revisit and retain knowledge efficiently.
- Provide an intuitive and scalable knowledge management platform.

---

## System Architecture

User

↓

Content Ingestion Layer

↓

AI Processing Layer

↓

Knowledge Graph Layer

↓

Search & Retrieval Layer

↓

Storage Layer

---

## Core Features

### Content Import

- Upload PDF documents
- Import article URLs
- Add personal notes
- Import YouTube video transcripts

### AI Processing

- Automatic summarization
- Key concept extraction
- Topic identification
- Entity recognition

### Knowledge Management

- Organize knowledge automatically
- Create relationships between concepts
- Knowledge graph visualization

### Search & Retrieval

- Natural language querying
- Semantic search
- Context-aware answers
- Learning history search

### Insights

- Frequently studied topics
- Learning timeline
- Topic growth tracking
- Knowledge gap identification

---

## Knowledge Data Structure

```json
{
    "id": 1,
    "title": "Introduction to Investing",
    "source": "YouTube",
    "summary": "Basic principles of investing and portfolio management.",
    "tags": ["finance", "investing"],
    "linked_topics": [
        "Mutual Funds",
        "Risk Management"
    ],
    "date_added": "2026-06-09"
}
```

---

## Coding Standards

### General Rules

- Follow PEP 8.
- Use descriptive variable and function names.
- Keep functions modular and focused.
- Avoid duplicated logic.
- Write maintainable and readable code.
- Document all major components.

### Function Naming

```python
def import_document():
    pass

def generate_summary():
    pass

def build_knowledge_graph():
    pass

def semantic_search():
    pass

def answer_query():
    pass
```

---

## Suggested Project Structure

```text
mindvault-ai/

├── main.py
├── README.md
├── USER_MANUAL.md
├── AGENTS.md

├── src/
│   ├── ingestion.py
│   ├── summarizer.py
│   ├── graph_builder.py
│   ├── search.py
│   ├── retrieval.py
│   └── storage.py

├── data/

└── assets/
```

---

## Testing Requirements

Verify:

- PDF import functionality
- Article ingestion
- YouTube transcript processing
- Summary generation
- Knowledge graph creation
- Semantic search accuracy
- Question answering functionality
- Data persistence

---

## Future Enhancements

### Version 2

- Browser extension
- Mobile support
- Multi-language support

### Version 3

- Team knowledge sharing
- Collaborative workspaces
- Shared knowledge graphs

### Version 4

- Personalized learning recommendations
- Automatic revision schedules

### Version 5

- Voice-based knowledge assistant
- Offline AI processing

---

## Development Principles

### User-Centric Design

Focus on simplicity and usability.

### AI-Assisted Learning

Use AI to enhance understanding, not replace learning.

### Modular Design

Build independent, reusable components.

### Open Source First

Encourage transparency and community contributions.

### Scalability

Design architecture that can support growing knowledge bases.

### Documentation First

Document every feature, module, and change.

---

## Contribution Guidelines

- Follow project coding standards.
- Keep features modular and maintainable.
- Update documentation for all changes.
- Write descriptive commit messages.
- Test features before creating merge requests.
- Maintain readability and consistency throughout the codebase.
