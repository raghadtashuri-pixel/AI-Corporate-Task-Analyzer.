# AI Corporate Task Analyzer

AI Corporate Task Analyzer is an intelligent system built using modern NLP and transformer-based models to analyze and classify corporate tasks reported by employees. The system processes text inputs, cleans and normalizes language, detects dialect, extracts linguistic features, and applies machine-learning classification to identify the task category and urgency level.

## 🔍 Key Features
- Text cleaning, normalization, and PII masking  
- Tokenization and linguistic feature extraction  
- Dialect detection (MSA vs Saudi dialect)  
- Attention-based priority scoring  
- Task classification using CAMeLBERT  
- Semantic embeddings using SentenceTransformer  
- FAISS index for fast semantic search  
- Cross-Encoder reranking for improved relevance  
- Visual dashboards for insights and analytics  
- Detailed token-level and attention-level analysis  

## 📁 Project Workflow
1. **Preprocessing**: Clean, normalize, and mask sensitive data  
2. **Linguistic Analysis**: Tokenization, fertility, UNK rate, clitic detection  
3. **Attention Extraction**: Compute attention maps and priority scores  
4. **Classification**: Predict task category using transformer models  
5. **Semantic Search**: Build FAISS index and rerank results  
6. **Visualization**: Generate charts and attention heatmaps  
7. **Reporting**: Produce a final summary of tasks and insights  

## 🧠 Technologies Used
- Python  
- Transformers (CAMeLBERT)  
- SentenceTransformer  
- FAISS  
- CrossEncoder  
- Scikit-learn  
- Matplotlib / Pandas  

## 🎯 Purpose
This project demonstrates a complete NLP pipeline for intelligent task management in corporate environments, helping organizations analyze issues, detect patterns, and make faster, more accurate decisions.

