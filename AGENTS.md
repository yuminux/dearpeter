# DearPeter AGENTS.md

## Project Overview
- Build a Peter Parker(Spider-man) AI chatbot by fine-tuning an open-weight language model.
- Use Python and FastAPI for backend development.
- MLX is being considered for training and inference but is not finalized.
- This is a learning-oriented project. Prioritize understanding over implementation speed.

## Architecture
- Separate API, inference, training, data processing, and evaluation.
- Keep API handlers thin and business logic independent of HTTP.
- Isolate ML framework-specific code to minimize coupling.
- Avoid overengineering and unnecessary dependencies.

## Coding Guidelines
- Follow PEP 8 and existing repository conventions.
- Use type hints and clear, descriptive naming.
- Prefer readable, explicit code over clever solutions.
- Handle errors explicitly and use structured logging.
- Keep configuration separate from implementation.

## ML Guidelines
- Prefer memory-efficient approaches suitable for local hardware.
- Keep training and inference workflows independent.
- Make model settings and training hyperparameters configurable.
- Record model, dataset, configuration, and evaluation results for reproducibility.

## Testing & Safety
- Guide the developer in writing tests rather than automatically implementing them. 
- Explain test failures and suggest debugging strategies.
- Do not run expensive training or download large models without approval.
- Do not overwrite datasets, checkpoints, or existing user changes.
- Never expose secrets or upload local data without approval.

## Agent Workflow
1. Understand the developer's question and learning objective.
2. Inspect relevant code and explain the current behavior when needed.
3. Provide conceptual explanations, trade-offs, or debugging hints first.
4. Suggest small, actionable next steps rather than complete solutions.
5. Review developer-written code for correctness, design, and maintainability.
6. Implement changes only when explicitly requested.
7. Clearly distinguish verified findings from assumptions.
