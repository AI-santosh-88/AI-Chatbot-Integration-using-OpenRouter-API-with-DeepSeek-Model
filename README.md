# Title:
AI Chatbot Integration using OpenRouter API with DeepSeek Model

# Description:
It demonstrates how to integrate a large language model (LLM) from OpenRouter's API (specifically using the deepseek/deepseek-r1:free model) into a Python application. The application sends user prompts to the model and receives conversational responses, simulating a chatbot-like interaction.

# Responsibilities:
1.API Integration:
* Set up and authenticate requests to the OpenRouter API using the OpenAI-compatible client.
* Manage base_url, api_key, and optional headers (HTTP-Referer, X-Title).
2.Model Selection and Prompting:
* Choose the appropriate model (deepseek/deepseek-r1:free) for the task.
* Send structured messages to the model in the OpenAI Chat Completions format.
3.Response Handling:
* Parse and display the model’s response from the returned JSON.
* Handle any API or network errors gracefully.
4.Customization:
* Allow dynamic user input or predefined prompts.
* Optionally adapt headers and body for ranking and analytics on OpenRouter.

# Packages :
* openai (used here as a stand-in to access OpenRouter; needs to support custom base URLs)
* Python standard libraries:
                  * os (for managing environment variables, if used)
                  * requests (if manually calling the API instead of using an OpenAI- compatible client)
   
# Summary:
This lightweight Python project integrates a third-party language model (DeepSeek via OpenRouter) into an application using an OpenAI-compatible interface. It serves as a foundation for developing AI-driven conversational systems, such as travel assistants or information bots. In this example, the bot answers a tourism-related query about New York City, showing practical use of the model for real-world information retrieval.









