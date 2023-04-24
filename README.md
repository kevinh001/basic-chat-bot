Chat Bot
This is a simple chat bot that can answer questions and learn from new input. The bot is designed to use a knowledge base stored in a JSON file. The JSON file contains a list of questions and answers that the bot can use to respond to user input.

Getting Started
Install Python (if not already installed) from the official website.
Download the project files to your computer.
Open a terminal or command prompt and navigate to the project directory.
Run the command pip install -r requirements.txt to install the required dependencies.
Run the command python main.py to start the chat bot.
How to Use
Once the chat bot is running, you can ask it questions or teach it new things. Here's an example conversation:

vbnet
Copy code
You: What is the capital of France?
Bot: Paris
You: Who invented the telephone?
Bot: Alexander Graham Bell
You: What is the tallest mountain in the world?
Bot: I don't know the answer. Can you teach me?
Type the answer or "skip" to skip: Mount Everest is the tallest mountain in the world.
Bot: Thank you! I learned a new response.
You: Quit
If the bot knows the answer to a question, it will respond with the answer. If it doesn't know the answer, it will ask you to teach it and store the new question and answer in the knowledge base.

To exit the chat bot, type "quit" at any time.

Modifying the Knowledge Base
The knowledge base is stored in the file knowledge_base.json. You can modify this file to add or remove questions and answers. Here's an example of the file structure:

json
Copy code
{
  "questions": [
    {
      "question": "What is the capital of France?",
      "answer": "Paris"
    },
    {
      "question": "Who invented the telephone?",
      "answer": "Alexander Graham Bell"
    }
  ]
}
Each question and answer is stored as a JSON object in the "questions" array. To add a new question and answer, you can simply add a new JSON object to the array:

json
Copy code
{
  "question": "What is the tallest mountain in the world?",
  "answer": "Mount Everest"
}
Make sure to save the file after making any changes.

Troubleshooting
If you encounter any errors while running the chat bot, please make sure that you have installed Python and the required dependencies as described in the "Getting Started" section. If you continue to have issues, please consult the Python documentation or seek help from the Python community.

Contributing
If you'd like to contribute to this project, please fork the repository and create a new branch for your changes. Once you've made your changes, submit a pull request and we'll review your changes. Thank you for your contribution!
