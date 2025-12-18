# MedAware-AI-Symptom-Assistant
AI-powered symptom analysis assistant using ML, image-based eye scanning, and explainable AI to provide risk-level health insights.

# MedAware – AI Symptom Analysis Assistant

## Overview
MedAware is an AI-powered symptom analysis assistant designed to support early health awareness and informed decision-making. The system analyzes user-reported symptoms and visual eye indicators to suggest possible medical conditions along with confidence scores and risk levels. It is intended as a decision-support tool and does not replace professional medical diagnosis.

---

## Problem Statement
Develop an AI-based symptom analysis system that accepts structured and unstructured user inputs, leverages machine learning and medical datasets, and provides explainable, guideline-aware health insights, particularly for users in regions with limited access to healthcare professionals.

---

## Key Features
- Text-based symptom input (structured and unstructured)
- Multilingual voice input with speech-to-text and translation
- Eye scan analysis using image-based machine learning
- Disease prediction with confidence scores
- Risk classification (Low / Medium / High)
- Explainable medical reasoning using AI
- Ethical and privacy-aware design

---

## System Architecture
1. User inputs symptoms via text or voice
2. Voice input is converted to text and translated
3. Eye image is captured and preprocessed
4. ML models analyze symptom data and eye images
5. Multimodal fusion combines model outputs
6. AI generates explainable medical insights
7. Final risk level and recommendations are displayed

---

## Machine Learning Approach
- **Symptom Analysis Model:** Supervised classification (Naive Bayes / Logistic Regression)
- **Eye Scan Model:** CNN-based image classification
- **Fusion Layer:** Weighted decision-based multimodal fusion
- **Explainability Layer:** Gemini LLM for guideline-aware reasoning

---

## Tech Stack
**Frontend:** HTML, CSS, Tailwind CSS, Node.js  
**Backend:** Firebase  
**Machine Learning:** TensorFlow (Google Colab)  
**LLM:** Gemini Flash  
**APIs:** Gemini API, Google Translate API, OpenFDA API  

---

## Ethical Considerations
- The system does not provide medical diagnosis
- Designed strictly for decision support
- User consent and data privacy are maintained
- Encourages professional medical consultation

---

## Team Members
- Nishanth A.A  
- J. Mohamed Arif  
- Hima Sri  
- S. Haridev  
- M.K. Keerthivasan  

---

## How to Run (Prototype)
1. Open the frontend files in a browser
2. Connect backend services (Firebase)
3. Run ML models using provided notebooks
4. Test symptom input and eye scan features

---

## License
This project is licensed under the MIT License.

