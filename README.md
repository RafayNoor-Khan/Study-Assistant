# 📚 Study Assistant Chatbot – Exam Prep Helper (OpenAI)

A web-based chatbot that helps students prepare for exams by providing detailed explanations, lists of key points, and general answers.  
Built using **Flask**, **OpenAI API**, and custom prompt templates to handle different question types while maintaining conversation context.  
Deployed online for interactive access by students.

---

## 🚀 Features
- Context-aware chatbot using session memory  
- Handles different types of queries:
  - **Explain** – gives detailed explanations  
  - **List** – lists key points, features, or advantages  
  - **General** – answers standard questions  
- Interactive web interface for students  
- Deployed online via PythonAnywhere  

---

## 🛠 Tech Stack
- Python (Flask)  
- OpenAI API (Llama3 or GPT-based models)  
- HTML / CSS for frontend  
- dotenv for environment variables (API keys & secrets)  

---

## 🌐 Live Demo
Try it online: [Study Assistant Chatbot](https://noorkhan.pythonanywhere.com/)

## 📹 Demo Video
Watch the chatbot in action: [Demo Video][(demo here)](https://drive.google.com/file/d/1yip2HQS0EQmFJjB9G9e-MU1AMuL8gMyx/view?usp=sharing)

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/study-assistant-chatbot.git
   cd study-assistant-chatbot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root folder and add your keys:
   ```
   OPENAI_API_KEY=your_openai_api_key
   FLASK_SECRET_KEY=your_flask_secret
   MODEL=llama3-70b-8192
   ```
4. Run locally:
   ```bash
   python app.py
   ```
5. Open your browser at:
   ```
   http://127.0.0.1:5000/
   ```


## 💡 Future Improvements
- Add voice-based input and output for interactive learning  
- Integrate adaptive learning features for personalized study plans  
- Enhance conversation memory for multi-turn complex queries  
- Add analytics dashboard for student performance  


**Author:** Rafay Noor Khan  
🎓 BS Data Science | Interested in AI, NLP & Education Technology
