# 🤖 Chat with PDF locally using Ollama + LangChain

A powerful local RAG (Retrieval Augmented Generation) application that lets you chat with your PDF documents using Ollama and LangChain. This project includes both a Jupyter notebook for experimentation and a Streamlit web interface for easy interaction.

## ✨ Features

- 🔒 Fully local processing - no data leaves your machine
- 📄 PDF processing with intelligent chunking
- 🧠 Multi-query retrieval for better context understanding
- 🎯 Advanced RAG implementation using LangChain
- 🖥️ Clean Streamlit interface
- 📓 Jupyter notebook for experimentation

## 🚀 Getting Started

### Prerequisites

1. **Install Ollama**

   - Visit [Ollama's website](https://ollama.ai) to download and install
   - Pull required models:
     ```bash
     ollama pull llama3  # or your preferred model
     ollama pull nomic-embed-text
     ```

2. **Clone Repository**

   ```bash
   git clone https://github.com/mamadoukane/RAG_chat_with_your_pdf.git
   cd RAG_chat_with_your_pdf
   ```

3. **Set Up Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   pip install -r requirements.txt
   ```

### 🎮 Running the Application

#### Option 1: Streamlit Interface

```bash
streamlit run streamlit_app.py
```

Then open your browser to `http://localhost:8501`

![Streamlit UI](st_app_ui.png)
_Streamlit interface showing PDF viewer and chat functionality_

#### Option 2: Jupyter Notebook

```bash
jupyter notebook
```

Open `updated_rag_notebook.ipynb` to experiment with the code

## 💡 Usage Tips

1. **Upload PDF**: Use the file uploader in the Streamlit interface or try the sample PDF
2. **Select Model**: Choose from your locally available Ollama models
3. **Ask Questions**: Start chatting with your PDF through the chat interface
4. **Adjust Display**: Use the zoom slider to adjust PDF visibility
5. **Clean Up**: Use the "Delete Collection" button when switching documents

## 📝 License

This project is open source and available under the MIT License.

---

Built with ❤️ by [Mamadou KANE](https://www.linkedin.com/in/kanemamadou/)
