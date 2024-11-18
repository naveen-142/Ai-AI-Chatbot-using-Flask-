# Ai-AI-Chatbot-using-Flask- Google-Generative-AI

An interactive and intelligent chatbot web application built with Flask and Google Generative AI (Gemini 1.5). This project demonstrates a full-stack implementation with a dynamic front-end, Flask-powered back-end, and robust API integration.

## Features

- Interactive chatbot interface for user-friendly communication.
- Integrated with Google Generative AI to provide intelligent, context-aware responses.
- Responsive and aesthetically pleasing UI using Bootstrap and custom styling.
- Real-time communication between the front-end and back-end using JavaScript's fetch API.
- Robust error handling for seamless user experience.

## Tech Stack

- Front-End: HTML, CSS, JavaScript, Bootstrap 5
- Back-End: Flask (Python)
- API Integration: Google Generative AI API (Gemini 1.5)
- Tools: Git, GitHub, Visual Studio Code


## Setup and Installation

### Prerequisites
1. Python 3.8 or later
2. Google Generative AI API Key
3. Flask and related dependencies

### Installation Steps
1. Create a new project folder:
Open your terminal and run the following command to create an empty folder for the project:

mkdir ai-chatbot
cd ai-chatbot

2. Set up a virtual environment:
Create and activate a virtual environment to manage your project dependencies:

python -m venv venv
#### Activate the virtual environment
**On macOS/Linux:**
source venv/bin/activate
**On Windows:**
venv\Scripts\activate

3. Install Flask and other dependencies:
Install the required Python packages for the project:

pip install flask google-generativeai

4. Create the project files:
Create the following files in your ai-chatbot folder:

- app.py: Contains the backend code.
- templates/index.html: For the user interface.
- Any other files like CSS or JavaScript for styling or functionality.


5. Set up your Google Generative AI API key:
Replace the placeholder GOOGLE_API_KEY in app.py with your actual API key.

6. Run the application:
Start the Flask app:

python app.py

7. Open the application in your browser:
Access the chatbot at:


http://127.0.0.1:5000


## Usage

1. Open the web application in your browser.
2. Type your message in the input box and click "Send."
3. The chatbot responds with context-aware messages generated by Google Generative AI

## API Configuration
This project uses Google Generative AI. To configure the API:

1. Obtain an API key from Google Cloud Console.
2. Replace the placeholder GOOGLE_API_KEY in app.py.

## Acknowledgments
[Google Generative AI](https://aistudio.google.com/prompts/new_chat)
[Flask Framework](https://flask.palletsprojects.com/en/stable/)
[Bootstrap](https://getbootstrap.com/)

## screenshots


![alt text](<Screenshot 2024-11-18 211856.png>)

![alt text](<Screenshot 2024-11-18 213317.png>)