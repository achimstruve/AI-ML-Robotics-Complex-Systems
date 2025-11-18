# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a portfolio repository showcasing AI/ML research and complex systems engineering projects. The focus areas are:

- **LLM Training, Finetuning & Evaluation**: Custom training pipelines, parameter-efficient finetuning, evaluation frameworks
- **Multi-Agent Simulation & Agentic Systems**: Multi-agent environments, emergent behaviors, coordination mechanisms
- **AI × Economics × Token Engineering**: Incentive structures, market dynamics, decentralized coordination
- **Data Science for High-Dimensional & Dynamic Systems**: Advanced analytics, time-series analysis, causal inference

## Repository Structure

- `projects/`: Individual research and engineering projects, each self-contained with:
  - Research objectives and methodology
  - Implementation code and experiments
  - Results and analysis
  - Documentation for reproducibility

## Technical Stack

Projects in this repository typically use:
- **ML/AI Frameworks**: PyTorch, Transformers (Hugging Face), JAX
- **Agent-Based Modeling**: Custom simulation frameworks
- **Data Science**: NumPy, Pandas, scikit-learn
- **Distributed Training**: Tools for scaling LLM training

## Development Approach

When working in this repository:

- Each project is independent and self-contained within `projects/`
- Implementations should be production-ready and scalable, not just proof-of-concepts
- Include rigorous evaluation and experimental validation
- Document methodology, setup, and reproduction steps within each project
- Code should bridge theoretical insights with practical applications
- Focus on reproducibility: include requirements, data sources, and configuration

## Project Creation

When creating new projects:
1. Create a dedicated subdirectory in `projects/`
2. Include a project-specific README with objectives, methodology, setup instructions
3. Structure code for clarity: separate data processing, models, training, evaluation
4. Include requirements.txt or pyproject.toml for dependencies
5. Document key design decisions and architectural choices
