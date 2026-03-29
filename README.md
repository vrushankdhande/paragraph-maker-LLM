# 📌 Paragraph Maker using LLM (LangChain + Groq)

This project is a simple yet powerful Streamlit web application that uses LangChain and Groq LLM (LLaMA 3.3 70B) to transform raw text into well-structured paragraphs.

Users can control:
- ✍️ Paragraph length (word count)
- 🎯 Writing style (Informative, Conversational, Formal, Casual)

## 🚀 Features
- 🧠 Powered by Groq LLM (LLaMA 3.3-70B)
- 🔗 Uses LangChain Prompt Templates
- 🎨 Clean UI with custom background
- ✂️ Automatically breaks text into readable paragraphs
- ⚡ Fast inference using Groq API

## 🏗️ Tech Stack
- Python
- Streamlit
- LangChain
- Groq API (LLM)
- HTML/CSS (for styling)

## 📂 Project Structure
```
├── app.py              # Main Streamlit app
├── constants.py        # Stores Groq API key
├── requirements.txt    # Dependencies
└── README.md           # Documentation
```

## ⚙️ Installation
- Bash
```
git clone https://github.com/your-username/paragraph-maker-llm.git
cd paragraph-maker-llm
pip install -r requirements.txt
```

## 🔑 Setup
Add your Groq API key in constants.py:
- python
```
groq_key = "your_api_key_here"
```
## ▶️ Run the App
Bash
```
streamlit run app.py
```

## 💡 How It Works

1. User inputs raw text  
2. Selects:
   - Number of words per paragraph  
   - Writing style  
3. LangChain builds a structured prompt  
4. Groq LLM processes the request  
5. Output is displayed as formatted paragraphs

## 🎯 Use Cases
- Blog writing ✍️
- Content formatting 📄
- Report structuring 📊
- AI writing assistance 🤖

## 🔮 Future Improvements
- Download output as file (PDF/Doc)
- Multi-language support
- Advanced formatting (headings, bullets)
- RAG integration for contextual writing
