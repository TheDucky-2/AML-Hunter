# AML Hunter: Autonomous Anti-Money Laundering Detection System

**AML Hunter** is a self-built, end-to-end pipeline for detecting and explaining potential Anti-Money Laundering (AML) activities using real-world transaction data. It combines machine learning, model explainability, and autonomous agents to assist compliance teams in identifying suspicious behavior.

---

## What It Does

- Detects potentially suspicious financial transactions using **XGBoost** and **LSTM**
- Handles both **labeled** and **unlabeled** data using **PCA** for unsupervised risk patterns
- Generates explainable insights using **SHAP**
- Uses **RAG (Retrieval Augmented Generation)** to create human-readable summaries of flagged transactions
- Orchestrates agents with **Crew AI** to automate:
  - Data analysis
  - Model training
  - SHAP interpretation
  - Insight generation

---

## Why I Am Building This

Coming from a non-technical background, I self-taught Python, ML, and AI tools to explore how real-world financial crime can be detected with data. AML Hunter is my attempt to combine everything I’ve learned — from fraud detection to LLM-powered agents — into a single working system.

---

## Tools & Technologies

- **Python**: pandas, NumPy, matplotlib
- **Machine Learning**: XGBoost, LSTM, PCA
- **Explainability**: SHAP
- **LLMs & AI Agents**: LangChain, RAG, Crew AI
- **Data**: Real-world public transaction data (~$80B+ in transaction value)

---

## How It Works (Simplified)

1. **Load & Preprocess Data**  
   Clean transaction records, engineer features, and label known suspicious activity.

2. **Train ML Models**  
   - XGBoost (supervised)  
   - LSTM for temporal patterns  
   - PCA for anomaly detection

3. **Explain Predictions**  
   SHAP values highlight which features triggered suspicion.

4. **Summarize & Investigate**  
   RAG + LLM agents generate clear summaries of why a transaction may be risky.

5. **Automate the Flow**  
   Crew AI agents work in sequence to handle the end-to-end pipeline.

---

## Structure

aml-hunter/
- `data/` – Real-world transaction datasets  
- `models/` – Saved ML model files  
- `agents/` – Crew AI agent logic for automation  
- `notebooks/` – Jupyter notebooks for EDA and experimentation  
- `pipeline/` – Scripts for data preparation, training, and inference  
- `explainability/` – SHAP & RAG tools for interpreting results  
- `README.md` – Project documentation

---

## Project Status

- Ongoing — actively building and improving

---

## About Me

I'm a self-taught data analyst and aspiring FinCrime ML engineer, with a background in customer experience at American Express and CreditOne. I've handled real-world fraud and compliance issues firsthand — now I build tools to fight them.

---

## Contact

Feel free to connect or ask questions:

- `LinkedIn`: https://www.linkedin.com/in/kshitij-sharma/ba81b5233/
- `Email`: nuclearreactor11@atomicmail.io

---

## License

MIT License
