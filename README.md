# python-template-repo

Assumes you have `uv` and `pyenv` installed.

```
pyenv local 3.11
uv venv .venv
source .venv/bin/activate
uv pip install -r requirements.txt
pre-commit install
```