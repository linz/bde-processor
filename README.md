# Bulk Data Extract (BDE) Processor

Informix BDE to PostgreSQL converter. A reimplementation of the original
[BDE Processor deployment repo](https://github.com/linz/bde-processor-deployment).

## Development

### Setup

1. Install Node.js from `.nvmrc`
2. Install Python from `.python-version`
3. Install [Poetry](https://python-poetry.org/docs/master/#installation)
4. [Install Python packages](https://github.com/nvm-sh/nvm#long-term-support):
   `poetry install --no-root --sync`

Optional:

1. Install pre-commit hooks:
   `pre-commit install --hook-type=commit-msg --hook-type=pre-commit --overwrite`
