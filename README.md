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
