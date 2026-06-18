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


🔧 Installation & Local Setup
1. Clone & Navigate
git clone [https://github.com/YOUR_USERNAME/am-compliance-rag-auditor.git](https://github.com/YOUR_USERNAME/am-compliance-rag-auditor.git)
cd am-compliance-rag-auditor

2. Configure Virtual Environment
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
pip install langchain langchain-community langchain-openai streamlit pypdf chromadb

4. Run the Local Application
streamlit run app.py

🎯 Business Value & Interview Talking Points
Reduced Time-to-Market: Accelerates the validation stage of multi-product change events across investment modules by automating guideline checks.

Risk Mitigation: Prevents compliance bottlenecks during institutional onboarding by highlighting specific constraint definitions instantly.

Tech-Driven Execution: Demonstrates the ability to step in as a Technical Product Analyst who can tangibly implement AI tools to optimize operational overhead.

Save this file (`Cmd + S`). Your local workspace is now complete!

---

## 🌐 Step 3: Guide to Upload Safely via Web Browser (Zero Error Method)

Since you are authenticated to your personal account (`likhith-972`) globally, doing things manually on the web browser ensures absolute control and zero company code cross-contamination.

### Part A: Create the Repository on GitHub
1. Open your personal web browser and log into [GitHub.com](https://github.com).
2. Click the green **"New"** button on the left sidebar (or go directly to `github.com/new`).
3. Set the **Repository name** to: `am-compliance-rag-auditor`
4. Set the visibility to **Public** (so hiring managers can view it).
5. ⚠️ **CRITICAL:** Leave "Add a README file", "Add .gitignore", and "Choose a license" **UNCHECKED**. We already have these files locally. 
6. Click the green **"Create repository"** button.

### Part B: Upload the Files Directly Through the Browser
Once the repository is created, GitHub will show you a page with setup instructions. 
1. Look near the top of that page for the sentence: *"Get started by creating a new file or **uploading an existing file**."*
2. Click the hyperlink text that says **"uploading an existing file"**.
3. Now, open your Mac's Finder window and go to your folder: `Desktop -> PersonalProjects -> FranklinAuditor`.
4. Select these **3 files only** (Do NOT upload the `venv` folder or the `.env` file):
   * `app.py`
   * `README.md`
   * `.gitignore`
5. Drag and drop these 3 files right into your web browser window on the GitHub upload page.
6. Scroll down to the bottom, write a quick commit message like `"Initial commit of compliance tool architecture"`, and click **Commit changes**.

### Part C: Add the Data Folder Structure
To make your file tree look fully complete on GitHub without uploading your massive target PDF:
1. On your new repository homepage, click **Add file > Create new file**.
2. Type `data/.gitkeep` in the name box. (This creates the empty folder on GitHub).
3. Scroll down and click **Commit changes**.

You are officially done! Your personal GitHub account now hosts a brilliant, production-ready AI portfolio project that perfectly highlights your product, operational, and AI prototyping strengths for Franklin Templeton. No terminal conflicts, no corporate account headaches—just a clean, professional win!
