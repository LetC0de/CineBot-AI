# 🎬 CineBot – AI Powered Movie Information Extraction System

CineBot is an AI-powered media intelligence project that transforms messy movie-related text into clean structured data using Large Language Models (LLMs).

The system is designed for streaming platforms, production houses, movie analytics companies, and entertainment applications that receive huge volumes of unstructured movie information every day.

Instead of manually reading long paragraphs, CineBot automatically extracts important movie metadata and converts it into structured output ready for databases, APIs, analytics systems, and recommendation engines.

---

# 🚀 Project Idea

Modern entertainment companies receive large amounts of movie-related content daily, such as:

- Movie descriptions
- Press releases
- Blog articles
- Review summaries
- Metadata from different sources

But most of this information arrives as:

- Long paragraphs
- Messy text
- Unstructured data
- Difficult-to-process content

Manual extraction takes a lot of time and effort.

CineBot solves this problem using AI.

The application reads raw movie paragraphs and automatically extracts important information like:

- Movie title
- Genre
- Director
- Cast
- Ratings
- Themes
- Summary

Then it converts the output into clean structured JSON format.

---

# 🧠 Real-World Scenario

Imagine a media intelligence company called **CineBot Analytics**.

Every day the company receives thousands of movie-related paragraphs from:

- Streaming platforms
- Entertainment websites
- Review platforms
- Production houses
- Media blogs

The data is unstructured and difficult to organize manually.

Streaming companies require structured metadata for:

- Search systems
- Recommendation engines
- Analytics dashboards
- APIs
- Databases

CineBot automates this entire workflow using AI-powered information extraction.

---

# ❌ The Problem

Most incoming movie data:

- Comes in long paragraphs
- Is inconsistent
- Has missing formatting
- Is difficult to process manually

Manual extraction is:

- Time-consuming
- Expensive
- Error-prone
- Hard to scale

Companies don't want raw text.

They want structured data they can:
- Store
- Search
- Filter
- Analyze
- Send through APIs

This is called **Structured Output**.

---

# ✅ Solution

CineBot builds an AI-powered extraction pipeline that:

1. Takes a raw movie paragraph
2. Understands the content using LLMs
3. Extracts structured movie metadata
4. Generates a clean summary
5. Returns the result in structured format
6. Makes the data database-ready

---

# 🛠️ Technologies Used

- Python
- LangChain
- Mistral AI
- Pydantic
- dotenv

---

# 📁 Project Structure

```bash
CineBot/
│
├── core.py
├── structure_output.py
├── .env
├── requirements.txt
└── README.md
```

---

# 📌 core.py

## Overview

`core.py` is the first version of the project.

It focuses on:
- Prompt engineering
- Information extraction
- Human-readable output formatting

The system takes a movie paragraph as input and returns structured readable movie information.

---

## Features

- Prompt Engineering using LangChain
- AI-powered metadata extraction
- Summary generation
- Clean readable formatting
- Missing value handling using NULL

---

## Workflow

### Step 1 – User Gives Paragraph

```txt
A skilled thief who steals secrets through dream-sharing technology is given an impossible mission...
```

### Step 2 – Prompt Creation

LangChain creates a structured prompt for the AI model.

### Step 3 – AI Processing

Mistral AI analyzes the paragraph.

### Step 4 – Information Extraction

The AI extracts:
- Title
- Genre
- Director
- Cast
- Themes
- Ratings
- Summary

### Step 5 – Output Generation

The result is displayed in clean readable format.

---


# 📌 structure_output.py

## Overview

`structure_output.py` is the advanced version of the project.

Instead of generating plain readable text, this version produces clean structured output using:

- Pydantic Models
- LangChain Output Parsers
- Structured AI Responses

This makes the output production-ready for:
- APIs
- Databases
- Recommendation systems
- Analytics pipelines

---

# 🔥 Why Structured Output Matters

Normal AI text is difficult for machines to use directly.

Companies need:
- JSON
- Validated schemas
- Consistent structure
- Machine-readable output

Structured output solves this problem.

---

# ⚡ Features

- Structured JSON output
- Pydantic validation
- Output parsing
- Type safety
- Database-friendly responses
- Consistent AI responses

---



# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/LetC0de/CineBot-AI.git

cd cinebot
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Create .env File

```env
MISTRAL_API_KEY=your_api_key_here
```

---

# ▶️ Run core.py

```bash
python core.py
```

---

# ▶️ Run structure_output.py

```bash
python structure_output.py
```

---

# 📦 requirements.txt

```txt
langchain
langchain-mistralai
python-dotenv
pydantic
```

---

# 🔮 Future Improvements

- FastAPI Integration
- MongoDB Storage
- PostgreSQL Support
- Web Dashboard
- Movie Recommendation Engine
- Sentiment Analysis
- Multi-language Support
- Vector Database Integration
- RAG Pipeline
- Streaming Platform Analytics

---

# 📚 Concepts Learned

This project demonstrates:

- Prompt Engineering
- Structured Outputs
- LangChain Basics
- LLM Applications
- AI Pipelines
- Output Parsing
- Pydantic Validation
- Real-world AI Workflows

---