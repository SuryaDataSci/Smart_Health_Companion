# Smart_Health_Companion
AI-powered Smart Health Companion that analyzes lab reports, predicts disease risks, and provides simplified medical explanations using Cohere LLM.



💡 Smart Health Companion is an AI-driven healthcare assistant built with Streamlit that allows users to upload their lab reports (PDF/CSV), analyze critical health parameters, and generate easy-to-understand medical explanations. It integrates a Cohere language model to provide personalized insights and abnormality detection, helping users understand their health without complex jargon.



# 🏥 Smart Health Companion

An AI-powered web app that predicts disease risk and explains lab reports in simple language using Cohere LLM.

![Smart Health Banner](https://img.shields.io/badge/AI-Healthcare-blue)  
![Python](https://img.shields.io/badge/Python-3.10-blue) ![Streamlit](https://img.shields.io/badge/Streamlit-App-orange) ![Cohere](https://img.shields.io/badge/Cohere-LLM-purple)

---

## 🚀 Features

✅ Upload lab reports as **PDF or CSV**  
✅ Extract & analyze test values  
✅ Predict potential health risks using ML  
✅ Explain results using **Cohere LLM**  
✅ Detect abnormalities & offer suggestions  
✅ Clean, responsive Streamlit UI

---

## 🧠 How It Works

1. **Upload Lab Report**: Upload your medical lab report in PDF or CSV format.
2. **Parse the Report**: The app extracts and preprocesses medical values.
3. **Risk Prediction**: Machine learning model predicts health risks.
4. **LLM Explanation**: A prompt is sent to the Cohere LLM, which returns a plain-language summary of your results.

---

## 📂 Project Structure




smart-health-companion/
│
├── main.py # Streamlit frontend
├── .env # Contains your API key
├── requirements.txt # Python dependencies
│
├── utils/
│ ├── predict.py # Prediction logic
│ ├── llm_explainer.py # LLM integration using Cohere
│ └── pdf_parser.py # PDF parsing logic



🧪 Tech Stack
Frontend: Streamlit

Backend: Python (Pandas, Regex, PDFMiner)

AI/ML:

ML Risk Prediction Model

Cohere Language Model (LLM) for NLP explanations

🔍 Future Improvements
Integration with real-time health APIs

Support for different languages

Export medical explanations to PDF

Symptom checker chatbot integration





