
# Chatbot Using NLP

This project implements a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand user inputs and respond based on predefined intents.

## Features
- **Intent-Based Responses:** Uses a JSON file to define intents and responses.
- **NLP Processing:** Utilizes tokenization and pattern matching for user input.
- **GUI Interface:** Built with a modern and user-friendly interface.
- **Conversation History:** Tracks and displays past messages.

## Screenshot
Below is a screenshot of the chatbot interface:
![Screenshot 2025-03-12 185201](https://github.com/user-attachments/assets/48a55ec8-3c28-436b-93fe-768aca35ffa1)



## Project Structure
- `chatbot.py` - The main Python script for running the chatbot.
- `Implementation of ChatBot.ipynb` - A Jupyter Notebook explaining the implementation in detail.
- `intents.json` - A JSON file containing chatbot intents and responses.
- `Screenshot 2025-03-12 185201.png` - A screenshot of the chatbot UI.

## Installation

### Prerequisites
Ensure you have Python installed (version 3.6 or higher) and install the required libraries:

```bash
pip install nltk tensorflow keras tk
```

### Running the Chatbot
To start the chatbot, run the following command:

```bash
python chatbot.py
```

## How It Works
1. The chatbot loads predefined intents from `intents.json`.
2. It processes user input using NLP techniques.
3. Based on the best-matched intent, the chatbot provides a response.
4. The GUI displays the conversation.

## Customization
You can add more intents in `intents.json` to improve chatbot responses.

## License
This project is open-source and available for modification and distribution.

