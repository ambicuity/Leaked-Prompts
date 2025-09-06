# Leaked-Prompts

A professional collection of reverse-engineered and system prompts for large language models, structured for educational and research purposes. This repository documents actual system prompts extracted from various AI platforms and services.

## Table of Contents

- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [File Naming Convention](#file-naming-convention)
- [Prompt Categories](#prompt-categories)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository serves as a detailed collection of system prompts and internal instructions extracted from various large language models (LLMs). The prompts are organized by AI platform and model version, documenting the actual system-level instructions used by these models in production environments.

### System Prompts by Platform

- **Anthropic**: Claude 4, Claude 3.5 (Sonnet, Sonnet Computer Use, Haiku), Claude 3 (Opus, Haiku) models and variants
- **Google**: Gemini 2.5 Pro, Gemini 2.0 (Flash, Flash Thinking), Gemini 1.5 (Pro, Flash), Gemini 1.0 Pro, Gemma 3 (270M-27B) models and variants  
- **OpenAI**: GPT-OSS (20B/120B), GPT-5, GPT-4o (standard, mini), GPT-4 Turbo, GPT-4, GPT-3.5 Turbo, O1 (reasoning), O1-Mini models and variants
- **Perplexity**: Perplexity AI models
- **Proton**: Proton's AI services
- **xAI**: Grok-2, Grok-2 Mini and other xAI models
- **Misc**: Meta Llama (3.3 70B, 3.2 90B/3B/1B, 3.1 405B/70B, Code Llama), Mistral (Large 2), Cohere (Command R+), DeepSeek (V3, R1), Qwen (3, 2.5 72B), Nomic Embed Text, GitHub Copilot, and other models

## Directory Structure

```
Leaked-Prompts/
├── README.md
├── LICENSE
├── Anthropic/          # Claude models and variants
├── Google/             # Gemini models and variants
├── Misc/               # Other models and platforms
├── OpenAI/             # GPT models and variants
├── Perplexity/         # Perplexity AI models
├── Proton/             # Proton's AI services
└── xAI/                # Grok and other xAI models
```

Each directory contains model-specific system prompts with their own README.md explaining the model's characteristics and documented prompt variations.

## File Naming Convention

All markdown files follow a consistent naming pattern for clarity and easy navigation:

```
[model-name]-[version]-[topic].md
```

**Examples:**
- `claude-4-advanced-constitutional-ai.md`
- `gpt-5-advanced-system-message.md`
- `gpt-4o-multimodal-system-message.md`
- `o1-reasoning-system-message.md`
- `gemini-2-5-pro-advanced-multimodal.md`
- `gemini-1-5-pro-advanced-multimodal-system-message.md`
- `claude-3-5-sonnet-full-system-message.md`
- `gpt-4-listener-personality.md`
- `llama-3-1-405b-flagship-system-message.md`
- `mistral-large-advanced-reasoning-system-message.md`
- `cohere-command-r-plus-enterprise-system-message.md`
- `github-copilot-ai-programming-assistant-system-message.md`

## Prompt Categories

### Base System Prompts
Core system instructions that define the fundamental behavior and constraints of each model. These establish the primary operational parameters.

### Tool-Enabled Prompts
System prompts that include instructions for using specific tools, APIs, or capabilities. These show how models integrate with external systems and functions.

### Personality and Persona Prompts
Advanced system prompts that define specific personalities, conversation styles, or behavioral patterns. These demonstrate how different interaction modes are configured.

## Contributing

We welcome contributions of new leaked prompts, improvements to existing documentation, and additional prompt variations. Please ensure:

1. Follow the established file naming convention
2. Include source information or extraction method when possible
3. Verify authenticity of system prompts when feasible
4. Maintain the research and documentation focus

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Topics

`ai` `prompts` `prompt-engineering` `llm` `large-language-models` `chatbots` `openai` `gemini` `anthropic` `claude`