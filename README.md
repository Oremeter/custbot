# DCS Charging Solutions Chatbot

This project is a customer service chatbot for **DCS Charging Solutions**, built with LangChain's ReAct agent and deployed via Chainlit. The bot can provide general information and answer company-specific questions using OpenAI's language model and custom tools.

## Features
- **ReAct Agent**: Uses reasoning and acting (ReAct) framework to decide when to use company-specific knowledge or the language model.
- **Chainlit UI**: Provides an easy-to-use interface for interacting with the chatbot.
- **Company-Specific Tool**: Answers queries related to DCS's payment options, account assistance, and contact details.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/dcs-chatbot.git
    cd dcs-chatbot
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Add your OpenAI API key:
    - Create a `.env` file in the project root.
    - Add the following line to the `.env` file:
      ```env
      OPENAI_API_KEY=your_openai_api_key
      ```

## Usage

Run the application with Chainlit:
```bash
chainlit run app.py -w
