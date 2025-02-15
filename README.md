# RAG Document Q&A with Ollama and Qwen-2.5

## 📌 Overview

This project is a **Retrieval-Augmented Generation (RAG) based Document Q&A system** that leverages:

- **Ollama Embeddings** for vector representations
- **FAISS** for efficient vector search
- **LangChain** for chaining retrieval and generation steps
- **Groq's Qwen-2.5-32B** model for accurate text generation
- **Streamlit** for a user-friendly interface

With this system, users can **upload research papers in PDF format** and ask questions about their content. The model retrieves relevant chunks from the documents and generates precise responses.

---

## 🚀 Features

✅ Load and process research papers dynamically\
✅ Generate vector embeddings using **Ollama**\
✅ Efficient similarity search with **FAISS**\
✅ Retrieve document chunks relevant to the query\
✅ Generate accurate responses using **Qwen-2.5-32B**\
✅ Streamlit UI for interactive Q&A\
✅ Real-time response time tracking

---

## 📦 Tech Stack

- **Python 3.10**
- **LangChain**
- **FAISS**
- **Ollama Embeddings**
- **Streamlit**
- **Groq API (Qwen-2.5-32B)**
- **PyPDFLoader**

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/laavanjan/RAG-Document-Q-A-With-Ollama-And-qwen-2.5.git
cd RAG-Document-Q-A-With-Ollama-And-qwen-2.5
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables

Create a `.env` file in the project directory and add your **Groq API Key**:

```env
GROQ_KEY=your_api_key_here
```

### 5️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

---

## 📂 Project Structure

```
├── research_papers/          # Folder containing PDF documents
├── app.py                    # Main Streamlit application
├── requirements.txt          # Required dependencies
├── .env                      # Environment variables (not shared)
└── README.md                 # This documentation
```

---

## 🎯 How It Works

1️⃣ Upload research papers (PDFs are automatically processed).\
2️⃣ The system extracts text and generates **vector embeddings**.\
3️⃣ User submits a question via Streamlit UI.\
4️⃣ The **retriever fetches the most relevant document chunks**.\
5️⃣ Qwen-2.5-32B generates an answer **based on the retrieved context**.\
6️⃣ Users can explore document similarity search results.

---

## 📸 Screenshots



---

## 🛠 Future Enhancements

🔹 Add support for more document formats (TXT, DOCX)\
🔹 Improve response quality with fine-tuned embeddings\
🔹 Deploy as a web service with **FastAPI**\
🔹 Store and retrieve historical queries for analysis

---

## 🤝 Contribution

Contributions are welcome! Feel free to submit issues and pull requests.

---

## 📜 License

This project is licensed under the **GPL License**.

---

⭐ **If you like this project, don't forget to star the repository!** ⭐

