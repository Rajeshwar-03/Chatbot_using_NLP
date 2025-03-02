# Chatbot_using_NLP
Training for the project on implementation of Chatbot using NLP
Chatbot with SQLite Logging
This project is a simple intent-based chatbot built in Python. The chatbot uses natural language processing techniques with NLTK for text processing, scikit-learn's TF-IDF vectorization and Logistic Regression for intent classification, and SQLite for logging conversations.

Features
Predefined intents with multiple example phrases and responses
Text preprocessing that removes punctuation, tokenizes, and lemmatizes input sentences
TF-IDF vectorization to convert text into numerical features
Logistic Regression classifier with a configurable confidence threshold to decide on responses
Fallback mechanism when the classifier's confidence is too low
SQLite database integration to log every conversation (including timestamps, user messages, and bot responses)
Debug output for viewing probability distributions during predictions
Requirements
Python 3.x
nltk
scikit-learn
numpy
sqlite3 (included with Python)
Installation
Clone the repository:

Change into the project directory:

(Optional) Create and activate a virtual environment:

Install the required packages:

If a requirements.txt file is not provided, install dependencies manually:

Setup
The project automatically downloads the necessary NLTK packages (punkt and wordnet) on first run. Ensure you have an internet connection when you run the script for the first time.

Usage
Run the chatbot script with:

Type your message and press Enter. To exit the chat, type quit. All conversations are logged in an SQLite database file named chatbot.db under the table chat_logs.

Logging
Each conversation is stored in the chat_logs table with the following columns:

id: Unique identifier for each record
timestamp: Date and time when the conversation took place
user_message: The user's message
bot_response: The chatbot's response
Debugging
For every user input, the script prints the probability distribution across the intents. This helps in understanding how the classifier interprets the input and aids in tuning the model. You can comment out or remove the debug print statement if you do not wish to see this output.

License
This project is open source and available under the MIT License.

Contact
For any questions or issues, please reach out via email at 22bk1a6611@stpetershyd.com

