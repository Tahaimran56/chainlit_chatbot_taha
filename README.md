                                    chatbot(chainlit)
Chainlit is an open-source Python framework designed to make it incredibly easy to build conversational AI applications directly in Python.
Think of it as a tool to rapidly create user interfaces for things like chatbots, AI assistants, and applications driven by Large Language Models (LLMs).

uv add openai-agents python-dotenv chainlit
Give these commands to run the project:

cd chatbot

uv venv
On Mac:

source .venv/bin/activate
Using uv to run the project

When we initiated our project with UV, it created a default file named main.py. Delete it and create an file:

chatbot.py

uv run chainlit run main.py -w
learn-agentic-ai/01_ai_agents_first/06_chatbot/chatbot at main · panaversity/learn-agentic-ai
