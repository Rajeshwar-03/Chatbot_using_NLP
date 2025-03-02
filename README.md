# Chatbot using NLP

## Description
This project implements a simple chatbot using Natural Language Processing (NLP) techniques with `nltk`, `scikit-learn`, and `streamlit` for the user interface. The chatbot is designed to recognize user input patterns and provide appropriate responses based on predefined intents.

## Features
- Recognizes and responds to greetings, farewells, and common user queries.
- Utilizes `nltk` for tokenization and preprocessing.
- Uses `scikit-learn` for text vectorization and classification.
- Provides a user-friendly interface with `streamlit`.

## Installation
### Prerequisites
Ensure you have Python installed (Python 3.13 recommended).

### Install Dependencies
Run the following command to install required packages:
```sh
pip install nltk scikit-learn streamlit
```

## Usage
1. Run the chatbot using Streamlit:
```sh
streamlit run chatbot.py
```
2. Interact with the chatbot through the web-based interface.

## Project Structure
- `chatbot.py` - Main script containing chatbot logic and Streamlit UI.
- `nltk_data/` - Directory for storing downloaded `nltk` data.
- `requirements.txt` - List of dependencies for easy installation.

## Intents
The chatbot recognizes the following intents:
- **Greeting**: Responds to "Hi", "Hello", etc.
- **Goodbye**: Recognizes farewells.
- **Thanks**: Acknowledges gratitude.
- **About**: Provides chatbot information.
- **Help**: Offers assistance.
- **Age**: Responds to age-related queries.
- **Weather**: Provides basic weather information.
- **Budgeting**: Offers budgeting advice.
- **Credit Score**: Explains credit scores and how to check them.

## Dependencies
- `nltk` (Natural Language Toolkit)
- `scikit-learn` (Machine Learning for text classification)
- `streamlit` (Web UI framework)

## License
This project is open-source and available under the MIT License.

## Author
Developed by BADDAM RAJESHWAR REDDY

