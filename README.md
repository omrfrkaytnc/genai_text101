# genai_text101

Welcome to `genai_text101`, a comprehensive project demonstrating the integration of multiple AI models into Python applications. This repository showcases the usage of several generative AI models, including OpenAI's GPT-4, Anthropic's Claude, Cohere's Command, Google's Gemini, and open-source models like Llama 2 and Mixtral. Each model is integrated into a Streamlit application, allowing for interactive communication with users.

## Overview

This repository contains several Python scripts, each demonstrating how to connect and interact with different generative AI models through their respective APIs. The primary objective of this project is to provide a hands-on example of building chat applications that can answer user queries using different AI services.

## Features

- **OpenAI GPT-4**: Interactive chat application leveraging OpenAI's GPT-4 model.
- **Anthropic Claude**: Streamlit interface to interact with Claude, a model from Anthropic.
- **Cohere Command**: Cohere's AI model integrated into a chat application.
- **Google Gemini**: Utilizing Google's Gemini model for generating responses.
- **Open-Source Models**: Implementations using open-source models like Llama 2 and Mixtral via the Replicate platform.

## Repository Structure

- `app.py`: Demonstrates the integration of OpenAI's GPT-4 model.
- `chat.py`: A chat interface built with Streamlit, utilizing OpenAI's GPT-4 model for interactive communication.
- `claude.py`: Implements a chat interface for Anthropic's Claude model.
- `command.py`: A Streamlit-based chat application using Cohere's Command model.
- `gemini.py`: Integrates Google's Gemini model into a chat interface.
- `open_source.py`: Examples of using open-source models Llama 2 and Mixtral for generating AI responses.

## Getting Started

### Prerequisites

- Python 3.7+
- Streamlit
- dotenv
- Necessary API keys for each model (OpenAI, Anthropic, Cohere, Google, Replicate)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/genai_text101.git
   cd genai_text101
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
3. Set up your environment variables:
Create a .env file in the root directory and add your API keys:
   ```env
    openai_apikey=your_openai_api_key
    anthropic_apikey=your_anthropic_api_key
    cohere_apikey=your_cohere_api_key
    google_apikey=your_google_api_key
    replicate_apikey=your_replicate_api_key

### Running the Applications

Each script is a standalone application that can be run independently. 
For example, to run the OpenAI chat application:

   ```bash
   streamlit run chat.py



### Running the Applications

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.


### License

This project is licensed under the MIT License.
