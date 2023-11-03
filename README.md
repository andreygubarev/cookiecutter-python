# Cookiecutter Template for Python

Template supports the following features:
- `direnv` for environment variables management
- `pre-commit` for pre-commit hooks
- - `black` for Python code formatting
- - `isort` for Python imports sorting
- - `flake8` for Python code linting
- `build` for building Python package
- `pipenv` for Python dependencies management
- `pytest` for testing Python package
- - `pytest-cov` for testing Python code coverage
- - `pytest-asyncio` for testing async Python code
- - `pytest-docker-tools` for using Docker for fixtures
- `github-actions` for CI/CD

## Usage

Generate your project from the project template using latest version:
```bash
cookiecutter https://github.com/andreygubarev/cookiecutter-python.git
```

## Reference

- direnv: https://direnv.net/
- pre-commit: https://pre-commit.com/
- black: https://github.com/psf/black
- isort: https://pycqa.github.io/isort/
- flake8: https://flake8.pycqa.org/en/latest/
- build: https://pip.pypa.io/en/stable/reference/build-system/pyproject-toml/
- pipenv: https://pipenv.pypa.io/en/latest/
- pytest: https://docs.pytest.org/en/stable/
- pytest-cov: https://pytest-cov.readthedocs.io/en/latest/
- pytest-asyncio: https://pypi.org/project/pytest-asyncio/
- pytest-docker-tools: https://pypi.org/project/pytest-docker-tools/
