# P.U.M.P. — Python's Universal Modules Pack

P.U.M.P. is a modular collection of Python utilities and frameworks designed to
accelerate development. Each module is self-contained and can be used independently,
or together as part of the full toolkit.

## Structure

- All modules live under [`modules/`](modules/).
- Each module is a standalone Python package (`pyproject.toml`, `src/`, `tests/`).
- Modules are grouped by relevance (e.g., `foundation/`, `web/`, `data/`, `ux/`).

## Usage

Install an individual module directly from Git:

```bash
pip install "git+https://github.com/<your-username>/pump.git#subdirectory=modules/ux/termuikit"
```
