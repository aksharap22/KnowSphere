# KnowSphere

An AI-powered personal knowledge management system that helps users organize, summarize, connect, and retrieve information from PDFs, articles, YouTube videos, and personal notes.

## Features

### Content Import

- Upload PDF documents
- Import article URLs
- Add personal notes
- Import YouTube video transcripts

### AI Summarization

- Generate concise summaries
- Extract key concepts
- Identify important topics

### Knowledge Graph

- Connect related concepts
- Visualize topic relationships
- Discover hidden connections

### Intelligent Search

- Ask questions in natural language
- Search across all uploaded content
- Retrieve context-aware answers

### Learning Insights

- View learning history
- Track frequently explored topics
- Monitor knowledge growth

## Prerequisites

Python 3.10 or later

## Setup

Clone the repository.

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Run the application from the root directory:

```bash
python main.py
```

## Running Tests

To run unit tests:

```bash
PYTHONPATH=. pytest tests/unit/
```

## Project Structure

- main.py: Entry point for the application.
- src/ingestion.py: Handles content import and processing.
- src/summarizer.py: Generates AI summaries.
- src/graph_builder.py: Builds concept relationships.
- src/search.py: Handles semantic search.
- src/storage.py: Manages data persistence.
- specs/: Project specifications and planning documents.

## License

Educational purpose - feel free to use, learn, and contribute.
