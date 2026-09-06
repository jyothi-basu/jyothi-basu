# Jyothi Basu

Backend-focused Python developer building APIs, authentication systems, layered backend applications, and AI-powered backend systems.

Currently interning at FamilyShell as a Software Engineering Trainee Intern, gaining hands-on experience with modern backend workflows, team-based product development, debugging, and feature development on a production-oriented application.

---

## Technical Focus

* Python
* FastAPI and Flask
* REST API design
* Authentication and authorization
* JWT and protected routes
* MySQL, SQLite, MongoDB, and Redis
* Docker and containerized development
* RAG and vector search
* LangChain and tool calling
* Input validation and business rules
* Layered architecture
* Git, pull requests, and code review
* Testing and debugging

---

## Featured Work

### FamilyShell Internship

**Software Engineering Trainee Intern at FamilyShell**

Website: [https://familyshell.com/](https://familyshell.com/)

Currently gaining hands-on software engineering experience through technical training and development work on a production-oriented application.

**Technologies and areas of experience:**

* FastAPI
* MongoDB
* Redis
* Docker
* Flutter
* Authentication
* File uploads
* Cloudflare R2 storage

**Engineering work:**

* Investigating and resolving backend and frontend issues across FastAPI APIs, MongoDB, Redis, Flutter, authentication, file uploads, and cloud storage.
* Reproducing bugs, analyzing application and backend logs, tracing frontend-backend data flows, identifying root causes, implementing fixes, and validating them through testing.
* Working on the Health Records feature, including attachment upload, multi-file handling, Flutter Web compatibility, filename preservation, legacy-data compatibility, attachment viewing, and cloud-storage integration.
* Collaborating with the development team to test fixes, document bugs, and improve application functionality.

---

### Inventory Management API
Production-style Flask REST API for managing inventory with MySQL, JWT authentication, role-based authorization, and layered backend architecture.

#### Highlights

* Full CRUD operations
* Secure signup and login with bcrypt and JWT
* Admin/staff route permissions
* Input validation and structured error responses
* Layered backend architecture
* MySQL database
* Environment-based configuration
* Deployed on Render
* MySQL hosted on AlwaysData

**Repository:**
[https://github.com/jyothi-basu/inventory-management-api](https://github.com/jyothi-basu/inventory-management-api)

**Live API:**
[https://inventory-management-api-4ikv.onrender.com/](https://inventory-management-api-4ikv.onrender.com/)

---

### Investment Portfolio Tracker
A **production-style FastAPI investment portfolio application** featuring a provider-agnostic, multi-source AI assistant powered by **LangChain, Retrieval-Augmented Generation (RAG), and the Model Context Protocol (MCP)**.
Instead of answering questions from a single source, the assistant combines live portfolio data, uploaded financial documents, and application knowledge within the same conversation.

#### AI Knowledge Sources

* **Portfolio data** — Holdings, BUY/SELL transactions, Demat accounts, portfolio summaries, and investment calculations through backend tools.
* **Uploaded financial documents** — Retrieval-Augmented Generation (RAG) using ChromaDB with document-grounded source citations.
* **Application knowledge** — A dedicated tool that answers questions about how to use the application.

The same RAG pipeline powers both the web AI assistant and the **MCP STDIO server**, allowing external AI clients such as **Codex CLI** to search uploaded financial documents without duplicating backend logic.

#### Highlights

* Multi-Demat investment portfolio management.
* BUY/SELL transaction management and portfolio calculations.
* Layered FastAPI backend architecture with route, service, repository, and AI layers.
* Provider-agnostic AI architecture supporting native Gemini SDK and OpenAI-compatible LLM providers.
* Configurable embeddings using OpenAI-compatible providers or local SentenceTransformer models.
* Persistent chat history with user-specific conversations.
* Financial document upload, validation, and storage.
* ChromaDB-powered semantic search with Retrieval-Augmented Generation (RAG).
* LangChain tool-calling AI assistant with multi-tool orchestration.
* Trusted server-side request context for authenticated document retrieval.
* User- and chat-scoped document retrieval with source citations.
* MCP STDIO server exposing document search to external AI clients while reusing the existing RAG backend.

#### Tech Stack

**Backend:** FastAPI, Python

**AI:** LangChain, Gemini SDK, OpenAI-compatible providers

**RAG:** ChromaDB, SentenceTransformers / OpenAI-compatible embeddings

**Database:** SQLite

**Protocol:** Model Context Protocol (STDIO)

#### Project Status

Current release: **v0.5.0 — FastAPI Backend Migration**

Next planned milestones:

* MCP SSE server.
* LangGraph agent orchestration.
* Present Value (PV) and Net Present Value (NPV) analysis.

**Repository:**
[https://github.com/jyothi-basu/investment-portfolio-tracker](https://github.com/jyothi-basu/investment-portfolio-tracker)

---

## Other Projects

### Expense Tracker

Command-line expense management application built as part of Python coursework.
**Repository:**
[https://github.com/satyamagrawal28/expanse-tracker-project](https://github.com/satyamagrawal28/expanse-tracker-project)

### Python Fundamentals Coursework

Collection of structured assignments covering core Python concepts.

**Repository:**
[https://github.com/jyothi-basu/visionaid-python-class-assignments](https://github.com/jyothi-basu/visionaid-python-class-assignments)

---

## Current Direction

* Strengthening Python backend development with Flask and FastAPI
* Building real-world experience with SQL and NoSQL databases, caching, and APIs
* Improving Docker and deployment skills
* Developing practical experience with RAG and tool-calling AI systems
* Improving testing, debugging, and code quality
* Growing through internship-based product development

---

## Education

**MBA — Systems Specialization**
Sathyabama Institute of Science and Technology, Chennai

---

## Connect

**LinkedIn:**
[https://linkedin.com/in/jyothi-basu-chodavarapu](https://linkedin.com/in/jyothi-basu-chodavarapu)

**Email:**
[jyothibasuchodavarapu@gmail.com](mailto:jyothibasuchodavarapu@gmail.com)
