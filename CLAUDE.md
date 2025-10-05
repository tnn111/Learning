# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal learning repository for experimenting with Python and the Anthropic API. The project uses Python 3.13+ and uv for package management.

## Development Setup

- **Python Version**: 3.13 (specified in `.python-version`)
- **Package Manager**: uv (for all dependency management)
- **Key Dependencies**: anthropic, python-dotenv, ipykernel

### Environment Setup

The project requires an `ANTHROPIC_API_KEY` environment variable. This is loaded via python-dotenv from a `.env` file (not in git).

## Running Code

### Jupyter Notebooks
- `AnthropicAPI.ipynb`: Contains examples of using the Anthropic API client
  - Demonstrates message creation with the Claude Sonnet 4.5 model
  - Uses JSON formatting for pretty-printing API responses

### Python Scripts
- Run the main script: `uv run main.py`
- Run any Python script: `uv run <script-name>.py`

## Code Architecture

The codebase is currently exploratory and learning-focused:
- `main.py`: Basic entry point (placeholder)
- `AnthropicAPI.ipynb`: Jupyter notebook for API experimentation
  - Creates Anthropic client with API key from environment
  - Makes API calls to Claude models
  - Formats and displays message responses using `json.dumps()` for readability
