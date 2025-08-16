# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Buildathon project repository for rapidly prototyping innovative AI solutions. The project is currently in its initial setup phase with Python as the primary language (based on the .gitignore configuration).

## Development Setup

Since this is a new project, when implementing features:
1. If using Python, create a `requirements.txt` or `pyproject.toml` for dependencies
2. Consider setting up a virtual environment: `python -m venv venv`
3. For any Python code, follow PEP 8 conventions

## Project Structure Recommendations

When building out this project:
- Place Python source code in a `src/` or app-specific directory
- Create a `tests/` directory for unit tests if implementing testing
- Add configuration files at the root level
- Use environment variables for sensitive configuration (note `.env` is gitignored)

## Common Commands

As the project develops, update this section with:
- How to install dependencies
- How to run the application
- How to run tests
- How to lint/format code

## Notes

- The repository uses Python-focused .gitignore settings
- Environment files (.env, .envrc) are ignored for security
- Common Python build artifacts and cache directories are excluded from version control