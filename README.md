# CI/CD Practice 🚀

A beginner-friendly project to learn CI/CD using Python and GitHub Actions.

## What this project does
A simple calculator app with automated testing and a CI pipeline that runs on every push.

## Features
- ➕ Add
- ➖ Subtract
- ✖️ Multiply
- ➗ Divide
- 🔢 Modulus

## How CI/CD works here
Every time code is pushed to `main`:
1. GitHub Actions spins up a server
2. Installs dependencies
3. Runs all tests automatically
4. ✅ Green = all tests pass
5. ❌ Red = something is broken

## Run locally
```bash
pip install -r requirements.txt
pytest test_calculator.py -v
```

## Tech Stack
- Python 3.11
- Pytest
- GitHub Actions
