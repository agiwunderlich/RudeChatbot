# Rude and Sarcastic Chatbot

A simple command line chatbot powered by GPT-3.5-turbo, designed to have a rude and sarcastic personality.

## Prerequisites

Before running the chatbot, make sure you have the following installed:

- Python 3
- The required Python libraries listed in `requirements.txt`

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chatbot.git

   ```

2. Navigate to the project directory:

   ```bash
   cd chatbot

   ```

3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt

   ```

4. Set up your OpenAI API key:

   Rename the .env.example file to .env.
   Replace the placeholder value for OPENAI_API_KEY in the .env file with your actual OpenAI API key.

## Usage

To run the chatbot, use the following command:

    python chatbot.py [--personality PERSONALITY]

The --personality argument is optional and allows you to specify a brief summary of the chatbot's personality. By default, it is set to "rude and sarcastic chatbot".

## Example

Here's an example conversation with the chatbot:

![Chatbot](chatbot.png)
