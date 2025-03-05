# Chatbot using NLP

## Description
This project implements a simple chatbot using Natural Language Processing (NLP) techniques with `nltk`, `scikit-learn`, and `streamlit` for the user interface. The chatbot is designed to recognize user input patterns and provide appropriate responses based on predefined intents.


## Features
- Recognizes and responds to greetings, farewells, and common user queries.
- Utilizes `nltk` for tokenization and text preprocessing.
- Uses `scikit-learn` for text vectorization and classification.
- Provides a user-friendly interface with `streamlit`.
- Can be expanded to include additional intents and responses.

## Requirements
Ensure Python is installed (Python 3.13 recommended). Install the necessary libraries before running the chatbot:
```sh
pip install nltk scikit-learn streamlit
```

## How It Works
1. The chatbot is trained on predefined intents (greetings, farewells, budgeting, etc.).
2. It uses TF-IDF vectorization to process and analyze user input.
3. Logistic Regression is used for classifying user queries.
4. Responses are selected randomly from predefined responses based on classification results.

## Running the Chatbot
1. Ensure all dependencies are installed.
2. Run the Python script to start the chatbot:
```sh
streamlit run chatbot.py
```
3. Interact with the chatbot through the web-based interface.

## Project Structure
- `chatbot.py` - Main script containing chatbot logic and Streamlit UI.
- `nltk_data/` - Directory for storing downloaded `nltk` data.
- `requirements.txt` - List of dependencies for easy installation.

## Example Interactions
```
User: Hello
Bot: Hi there!

User: How can I make a budget?
Bot: A good budgeting strategy is the 50/30/20 rule...
```

## Supported Intents
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

## Notes
- The chatbot currently works with predefined responses.
- Streamlit can be used to build a graphical interface for a better user experience.
- Future updates may include more advanced NLP techniques and real-time API integrations.

## Future Improvements
- Expand the dataset with more intents and responses.
- Integrate real-time data APIs (e.g., weather updates).
- Improve the model using deep learning techniques.
- Implement a feedback system to improve chatbot accuracy over time.

## License
This project is open-source and available under the MIT License.

## Author
Developed by BADDAM RAJESHWAR REDDY

