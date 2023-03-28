# AI-Chatbot-Luna-
*By Bamboothesecond

Introduction
This code is a Python program for a GUI-based chatbot that uses OpenAI's ChatCompletion API to generate responses. The chatbot model used is gpt-3.5-turbo, which is a highly advanced model developed by OpenAI.

The program has a clear history feature that allows the user to clear the chat log and start a new conversation. The conversation history is stored in a list called message_log, which contains a series of dictionaries representing the messages exchanged between the user and the chatbot.

The program creates a queue to communicate between the GUI and the background thread. The background thread handles incoming messages and sends them to the chatbot, and then receives the chatbot's response and sends it back to the GUI. The GUI consists of a text field for the user to input messages and a chat log that displays the conversation history.
