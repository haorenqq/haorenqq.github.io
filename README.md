# ChatGPT-web

## **URL**: https://niek.github.io/chatgpt-web/

ChatGPT-web is a simple one-page web interface to the OpenAI ChatGPT model. To use it, you need to register for an API key at https://platform.openai.com/account/api-keys first. All messages are stored in your browser's local storage, so you can close the tab and come back later to continue the conversation.

## Why?

Why not use the [official ChatGPT interface](https://chat.openai.com/)? Becauce ChatGPT-web will allow more customization, and since it uses the commercial OpenAI API it should be more reliable. It's also *much* cheaper than ChatGPT Pro - at $20 per month, you would need to use *10 million* tokens on the OpenAI API for this to break even. Finally, since ChatGPT-web is open source, so you can host it yourself and make changes as you want.

## Development

To run the development server, run

```bash
npm ci
npm run dev # or: npm run build
```