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
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

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
   ```
Replace chat.py with the respective script name to run other applications.

### Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.


### License

This project is licensed under the MIT License.

---

# genai_text101

`genai_text101` projesine hoş geldiniz. Bu proje, birden fazla yapay zeka modelinin Python uygulamalarına entegrasyonunu göstermektedir. Bu depo, OpenAI'nin GPT-4'ü, Anthropic'in Claude'u, Cohere'nin Command'i, Google'ın Gemini'si ve Llama 2 ve Mixtral gibi açık kaynak modeller de dahil olmak üzere çeşitli üretken yapay zeka modellerinin kullanımını göstermektedir. Her model, kullanıcılarla etkileşimli iletişim sağlayan bir Streamlit uygulamasına entegre edilmiştir.

## Genel Bakış

Bu depo, her biri farklı üretken yapay zeka modellerine kendi API'ları aracılığıyla nasıl bağlanılacağını ve bunlarla nasıl etkileşime girileceğini gösteren çeşitli Python betiklerini içermektedir. Bu projenin temel amacı, farklı yapay zeka hizmetlerini kullanarak kullanıcı sorgularını yanıtlayabilen sohbet uygulamaları oluşturmanın uygulamalı bir örneğini sağlamaktır.

## Özellikler

- **OpenAI GPT-4**: OpenAI'nin GPT-4 modelinden yararlanan etkileşimli sohbet uygulaması.
- **Anthropic Claude**: Anthropic'in Claude modeli ile etkileşim kurmak için Streamlit arayüzü.
- **Cohere Command**: Cohere'nin AI modelini kullanan bir sohbet uygulaması.
- **Google Gemini**: Google'ın Gemini modelini kullanarak yanıtlar oluşturan uygulama.
- **Açık Kaynak Modeller**: Llama 2 ve Mixtral gibi açık kaynak modelleri kullanarak yapay zeka yanıtları oluşturan uygulamalar.

## Depo Yapısı

- `app.py`: OpenAI'nin GPT-4 modelinin entegrasyonunu gösterir.
- `chat.py`: OpenAI'nin GPT-4 modelini kullanarak etkileşimli iletişim sağlayan bir Streamlit sohbet arayüzü.
- `claude.py`: Anthropic'in Claude modeli için bir sohbet arayüzü uygular.
- `command.py`: Cohere'nin Command modelini kullanan Streamlit tabanlı bir sohbet uygulaması.
- `gemini.py`: Google'ın Gemini modelini bir sohbet arayüzüne entegre eder.
- `open_source.py`: Llama 2 ve Mixtral gibi açık kaynak modelleri kullanarak yapay zeka yanıtları oluşturan örnekler.

## Başlarken

### Gereksinimler

- Python 3.7+
- Streamlit
- dotenv
- Her model için gerekli API anahtarları (OpenAI, Anthropic, Cohere, Google, Replicate)

### Kurulum

1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/yourusername/genai_text101.git
   cd genai_text101
   ```
2. Gerekli Python paketlerini yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

3. Ortam değişkenlerinizi ayarlayın:
Kök dizinde bir .env dosyası oluşturun ve API anahtarlarınızı ekleyin:
   ```env
    openai_apikey=your_openai_api_key
    anthropic_apikey=your_anthropic_api_key
    cohere_apikey=your_cohere_api_key
    google_apikey=your_google_api_key
    replicate_apikey=your_replicate_api_key
   ```

### Uygulamaları Çalıştırma

Her betik bağımsız olarak çalıştırılabilen bir uygulamadır.
Örneğin, OpenAI sohbet uygulamasını çalıştırmak için:

   ```bash
   streamlit run chat.py
   ```
### Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.
Diğer uygulamaları çalıştırmak için chat.py dosya adını ilgili betik adıyla değiştirin.
