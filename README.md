# ACBench — Agentic Cloud Benchmark

A standardized benchmark framework to evaluate end-to-end autonomous software workflows in the cloud.

## What it does
ACBench tests AI agents across realistic cloud scenarios, assessing their ability to build, deploy, detect failures, and automatically repair systems.

## Project Structure
- `scenarios/` — benchmark task definitions
- `agents/` — AI agent logic and API integration
- `evaluator/` — scoring and result analysis
- `results/` — output logs from benchmark runs

## Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Add your API keys to a `.env` file:
```
OPENAI_API_KEY=your_key_here
ANTHROPIC_API_KEY=your_key_here
```
