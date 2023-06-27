# Python + isort + black + mypy
```sh
python -m venv .venv
.venv\Scripts\activate

pip install poetry
poetry install
```
```sh
poetry run isort .
poetry run black .
poetry run mypy
```
