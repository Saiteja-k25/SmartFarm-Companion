# 🌱 SmartFarm Companion 🌾

An AI-powered Streamlit application designed to assist farmers and agricultural enthusiasts with crop recommendations, disease diagnosis, and an intelligent conversational assistant.

---

## 🚀 Features

### 1️⃣ Crop Recommendation System
🔹 **Inputs:** Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall  
🔹 **Predicts** the most suitable crop based on soil and environmental conditions  
🔹 **Powered by:** Random Forest model trained on agricultural data  

### 2️⃣ AI-Powered Crop Disease Diagnosis
🔹 **Identifies** potential crop diseases based on symptoms  
🔹 **Recommends** organic & chemical treatments  
🔹 **Provides** preventive measures for future protection  
🔹 **Powered by:** AI (Groq LLM) for expert analysis  

### 3️⃣ Conversational AI for Agriculture
🔹 **Ask any farming-related question** (e.g., best practices, fertilizers, weather impact)  
🔹 **AI-driven chatbot** provides instant, accurate responses  

---

## 🛠 Tech Stack
- **Python** 🐍  
- **Streamlit** 🎨 (User Interface)  
- **Scikit-Learn** 🤖 (Machine Learning)  
- **LangChain & Groq API** 🧠 (AI-powered chatbot & disease diagnosis)  
- **Pickle** 📦 (Model persistence)  

---

## 🎯 Project Structure
```
📂 Crop_Recommendation
│── 📂 Chat                    
│   ├── testing_prompts.ipynb 
│   ├── RAG.ipynb  
│
│── 📂 data                   
│   ├── Crop_recommendation.csv 
│   ├── farmerbook.pdf          
│
│── 📂 EDA                     
│   ├── explore.ipynb           
│
│── 📂 Research                 
│   ├── model_selection.ipynb  
│   ├── Predictions.ipynb      
│
│── 📂 saved_models            
│   ├── RF_Model.pkl   
│   ├── gb_model.pkl         
│
│── .env                       
│── .gitignore                  
│── app.py                      
│── README.md                   
│── requirements.txt            
```

---

## 🛠 Installation Guide

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/Saiteja-k25/SmartFarm-Companion.git
cd SmartFarm-Companion
```

### 🔹 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 🔹 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 4. Run the Application
```bash
streamlit run app.py
```
Access the app at `http://localhost:8501`

---

## 🤝 Contributing
We welcome contributions! To contribute:
1. Fork the repository  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:  
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request  

---

## 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 📞 Contact
For inquiries, contact:  
📧 **Saiteja Kurapati** - kurapatisaitejas@gmail.com  
📱 **Phone:** +91 6305656651  
🔗 **GitHub:** [Saiteja-k25](https://github.com/Saiteja-k25)  
```
