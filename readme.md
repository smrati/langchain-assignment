# Langchain Assignment
1. Write a script using langchain library to call a LLM using Ollama as provider. In this script, pass a prompt to llm and print its response
2. Read a txt file given [here](https://www.gutenberg.org/cache/epub/84/pg84.txt)   
using langchain text splitters convert this file into chunks such that no chunk has more than 1000 words in it.
3.  Create a terminal based chatbot using langchain which takes input from user using stdin and show response on stdout. Chatbot must maintain full memory of conversation.
Example: Let say user mentioned that he likes chinese food and ask llm to give it recipe for a chinense dish. LLM should respond with the recipe. Now in further communication if user ask "Give me recipe for another dish", chatbot should have a memory from previous conversation that user is talking about chinese food recipe only  