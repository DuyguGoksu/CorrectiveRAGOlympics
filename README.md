# Corrective RAG Olympics
Welcome to the Corrective RAG Model GitHub repository, designed to answer questions related to the Paris 2024 Olympics. This project leverages the GPT-3.5-turbo model via API calls to OpenAI and uses a Corrective Retrieval-Augmented Generation (CRAG) approach to enhance the accuracy and relevance of responses.

## Project Overview
This repository contains code and resources for a Corrective RAG model that retrieves and generates answers about the Paris 2024 Olympics. The model is designed to provide precise and up-to-date information by retrieving data from relevant sources before generating a response.

Here are the sources:

- [Paris Discovery Guide](https://www.parisdiscoveryguide.com/paris-2024-olympics-visitors-guide.html)
- [GigSky Blog](https://www.gigsky.com/blog/travelers-guide-to-the-paris-2024-olympics-tips-for-an-unforgettable-experience)
- [Olympics Guide](https://olympics.com/en/news/paris-olympics-2024-guide-preview-venues-new-events-torch-mascots-and-how-to-watch-live)

If any of the documents retrieved are irrelevant to the question, the model performs a web search using Tavily Search.

The implementation of the Corrective RAG model in this project is based on the example provided by LangChain. You can find the reference code [here](https://github.com/langchain-ai/langgraph/blob/main/examples/rag/langgraph_crag.ipynb)
