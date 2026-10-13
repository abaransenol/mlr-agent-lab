# MLR Agent Lab (`mlr-agent-lab`)

## Goal
The goal of this repository is to conduct Machine Learning experiments and lab tasks using agentic workflows with autonomous AI coding agents.

## Prerequisites
- **Python**: 3.10+
- **uv**: Fast Python package and environment manager
- **GitHub CLI (`gh`)**: For repository management

## Environment Setup
Create and manage the virtual environment using `uv`:

```bash
# Create a virtual environment
uv venv

# Activate virtual environment
source .venv/bin/activate
```

## How to Run Things

Run scripts directly through `uv`:
```bash
# Run a Python script
uv run hello.py
```

Install dependencies:
```bash
# Add dependencies
uv pip install <package-name>
```

## Running Checks
Before marking any task as done, verify that all scripts execute cleanly:
```bash
# Verify Python script execution
uv run python hello.py
```
