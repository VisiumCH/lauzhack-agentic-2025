# Building Agents with LangChain and LangGraph: From GPT to Multi-Agent Systems

This workshop is organized by [Visium](https://visium.com/) for LauzHack [LauzHack 2025](https://lauzhack.com/workshops) at EPFL. It gives an introduction to LLMs and demonstrates how to build sophisticated AI agents using LangChain.

## Workshop Overview
The workshop explores the progression from basic language models to complex multi-agent systems through hands-on examples in financial analysis.

### Introduction to LLMs and Agents
Learn the basics of building AI applications with LangChain, including:
- Setting up a basic chatbot
- Setting up a basic agentic system

## Getting Started

### Prerequisites
- Python 3.12 or higher
- OpenAI API key

### Environment Setup

To set up your Python environment:

#### Using Conda/Mamba
```bash
# Use mamba instead of conda if preferred
conda create -n financial-advisor python=3.12
conda activate financial-advisor
pip install -e .
```

#### Using venv
```bash
python -m venv .venv

# On Linux/Mac:
source .venv/bin/activate
# On Windows:
.venv\Scripts\activate

pip install -e .
```

#### Using UV
```bash
uv sync
```

### Configuration

You'll need to configure your OpenAI API key. Here are two ways to do it:

Set it as an environment variable:
```bash
export OPENAI_API_KEY='your-api-key-here'
```

Or store it in a `.env` file in your project root:
```bash
OPENAI_API_KEY='your-api-key-here'
```

### Development Environment

This workshop uses Jupyter notebooks. You can run them using:

- VS Code with the Python extension installed
- Jupyter Lab through the web interface  with `jupyter lab`

## About
### Visium
[Visium](https://visium.com/) is a Swiss-born AI & Data company helping businesses build their data-driven future through artificial intelligence and advanced data analytics. We help organizations leverage cutting-edge technology to solve complex business challenges.

### LauzHack
LauzHack is an association created by EPFL aiming to bring together students and machine
learning professionals. They are well known for their Hackathon which is considered one of
the largest in Lausanne. For more information about LauzHack, visit [https://lauzhack.com/](https://lauzhack.com/).