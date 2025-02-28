## OpenAI LLM Guard

## Overview

OpenAI LLM Guard is a Python-based application that integrates LLM Guard to enhance security by sanitizing user prompts and filtering AI-generated responses. It helps protect against prompt injections, sensitive data leakage, and toxic content while ensuring responses remain relevant.

## Features

- Prompt scanning: Detects and removes harmful or manipulative user inputs.

- Response filtering: Ensures AI-generated content does not contain sensitive or harmful information.

- Supports OpenAI's GPT models: Works seamlessly with gpt-3.5-turbo and other OpenAI models.

- Anonymization & de-anonymization: Protects user data through secure vault storage.

- Relevance & sensitivity checks: Prevents AI from refusing responses in a harmful way.

## Prerequisites

- Ensure you have the following installed before running the project:

- Python 3.x

- OpenAI API key

- Required Python dependencies

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/OpenAI-LLM-Guard.git
cd OpenAI-LLM-Guard
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Set up environment variables: Create a .env file and add your OpenAI API key:
```bash
OPEN_API_KEY=your_openai_api_key
```
## Usage

1. Run the script:
```bash
python main.py
```
2. The application will:

- Sanitize the input prompt

- Check for prompt injections, toxicity, and token limits

- Send the cleaned prompt to OpenAI

- Filter and validate the AI's response

- Output only safe and relevant responses

## Dependencies

- openai

- llm_guard

Install dependencies manually if needed:
```bash
pip install openai llm_guard
```
