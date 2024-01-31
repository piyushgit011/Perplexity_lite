# Perplexity Lite Using LangGraph, GPT-3, and Tavily AI:

In this tutorial, I have utilized LangGraph, a library designed for building stateful, multi-actor applications. LangGraph, built on LangChain, allows for the coordination of multiple 'actors' in a cyclical computation process. This is particularly useful for adding cycles to your LLM applications, extending beyond the capabilities of a traditional DAG framework.

I also used Tavily AI, an incredible tool for rapid insights and comprehensive research. Tavily AI streamlines the research process, from source gathering to organizing results, making it an invaluable asset for developers.

Of course, the project wouldn't be complete without discussing GPT-3, a large language model that's pivotal in the development of advanced AI applications.

By combining these tools, I've managed to create an application similar to Perplexity AI, known for its ability to unlock knowledge through information discovery and sharing.

Modules used in the code:-

Create_openai_functions_agent in LangChain agents is a method used to create an agent that utilizes OpenAI's APIs for function-enabled API tasks . 
The method takes three arguments: 

llm: A BaseLanguageModel instance, which represents the language model to be used by the agent. 

tools: A Sequence[BaseTool] instance, which represents the tools to be used by the agent.
