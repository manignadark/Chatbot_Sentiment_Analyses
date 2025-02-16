# Chatbot with Sentiment Detection

## Overview

This project is a simple chatbot application built using Flask and Natural Language Processing (NLP) techniques. The purpose of this project is to demonstrate how to create a chatbot that can analyze the sentiment of user messages and respond accordingly.

## Features

- User-friendly interface for chatting
- Sentiment detection of user inputs (positive, negative, neutral)
- Logs conversation history

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Installation

Follow these steps to get your development environment set up:

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/chatbot_project.git
cd chatbot_project

1. Set up a virtual environment (optional but recommended):

python -m venv chatbot_env
source chatbot_env/bin/activate  # For macOS/Linux
chatbot_env\Scripts\activate     # For Windows

1. Install the required packages:

pip install -r requirements.txt

Running the Application

Once you have everything installed, you can run the application by executing:

python app.py

This will start a local server (typically at http://127.0.0.1:5000) where you can access the chatbot.

Usage

1. Open your web browser and navigate to http://127.0.0.1:5000.

2. Type a message in the input box and click the "Send" button.

3. The chatbot will respond based on the sentiment of your message.

Additional Information

- Ensure that you have Python 3.x installed on your machine.

- You may have to download additional NLTK data by running the following commands in a Python shell:

import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('vader_lexicon')

License

This project is licensed under the MIT License. See the LICENSE file for more information.

Contributing

1. Fork the project.

2. Create your feature branch (git checkout -b feature/YourFeature).

3. Commit your changes (git commit -m 'Add some feature').

4. Push to the branch (git push origin feature/YourFeature).

5. Open a Pull Request.

Acknowledgments

- Flask - Micro web framework for Python.

- NLTK - Natural Language Toolkit for Python.

For any inquiries, feel free to reach out to [your email] or raise issues in the project repository.

### Customization

- Replace `yourusername/chatbot_project.git` with the link to your actual GitHub repository.
- You can add more features or instructions based on the specifics of your project and its requirements.
- Include your contact information or preferred methods for reaching you regarding project issues or contributions.
