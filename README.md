# Startup_Bliueprint_Generator
AI-powered agent built with IBM watsonx.ai that transforms startup ideas into actionable business blueprints, including business models, revenue plans, legal checklists, and funding strategies, using Granite LLM and vectorized documents.


The **Startup Blueprint Generator** is an AI‑powered virtual consultant that transforms raw startup ideas into **comprehensive, actionable business blueprints**.

Built using **IBM watsonx.ai**, **Granite LLM**, and **vectorized document retrieval (RAG)**, this project takes user inputs like **idea, industry, budget, and location** and generates a structured startup plan referencing **real‑world documents** (e.g., **Startup India guides, funding scheme guidelines, and business model templates**).

---

## Features
- **Complete Startup Blueprints** including:
  - Idea Summary
  - Business Model (value proposition, customer segments, key activities)
  - Revenue Model (pricing, cost structure, revenue streams)
  - Market Research & Competitor Insights
  - Legal & Compliance Checklist (for India)
  - Funding & Go‑to‑Market Strategy
- **Vectorized Documents (RAG):** Uses government policies & templates for authentic insights.
- **PDF Export:** Converts generated blueprints into a professional PDF report.
- **Notebook & API:** Run as a Jupyter notebook or integrate via deployed API endpoint.

---

## Tech Stack
- **IBM watsonx.ai** (Granite LLM)
- **Agent Lab + Vector Store** (Milvus / In-memory)
- **Watson Studio Notebooks** (Python 3.11)
- **FPDF** for PDF generation

---

## Setup & Usage

### 1. Clone this repository
```bash
git clone https://github.com/your-username/Startup-Blueprint-Generator.git
cd Startup-Blueprint-Generator
