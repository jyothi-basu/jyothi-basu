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
* MySQL, PostgreSQL, SQLite, MongoDB, and Redis
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
A **production-style FastAPI investment portfolio application** featuring a provider-agnostic AI assistant powered by **LangGraph, LangChain, Retrieval-Augmented Generation (RAG), and the Model Context Protocol (MCP)**.
Instead of answering questions from a single source, the assistant combines **live portfolio data**, **uploaded financial documents**, and **application knowledge** within the same conversation while keeping user and conversation context securely managed on the backend.

#### AI Knowledge Sources
The assistant retrieves information from three independent backend knowledge sources through tool calling:
* **Portfolio data** — Holdings, BUY/SELL transactions, Demat accounts, portfolio summaries, stock prices, and investment calculations through authenticated backend tools.
* **Uploaded financial documents** — Retrieval-Augmented Generation (RAG) using ChromaDB with document-grounded source citations and chat-scoped document isolation.
* **Application knowledge** — A dedicated tool that answers questions about how to use the application and its features.
The same RAG pipeline powers both the web AI assistant and the **MCP server**, allowing external AI clients such as **Codex CLI** to securely search uploaded documents using the existing backend implementation.

#### Highlights
* Multi-Demat investment portfolio management.
* BUY/SELL transaction management with automatic holdings and portfolio calculations.
* Layered backend architecture (**Routes → Services → Repository → AI**).
* **JWT authentication** with access and refresh tokens stored in secure cookies.
* Provider-agnostic AI architecture supporting the native Gemini SDK and OpenAI-compatible LLM providers.
* **LangGraph orchestration** for AI agent, tool execution, conversation title generation, and persistence.
* Shared AI tool registry reused by both the web assistant and MCP.
* Configurable embeddings using OpenAI-compatible providers or local SentenceTransformer models.
* Persistent user-specific chat history with automatic conversation titles.
* Financial document upload, validation, storage, and deletion.
* ChromaDB-powered semantic search with Retrieval-Augmented Generation (RAG).
* Trusted backend context that prevents AI models from receiving internal `user_id` or `chat_id`.
* User- and chat-scoped document retrieval with grounded source citations.
* **Model Context Protocol (MCP)** with Streamable HTTP, Personal Access Token (PAT) authentication, conversation selection, and shared backend tools.
* Automated **pytest** test suite covering authentication, portfolio management, document workflows, AI tools, and MCP integration.

#### Tech Stack
**Backend:** FastAPI, Python
**AI:** LangGraph, LangChain, Gemini SDK, OpenAI-compatible LLM providers
**RAG:** ChromaDB, SentenceTransformers, OpenAI-compatible embeddings
**Authentication:** JWT (Access & Refresh Tokens), Personal Access Tokens (PAT)
**Database:** SQLite
**Protocols:** Model Context Protocol (Streamable HTTP and STDIO)
**Testing:** pytest

#### Architecture Highlights
* **Layered Architecture:** Routes → Services → Repository → AI.
* **Provider-Agnostic AI Layer:** Switch between Gemini SDK and OpenAI-compatible providers without changing business logic.
* **Trusted Context Isolation:** The backend injects authenticated user and conversation context; AI tools never receive internal identifiers.
* **Shared AI/MCP Tools:** The same tool implementations power both the web assistant and external MCP clients.

#### Planned Enhancements
* SQLAlchemy ORM migration with Alembic migrations.
* PostgreSQL support for production deployments.
* Email verification using Resend.
* Additional financial analysis tools (PV, FV, NPV, CAGR, SIP, etc.).
* Expanded pytest integration and CI workflow.
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
