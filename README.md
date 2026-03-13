# Experiments

A repository hosting Copilot AI experiments — exploring what GitHub Copilot can do across a variety of topics and use cases.

## Overview

This repository serves as a sandbox for experimenting with GitHub Copilot across different domains, including:

- **Automation** – scripts and tools that automate repetitive tasks
- **Data processing** – pipelines and transformations for working with data
- **Web development** – small web apps and API experiments
- **Machine learning** – model training, inference, and evaluation snippets
- **Utilities** – general-purpose helper libraries and tools

## Structure

```
experiments/
├── <experiment-name>/
│   ├── README.md       # Description and instructions for the experiment
│   ├── pyproject.toml  # Project metadata and dependencies (uv)
│   └── ...             # Source files
```

Each experiment lives in its own top-level directory and contains a `README.md` explaining its purpose and how to run it.

## Getting Started

### Prerequisites

- [uv](https://docs.astral.sh/uv/getting-started/installation/)

### Running an experiment

```bash
cd <experiment-name>
uv run python main.py
```

## Contributing

1. Create a new directory for your experiment under the repository root.
2. Run `uv init` inside it to generate `pyproject.toml` and `.python-version`.
3. Add a `README.md` describing what the experiment does and how to run it.
4. Use `uv add <package>` to declare any dependencies.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
