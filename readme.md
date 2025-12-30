# AI-Powered Semantic Career Recommendation Agent

## Overview
This project is an **AI-powered career recommendation system** that analyzes resume content and predicts the **best-fit job role** using **semantic understanding** instead of traditional keyword matching.

The system leverages **BERT-based sentence embeddings** and **cosine similarity** to understand the meaning of resume text and compare it with predefined job role descriptions. It also performs **skill gap analysis** and provides a **personalized learning roadmap**.

---

## Problem Statement
Most resume screening systems rely on keyword matching, which:
- Fails to capture contextual meaning
- Does not handle synonyms effectively
- Produces inaccurate role recommendations

This project addresses the problem by using **transformer-based NLP models** for semantic resume–job matching.

---

## Features
- Semantic resume analysis using BERT embeddings  
- Best-fit job role prediction  
- Confidence-based job-fit scoring  
- Skill gap identification  
- Personalized learning roadmap recommendation  
- Explainable AI decision-making

---

## System Architecture
Resume Text
↓
BERT Sentence Embeddings
↓
Cosine Similarity Engine
↓
Job Role Prediction
↓
Skill Gap Analysis
↓
Learning Roadmap Recommendation

yaml
Copy code

---

## Technologies Used
- Python  
- Natural Language Processing (NLP)  
- Transformer Models (BERT-based)  
- Sentence-Transformers  
- Scikit-learn  
- Pandas  

---

## Project Structure
├── notebook.ipynb / notebook.py
├── README.md
├── requirements.txt

yaml
Copy code

---

## Role-Based Knowledge Base
Each job role is defined with:
- A natural language job description  
- A list of required skills  
- A learning roadmap  

This role-based design improves scalability, explainability, and maintainability.

---

## How It Works
1. Job role descriptions are converted into **semantic embeddings** using a pretrained transformer model.
2. Resume text is encoded into a semantic embedding.
3. **Cosine similarity** is computed between resume and role embeddings.
4. The role with the highest similarity score is selected.
5. Resume skills are compared with role requirements to identify skill gaps.
6. A personalized learning roadmap is generated.

---

## Sample Output
Predicted Job Role: Software Developer
Semantic Fit Score: 84.6%

Matched Skills:

Python

C++

Missing Skills:

Data Structures

OOPs

Recommended Learning Roadmap:
→ Programming Basics
→ Data Structures
→ Algorithms
→ OOPs
→ Projects

yaml
Copy code

---

## How to Run

### 1) Install Dependencies
```bash
pip install sentence-transformers scikit-learn pandas
2) Run the Project
Open the notebook or Python script

Paste your resume text when prompted

View predictions and recommendations

 Key Takeaways
Built a real-world AI system using transformer-based NLP

Applied semantic similarity for decision making

Designed explainable AI logic

Implemented end-to-end AI agent workflow

Future Improvements
Resume PDF upload and parsing

Web interface using Streamlit or Flask

Expanded job role dataset

Model fine-tuning for domain-specific roles

Resume Description (Suggested)
Built a BERT-based AI career recommendation agent using transformer embeddings and cosine similarity to perform semantic resume–job matching with explainable skill gap analysis and personalized learning roadmap generation.

 License
This project is intended for learning and demonstration purposes.

