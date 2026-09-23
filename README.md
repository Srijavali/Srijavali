<div align="center">

# Hi, I'm Sri Javali 👋

### Software Engineer • AI/ML Researcher • AI Systems Builder

<p>
  I build software that sits at the intersection of
  <b>full-stack engineering</b>, <b>AI/ML</b>, and <b>research</b>.
</p>

<p>
  <a href="https://www.linkedin.com/in/sri-javali-kotha-b82619349">LinkedIn</a> •
  <a href="https://github.com/Srijavali">GitHub</a> •
  <a href="https://kotha-sri-javali-portfolio.vercel.app/">Portfolio</a>
</p>

</div>

---

## 🧭 Who I Am

I'm a Computer Science Engineering student and **Research Intern at IIIT Hyderabad** who enjoys taking problems from:

**idea → research → architecture → implementation → evaluation → deployment**

My work spans three connected areas:

### 💻 Software Engineering

I build practical applications and backend systems using **JavaScript/TypeScript, React, Next.js, Node.js, Express.js, Python, FastAPI, REST APIs, PostgreSQL, MongoDB, WebSockets, and Git**.

I'm especially interested in understanding how the layers of a system fit together — from a frontend interaction and API contract to authentication, backend services, databases, asynchronous processing, testing, and deployment.

### 🤖 AI / ML Engineering

I build AI systems around **Computer Vision, Vision Transformers, YOLO, LLMs, RAG, agentic workflows, OCR, semantic search, and AI evaluation**.

I care about more than getting a model to work once. I focus on **data quality, evaluation, reliability, latency, cost, grounding, and how the model behaves inside the larger software system**.

### 🔬 Research

I approach engineering decisions with a research mindset.

When a problem does not have an obvious solution, I don't want to jump to the first implementation. I investigate the alternatives, understand the constraints, test assumptions, compare trade-offs, and then choose an approach that I can justify.

That mindset has shaped my work in:

- LLM security and guardrails
- Prompt injection and retrieval-level attacks
- Trust-aware AI systems
- RAG reliability and grounding
- Computer Vision
- AI-assisted education
- Intelligent agricultural advisory systems

---

# 🚀 What I Build

