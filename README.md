# Conversation Prompts Archive

This repository is a collection of archived conversation prompts organized by topics and examples. It serves as a reference for various use cases such as training datasets, AI dialogue modeling, or educational purposes.

## Table of Contents

1. [Introduction](#introduction)
2. [Usage](#usage)
   - [How to Add a Conversation](#how-to-add-a-conversation)
   - [File Naming Convention](#file-naming-convention)
3. [Examples](#examples)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

This repository aims to store conversation prompts and responses in a structured format for easy reference. Each conversation is captured in a markdown file with appropriate annotations and context.

## Usage

### How to Add a Conversation

1. **Create a New File**: Each conversation should be stored in its own markdown file within the `conversations` directory. Use a clear and descriptive name for each file.
2. **Use Proper Formatting**: Ensure the conversations follow this basic structure:


   ```markdown
   # Title of Conversation

   **Context**: A brief description of the prompt or use case.

   **Date**: YYYY-MM-DD

   **Prompt**: I want to abcxyz...
   ```


### Example

**Context**: A user asks an AI chatbot for the weather forecast in their city for the upcoming week.

**Date**: 2024-10-23

### Prompt:

```
AI: The weather in San Francisco for the week will be mostly sunny with temperatures ranging between 60°F and 72°F. There might be light showers on Wednesday.
User: Will I need an umbrella on Wednesday?
AI: It's recommended to carry one since there is a 40% chance of light rain in the afternoon.
```

## Best Practices

### Formatting
- **Headings**: Use level 1 (`#`) for titles and level 3 (`###`) for prompt/response sections.
- **Code Blocks**: Wrap both the prompt and response in triple backticks (`` ``` ``) to distinguish them from plain text.
- **Contextual Information**: Always provide clear context for each conversation so others understand the scenario.
- **Consistency**: Ensure consistent structure for all conversations (e.g., Prompt, Response, Follow-up) to maintain uniformity.

### Naming Conventions for Files
- **Topic-Oriented**: The filename should reflect the conversation's topic or purpose (e.g., `ai-weather-forecast-prompt.md`).
- **Hyphen-Case**: Use lowercase with hyphens to separate words (e.g., `customer-support-chat.md`).

### Example Filename
- `ai-training-dataset-prompt.md`: A conversation related to training an AI model with dataset prompts.
- `chatbot-customer-support.md`: A conversation showing how a chatbot handles customer support questions.

## Future Plans

We aim to add the following in the next iterations of the repository:

1. **Metadata for Each Conversation**:
   - Add a structured metadata block to store additional information such as tags, the model used, or response times.

   Example:
   ```markdown
   ---
   title: AI Weather Forecast Chat
   tags: [AI, chatbot, weather]
   model: GPT-3
   response-time: 1.2s
   ---
   ```

## TBD
