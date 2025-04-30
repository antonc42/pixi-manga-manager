# Pixi Manga Manager
Flexible manga library organizer, metadata scraper, and renamer.

## Installation

TODO after learning more about Beeware.

## Developing

### Prerequisites
It is recommended to install the [`uv` package and project manager](https://docs.astral.sh/uv/getting-started/installation/).

Also install the [`just` command runner](https://just.systems/man/en/packages.html).

If `uv` was installed, the easiest way to get `just` is to install it via `uv`.
```bash
uv tool install rust-just
```

### Virtual Environment
Create a virtual environment.
```bash
uv sync
```
Pip equivalent.
```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install $(python3 -c 'import tomllib; print(*tomllib.load(open("pyproject.toml", "rb"))["project"]["dependencies"])')
python3 -m pip install --group dev
```

Activate the virtual environment.
```bash
source .venv/bin/activate
```