```text
                SOFTWARE ENGINEERING
                       │
        ┌──────────────┼──────────────┐
        │              │              │
      Frontend       Backend        Data
        │              │              │
 React / Next.js   Node / FastAPI   PostgreSQL
 TypeScript        REST / WS        MongoDB
                   Auth / APIs      Vector DBs
        │              │              │
        └──────────────┼──────────────┘
                       │
                       ▼
                AI / ML SYSTEMS
                       │
        ┌──────────────┼──────────────┐
        │              │              │
   Computer Vision    LLMs           RAG
   ViT / YOLO        Agents       Retrieval
   MediaPipe         Tool Calls    Guardrails
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                RESEARCH & EVALUATION




🛠️ Tech Stack
Languages

Python Java JavaScript TypeScript C SQL

Software & Web Engineering

React Next.js Node.js Express.js FastAPI REST APIs WebSockets

HTML CSS Git GitHub Postman

Databases & Data

PostgreSQL MongoDB ChromaDB FAISS

CRUD Data Modeling Indexing Semantic Search

AI / ML

PyTorch TensorFlow Hugging Face Transformers

Vision Transformers YOLO CNNs Computer Vision

NLP LLMs RAG Vector Embeddings

AI Systems & Research

Agentic AI Tool Calling Prompt Engineering

Context Engineering AI Guardrails Trust Scoring

LLM Evaluation Retrieval Pipelines AI Safety

Engineering Practices

Unit Testing Integration Testing Debugging

API Testing Code Reviews Pull Requests

Modular Architecture Background Processing Queues Retries Idempotency

💼 Current Experience
PM Accelerator — Full Stack (AI/ML) Developer Intern
Frontend Lead • MatchBook

I'm currently one of the frontend leads building MatchBook from scratch.

My work includes:

Building application workflows with Next.js and TypeScript
Developing Buyer Onboarding, Buyer Profile, and Seller Profile
Designing reusable frontend components and application flows
Connecting frontend workflows with backend services through API wiring
Working with Supabase for authentication, sessions, and frontend data workflows
Mapping frontend data to backend contracts and handling request/response flows
Debugging TypeScript, API integration, authentication, environment, and integration issues
Collaborating through Git branches, commits, pull requests, and code reviews

This experience has strengthened how I think about real software systems, not just isolated features.

🔬 Research Experience
Research Intern — IIIT Hyderabad

My research work has involved Computer Vision, deep learning, model evaluation, and real-world deployment constraints.

I have worked on:

YOLO-based object detection
Vision Transformer pipelines
Real-world datasets and preprocessing
Robustness under occlusions and density variations
Accuracy vs. latency trade-offs
Reliability considerations for safety-oriented systems
Current Research

I'm also working on LLM Security, RAG Security, and Trustworthy AI.

The work explores:

Prompt injection detection
Retrieval-level attacks
Sensitive-information disclosure
Trust scoring
Retrieval risk assessment
Policy enforcement
Model-agnostic guardrails
Explainable security decisions
LoRA-based lightweight adaptation

My goal is to understand not only whether an AI system produces an answer, but whether the system should trust, retrieve, generate, or expose that answer in the first place.

🌟 Work I'm Proud Of
🧠 JoyVerse — AI-Powered Cognitive Learning Platform

JoyVerse is one of the projects I'm most proud of because it required combining product thinking, full-stack engineering, computer vision, and AI into one system.

It is a gamified learning platform designed for children with dyslexia, with separate workflows for children, parents, therapists, and a super-admin.

What we built
Child-facing interactive games
Parent dashboard
Therapist dashboard
Super-admin dashboard
Behavioral and performance analytics
Real-time communication
AI-assisted interaction

The games were designed around different capabilities such as memory, word recognition, reflex-based interaction, and confidence-related activities.

Performance signals from these interactions could then be used to give therapists a more useful picture of how a child was engaging with the activities.

AI + Privacy-Aware Interaction

We used:

Vision Transformers
MediaPipe Face Mesh
Facial landmark extraction
Real-time interaction pipelines

MediaPipe was used to extract facial landmarks and derive expression-related signals that could influence the game's animations and interaction.

The interesting part for me was not using AI for the sake of AI. It was figuring out how AI, frontend interaction, backend services, and reporting could work together as one coherent product.

Stack

React Node.js Express.js MongoDB WebSockets OAuth Vision Transformers MediaPipe

🎥 Project Demo

🌿 Plant Disease Detection & Advisory System

An end-to-end AI system combining Computer Vision + RAG + external data sources for agricultural disease detection and advisory support.

Highlights
~97.6% disease classification accuracy
Vision Transformer classifier
FastAPI services
RAG-based knowledge retrieval
OCR pipelines
Weather API integration
Government-source knowledge synchronization
Multilingual advisory workflows

One of the most interesting engineering decisions involved keeping the advisory layer grounded in retrieved knowledge rather than introducing another generative model unnecessarily.

When the trusted source published updated precaution documents without providing a public API, I explored several alternatives — including webhooks, API access, polling, RSS-based change detection, and content hashing — and designed a mechanism to synchronize updated knowledge into the retrieval pipeline while balancing freshness, latency, reliability, and system complexity.

That experience reinforced one of the principles I care about most:

Good engineering is not choosing the most sophisticated solution. It is choosing the solution you can justify under the real constraints of the system.

Stack

Python FastAPI Streamlit Vision Transformers RAG LangChain ChromaDB OCR Weather APIs RSS

🎥 Project Demo

🤖 Atlas AI — Agentic Financial Intelligence Assistant

A backend-heavy AI system built around persistent context, structured tool calling, PostgreSQL, scheduling, and asynchronous workflows.

Highlights
Persistent user context
LLM tool calling
PostgreSQL-backed state
Scheduling
Background processing
Queueing and retries
Idempotent workflows
Multimodal preprocessing
149 automated tests
Stack

Python FastAPI PostgreSQL Pytest LLM Tool Calling Telegram

🛡️ LLM Security & Trustworthy AI
Current Research Direction
User Query
    ↓
Intent Analysis
    ↓
Risk Detection
    ↓
Retrieval Risk Assessment
    ↓
Context / Sensitivity Analysis
    ↓
Trust Scoring
    ↓
Policy Enforcement
    ↓
Controlled Generation

I'm exploring architectures that combine:

Deterministic rules
Risk aggregation
Model-based reasoning
Retrieval governance
Trust scoring
Explainable decisions

The focus is to make AI systems more reliable, interpretable, and resistant to adversarial behavior.

🧪 How I Think About Engineering

I tend to ask questions before I commit to an implementation:

What is actually causing the problem?

What assumptions are we making?

Can the current architecture solve it without adding another component?

What happens to latency, cost, reliability, and maintainability?

What happens when an external dependency changes?

How do we validate that the solution actually works?

What evidence would make me change my decision?

This is probably the part of engineering I enjoy most — understanding the system deeply enough to make a decision I can defend.

📈 Currently Exploring

Agentic AI LangGraph MCP

Multi-Agent Systems AI Evaluation

Production LLM Engineering

LLM Security RAG Reliability

🌱 Open Source
Merged pull requests into codeforces-contest-scraper
Improved contributor documentation and onboarding
Added unit tests and bug fixes
Collaborated through Git, pull requests, and code reviews
📫 Let's Connect

Email

kothasrijavali@gmail.com

LinkedIn

linkedin.com/in/sri-javali-kotha-b82619349

GitHub

github.com/Srijavali

Portfolio

kotha-sri-javali-portfolio.vercel.app

<div align="center">
Building software. Researching deeply. Making AI useful.
</div> ```
