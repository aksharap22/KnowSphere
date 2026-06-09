# User Manual

# KnowSphere

## Introduction

KnowSphere is an intelligent knowledge management platform designed to help users store, organize, and retrieve information efficiently.

Users can upload content from multiple sources, generate summaries, explore relationships between concepts, and search their personal knowledge base using natural language.

---

## Features

- Upload PDF documents
- Import article links
- Add personal notes
- Import YouTube video transcripts
- Generate AI summaries
- Explore knowledge graph connections
- Search using natural language
- Track learning history

---

## Getting Started

### Run the Application

```bash
python main.py
```

---

## Main Menu

```text
1. Upload Content
2. View Knowledge Base
3. Search Knowledge
4. View Knowledge Graph
5. Learning Insights
6. Exit
```

---

## Uploading Content

Select option 1.

Supported sources:

- PDF Documents
- Article URLs
- Personal Notes
- YouTube Links

Example:

```text
Enter Source Type: PDF
Upload File: investing_basics.pdf
```

The content will be processed and added to the knowledge base.

---

## Viewing Knowledge Base

Select option 2.

Example:

```text
Title: Introduction to Investing
Source: YouTube
Topics: Finance, Risk Management
Date Added: 09-06-2026
```

---

## Searching Knowledge

Select option 3.

Example:

```text
What did I learn about investing last month?
```

The system will search across all stored content and provide relevant answers.

---

## Viewing Knowledge Graph

Select option 4.

Users can:

- Explore connected concepts
- View topic relationships
- Discover related knowledge areas

---

## Learning Insights

Select option 5.

Statistics displayed:

- Total Documents
- Total Topics
- Most Studied Topic
- Recent Learning Activity

Example:

```text
Total Documents: 25
Total Topics: 82
Most Studied Topic: Artificial Intelligence
```

---

## Troubleshooting

### Application Does Not Start

Verify Python installation:

```bash
python --version
```

### Content Not Processing

- Check internet connectivity.
- Verify supported file formats.
- Retry importing content.

### Search Not Returning Results

- Ensure content was successfully uploaded.
- Try more specific search terms.
- Refresh the knowledge index.

---

## Support

For bug reports, feature requests, or improvement suggestions, create an issue in the project repository.
