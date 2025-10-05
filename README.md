# WatsonxRAG-PDF-Chatbot
**“RAG-powered chatbot to ask questions from PDF documents using IBM Watsonx.ai, LangChain, and Gradio.”

Perfect — you’ve basically built a **Retrieval-Augmented Generation (RAG) Chatbot using IBM Watsonx.ai and LangChain**, which uses **Mixtral-8x7B** for text generation and **Slate-125M** for embeddings.

Let’s give it a professional open-source structure 👇

---

## 🧠 **Project Name**

**WatsonxRAG-PDF-Chatbot**

---

## 📝 **README.md**

Here’s a complete, production-ready README you can put directly in your GitHub repository:

````markdown
# 🤖 WatsonxRAG-PDF-Chatbot

A Retrieval-Augmented Generation (RAG) chatbot powered by **IBM Watsonx.ai**, **LangChain**, and **Gradio**.  
This app allows users to **upload a PDF document** and **ask natural language questions** about its content.  
The chatbot retrieves relevant document chunks using **Chroma Vector DB** and answers using **Mixtral-8x7B-Instruct** hosted on IBM Watsonx.ai.

---

## 🚀 Features
- 📄 Upload any PDF document
- 💬 Ask natural-language questions about its content
- 🔍 Intelligent retrieval using Watsonx embeddings
- 🧩 Chunking with LangChain text splitter
- 🧠 Powered by IBM Watsonx.ai Foundation Models (LLM + Embeddings)
- 🌐 Simple Gradio web interface

---

## 🏗️ Tech Stack
- **IBM Watsonx.ai** – for LLM (`mistralai/mixtral-8x7b-instruct-v01`) and embeddings (`ibm/slate-125m-english-rtrvr`)
- **LangChain** – for RAG pipeline (retrieval, QA chain, chunking)
- **Chroma** – for vector storage
- **Gradio** – for the user interface
- **Python 3.10+**

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/WatsonxRAG-PDF-Chatbot.git
   cd WatsonxRAG-PDF-Chatbot
````

2. **Create and activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # (on Linux/Mac)
   venv\Scripts\activate      # (on Windows)
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set IBM Watsonx credentials**
   Create a `.env` file in the project root and add:

   ```bash
   WATSONX_API_KEY=<your_ibm_watsonx_api_key>
   WATSONX_URL=https://us-south.ml.cloud.ibm.com
   PROJECT_ID=skills-network
   ```

---

## ▶️ Running the Application

1. **Start the app**

   ```bash
   python app.py
   ```

2. **Access the UI**
   Open your browser and visit:

   ```
   http://0.0.0.0:7860
   ```

3. **Usage**

   * Upload a PDF file (e.g., research paper, report, manual)
   * Ask a question (e.g., “What are the main findings?”)
   * The chatbot retrieves and answers using document context.

---

## 🧩 Project Structure

```
WatsonxRAG-PDF-Chatbot/
│
├── app.py                # Main application script
├── requirements.txt      # Python dependencies
├── README.md             # Documentation
├── .env.example          # Sample environment variables
└── data/                 # (optional) Store PDFs or cache
```

---

## ⚙️ Requirements

```
ibm-watsonx-ai
langchain
langchain-ibm
langchain-community
chromadb
pypdf
gradio
python-dotenv
```

---

## 💡 Example Queries

* “Summarize the document.”
* “What are the key recommendations?”
* “List all important terms and definitions.”
* “Explain the methodology section.”

---

## 🌍 Deployment Options

You can deploy this on:

* **Local machine** (default)
* **IBM Cloud Code Engine**
* **Hugging Face Spaces**
* **Render / Vercel / AWS EC2**

---

## 📜 License

MIT License © 2025 [Your Name]

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

---

## 🧑‍💻 Author

**Sooraj Aryan**
AI Engineer & Research Enthusiast
💼 [LinkedIn](https://www.linkedin.com/) | 🌐 [GitHub](https://github.com/<your-username>)

````

---

## 🧾 **GitHub Repo Details**

- **Repo Name:** `WatsonxRAG-PDF-Chatbot`
- **Description:** “A Retrieval-Augmented Generation chatbot using IBM Watsonx.ai and LangChain that lets you chat with your PDFs.”
- **Topics/Tags:** `ibm-watsonx`, `rag`, `langchain`, `gradio`, `pdf-chatbot`, `mixtral`, `vectorstore`, `chromadb`, `ai`

---

## ⚡ **How to Run (Quick Summary)**
```bash
git clone https://github.com/<your-username>/WatsonxRAG-PDF-Chatbot.git
cd WatsonxRAG-PDF-Chatbot
pip install -r requirements.txt
python app.py
````

Then open 👉 [http://localhost:7860](http://localhost:7860)

---

Would you like me to generate the **`requirements.txt`** file for this project as well (with all exact compatible versions)?
