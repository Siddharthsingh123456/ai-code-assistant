# AI Code Assistant

An AI-powered coding workspace for asking questions about code, understanding unfamiliar snippets, reviewing implementation choices, optimizing code, and drafting tests.

## Features

- Explain code and programming concepts
- Review code for potential issues
- Suggest readability and performance improvements
- Generate test ideas and example tests
- Work across multiple programming languages
- Server-side AI integration
- Optional MongoDB persistence for saved reviews

## Technology

- React 18 and Vite 5
- Node.js 24
- Express and Mongoose
- MongoDB
- OpenAI-compatible model API
- Vercel deployment configuration

## Requirements

- Node.js 24.x and npm
- AI provider API key
- MongoDB URI if database persistence is required

## Local setup

```bash
git clone https://github.com/Siddharthsingh123456/ai-code-assistant.git
cd ai-code-assistant
npm install
```

Create `.env` from the supplied `.env.example`:

```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```

Do not commit secrets or paste confidential source code into external AI services.

## Run and build

```bash
npm run dev
npm run build
npm run preview
```

The `check` script runs the production build:

```bash
npm run check
```

## Deployment

Deploy the repository root with Vercel. Add required environment variables in the Vercel project settings and inspect deployment logs after publishing.

## Responsible use

AI-generated suggestions can be incorrect or insecure. Review all generated code, run tests, and perform security checks before merging or deploying it. Do not treat generated code as a substitute for code review.

## License

No license file is currently specified. Contact the repository owner for reuse permissions.
