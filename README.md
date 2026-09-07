# AI Engineering Journey

A cloud-first learning and portfolio repository for progressing from software engineering foundations to production AI systems.

## Target path

**Software Engineering → Machine Learning → Deep Learning → LLM Engineering → Agentic AI → Production AI Systems**

The technical progression is intentionally staged:

`Python → Git/GitHub → Linux → SQL/PostgreSQL → testing → FastAPI → cloud deployment → NumPy/Pandas/scikit-learn → PyTorch → Transformers → LLM APIs → RAG → vector search → agents → MCP → AI evaluations → observability → AWS → CI/CD/MLOps`

Tools are introduced when they become useful. This repository is not intended to install the entire AI stack on day one.

## Development model

Primary development is cloud-first:

```text
GitHub Codespaces
      ↓
GitHub repository
      ↓
GitHub Actions
      ↓
application / ML / AI code
      ↓
AWS and other cloud services when production deployment becomes necessary
```

Railway is intentionally not part of this learning environment. The local Windows machine is primarily an access point, and heavy local Docker/VM infrastructure is not required for the foundation phase.

## Repository organization

```text
.devcontainer/        Codespaces configuration
.github/workflows/    Continuous integration
semester-1/           Foundation curriculum
projects/             Independent portfolio projects
tests/                Repository-level automated tests
```

## Semester 1 focus

- Python programming
- Git and GitHub
- Linux fundamentals
- SQL and relational databases
- Testing
- Mathematics needed for machine learning

## Engineering rules

- Keep dependencies minimal.
- Never commit credentials, API keys, `.env` files, or other secrets.
- Prefer reproducible cloud development.
- Write and understand foundational code before relying on AI code generation.
- Commit meaningful work frequently.
- Test before pushing.
- Build portfolio projects separately from small exercises.

## Current phase

**Week 1:** Python fundamentals and Git/GitHub foundations.
