# Bulk Data Extract (BDE) Processor

Pipeline to extract, transform and load Landonline data to the LINZ Data Service
and others. A reimplementation of the legacy
[BDE Processor deployment repo](https://github.com/linz/bde-processor-deployment).

The database content is licensed under the Creative Commons Attribution 4.0
International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative
Commons, PO Box 1866, Mountain View, CA 94042, USA.

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
