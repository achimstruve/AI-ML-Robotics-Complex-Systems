# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a portfolio repository showcasing AI/ML research, robotics engineering, and complex systems projects. The focus areas are:

- **LLM Training, Finetuning & Evaluation**: Custom training pipelines, parameter-efficient finetuning, evaluation frameworks
- **Multi-Agent Simulation & Agentic Systems**: Multi-agent environments, emergent behaviors, coordination mechanisms
- **Robotics & Embodied AI**: Robot control systems, perception pipelines, motion planning, manipulation, embodied intelligence
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
- **Robotics**: ROS/ROS2, MoveIt, Gazebo, PyBullet, Isaac Sim, robot control libraries
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
- Focus on reproducibility: include dependencies, data sources, and configuration

### Dependency Management

- **Use `uv` exclusively** for Python dependency management across all projects
- Each project must have a `pyproject.toml` file (never use `requirements.txt`)
- Define dependencies in `pyproject.toml` using uv's format
- Separate development dependencies using `[tool.uv.dev-dependencies]` or via `uv add --dev`
- Include clear setup instructions using uv commands in each project's README

## Project Creation

When creating new projects:
1. Create a dedicated subdirectory in `projects/`
2. Initialize with `uv init` to create `pyproject.toml`
3. Include a project-specific README with objectives, methodology, setup instructions
4. Structure code for clarity: separate data processing, models, training, evaluation
5. Add dependencies using `uv add <package>` (never manually edit pyproject.toml dependencies)
6. Document key design decisions and architectural choices
