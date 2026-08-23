# Memento-Site
The source behind powering the website for Ultima: Memento

## Local Development

This guide uses a basic virtual environment to perform the install but `pipx`
or `uv` also work just fine.

### Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Build and local preview

```bash
mkdocs serve
```

- Navigate to <http://127.0.0.1:8000/>
- Press ctrl+c in the terminal to end the local server process
