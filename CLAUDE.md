# CLAUDE.md

## Python environment

This project uses a virtual environment at `venv/`.

- Always run Python with `venv/Scripts/python`. Never use the system `python`.
- Install packages with `venv/Scripts/python -m pip install <package>`.
- Run tools through the venv interpreter too, e.g. `venv/Scripts/python -m pytest`.
- Don't rely on activating the venv. Shell state doesn't carry over between commands.
