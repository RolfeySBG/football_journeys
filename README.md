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

```
pre-commit run --all-files
```
