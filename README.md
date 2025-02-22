# `webots_py`

These are the Webots Python bindings. I made a psychotic `pyproject.toml` representation so you can use them as a package and export their types without 9000 type errors.

## Installation

1. Install Webots using [the tarball method](https://cyberbotics.com/doc/guide/installation-procedure#installing-the-tarball-package).
2. Clone this repo over its `webots/lib/controller` directory. It should replace `python/`.
3. `set -Ux WEBOTS_HOME /home/barrett/bin/webots/` (or your path) before you use Python.
4. `deactivate && uv sync && . .venv/bin/activate.fish`
5. `from python.controller import Robot` or whatever :D

These bindings might work without this method, though. I haven't yet tested it. Please update these docs if you do!
