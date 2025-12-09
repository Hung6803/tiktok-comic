# TikTok Comic Generator

Generate TikTok-style comic stories using AI (DeepSeek + Gemini).

## Features

- **Single Mode**: Create standalone comic stories (1-50 panels)
- **Series Mode**: Create multi-episode series (1-100 episodes)
- **Spinoff Mode**: Create spin-off stories from existing stories
- **AI Integration**: DeepSeek for text, Gemini for images
- **Hybrid Mode**: Gemini for outlines, DeepSeek for panel details
- **Character Management**: Create and manage characters with visual descriptions
- **Story Storage**: Save and load stories to continue later

## Installation

```bash
npm install
```

## Configuration

Copy `.env.example` to `.env` and configure:

```bash
cp .env.example .env
```

Environment variables:
- `PORT`: Server port (default: 3002)
- `HOST`: Server host (default: 0.0.0.0)

## Usage

Development:
```bash
npm run dev
```

Production:
```bash
npm start
```

## API Keys Required

- **DeepSeek API Key**: For text generation
- **Gemini API Key**: For image generation

Enter your API keys in the Settings panel of the web interface.

## Tech Stack

- Backend: Node.js, Express.js
- Frontend: Vanilla JavaScript, Tailwind CSS
- AI: DeepSeek API, Google Gemini API
