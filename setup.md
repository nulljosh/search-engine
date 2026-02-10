# Setup

## Dependencies
- Python 3.10+
- No external deps for core

## Install
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .
```

## Run
```bash
# Index documents
python src/index.py docs/

# Search
python src/search.py "your query"
```
