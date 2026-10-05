# Coach

A personal, all-around life coach powered by [Mastra](https://mastra.ai) and deployed on the Mastra platform.

## Features

- **Coach agent** – supportive, direct coaching across health, habits, goals, and reflection
- **Memory** – remembers your goals, check-ins, and preferences across conversations
- **Tools** – set and track goals, log daily check-ins and wins, review progress
- **Workflows** – daily check-in and weekly review

## Getting Started

Requires Node.js 22.13+.

```bash
npm install
npm run dev
```

Open the Mastra playground at http://localhost:4111 to chat with your coach.

## Environment

Copy `.env.example` to `.env` and set your key:

```bash
cp .env.example .env
```

## Deploy

```bash
npm run build
```

Then deploy to the Mastra platform.

## License

MIT
