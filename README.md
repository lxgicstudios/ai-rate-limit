# ai-rate-limit

[![npm version](https://img.shields.io/npm/v/ai-rate-limit.svg)](https://www.npmjs.com/package/ai-rate-limit)
[![npm downloads](https://img.shields.io/npm/dm/ai-rate-limit.svg)](https://www.npmjs.com/package/ai-rate-limit)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-rate-limit)](https://github.com/lxgic-studios/ai-rate-limit/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate rate limiting configurations using AI.

## Install

```bash
npm install -g ai-rate-limit
```

## Usage

```bash
npx ai-rate-limit "100 requests per minute per IP"
npx ai-rate-limit "10 login attempts per hour, block for 30 min"
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
