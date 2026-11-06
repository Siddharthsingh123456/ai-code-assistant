# AI Code Assistant

An AI-assisted coding workspace for understanding, reviewing, optimizing, and testing code across programming languages.

## Features
- Explain code and programming concepts
- Review snippets for potential issues
- Suggest readability and performance improvements
- Draft test cases and examples
- Server-side AI integration and optional MongoDB persistence
- Responsive developer-focused interface

## Stack
React 18 · Vite 5 · Node.js 24 · Express · Mongoose · MongoDB · OpenAI-compatible API · Vercel

## Requirements
Node.js 24.x, npm, an AI provider API key, and MongoDB URI if persistence is enabled.

## Setup
```bash
git clone https://github.com/Siddharthsingh123456/ai-code-assistant.git
cd ai-code-assistant
npm install
```
Create `.env` using `.env.example`:
```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```
Never commit real credentials.

## Run
```bash
npm run dev
npm run build
npm run preview
```
`npm run check` runs the production build.

## Deploy
Import the repository root into Vercel and configure required environment variables. Verify API routes and database connectivity after deployment.

## Safety
AI-generated code can be incorrect or insecure. Review suggestions, run tests, and perform security checks before using generated code in production. Do not submit confidential source code to external services without authorization.

## License
No license file is currently specified. Contact the repository owner before reuse.
