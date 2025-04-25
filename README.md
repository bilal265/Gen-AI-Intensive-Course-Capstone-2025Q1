# Gen-AI-Intensive-Course-Capstone-2025Q1
## 🧠 GenAI-Powered Medical Report Simplifier
This project is a capstone submission for the Google Gen AI Intensive Course. It demonstrates how Generative AI can be used to simplify complex medical reports for better patient understanding, especially those without a medical background.

### 📌 Project Overview
Medical reports are often dense and filled with technical jargon. This project uses Generative AI (specifically large language models) to automatically simplify these reports, making them more accessible and readable.

### ✅ Key Features
1. Upload a medical report text (e.g., discharge summary, diagnosis report).

2. Process and extract key information.

3. Generate a patient-friendly explanation using a language model.

4. Evaluate readability improvements using metrics like Flesch Reading Ease.

### 📂 Project Structure
genai-powered-medical-report-simplifier.ipynb — Main notebook containing:
Data preprocessing
Prompt engineering for simplification
LLM-based simplification logic
Evaluation and testing

### 🛠️ Technologies Used
Python
Jupyter Notebook
OpenAI GPT (or similar LLM via HuggingFace)
transformers, textstat, matplotlib
Pandas, NumPy

### 🚀 Getting Started
Prerequisites
Python 3.8+
Jupyter Notebook
API key for LLM (e.g., OpenAI, HuggingFace)

### Installation
![image](https://github.com/user-attachments/assets/ddeecd9a-7461-4c50-8143-fca6a7cf777e)

### Run the Notebook
![image](https://github.com/user-attachments/assets/3a299c39-57cd-4961-9150-edc33ecabaa2)

### 📊 Example Output
Original: “Patient presents with dyspnea and tachycardia…”

Simplified: “The patient is having trouble breathing and a fast heartbeat…”

### 📈 Evaluation
Used textstat to calculate readability scores before and after simplification.

Visualized improvement using bar charts.

### 💡 Future Improvements
Add support for multi-language reports.

Integrate with voice assistants for audio output.

Deploy as a web app (e.g., using Streamlit or Flask).

### 📜 License
This project is for educational purposes as part of the Google Gen AI Intensive Program. Please cite appropriately if used or modified.
