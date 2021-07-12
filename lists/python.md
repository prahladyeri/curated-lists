# Python Programming Resources

## Official docs and other resources
- [Python Official docs](https://docs.python.org/)
- [PEP-8 - Guidelines for writing python code](https://www.python.org/dev/peps/pep-0008)
- [Python Package Index - The official python package repo](https://pypi.python.org/)
- [/r/learnpython wiki](https://www.reddit.com/r/learnpython/wiki/index#wiki_practice_python)
- [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/) - Must have resource for Windows users of Python. Provides all the compiled package files in pip installable(*.whl) files.

## Libraries

### Database Connectivity
- [mysql-connector-python](mysql-connector-python) - Official mysql client library by Oracle.
- [PyMySQL](https://pypi.org/project/PyMySQL/) - A pure-Python MySQL client library, based on PEP 249. [Apparently faster than the official driver](https://stackoverflow.com/a/25724855/849365)
- [mysqlclient](https://pypi.org/project/mysqlclient/) - Another mysql client library implementation.  [Apparently, the fastest implementation as it is C based](https://stackoverflow.com/a/25724855/849365). Django's recommended, also used by debian and ubuntu repos for `python3-mysqldb` package.
- [psycopg2](https://pypi.org/project/psycopg2/) - Most popular postgresql driver for python.
- [SQLAlchemy](http://www.sqlalchemy.org/) - The "bread and butter" [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping) library in the python world. Extremely versatile and flexible enough to work with almost any RDBMS known to mankind.

### Scientific/Statistical
- [scipy](https://docs.scipy.org) - Important python package for mathematicians and statisticians.
- [numpy](http://www.numpy.org/) - A package for scientific computing.
- [matplotlib](http://matplotlib.org/) - A 2d plotting library.
- [pandas](http://pandas.pydata.org/) - High performance Data Analysis library for Python.
- [nltk](http://www.nltk.org/) - Widely used Python library in the field of *Natural Language Processing*.

### Machine Learning
- [gpt-2](https://github.com/openai/gpt-2) - Neuralnet/AI library, Code from the paper "Language Models are Unsupervised Multitask Learners".
- [scikit-learn](https://scikit-learn.org/) - A free software machine learning library for the Python programming language.
- [tensorflow](https://www.tensorflow.org/) - A free and open-source software library for dataflow and differentiable programming across a range of tasks.

### Networking/Scraping
- [requests](http://docs.python-requests.org/en/latest/) - A popular library for handling HTTP requests.
- [Twisted](https://twistedmatrix.com/) - An event driven networking engine written in python. Twisted is to python what System.Net is to C# or java.net package is to Java.
- [Mechanize](https://pypi.python.org/pypi/mechanize/) - A fully-fledged web-scraping framework written in Python.

### Spreadsheets/Documents
- [openpyxl](https://openpyxl.readthedocs.io) - A pure python library to export/import data in `Microsoft Excel` format.
- [xlrd](https://blogs.harvard.edu/rprasad/2014/06/16/reading-excel-with-python-xlrd/) - A pure python library to read Microsoft Excel 97 (*.xls) format workbooks.
- [python-docx](https://python-docx.readthedocs.io) - Python library to write to work with Microsoft Word Documents.
- [markdown](https://pypi.org/project/Markdown/) - Python library to work with markdown format.
- [Pandoc](https://pandoc.org) - Wonderful tool to convert document from one format to another, supports markdown, reST, doc, docx, pdf and a number of other formats.
- [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - A mind-blowing XML parsing library that is widely used in web-scraping scripts and applications in python.
- [lxml](https://lxml.de) - Library to process xml/html with python.

### Build and DevOps
- [Twine](https://github.com/pypa/twine/) - Utility for interacting with PyPi packaging system.
- [PyTest](https://github.com/pytest-dev/pytest) - Perhaps the De-facto testing module in python world.
- [sphinx](https://www.sphinx-doc.org/en/master/usage/quickstart.html) - The standard documentation tool for python.
- [readthedocs.org](https://readthedocs.org) - Online document hosting facility for pythonistas, based on Sphinx and integrates with github repositories and hooks.

### Others
- [cookiecutter](https://github.com/cookiecutter/cookiecutter) - A command-line utility that creates projects from cookiecutters.
- [Pelican](https://github.com/getpelican/pelican) - A static site generator that supports markdown and reST syntax. Written in python.
- [pygments](https://pypi.org/project/Pygments/) - A syntax highlighting package written in Python.
- [pygame](http://pygame.org/) - A popular python gaming library.
- [panda3d](https://www.panda3d.org/) - Python graphics library.
- [pyglet](http://www.pyglet.org/) - Python graphics library.
- [Kivy](https://en.wikipedia.org/wiki/Kivy) - A modern GUI toolkit for building apps, works seamlessly on Linux, Android, Windows and Mac.
- [PySide](https://en.wikipedia.org/wiki/PySide) - Alternative GUI toolkit in Python, the open source version of PyQt which is commercial.
- [PySimpleGUI](https://pysimplegui.readthedocs.io/) - Another GUI toolkit similar to PyQT and tkinter.
- [Tweepy](http://tweepy.readthedocs.io/) - Library to access tweets using the twitter api.
- [pytz](https://pypi.org/project/pytz/) - Library to work with time-zones.
- [tqdm](https://github.com/tqdm/tqdm) - Instantly make your loops show a smart progress meter.
- [faker](https://github.com/joke2k/faker) - Package to generate fake data to test your python apps.
- [Google API Python Client](https://github.com/googleapis/google-api-python-client) - Goole API client for Python.
- [Google API Python - OAuth2 library](https://github.com/googleapis/oauth2client) - Goole API client for Python.
- [Flatlib](https://github.com/flatangle/flatlib) - Astrology library written in pure Python (supports both tropical and siderial systems).

## Web-Frameworks
- [Django](https://www.djangoproject.com/) - A popular web framework written in Python. Often touted as the web framework for busy journalists with deadlines, Django is very flexible and can be adapted to any web project needs.
- [Flask](http://flask.pocoo.org) - A minimalist web framework. While not as popular and stuffed as Django, Flask follows a more `lego block` approach to development - starting from a minimal core, and keep adding as needed. An excellent framework, nevertheless.
- [Bottle](http://bottlepy.org/) - A single module web framework for Python.

## Online tutorials, articles, books, puzzles
- [Full Stack Python](https://fullstackpython.com) - Handy resource outlining the web development process using python frameworks and libraries.
- [Dive Into Python - Mark Pilgrim](https://linux.die.net/diveintopython/html/toc/index.html) - Must read for all python learners and enthusiasts.
- [Django vs. Flask: Picking the Right Python Web Framework](https://www.tivix.com/blog/django-vs-flask-picking-the-right-python-framework) - Excellent guide for choosing between django and flask, the two most popular python web frameworks.
- [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/)
- [Writing a Virtual Machine in Python](http://pythonguy.wordpress.com/2008/04/17/writing-a-virtual-machine-in-python/)
- [Coding Bat - Python](http://codingbat.com/python)
- [Simple Python Programs](https://wiki.python.org/moin/SimplePrograms)
- [Beginners Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- [Learn Python, Break Python - A beginners guide](http://learnpythonbreakpython.com/)
- [Automate boring stuff with Python](http://automatetheboringstuff.com/)

## Popular Youtube channels

- [Corey Schafer](https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g)
- [Engineer Man](https://www.youtube.com/channel/UCrUL8K81R4VBzm-KOYwrcxQ)
- [Real Python](https://www.youtube.com/channel/UCI0vQvr9aFn27yR6Ej6n5UA)
