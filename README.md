# CPG Python Template

Template repository based on the [CPG team-docs](https://github.com/populationgenomics/team-docs/blob/main/new_repository.md) content.

This contains python and markdown linting configuration, and a github linting action.
Before making a new repository based on this template, it may be worth auditing the versions of linting tools and GitHub Actions listed in _.pre-commit-config.yaml_ and _.github/workflows_.

As of `03-06-2024` this repository has been reduced to using Ruff and MyPy
- Ruff implements linting, import sorting, formatting (since 0.1.2 Ruff has implemented Black-style formatting)
- MyPy implements static type checking based on type hints and syntax
