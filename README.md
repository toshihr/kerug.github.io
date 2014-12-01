My python wheels
================

PySide for Yosemite
--------------------

The wheel was built as follows:

```sh
$ git clone https://github.com/PySide/pyside-setup.git
$ cd pyside-setup
$ python setup.py bdist_wheel --universal
```

### How to install

```sh
pip install --find-links=https://kerug.github.io/python-wheelhouse --use-wheel --no-index --pre PySide
```
