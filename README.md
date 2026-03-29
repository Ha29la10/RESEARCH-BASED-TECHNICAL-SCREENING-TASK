# AI-Based Candidate Ranking System using Semantic Similarity

## 📌 Overview
This project implements an AI-driven system for **automatic CV screening and candidate ranking**.  
It uses **semantic similarity (Sentence Transformers)** to match candidates with job descriptions and provides **explainable results** showing why candidates are ranked highly.

---

## 🎯 Objectives
- Automate candidate evaluation from CVs
- Improve matching using **semantic understanding instead of keyword matching**
- Provide **transparent and explainable rankings**
- Identify dataset challenges such as missing data and inconsistencies

---

## 🧠 Roles Covered
- AI Engineer (Multimodal & LLM Systems)
- Full Stack Engineer (AI-Driven Platforms)

---

## ⚙️ Methodology

### 1. Data Processing
- Extract text from CVs (PDF / DOCX)
- Parse into:
  - Skills
  - Experience
  - Projects
  - Education

### 2. Preprocessing
- Clean text
- Handle missing and inconsistent data

### 3. Feature Extraction
- Convert text into embeddings using:
  SentenceTransformer('all-MiniLM-L6-v2')
