# 🤖 ProfBotix: Math and Programming Tutor Chatbot

## 📖 Overview
**ProfBotix** is a Flask-based web application designed to make learning math and programming fun and interactive. With its friendly and humorous personality, the chatbot can answer typed questions or process text extracted from uploaded images. Powered by OpenAI's GPT-3.5-turbo, ProfBotix provides insightful explanations, feedback on weaknesses, and exam preparation suggestions.

---

## ✨ Features
- **Image Uploads**: Users can upload images containing text questions, and the chatbot extracts the text using Optical Character Recognition (OCR) before responding.
- **Chat-Based Interaction**: Type your math or programming questions directly into the chat for instant responses.
- **Feedback and Suggestions**: Gain insights into your weak areas and tips for improving in mathematics and programming.
- **Engaging Personality**: Learn with a chatbot that combines humor and expertise for an enjoyable experience.

---

## 🏗️ Requirements
To run ProfBotix, ensure you have the following installed:

- **Python 3.x**
- Libraries:
  - `Flask`: Web framework
  - `openai`: Access OpenAI's GPT models
  - `Pillow`: Image processing
  - `pytesseract`: OCR for text extraction
  - `python-dotenv`: Environment variable management

Install these libraries using pip:
```bash
pip install Flask openai Pillow pytesseract python-dotenv
