# TARA-Report-Generator
RAG (HayStack) + LLM (Gemini) powered automated TARA Report Generation Framework

---

## 🧩 Overview
This project implements a *Retrieval-Augmented Generation (RAG)* framework for generating *Threat Analysis and Risk Assessment (TARA)* reports in the context of automotive cybersecurity.  
The system integrates *Haystack* for retrieval, *Google Gemini API* as the LLM backend, and *Streamlit* for an interactive front-end interface.

---

## ⚙ Technical Architecture
- **RAG Pipeline:** Built using *deepset Haystack*, enabling contextual retrieval of cybersecurity-relevant information.  
- **LLM Integration:** Utilizes *Google Gemini API* for high-quality, context-aware text generation and reasoning.  
- **Knowledge Source:** Custom dataset derived from *ISO/SAE 21434 documents* and structured summaries of *automotive ECU threat surfaces* (including ECU names, attack vectors, and associated assets).  
- **Frontend Hosting:** Deployed via *Streamlit*, allowing seamless input, processing, and report visualization.

---

## 💡 Key Highlights
- Automates the TARA report creation process using domain-specific RAG-LLM architecture.  
- Incorporates standard-compliant cybersecurity knowledge for improved accuracy and traceability.  
- Modular, scalable pipeline designed for future extension with additional LLMs or domain datasets.  

---

## 🚀 Tech Stack
| Component | Technology Used |
|------------|----------------|
| Retrieval | Haystack |
| Language Model | Google Gemini API |
| Frontend | Streamlit |
| Data Source | ISO/SAE 21434 docs, ECU threat summaries |
| Language | Python |

---

## 🧪 Steps to Run the Project Demo

1. **Prepare the Data Files:**  
   Upload the following four JSON files to your Colab workspace:  
   - `attack1.json`  
   - `attack2.json`  
   - `ecu_hints.json`  
   - `iso.json`  

2. **Set Up API Keys:**  
   - Generate a **Google API Key** through [Google AI Studio](https://aistudio.google.com/).  
   - Generate an **Ngrok Auth Key** through [ngrok.com](https://ngrok.com/) for Streamlit hosting.

3. **Run the Notebook:**  
   - Open the provided `.ipynb` file in Google Colab.  
   - Execute all the code blocks **sequentially** as provided (in order).  
   - Once all cells are executed successfully, the Streamlit app link (provided by ngrok) will appear for interactive demo access.

---

## 📄 Contributors
- [Anirudh Navalgund](https://github.com/Anirudh-Navalgund/)
- [Shashank Padavalkar](https://github.com/Shashank-Padavalkar)
- [E Sujaya](https://github.com/Sujaya-E)
- [Royston Vedamuthu](https://github.com/RoystonV)
