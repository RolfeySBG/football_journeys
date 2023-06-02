# Football Journeys

## Developer Setup

### Setup Conda environment
```
conda create --name football_journeys python=3.10
conda activate football_journeys
```

### Install Dependencies
```
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

Below code quality checks are implemented:
- Flake8: basic code quality checks
- Pylint: ensures PEP8 compliance and finds various code issues

Now, it will run automatically on staged changes as you commit, and it can also be ran manually (include `--all-files` to run against all files in the repo):
```
pre-commit run --all-files
```
