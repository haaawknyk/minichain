# minichain

Minimal tool-calling agent loop, framework-free

Side project, maintained when I have time.

## Usage

```bash
python agent.py "how many words in my note called todo?"
```

## Features

- Three tools: calculator, word count, note lookup
- Plain loop: plan -> call -> observe -> answer
- Works with any OpenAI-compatible model
- Tool schemas declared next to the functions

## Getting started

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── agent.py
└── requirements.txt
```
