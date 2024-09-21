# Sophia Chatbot

Sophia is a simple web-based chatbot that provides greetings and responses using a Hugging Face model. The chatbot is built with Python (Flask for the backend) and HTML for the frontend, using jQuery and Bootstrap for styling.

## Features
- Interactive chatbot with a user-friendly interface
- Uses Hugging Face model for natural language processing
- Simple greeting functionalities

## Technologies Used
- **Python (Flask):** Backend framework used to handle HTTP requests.
- **Hugging Face:** Model used for text processing and responses.
- **HTML/CSS:** For designing the user interface.
- **Bootstrap & jQuery:** Used for responsive design and AJAX functionality.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Ayoona22/Sophia_Chatbot.git
cd Sophia_Chatbot
```

### 2. Install Dependencies
Make sure you have Python installed. Install the required packages by running:
```bash
pip install -r req.txt
```

### 3. Run the Application
After installing the dependencies, you can run the Flask app by executing:
```bash
python app.py
```

### 4. Open in Browser
Once the app is running, open your browser and go to:
```bash
http://127.0.0.1:5000
```

### 5. Chat with Sophia!
You can now chat with Sophia through the web interface. Type your message in the input box, and the bot will reply with simple responses.

## File Structure
```bash
.
├── app.py              # Backend Python script
├── templates
│   └── chat.html       # Frontend HTML file for chat interface
├── static
│   └── style.css       # Optional: Add styles for the chatbot UI
└── req.txt    # Python dependencies
```

## Future Improvements
- Improve the bot's intelligence to handle more complex conversations.
- Add more features like storing chat history.
- Allow users to switch between different conversation models.

#### Author - Ayoona Maria John



