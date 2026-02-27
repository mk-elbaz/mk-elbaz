# Hi there, I'm Mohammed Elbaz 👋

**Software Engineer | GenAI & DevOps | Internal Tooling & DevEx**

Welcome to my GitHub! I am a Software Engineer based in Cairo, Egypt, specializing in the intersection of **Generative AI** and **DevOps**. My passion lies in building Developer Experience (DevEx) tools, architecting scalable serverless environments, and orchestrating autonomous AIOps agents to automate the heavy lifting of software engineering.

While much of my daily work involves hardening enterprise infrastructure and building internal AI tools on air-gapped, self-hosted systems, this profile showcases my open-source implementations of production-ready GenAI and DevOps architectures.

---

### 🚀 Featured Architectures & Projects

I build tools that solve actual engineering bottlenecks—from "review fatigue" to complex codebase onboarding and automated incident response.

#### 🛡️ [CloudWatch AI Sentinel](https://github.com/mk-elbaz/CloudwatchSentinel)
**AIOps & Infrastructure Observability**
An intelligent AWS monitoring agent that automates the investigative phase of Site Reliability Engineering (SRE).
* **Architecture:** Python, Boto3, MySQL, Streamlit, Docker.
* **Key Features:** Uses LLMs for semantic log analysis to identify root causes (RCA), automatically groups anomalies, and scans AWS infrastructure for security/compliance risks (e.g., wildcards in IAM, public S3 buckets).

#### 🕸️ [RepoChat](https://github.com/mk-elbaz/RepoChat)
**AST-Aware Codebase Knowledge Graph**
A sophisticated RAG tool designed to help developers navigate complex GitLab repositories using structural code analysis.
* **Architecture:** Python, LangChain, Qdrant (Vector DB), Tree-sitter, Chainlit.
* **Key Features:** Uses **AST-based chunking** (splitting code by functions/classes rather than arbitrary tokens), constructs Knowledge Graphs to map callers/callees, and features intelligent routing between models (GPT-4o for chat, o4-mini/o3 for deep reasoning).

#### ⚡ [HybridRAG (RAGMaster)](https://github.com/mk-elbaz/RAGMaster)
**Production-Ready Hybrid Search RAG**
A high-performance document retrieval system combining keyword precision with semantic understanding.
* **Architecture:** Python, FAISS (Dense), BM25 (Sparse), Prometheus, Chainlit.
* **Key Features:** Implements Alpha-tuned hybrid search fusion, semantic/hierarchical chunking strategies, and real-time observability via Prometheus metrics to monitor query latency and token costs. 

#### 🐛 [AI Code Reviewer](https://github.com/mk-elbaz/AICodeReviewer)
**Automated GitLab MR Analysis**
A VS Code Extension acting as a first-line defense against bugs, style inconsistencies, and security flaws in Merge Requests.
* **Architecture:** TypeScript, VS Code Extension API, Axios.
* **Key Features:** Multi-LLM support (Groq for 2-5s inference, OpenAI for complex reasoning, Hugging Face for open-source models), secure system-level secret storage, and a seamless GitLab API integration.

---

### 🛠️ My Tech Stack

**Generative AI & LLMOps:**
![LangChain](https://img.shields.io/badge/LangChain-FFFFFF?style=flat-square&logo=langchain&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-000000?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-D32F2F?style=flat-square)
`AST-Chunking (Tree-sitter)` | `Hybrid Search (BM25)` | `Knowledge Graphs`

**Cloud, DevOps & Observability:**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
`Boto3` | `GitLab CI/CD` | `Bref (Serverless)` 

**Languages & Interfaces:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
`Streamlit` | `Chainlit` | `VS Code API`

---

### 📈 Continuous Learning
* 🎓 **Specialization:** Generative AI for Software Developers (IBM)
* 🎓 **Specialization:** DevOps on AWS (AWS)

### 📫 Let's Connect
I'm always open to discussing GenAI orchestration, AIOps, or how to build better internal developer tools.
* 💼 **LinkedIn:** [linkedin.com/in/mk-elbaz](https://linkedin.com/in/mk-elbaz)
* 📧 **Email:** mk.elbaz9248@gmail.com
