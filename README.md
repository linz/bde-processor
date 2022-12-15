# Bulk Data Extract (BDE) Processor

Pipeline to extract, transform and load Landonline data to the LINZ Data Service
and others. A reimplementation of the legacy
[BDE Processor deployment repo](https://github.com/linz/bde-processor-deployment).

The content of the following tables is licensed under the
[LINZ Licence for Personal Data 2.1](https://data.linz.govt.nz/license/linz-licence-personal-data-21/):

-  [NZ Property Titles Owners List](https://data.linz.govt.nz/table/51564-nz-property-titles-owners-list/)
-  [NZ Title Memorials List (including Mortgages, Leases, Easements)](https://data.linz.govt.nz/table/51695/)
-  [NZ Title Memorials Additional Text List](https://data.linz.govt.nz/table/51696/)
-  [NZ Property Titles Including Owners](https://data.linz.govt.nz/layer/50805/)
-  [NZ Property Title Owners](https://data.linz.govt.nz/layer/50806/)
-  [Landonline: Alias](https://data.linz.govt.nz/table/51982/)
-  [Landonline: Encumbrance](https://data.linz.govt.nz/table/51985/)
-  [Landonline: Nominal Index](https://data.linz.govt.nz/table/51994/)
-  [Landonline: Title Memorial Text](https://data.linz.govt.nz/table/52007/)
-  [Landonline: Proprietor](https://data.linz.govt.nz/tables/51998/)

Database content which is not in the tables listed above is licensed under the
Creative Commons Attribution 4.0 International License. To view a copy of this
license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to
Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

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
