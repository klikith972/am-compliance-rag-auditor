# 📊 GenAI Asset Management Compliance & Onboarding Auditor

A high-performance Generative AI Proof-of-Concept (PoC) designed to automate the auditing of mutual fund prospectuses, Scheme Information Documents (SIDs), and regulatory onboarding guidelines. This tool leverages a **Retrieval-Augmented Generation (RAG)** pipeline to help Product Development, Implementation, and Compliance teams instantly cross-reference operational questions against complex financial frameworks.

---

## 🚀 Core Features
* **Automated Document Parsing:** Extracts and structures text data directly from dense multi-page financial PDFs.
* **Contextual Search (RAG):** Uses an ephemeral vector database to index regulatory constraints, bypassing manual document navigation.
* **Intelligent Audit Analytics:** Provides highly objective, structured, and legally contextualized summaries to onboarding queries.
* **Enterprise Security Architecture:** Uses zero-retention runtime memory storage (In-Memory Ephemeral Store) and dynamic UI key input handling to eliminate hardcoded API credentials.

---

## 🛠️ The Tech Stack
* **Framework:** LangChain (Python)
* **LLM Engine:** Google Gemini 2.5 Flash via OpenRouter API Gateway
* **Vector Database:** ChromaDB (Configured as an `EphemeralClient` for local processing)
* **User Interface:** Streamlit (Web UI wrapper)
* **Data Processing:** PyPDF & Recursive Character Text Splitting

---

## 📂 Project Architecture
```text
am-compliance-rag-auditor/
│
├── data/
│   └── fund_guidelines.pdf       # Target Investment Prospectus / Policy Document
├── .gitignore                    # Ensures environment isolation
├── README.md                     # Project documentation & business blueprint
└── app.py                        # Main RAG architecture & Streamlit UI engine
