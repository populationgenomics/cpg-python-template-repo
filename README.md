# CPG Python Template

General-purpose template for CPG Python repositories. Provides project structure, linting, type checking, testing, and CI out of the box.

## What's included

- `pyproject.toml` with hatchling build, ruff linting, mypy, pytest config
- `.pre-commit-config.yaml` with ruff, mypy, and CPG ID checker hooks
- GitHub Actions for linting and testing
- `src/` layout with placeholder package
- `test/` directory with pytest

## Quick start

1. Create a new repo from this template
2. Rename `package_name` in `src/`, `pyproject.toml`, and hatch build config
3. Update the project name, description, and repository URL in `pyproject.toml`
4. Add your dependencies to `pyproject.toml`
5. Install: `pip install .[dev]`
6. Run linting: `pre-commit run --all-files`
7. Run tests: `pytest test`

## For cpg-flow workflows

If you're building a cpg-flow pipeline, use the [cpg-flow-pipeline-template](https://github.com/populationgenomics/cpg-flow-pipeline-template) instead. It extends this template with stages, jobs, scripts, Docker builds, and Artifact Registry CI.
