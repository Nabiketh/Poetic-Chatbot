# 🌸 Poetic Personality Chatbot

A creative AI chatbot that transforms any user input into a beautiful, poetic response using Google's Gemini AI. Instead of providing plain answers, the chatbot responds with short, expressive poems, creating a unique and engaging conversational experience.

---

## 📖 Project Overview

The **Poetic Personality Chatbot** demonstrates how prompt engineering can shape the personality and response style of a Large Language Model (LLM). The chatbot is designed to answer every query—whether factual, emotional, or conversational—in a poetic and imaginative manner.

This project was developed using **Google Gemini 2.0 Flash** and implemented in **Google Colab** with Python.

---

## ✨ Features

* 🌼 AI-powered poetic conversations
* 🤖 Uses Google's Gemini 2.0 Flash model
* ✍️ Responds to every prompt in poetic form
* ⚡ Fast response generation
* 🎭 Personality-driven chatbot using prompt engineering
* 💬 Smooth streaming output for a natural chat experience

---

## 🛠️ Tech Stack

* Python
* Google Colab
* Google Gemini API
* google-genai SDK

---

## 📂 Project Structure

```text
Case Project 1/
│
├── Poetic_chatbot.ipynb      # Main chatbot implementation
├── Case_project 1.pdf        # Project documentation
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>

cd Case-Project-1
```

### 2. Install Dependencies

```bash
pip install google-genai
```

### 3. Configure the Gemini API Key

Obtain a Gemini API key from **Google AI Studio** and configure it in your environment or Google Colab notebook.

Example:

```python
from google.colab import userdata

API_KEY = userdata.get("GEMINI_API_KEY")
```

---

## ▶️ Run the Chatbot

Open the notebook:

```text
Poetic_chatbot.ipynb
```

Run all cells and start interacting with the chatbot.

Example:

**Input**

```
How are you today?
```

**Output**

```
Like morning dew upon a leaf,
I bloom between both joy and grief.
Each whispered word becomes my song,
A place where gentle hearts belong.
```

---

## 💡 How It Works

1. The user enters a message.
2. The message is sent to the Gemini API.
3. A carefully designed system prompt instructs the AI to always reply in poetic form.
4. The generated response is displayed with a streaming effect for a conversational experience.

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Working with the Google Gemini API
* Integrating LLMs into Python applications
* Prompt engineering techniques
* Creating personality-driven AI chatbots
* Handling API authentication and responses
* Improving user interaction with streaming outputs

---

## 🚧 Challenges Faced

* Managing Gemini API authentication
* Refining prompts to consistently produce poetic responses
* Handling API rate limits gracefully
* Designing prompts that maintain creativity across different types of user input

---

## 🔮 Future Improvements

* Voice-based interaction
* Multiple chatbot personalities
* Web-based interface using Streamlit or Flask
* Conversation history
* Adjustable poem styles (Haiku, Sonnet, Free Verse, etc.)
* Multilingual poetic responses

---

## 👨‍💻 Author

**Nabiketh Thalari**

---

## 📄 License

This project is intended for educational and learning purposes.
