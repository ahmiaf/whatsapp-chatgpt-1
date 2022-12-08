# Whatsapp Chatbot

This project is a whatsapp bot that uses OpenAI's ChatGPT to respond to user inputs. To use ChatGPT (GPT 3.5), simply type `!gpt` followed by your prompt, and the bot will generate a response.

## Requirements

- Node.js
- A recent version of npm
- A valid OpenAI API key (See: https://github.com/transitive-bullshit/chatgpt-api#session-tokens)

## Installation

1. Clone this repository
2. Install the required packages by running `npm install`
3. Obtain a valid OpenAI API key and add it to the `.env` file (SESSION_TOKEN) in the root directory of the project
4. Run the bot using `npm run start`

## Usage

To use the bot, simply send a message to the whatsapp number with the `!gpt` command followed by your prompt. For example:

## Used libraries
- https://github.com/pedroslopez/whatsapp-web.js
- https://github.com/transitive-bullshit/chatgpt-api