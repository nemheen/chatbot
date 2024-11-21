# Chatbot for Intent Recognition

This repository contains a simple chatbot implementation designed to recognize user intents and provide predefined responses. The chatbot is built using a **TensorFlow Keras Sequential Model** and trained on labeled intent data stored in a JSON file. 

## Features
- **Text Classification:** Recognizes user intent from input text using a trained neural network.
- **Customizable Intents:** Easily modify the `intents.json` file to add or update intents and responses.
- **Preprocessing and Tokenization:** Utilizes text tokenization and sequence padding to handle user inputs effectively.
- **Persistence:** Saves the trained model, tokenizer, and label encoder for reuse without retraining.
- **Interactive Chat:** Engages with users through a command-line interface.


## Example Conversation
```
Start messaging with the bot (type quit to stop)!
User: Hi
ChatBot: Hello! How can I assist you today?
User: I want to know about shipping.
ChatBot: Sure, shipping usually takes 3-5 business days. Let me know if you have more questions.
User: Quit
```
