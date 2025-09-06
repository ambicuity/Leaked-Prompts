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

This repository serves as a comprehensive collection of system prompts and internal instructions extracted from various large language models (LLMs). The prompts are organized by AI platform and model version, documenting the actual system-level instructions used by these models in production environments.

### System Prompts by Platform

- **Anthropic**: Claude models and variants
- **Google**: Gemini models and variants
- **OpenAI**: GPT models and variants
- **Perplexity**: Perplexity AI models
- **Proton**: Proton's AI services
- **xAI**: Grok and other xAI models
- **Misc**: Other models and platforms

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
- `claude-3-5-sonnet-full-system-message.md`
- `gpt-4-listener-personality.md`
- `gemini-2-0-flash-webapp.md`

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