# 🦜🔗 LangChain Zero-to-Hero
> *Unleashing the power of LLMs, one chain at a time.*

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![LangChain](https://img.shields.io/badge/🦜_LangChain-0.1-green?style=for-the-badge)
![Groq](https://img.shields.io/badge/Powered_By-Groq_🚀-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Module_2_Uploaded-2ea44f?style=for-the-badge)

## 🚀 Mission Brief
> **Latest Update**: Module 2 (Memory & State) is now live! 🧠 ✨

Welcome to my **LangChain Learning Lab**! This repository documents my journey into the world of **LLM Orchestration**. Here, we break down complex AI concepts into bite-sized, executable Jupyter Notebooks.

Whether you're building simple chatbots or autonomous agents, this path covers it all.

---

## 🗺️ The Roadmap

### **Module 1: Foundations & Setup** 🐣
- [x] **[01_basics.ipynb](./01_basics.ipynb)**: Environment Setup, PromptTemplates, Simple Chains.

### **Module 2: Memory & State** 🧠
- [x] **[02_memory.ipynb](./02_memory.ipynb)**: Chat History, `ConversationBufferMemory`, `RunnableWithMessageHistory`.

### **Module 3: Data Connections (RAG)** 📚
- [ ] **04_rag_basics.ipynb**:
    - Document Loaders (Text, PDF)
    - Splitting & Chunking Text
    - Vector Stores & Embeddings
    - Retrieval Chains

### **Module 4: Chains & Flows** ⛓️
- [ ] **03_lcel_chains.ipynb**:
    - Sequential Chains
    - RunnableSequence (LCEL)
    - Piping components

### **Module 5: Agents & Tools** 🤖
- [ ] **05_agents.ipynb**:
    - Creating Custom Tools
    - Using Built-in Tools
    - Building an Agent (ReAct)

---

## 🛠️ Setup & Usage

1.  **Clone the Repo**
    ```bash
    git clone https://github.com/your-username/langchain-learning.git
    cd langchain-learning
    ```

2.  **Ignite the Environment**
    ```bash
    # Create virtual environment
    python -m venv venv
    
    # Activate (Windows)
    .\venv\Scripts\activate
    
    # Install dependencies
    pip install -r requirements.txt
    ```

3.  **Configure Secrets**
    Create a `.env` file and add your keys:
    ```ini
    OPENAI_API_KEY=sk-...
    GROQ_API_KEY=gsk_...
    ```

4.  **Launch!** 🚀
    Open VS Code or Jupyter Lab and start hacking.

---

## 🧪 Tech Stack
- **LangChain**: The framework for LLM apps.
- **Groq API**: Lightning-fast inference (Llama 3.1).
- **Jupyter**: For interactive experimentation.
- **Python-dotenv**: For managing secrets securely.

---

> *"The best way to predict the future is to invent it."* - Alan Kay
