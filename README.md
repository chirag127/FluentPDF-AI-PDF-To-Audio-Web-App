# Spokable-PDF-AI-Driven-Text-to-Speech-Web-App
## VISUAL AUTHORITY
[![Build Status](https://img.shields.io/github/actions/status/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/ci?branch=main&style=flat-square)](https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App?style=flat-square)](https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App?style=flat-square)](https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/stargazers)

## BLUF
Spokable is a browser-based, fully client-side web app that leverages Cerebras Inference and OpenAI's SDK to transform technical PDFs into natural spoken language, enabling seamless text-to-speech integration without any server.

## TABLE OF CONTENTS
- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [AI Agent Directives](#ai-agent-directives)
- [Contributing](#contributing)
- [License](#license)

## OVERVIEW
This web app utilizes the latest advancements in AI to provide an unparalleled user experience. By integrating Cerebras Inference, we ensure high-quality, efficient, and secure text-to-speech conversion.

## FEATURES
- **AI-Driven Text-to-Speech**: Leverage Cerebras Inference for accurate and natural speech synthesis.
- **Client-Side**: All processing occurs within the browser, ensuring privacy and security.
- **PDF Support**: Easily convert technical PDFs into spoken language.

## SETUP
1. Clone the repository: `git clone https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App.git`
2. Install dependencies: `npm install`
3. Start the application: `npm start`

## AI AGENT DIRECTIVES
### Client Configuration
* **Base URL:** `https://api.cerebras.ai/v1`
* **API Key Variable:** `CEREBRAS_API_KEY`
* **Library:** Use the standard `openai` Node.js library.
javascript
const { OpenAI } = require('openai');
const client = new OpenAI({
  base_url: 'https://api.cerebras.ai/v1',
  api_key: process.env.CEREBRAS_API_KEY
});

### Model Hierarchy (Fallback Cascade)
Always attempt the highest-parameter model first for complex reasoning, cascading down for speed.
* **Tier 1 (Frontier Intelligence):** `zai-glm-4.6` (357B)
* **Tier 2 (Heavy Reasoning):** `qwen-3-235b-a22b-instruct-2507` (235B)
* **Tier 3 (General Purpose):** `gpt-oss-120b` (120B)
* **Tier 4 (Balanced Workhorse):** `llama-3.3-70b` (70B)
* **Tier 5 (Fast Inference):** `qwen-3-32b` (32B)
* **Tier 6 (Ultra-Fast/Instant):** `llama3.1-8b` (8B)

## CONTRIBUTING
See [CONTRIBUTING.md](https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/blob/main/CONTRIBUTING.md) for details on how to contribute to this project.

## LICENSE
This project is licensed under the [CC BY-NC 4.0](https://github.com/chirag127/Spokable-PDF-AI-Driven-Text-to-Speech-Web-App/blob/main/LICENSE) license.