# HR AI Assistant

An AI-powered HR assistant for managing human resources tasks.

## Project Structure

```
hr-ai-assistant/
├── hr_ai_assistant/          # Main package
│   └── __init__.py
├── tests/                     # Tests directory
│   └── __init__.py
├── docs/                      # Documentation
├── venv/                      # Virtual environment
├── pyproject.toml             # Project configuration
├── requirements.txt           # Dependencies
├── README.md                  # This file
└── .gitignore
```

## Setup

### 1. Create and activate virtual environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Install package in development mode

```bash
pip install -e .
```

## Development

### Run tests

```bash
pytest
```

### Run tests with coverage

```bash
pytest --cov=hr_ai_assistant
```

### Format code

```bash
black hr_ai_assistant tests
```

### Lint code

```bash
ruff check hr_ai_assistant tests
```

### Type checking

```bash
mypy hr_ai_assistant
```

## License

MIT License