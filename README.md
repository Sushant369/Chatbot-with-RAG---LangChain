# RAG Chatbot using LangChain, OpenAI, and Pinecone

### This project demonstrates the creation of an AI chatbot utilizing LangChain, OpenAI, and Pinecone vector DB. The chatbot uses the Retrieval Augmented Generation (RAG) technique to learn from external sources, specifically geared towards the latest developments in Generative AI.

## Features
- AI chatbot capable of holding informative conversations.
- Uses a dataset from the Llama 2 ArXiv paper, among other sources.
- Integrates multiple technologies including LangChain and OpenAI.

### Architecture

The RAG Chatbot is built on a three-component architecture:

1. **LangChain**: Manages the flow of the conversation and decision-making processes, determining when to call retrieval models or directly generate responses.
2. **OpenAI (GPT-3.5 Turbo)**: Acts as the backbone for generating responses based on the input and context provided by LangChain.
3. **Pinecone Vector DB**: Stores and retrieves data used to augment the generative capabilities of GPT-3.5, facilitating context-rich responses.

### Technology Stack

- **Programming Language**: Python 3.8
- **Frameworks/Libraries**: LangChain, OpenAI, Pinecone-client, `datasets`, `tiktoken`
- **APIs**: OpenAI API, Pinecone API
- **Tools**: Jupyter Notebook

### Data Flow Diagram

Below is a simple diagram illustrating the flow of data through the chatbot system:

![image](https://github.com/Sushant369/Chatbot-with-RAG---LangChain/assets/72655705/e79e8d55-2836-4a38-b06e-7ab013a87142)

- **User Input**: User asks a question.
- **LangChain**: Decides the response strategy.
- **Pinecone DB**: Retrieves relevant information.
- **OpenAI**: Generates the final response based on the augmented data.

### API References

The chatbot utilizes the following APIs:

- **OpenAI API**: Used for generating text responses. [API Documentation](https://beta.openai.com/docs/)
- **Pinecone API**: Used for vector database management. [API Documentation](https://www.pinecone.io/docs/)

