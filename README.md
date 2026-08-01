# HarvestIQ
AI-Powered Predictive Crop Advisory System

HarvestIQ is an innovative agricultural decision support system that utilizes Machine Learning, Retrieval Augmented Generation, and Large Language Models to give recommendations on crop management
The system was implemented through a Streamlit dashboard that provides yield prediction, AI-powered recommendations grounded in real agricultural documents, and a contextual chatbot

---
## Features
- Crop Yield Prediction using ML
- Gemini-powered AI Recommendations
- RAG Implementation using FAISS
- Tamil & English Language Support
- Voice Input (Speech to Text)
- Voice Output (Edge TTS)
- Streamlit Dashboard
- Model Comparison
- Contextual Chatbot
---
## System Architecture
```
Farmer
│
▼
Streamlit Frontend (app.py)
│
▼
backend.py
│
▼
ML Prediction (XGBoost)
│
▼
FAISS Retrieval
│
▼
Gemini LLM
│
▼
AI Recommendation
│
▼
Translation (Tamil ⇄ English)
│
▼
Edge TTS
```
---
## ML Algorithms Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor (Best Model)
---
## Technologies Used
| Category | Technologies |
|--------|----------|
| Frontend | Streamlit |
| Backend | Python |
| ML | Scikit-learn, XGBoost |
| AI | Gemini LLM, LangChain, FAISS, Sentence Transformers |
| Translator & Voice | Speech Recognition, Microsoft Edge TTS |
| Data Processing | Pandas, NumPy, Joblib |
| Development | VS Code, Git, GitHub |
---
## Model Comparison
| Algorithm | R² Score |
|--------|----------|
| Linear Regression | 0.0067 |
| Decision Tree | 0.9608 |
| Random Forest | 0.9787 |
| Gradient Boosting | 0.8789 |
| XGBoost | 0.9879 |
Best Model: XGBoost Regressor with an R² score of 0.9879
Evaluation Metrics:
- Mean Absolute Error: 0.0900
- Root Mean Squared Error: 0.1952
---
## Project Structure
```
HarvestIQ/
├── app.py
├── backend.py
├── featureengineering.py
├── predict.py
├── decisionengine.py
├── chat.py
├── translate.py
├── edgettshelper.py
├── build_vectorstore.py
├── train_models.py
├── data/
├── models/
├── vectorstore/
├── documents/
├── results/
├── notebooks/
├── requirements.txt
├── README.md
└── .gitignore
```
---
## Installation Instructions
Clone the repository:
```bash
git clone https://github.com/<your-username>/HarvestIQ.git
```
Navigate to the project directory:
```bash
cd HarvestIQ
```
Install the requirements:
```bash
pip install -r requirements.txt
```
Set up your API key:
```bash
cp .env.example .env
```
Then paste your Gemini API key into the .env file.

Run the application:
```bash
streamlit run app.py
```
---
## Future Scope
- Real-time weather API integration
- IoT sensor integration
- Satellite image analysis
- Market price prediction
- Mobile application development
- Language translation expansion
- Farmer profile and history tracking
---
## 👥 Team Information
Project : HarvestIQ -
