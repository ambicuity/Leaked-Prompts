# Leaked-Prompts

A professional collection of reverse-engineered and system prompts for large language models, now available in both **structured JSON format** and markdown format for maximum AI model compatibility. This repository contains comprehensive professional prompts designed for AI system integration.

## Table of Contents

- [Overview](#overview)
- [JSON Format](#json-format)
- [Directory Structure](#directory-structure)
- [File Naming Convention](#file-naming-convention)
- [Prompt Categories](#prompt-categories)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains **104+ comprehensive professional prompts** available in both **structured JSON format** and markdown format. Each prompt is designed for AI system integration with proper model-specific formatting requirements.

### JSON Format for AI Models

All prompts are now available in **structured JSON format** designed for optimal AI model integration:

```json
{
  "role": "software developer (fullstack)",
  "task": "Provide architecture and code for developing secure web applications",
  "description": "Detailed description of the prompt's purpose and capabilities",
  "prompt": "The actual system prompt content",
  "target_audience": "developers, technical teams, project managers",
  "tone": "professional, technical, detailed",
  "format": "code implementation with architectural guidance",
  "capabilities": [
    "Web application architecture design",
    "Backend and frontend development guidance",
    "Security best practices implementation"
  ],
  "constraints": [
    "Must prioritize security best practices",
    "Follow modern development standards"
  ],
  "examples": [
    {
      "input": "Sample user request",
      "context": "Context for the example"
    }
  ]
}
```

### Key JSON Structure Fields

- **role**: The specific role or persona the AI should adopt
- **task**: The primary task or function to perform
- **description**: Detailed explanation of the prompt's purpose
- **prompt**: The actual system prompt content
- **target_audience**: Who this prompt is designed for
- **tone**: The communication style and emotional approach
- **format**: Expected output format and structure
- **capabilities**: List of specific capabilities and use cases
- **constraints**: Important limitations and guidelines
- **examples**: Sample inputs and usage contexts

### Model-Specific Features

- **Llama models**: Include proper chat template format with `<s>[INST] <<SYS>>...<</SYS>>...[/INST]`
- **OpenAI models**: Optimized for reasoning and multimodal capabilities
- **Anthropic models**: Constitutional AI principles and safety guidelines
- **Google models**: Multimodal and advanced reasoning configurations

### Comprehensive Professional Collection

- **Technology & Development**: Software Developer, DevOps Engineer, ML Engineer, Data Scientist, Cybersecurity Specialist, IT Architect, Code Reviewer, etc.
- **Business & Management**: CEO, Product Manager, Financial Analyst, Investment Manager, Business Strategy Consultant, etc.
- **Creative & Content**: Storyteller, Screenwriter, Novelist, Composer, Journalist, Content Writer, SEO Specialist, etc.
- **Healthcare & Wellness**: Medical Advisor, Nutritionist, Fitness Coach, Mental Health Adviser, Personal Trainer
- **Education & Training**: Math Teacher, Philosophy Teacher, Programming Instructor, Career Counselor, Educational Content Creator
- **Professional Services**: Legal Advisor, Accountant, Recruiter, Real Estate Agent, Travel Advisor, Life Coach, etc.

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
├── Anthropic/          # Claude models with JSON/markdown formats
├── Creative/           # Creative prompts (storytelling, writing, etc.)
├── Education/          # Educational prompts (teachers, instructors, etc.)
├── Google/             # Gemini models with JSON/markdown formats
├── Healthcare/         # Healthcare and wellness prompts
├── Misc/               # Comprehensive professional prompts collection
├── OpenAI/             # GPT models with JSON/markdown formats
├── Perplexity/         # Perplexity AI models
├── Proton/             # Proton's AI services
└── xAI/                # Grok and other xAI models
```

Each directory contains:
- **JSON files** (`.json`) - Structured format optimized for AI model integration
- **Markdown files** (`.md`) - Human-readable documentation format
- **README.md** - Directory-specific documentation

## File Naming Convention

All files follow a consistent naming pattern for both JSON and markdown formats:

**JSON Format (Structured for AI Models):**
```
[prompt-name]-system-message.json
```

**Markdown Format (Human-readable Documentation):**
```
[prompt-name]-system-message.md
```

**Examples:**
- `storyteller-system-message.json` / `storyteller-system-message.md`
- `software-developer-fullstack-system-message.json` / `software-developer-fullstack-system-message.md`
- `gpt-4o-multimodal-system-message.json` / `gpt-4o-multimodal-system-message.md`
- `llama-3-2-1b-efficient-system-message.json` / `llama-3-2-1b-efficient-system-message.md`
- `medical-advisor-system-message.json` / `medical-advisor-system-message.md`

### Format Benefits

- **JSON files**: Machine-readable, structured data perfect for direct AI model integration
- **Markdown files**: Human-readable documentation with rich formatting and examples
- **Dual format**: Maximum compatibility across different use cases and systems

## Prompt Categories

### Professional Role-Based Prompts (JSON + Markdown)
Comprehensive collection of professional role prompts designed for real-world AI applications:

#### Technology & Development
- Software Developer (Fullstack), DevOps Engineer, Machine Learning Engineer
- Data Scientist, Cybersecurity Specialist, IT Architect, Code Reviewer
- Prompt Engineer, Software QA Tester, Python Interpreter, JavaScript Console

#### Business & Management  
- Chief Executive Officer, Product Manager, Financial Analyst, Investment Manager
- Business Strategy Consultant, Project Manager, Management Consultant
- Startup Advisor, Recruiter, Accessibility Auditor

#### Creative & Content
- Storyteller, Screenwriter, Novelist, Composer, Journalist
- Content Writer, SEO Specialist, Social Media Manager, Creative Designer
- Tech Writer, Proofreader, English Translator & Improver

#### Healthcare & Wellness
- Medical Advisor, Nutritionist, Fitness Coach, Mental Health Adviser
- Personal Trainer (specialized health and wellness guidance)

#### Education & Training
- Math Teacher, Philosophy Teacher, Programming Instructor
- Career Counselor, Educational Content Creator, AI Writing Tutor

#### Professional Services
- Legal Advisor, Accountant, Real Estate Agent, Travel Advisor
- Life Coach, Motivational Coach, Public Speaking Coach

### AI Model-Specific Prompts (JSON + Markdown)
Advanced system prompts optimized for specific AI models and platforms:

#### OpenAI Models
- GPT-5, GPT-4o (Multimodal), GPT-4 Turbo, GPT-3.5 Turbo
- O1 Reasoning, O1-Mini, GPT-4 Code Interpreter, GPT-4 Listener

#### Anthropic Models  
- Claude 4, Claude 3.5 (Sonnet, Haiku, Computer Use), Claude 3 (Opus, Haiku)

#### Google Models
- Gemini 2.5 Pro, Gemini 2.0 Flash, Gemini 1.5 Pro/Flash, Gemma 3

#### Meta Models
- Llama 3.3 70B, Llama 3.2 (90B/3B/1B), Llama 3.1 (405B/70B), Code Llama

#### Other Advanced Models
- Mistral Large 2, DeepSeek V3/R1, Qwen 3/2.5, Cohere Command R+
- xAI Grok-2/Mini, Perplexity Pro, GitHub Copilot, Nomic Embed

## Contributing

We welcome contributions of new prompts, improvements to existing documentation, and additional prompt variations. Please ensure:

1. **Follow naming conventions**: Use the established JSON/markdown dual format
2. **Maintain JSON structure**: Follow the structured format with required fields (role, task, description, prompt, etc.)
3. **Include both formats**: Provide both `.json` and `.md` versions for maximum compatibility
4. **Validate JSON**: Ensure all JSON files are properly formatted and valid
5. **Verify functionality**: Test prompts with appropriate AI models when possible
6. **Document sources**: Include source information or extraction method when possible

### JSON Format Requirements

All JSON prompts must include these core fields:
- `role`: The specific role or persona
- `task`: Primary task or function
- `description`: Detailed explanation
- `prompt`: The actual system prompt content
- `target_audience`: Intended users
- `tone`: Communication style
- `format`: Expected output format
- `capabilities`: List of specific use cases
- `constraints`: Important limitations

## Repository Statistics

- **Total Prompts**: 104+ professional prompts
- **Format Coverage**: 100% dual format (JSON + Markdown)
- **Categories**: 6 major categories with 50+ specialized roles
- **AI Models**: 15+ different model families supported
- **Validation**: All JSON files validated for proper structure

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Topics

`ai` `prompts` `prompt-engineering` `llm` `large-language-models` `chatbots` `openai` `gemini` `anthropic` `claude`