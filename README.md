
# 🤖 Chatbot using Transformers – NLP Assignment 3

## 📌 Project Overview

This project builds a conversational AI chatbot using **Hugging Face Transformers** and the **DialoGPT model**.
The chatbot interacts with users, understands input text, and generates meaningful responses in real time.

The system demonstrates how transformer-based models can be used to create intelligent conversational agents using Natural Language Processing (NLP).

---

## 🎯 Objective

* Build a chatbot using transformer-based NLP model
* Understand how pretrained models work
* Implement conversational AI using Hugging Face
* Generate dynamic responses based on user input

---

## 🛠️ Technologies Used

* Python
* Transformers (Hugging Face)
* PyTorch
* DialoGPT Model
* Google Colab

---

## 📂 Project Structure

```
chatbot-transformers/
│
├── chatbot.ipynb
├── README.md
```

---

## ⚙️ Installation

Install required libraries:

```bash
pip install transformers
pip install torch
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Install required libraries
3. Run all cells
4. Start chatting with the chatbot

Example:

```
Chatbot: Hello! I am your AI assistant. How can I help you today?

You: Hello
Chatbot: Hi there! How can I assist you?

You: What is Artificial Intelligence
Chatbot: Artificial Intelligence is the simulation of human intelligence in machines.

You: exit
Chatbot: Goodbye! Have a nice day.
```

---

## 🔄 Pipeline Flow

User Input → Tokenizer → Transformer Model → Response Generation → Output → Loop Until Exit

---

## 🧠 Model Used

**DialoGPT-medium**

* Pretrained conversational transformer model
* Developed using GPT-2 architecture
* Generates human-like responses
* Maintains conversation context

---

## 📊 Output Flow

```
User Input
   ↓
Tokenizer
   ↓
DialoGPT Transformer Model
   ↓
Response Generation
   ↓
Chatbot Output
   ↓
Loop Until Exit
```

---

## ✅ Features

* Transformer-based chatbot
* Uses Hugging Face pretrained model
* Real-time conversation
* Context-aware responses
* Exit condition included
* Fallback response for empty outputs
* Interactive user interface

---

## 📌 Conclusion

This project demonstrates how transformer-based NLP models can be used to build conversational chatbots.
By using Hugging Face DialoGPT, we successfully created an interactive chatbot capable of generating human-like responses and maintaining conversation flow.

---

## 🔑 Key Takeaways

* Learned how transformer models work
* Built chatbot using DialoGPT
* Implemented conversational AI system
* Generated dynamic responses
* Used Hugging Face Transformers
* Built interactive chatbot with exit condition

---

## 📎 Future Improvements

* Add GUI using Streamlit
* Deploy chatbot on web
* Add memory for long conversations
* Improve response accuracy
* Integrate multiple NLP models



---

