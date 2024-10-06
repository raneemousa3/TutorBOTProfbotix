# TutorBOTProfbotix
ProfBotix: Math and Programming Tutor Chatbot
Overview
ProfBotix is a Flask-based web application that serves as a humorous mathematics and programming tutor. Users can interact with the chatbot by either typing their questions or uploading images containing text. The chatbot uses OpenAI's GPT-3.5-turbo model to generate responses, offering assistance with mathematical concepts and programming inquiries while making the learning process fun and engaging.

Features
Upload images containing questions, and the chatbot extracts text using OCR (Optical Character Recognition).
Engage in a chat session where users can ask questions about mathematics and programming.
Receive feedback on weaknesses in knowledge and suggestions for exam preparation.
A friendly and humorous chatbot personality to make learning enjoyable.
Requirements
To run this application, you'll need:

Python 3.x
Flask for the web framework
OpenAI API client for accessing the GPT model
Pillow for image processing
Pytesseract for Optical Character Recognition
python-dotenv for environment variable management
You can install the required libraries using pip:

bash
Copy code
pip install Flask openai Pillow pytesseract python-dotenv
Tesseract Installation
Pytesseract requires Tesseract-OCR to be installed on your system. You can download and install it from Tesseract's GitHub page. Make sure to add Tesseract to your system's PATH.

Setup
OpenAI API Key:

Create an OpenAI account and obtain your API key.
Set your API key in a .env file in the project directory:
makefile
Copy code
OPENAI_API_KEY=your_openai_api_key


Interact with the Chatbot:

You can either type your questions in the chat box or upload an image with a question.
The chatbot will process your input and respond accordingly.
Code Explanation
Flask Application: The app is structured using Flask, with routes for the home page, chatbot functionality, and static content.
Image Processing: When an image is uploaded, Pytesseract is used to extract text from the image, which is then processed by the chatbot.
Chat History: The chat history is maintained to allow for context-aware responses.
OpenAI Integration: The chatbot generates responses based on user input and chat history using the OpenAI API.
