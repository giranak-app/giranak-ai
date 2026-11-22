# Giranak AI Service

Python/FastAPI service used by the Giranak backend.

## Features

- Category suggestion from a problem description
- Content filter (dirty words and spam)
- Review sentiment analysis

## Getting Started

Prerequisites: Python 3.11+.

1. Create a virtual environment: `python -m venv .venv`
2. Activate it: `.venv\Scripts\activate`
3. Install: `pip install -r requirements.txt`
4. Run: `uvicorn app.main:app --reload`
5. Docs: http://localhost:8000/docs

## API Contract

Endpoints, inputs, and outputs are documented in giranak-docs.

## Tests

`pytest`

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
