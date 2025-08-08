# 🤖 Rule-Based Chatbot Using NLTK
A simple rule-based chatbot built with Python and NLTK (Natural Language Toolkit). This chatbot uses pattern matching and basic natural language processing to provide responses to user input based on predefined rules.

## 📌 Features
-Basic conversational ability using regular expressions

-Predefined responses for greetings, name introduction, and help requests

-Humor: the bot can tell a joke!

-Graceful exit when user types 'exit'

-Easily extendable with more patterns and responses

## 🛠️ Technologies Used
Python 3.12

NLTK (Natural Language Toolkit)

### 🧠 How It Works
The chatbot uses the nltk.chat.util.Chat class which implements a simple rule-based NLP engine.
Each pattern is matched against user input using regular expressions, and a corresponding response is selected.

### 📂 Project Structure
```
AI_Chatbot_using_nltk.py      # Main Python script containing the chatbot logic
```
### 🚀 Getting Started

🔹 Prerequisites

Ensure you have Python installed. Then install NLTK:
```
pip install nltk 
```
🔹 Run the chatbot
```
python AI_Chatbot_using_nltk.py
```
You will see a prompt like:
```

Hello, I am your chatbot! Type 'exit' to end the conversation.
You:
```
### 💬 Example Interactions
```
You: hi
Chatbot: Hello! How can I help you today?

You: my name is Harini
Chatbot: Hello Harini! How can I assist you today?

You: tell me a joke
Chatbot: Why don't skeletons fight each other? They don't have the guts!

You: exit
Chatbot: Goodbye! Have a nice day!
```

### 🔄 Customize & Extend
You can easily extend this chatbot by adding more rules to the pairs list:
```
[r"what is your favorite color?", ["I love all colors equally!"]],
```
The format is:

```
[r"<regex_pattern>", ["response1", "response2", ...]]
```
