# [nbbrowserpdf](https://github.com/anaconda-server/nbbrowserpdf) dependencies

These are the build recipes of dependencies not included in Anaconda. They are
built from the PyPi sources distributions.

- [PyPDF2](https://github.com/mstamy2/PyPDF2) is a toolkit for working with
  Portable Document Format (PDF) files
- [ghost.py](https://github.com/jeanphix/Ghost.py) is a python-scriptable
  browser which uses Qt, either via [PySide](https://github.com/PySide) or
  [PyQt](https://riverbankcomputing.com/software/pyqt/intro)
  - both are available in anaconda, though PyQt is more actively maintained

You can install them with `conda` even without `nbbrowserpdf`!

```
conda install -c anaconda-nb-extensions pypdf2
conda install -c anaconda-nb-extensions ghost.py
```
