# Enhanced Q&A Chatbot with OLLAMA

A Streamlit-based chatbot application that leverages open-source language models through OLLAMA for question-answering interactions.

## Features

- Interactive web interface built with Streamlit
- Support for multiple open-source LLMs (llama3.2, gemma2:2b, mistral:7b)
- Adjustable response parameters (temperature and max tokens)
- LangSmith integration for tracking and monitoring
- Simple and intuitive user interface

## Prerequisites

```bash
pip install streamlit langchain-core langchain-community python-dotenv ollama
```

You'll also need:
- OLLAMA installed and running on your system
- LangSmith API key (for tracking)

## Environment Setup

Create a `.env` file in your project root with:

```
LANGCHAIN_API_KEY=your_langsmith_api_key_here
```

## Usage

1. Start OLLAMA service on your system
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
3. Access the web interface (localhost)
4. Select your preferred model and adjust parameters in the sidebar
5. Enter your question in the text input field
6. View the generated response

## Components

- **Model Selection**: Choose between llama3.2, gemma2:2b, and mistral:7b
- **Temperature Control**: Adjust response creativity (0.0 to 1.0)
- **Max Tokens**: Control response length (50 to 300 tokens)
- **Real-time Response**: Get immediate answers with loading indicator

## LangSmith Integration

The application includes LangSmith tracking for monitoring and analyzing:
- Model performance
- Response patterns
- Usage metrics

## Customization

You can modify the following parameters:
- Available models in the selection box
- Temperature range
- Token limits
- System prompt template
- UI elements and styling

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.