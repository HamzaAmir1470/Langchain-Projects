# 🦜🔗 LangChain Projects & Applications

Welcome to the **LangChain Projects** repository. This project showcases practical implementations, hands-on tutorials, and end-to-end AI applications built using **LangChain**, **Large Language Models (LLMs)**, **Vector Databases**, and **RAG (Retrieval-Augmented Generation)**.

---

## 📌 Project Overview

This repository serves as a comprehensive suite for building and experimenting with modern Generative AI and LLM workflows. Key areas covered include:

* 💬 **Chatbots & Conversational Agents**: Stateful conversational bots with memory management.
* 📚 **RAG Systems (Retrieval-Augmented Generation)**: Custom Q&A systems over PDFs, CSVs, and web pages.
* 🤖 **Autonomous AI Agents & Tools**: Intelligent agent workflows capable of decision-making and using custom tools/APIs.
* 🧠 **Prompt Engineering & Chains**: Sequential and parallel execution using LCEL (LangChain Expression Language).
* 🗂️ **Vector Embeddings & Stores**: Efficient semantic retrieval using ChromaDB, FAISS, or Pinecone.

---

## 🛠️ Tech Stack & Frameworks

* **Core Framework:** [LangChain](https://www.langchain.com/) / LangChain Community
* **Language:** Python 3.9+
* **LLM Providers:** OpenAI / Google Gemini / Hugging Face / Ollama (Local LLMs)
* **Vector Databases:** ChromaDB / FAISS / Pinecone
* **Deployment & UI (Optional):** Streamlit / Gradio / FastAPI

---

## 📁 Repository Structure

```text
Langchain-Projects/
│
├── 01_basics_and_chains/        # Fundamentals, Prompt Templates, Simple Chains
├── 02_rag_applications/         # RAG pipelines over custom documents (PDF, Text)
├── 03_agents_and_tools/         # Autonomous agents with custom tools & Web Search
├── 04_memory_and_chat/          # Conversational memory strategies & Chatbots
├── 05_vector_databases/         # Embeddings and indexing with ChromaDB/FAISS
│
├── requirements.txt             # Project dependencies
├── .env.example                 # Example environment variables setup
└── README.md                    # Repository documentation
```

---

## 🚀 Quick Start Guide

### 1. Clone the Repository

```bash
git clone https://github.com/HamzaAmir1470/Langchain-Projects.git
cd Langchain-Projects
```

### 2. Create a Virtual Environment

**On Linux / macOS:**

```bash
python3 -m venv venv
source venv/bin/activate
```

**On Windows:**

```cmd
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory by duplicating `.env.example`:

```bash
cp .env.example .env
```

Add your required API keys in `.env`:

```env
OPENAI_API_KEY=your_openai_api_key_here
GOOGLE_API_KEY=your_google_gemini_api_key_here
TAVILY_API_KEY=your_tavily_search_api_key_here
PINECONE_API_KEY=your_pinecone_api_key_here
```

---

## 💡 Usage Examples

### Running a RAG Pipeline / App

```bash
python 02_rag_applications/pdf_qa_bot.py
```

### Running Streamlit Applications (if applicable)

```bash
streamlit run app.py
```

---

## 🤝 Contributing

Contributions are welcome. If you want to add new LangChain projects, fix issues, or improve documentation:

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/AwesomeFeature`
3. Commit your changes: `git commit -m 'Add some AwesomeFeature'`
4. Push to the branch: `git push origin feature/AwesomeFeature`
5. Open a pull request.

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👤 Author

**Hamza Amir**

* **GitHub:** [@HamzaAmir1470](https://github.com/HamzaAmir1470)

---

⭐ *If you find this repository helpful, please consider giving it a star.*
