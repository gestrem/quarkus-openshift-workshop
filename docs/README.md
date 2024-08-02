# Generate and expose docs locally

```bash


    python3 -m venv  /Users/gestrem/python/
    source  /Users/gestrem/python/bin/activate

```
```bash
pip install pipenv
pipenv install
pipenv run mkdocs build --clean
pipenv run mkdocs serve
```
The doc should be available at http://127.0.0.1:8000/