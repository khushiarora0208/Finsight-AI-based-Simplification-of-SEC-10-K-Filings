# Finsight: AI-based Simplification of SEC 10-K Filings  

## 📌 Overview  
Finsight is an AI-driven NLP system designed to simplify the analysis of **SEC 10-K filings** for publicly traded companies. It leverages **retrieval-augmented generation (RAG)** and **large language models (LLMs)** to extract, summarize, and generate accurate responses to financial queries, making financial data more accessible to analysts, investors, and researchers.  

## 🚀 Features  
- **Automated SEC 10-K Retrieval**: Uses the **SEC API** to fetch the latest filings.  
- **Key Section Summarization**: Extracts and simplifies important sections like **Risk Factors (1A)** and **Management Discussion (7)**.  
- **Financial Question Answering (QA)**: Provides contextual, real-time answers to user queries.  
- **Document Embeddings & Vector Search**: Utilizes **FAISS** for efficient information retrieval.  
- **Fine-tuned LLM**: Optimized **Meta-Llama-3-8B-instruct** using **LoRA** adapters for financial domain knowledge.  
- **Summarization Model**: Uses **Facebook BART** for generating concise, meaningful summaries.  

## 🏗️ Tech Stack  
- **NLP Models**: Meta-Llama-3-8B, Facebook BART  
- **Embedding Model**: BAAI/bge-large-en-v1.5  
- **Vector Database**: FAISS  
- **Frameworks**: LangChain, PyTorch  
- **API**: SEC API  
- **Frontend**: Android App  

## 📊 Dataset  
- **Financial QA 10K Dataset**  
  - **7,000 entries** covering company filings  
  - Contains **question, answer, context, stock ticker, and filing type**  
- **SEC 10-K Filings**  
  - Extracted via **SEC API**  
  - Key sections: Risk Factors (1A) & Management Discussion (7)  

## 🎯 Future Enhancements  
- Improve financial-specific QA accuracy.  
- Expand to additional SEC filings (e.g., **8-K, 20-F**).  
- Optimize model efficiency for mobile deployment.  
- Integrate real-time stock data analysis.  
