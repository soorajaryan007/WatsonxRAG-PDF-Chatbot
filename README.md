Got it! Since you’ve already deployed your `qobot.py` on Render (free version), we can **edit your README and instructions** to reflect that deployment and make it more deployment-friendly. Here's a polished version tailored for your setup:

---

# 🤖 WatsonxRAG-PDF-Chatbot

A **Retrieval-Augmented Generation (RAG) chatbot** powered by **IBM Watsonx.ai**, **LangChain**, and **Gradio**.
Upload a PDF document and ask natural-language questions about it. The bot retrieves relevant document chunks using **Chroma Vector DB** and answers using **Mixtral-8x7B** on IBM Watsonx.ai.

---

## 🚀 Features

* 📄 Upload PDF documents
* 💬 Ask questions in natural language
* 🔍 Document retrieval using Watsonx embeddings
* 🧩 LangChain text chunking
* 🧠 Watsonx.ai LLM + embeddings
* 🌐 Gradio web interface
* ☁️ Deployed on **Render Free Tier**

---

## 🏗️ Tech Stack

* **IBM Watsonx.ai** – LLM (`mistralai/mixtral-8x7b-instruct-v01`) + embeddings (`ibm/slate-125m-english-rtrvr`)
* **LangChain** – RAG pipeline
* **Chroma** – Vector database
* **Gradio** – UI
* **Python 3.10+**

---

## 📦 Installation (for local development)

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/WatsonxRAG-PDF-Chatbot.git
   cd WatsonxRAG-PDF-Chatbot
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux / Mac
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set IBM Watsonx credentials in a `.env` file:

   ```bash
   WATSONX_API_KEY=<your_ibm_watsonx_api_key>
   WATSONX_URL=https://us-south.ml.cloud.ibm.com
   PROJECT_ID=<your_project_id>
   ```

---

## ▶️ Running Locally

```bash
python qobot.py
```

Then open 👉 [http://localhost:7860](http://localhost:7860)

---

## 🌐 Access via Render

Since your bot is deployed on Render (free plan), you can share the **public Render URL**:

```
https://watsonxrag-pdf-chatbot-1.onrender.com/
```

Users can **upload PDFs and chat directly** in the browser without installing anything.

> ⚠️ Free Render apps **sleep after 15 minutes of inactivity**. Users may need to refresh if the app is idle.

---

## 🧩 Project Structure

```
WatsonxRAG-PDF-Chatbot/
│
├── qobot.py             # Main application script
├── requirements.txt     # Python dependencies
├── README.md            # Documentation
├── .env.example         # Sample environment variables
└── data/                # (optional) PDFs / cache
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
* “List all key findings.”
* “Explain the methodology section.”
* “What are the main recommendations?”

---

## 🌍 Deployment Options

* **Render** (free or paid) ✅
* **Local machine**
* **Hugging Face Spaces**
* **Vercel / AWS EC2**

---

## 📜 License

MIT License © 2025 **Sooraj Aryan**

---

## 🤝 Contributing

Pull requests welcome! For major changes, open an issue first.

---

