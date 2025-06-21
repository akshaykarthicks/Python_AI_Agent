# Simple AI Agent

An interactive AI agent that leverages OpenRouter Llama-3 and Firecrawl tools to scrape, crawl, and extract data from websites via a command-line interface.

---

## Features
- Uses OpenRouter Llama-3 model for AI-powered responses
- Integrates Firecrawl tools for web scraping and crawling
- Interactive CLI for user input and agent responses
- Environment variable support via `.env`

---

## Installation

### Prerequisites
- Python 3.10 or higher
- [pip](https://pip.pypa.io/en/stable/)

### 1. Clone the repository
```bash
git clone <repo-url>
cd simple
```

### 2. Install dependencies
> **Note:** Dependencies are not listed in `pyproject.toml`. Install the following manually:
```bash
pip install mcp langchain langgraph langchain-openai python-dotenv
```

Or, if you use [uv](https://github.com/astral-sh/uv):
```bash
uv pip install mcp langchain langgraph langchain-openai python-dotenv
```

### 3. Set up environment variables
Create a `.env` file in the project root with:
```
OPENROUTER_API_KEY=your_openrouter_api_key
FIRECRAWL_API_KEY=your_firecrawl_api_key
```

---

## Usage

Run the main application:
```bash
python main.py
```

- Type your queries at the prompt.
- Type `quit` to exit.

---

## Configuration
- **OPENROUTER_API_KEY**: API key for OpenRouter (Llama-3 model)
- **FIRECRAWL_API_KEY**: API key for Firecrawl tools

---

## Project Structure

```
simple/
├── main.py           # Main application logic
├── pyproject.toml    # Project metadata
├── uv.lock           # Lock file for dependencies
├── .env              # Environment variables (not committed)
```

---
