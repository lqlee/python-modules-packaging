# Python Modules and Packaging
https://www.youtube.com/watch?v=m2EAQk4Qlew

This project is to demo the procedure how we can create modules and package them.

In another project, we can install it, import modules in the code.

A few commands:
```
python -m venv .venv
.venv\script\activate
deactivate

pip install build setuptools wheel
python -m build
python setup.py bdist_wheel
python setup.py sdist
python setup.py bdist_wheel sdist

pip install {forder/package.whl}

```

pip 2 uv: modern python project management workflow
https://www.youtube.com/watch?v=jd1aRE5pJWc

uv replacing pip/venv
https://www.youtube.com/watch?v=aVXs8lb7i9U
uv python list
uv python install cpython-3.12
uv run -p 3.12 ai.py
uv run -p 3.12 python
uv run -p pypy python
uv init -p 3.13  ## init a project 'test'
uv add pydantic-ai ## create .venv, add to pyproject.toml dependencies
uv run ai.py ${...}
uv tree  ## list the dependencies
uv add ruff --dev
uv remove ruff --dev
uv tool install ruff ## install to the global env
uv tool list ## list all tools
pyproject.toml add [project.scripts] ai = "ai:main"
uv build ## dist/....whl

