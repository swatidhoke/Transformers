# 🤖 Transformers Learning Journey

This repository contains my notes, code examples, experiments, and projects while learning Transformer architectures and Large Language Models (LLMs).

## 🎯 Goals

- Understand the evolution from RNNs and LSTMs to Transformers
- Learn the Attention Mechanism and Self-Attention
- Build Transformer components from scratch
- Explore BERT, GPT, and modern LLM architectures
- Fine-tune pretrained models
- Implement Retrieval-Augmented Generation (RAG)
- Prepare for AI/ML and LLM engineering interviews

---

## 📚 Course Roadmap

### Module 1: Foundations
- Traditional NLP
- Bag of Words
- TF-IDF
- Word Embeddings
- RNNs and LSTMs
- Limitations of sequential models

### Module 2: Attention Mechanism
- Query, Key, Value
- Scaled Dot Product Attention
- Self-Attention
- Attention Visualization

### Module 3: Transformer Architecture
- Encoder
- Decoder
- Multi-Head Attention
- Feed Forward Networks
- Residual Connections
- Layer Normalization

### Module 4: Positional Encoding
- Why Position Matters
- Sinusoidal Positional Encoding
- Learned Positional Embeddings

### Module 5: BERT
- Encoder-only Architecture
- Masked Language Modeling (MLM)
- Next Sentence Prediction (NSP)
- Text Classification

### Module 6: GPT
- Decoder-only Architecture
- Autoregressive Generation
- Next Token Prediction
- Text Generation

### Module 7: Hugging Face Transformers
- Pipelines
- Tokenizers
- Model Loading
- Inference

### Module 8: Fine-Tuning
- Transfer Learning
- PEFT
- LoRA
- Custom Datasets

### Module 9: Embeddings & Vector Databases
- Sentence Embeddings
- Similarity Search
- FAISS
- ChromaDB

### Module 10: Retrieval-Augmented Generation (RAG)
- Chunking
- Embeddings
- Retrieval
- Prompt Construction

### Module 11: LLM Training Concepts
- Pretraining
- Fine-Tuning
- Instruction Tuning
- RLHF

### Module 12: Production LLM Applications
- Prompt Engineering
- Agents
- Tool Calling
- Evaluation & Monitoring

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Transformers
- Hugging Face
- Datasets
- Sentence Transformers
- FAISS
- ChromaDB
- LangChain
- LlamaIndex

---

## 📂 Repository Structure

```text
transformers-learning/
│
├── notebooks/
│   ├── 01_attention_basics.ipynb
│   ├── 02_self_attention.ipynb
│   ├── 03_transformer_architecture.ipynb
│
├── projects/
│   ├── sentiment_analysis/
│   ├── text_generation/
│   ├── rag_chatbot/
│
├── datasets/
│
├── notes/
│   ├── attention.md
│   ├── bert.md
│   ├── gpt.md
│
├── src/
│   ├── attention.py
│   ├── transformer.py
│
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/swatidhoke/Transformers.git

cd Transformers

pip install -r requirements.txt
```

---

## 📦 Recommended Libraries

```bash
pip install torch transformers datasets accelerate
pip install sentence-transformers
pip install faiss-cpu chromadb
pip install langchain llama-index
```

---

## 🧪 Sample Code

```python
from transformers import pipeline

classifier = pipeline("sentiment-analysis")

result = classifier("Transformers are amazing!")
print(result)
```

---

## 🎓 Learning Resources

### Papers
- Attention Is All You Need
- BERT: Pre-training of Deep Bidirectional Transformers
- Language Models are Few-Shot Learners

### Courses
- Stanford CS224N
- Stanford CS25
- Hugging Face NLP Course

---

## 📈 Progress Tracker

- [x] NLP Basics
- [x] Attention Mechanism
- [ ] Transformer Architecture
- [ ] BERT
- [ ] GPT
- [ ] Fine-Tuning
- [ ] RAG
- [ ] Agentic AI
- [ ] Production Deployment

---

## 🎯 Future Projects

- Sentiment Analysis
- Document Q&A System
- RAG Chatbot
- AI Research Assistant
- Multi-Agent AI System

---

## 📜 License

This repository is for educational and learning purposes.

## 👩‍💻 Author

**Swati Salunkhe**

Learning Transformers, LLMs, RAG, and Generative AI one module at a time 🚀
