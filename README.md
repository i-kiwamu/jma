jma: Data downloader from JMA (Japan Meteorological Agency)
===========================================================

* Author: Kiwamu Ishikura
* Version: 1.0.0
* Licence: GPLv3

What's this?
------------
This is the program to get 1-hour meteorological data from JMA web site. You can retrieve data and save as csv.

Requirement
-----------
Python (>= 3.3)
*Beware that Python 2 can NOT work*

Install
-------
If you have pip, you can install by pip as follows::

```
$ pip install jma
```

Or, you can install by setup.py::

```
$ python3 setup.py install
```

Usage
-----
Just type as follows in your console::
```
$ jma
```

Program will ask you the beginning/final date of data you want, locations, and file name. Please follow the explanations.

If you put jmalib.py in your PYTHONLIB and put jma.py in your PATH, you can use these program anywhere. 
