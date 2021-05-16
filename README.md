# raspi-pictures

# local dev

## Virtual environment
`python -m venv .venv`
`source .venv/bin/activate`

## Install dependencies
If error due to pip version - `python -m pip install -U pip`
`pip install -r requirements.txt`  (eventually replace with poetry)

## azure-cli
Log into azure subscription `az login`
Create service principal - `az ad sp create-for-rbac --name localdev-sp-rbac`
