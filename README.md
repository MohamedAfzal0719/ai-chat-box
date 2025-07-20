# Simple-Chat-Bot

A simple command-line chatbot built with Python. This bot can engage in basic conversations, respond to user inputs, and provide information based on predefined rules.

---

## Features

- ✅ **Interactive Command-Line Interface**  
  Engage with the bot directly from your terminal.

- 💬 **Basic Conversational Abilities**  
  Responds to greetings, questions, and common phrases.

- 🔧 **Extensible**  
  Easily add new rules and responses to expand the bot's knowledge.

## Installation

To set up the Simple-Chat-Bot on your local machine, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/MEERAN2314/Simple-Chat-Bot.git
cd Simple-Chat-Bot
**2. Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Usage
You can run the chatbot in three different modes:

🔹 1. Command-Line Interface (CLI)
To start the chatbot from the terminal:
bash
Copy
Edit
python main.py

🔹 2. FastAPI (Web API)
To run the bot as a web service:

bash
Copy
Edit
uvicorn main:app --reload
Access the API at:
http://127.0.0.1:8000

🔹 3. Streamlit UI
To run the Streamlit-based interface:

bash
Copy
Edit
streamlit run ui.py
The Streamlit app will open in your browser at:
http://localhost:8501

Technologies Used
Python
FastAPI – For web API development
Streamlit – For browser-based user interface
main.py – Core logic (CLI + FastAPI endpoints)
ui.py – Streamlit frontend
requirements.txt – Package dependencies

License
This project is open source and available under the MIT License.

Author
👤 Mohamed Afzal S
