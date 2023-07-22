# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Admin Panels](#admin-panels)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [ASGI Servers](#asgi-servers)
    - [Asynchronous Programming](#asynchronous-programming)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Built-in Classes Enhancement](#built-in-classes-enhancement)
    - [Caching](#caching)
    - [ChatOps Tools](#chatops-tools)
    - [CMS](#cms)
    - [Code Analysis](#code-analysis)
    - [Command-line Interface Development](#command-line-interface-development)
    - [Command-line Tools](#command-line-tools)
    - [Compatibility](#compatibility)
    - [Computer Vision](#computer-vision)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [Data Analysis](#data-analysis)
    - [Data Validation](#data-validation)
    - [Data Visualization](#data-visualization)
    - [Database Drivers](#database-drivers)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Debugging Tools](#debugging-tools)
    - [Deep Learning](#deep-learning)
    - [DevOps Tools](#devops-tools)
    - [Distributed Computing](#distributed-computing)
    - [Distribution](#distribution)
    - [Documentation](#documentation)
    - [Downloader](#downloader)
    - [E-commerce](#e-commerce)
    - [Editor Plugins and IDEs](#editor-plugins-and-ides)
    - [Email](#email)
    - [Enterprise Application Integrations](#enterprise-application-integrations)
    - [Environment Management](#environment-management)
    - [Files](#file)
    - [Foreign Function Interface](#foreign-function-interface)
    - [Forms](#forms)
    - [Functional Programming](#functional-programming)
    - [Game Development](#game-development)
    - [Geolocation](#geolocation)
    - [GUI Development](#gui-development)
    - [Hardware](#hardware)
    - [HTML Manipulation](#html-manipulation)
    - [HTTP Clients](#http-clients)
    - [Image Processing](#image-processing)
    - [Implementations](#implementations)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Internationalization](#internationalization)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [News Feed](#news-feed)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Penetration testing](#penetration-testing)
    - [Permissions](#permissions)
    - [Processes](#processes)
    - [Recommender Systems](#recommender-systems)
    - [Refactoring](#refactoring)
    - [RESTful API](#restful-api)
    - [Robotics](#robotics)
    - [RPC Servers](#rpc-servers)
    - [Science](#science)
    - [Search](#search)
    - [Serialization](#serialization)
    - [Serverless Frameworks](#serverless-frameworks)
    - [Shell](#shell)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Static Site Generator](#static-site-generator)
    - [Tagging](#tagging)
    - [Task Queues](#task-queues)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [URL Manipulation](#url-manipulation)
    - [Video](#video)
    - [Web Asset Management](#web-asset-management)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
- [Resources](#resources)
    - [Books](#books)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
    - [Websites](#websites)
- [Contributing](#contributing)

---

## Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
* [django-grappelli](https://grappelliproject.com/) - A jazzy skin for the Django Admin-Interface.
* [django-jet](https://github.com/geex-arts/django-jet) - Modern responsive template for the Django admin interface with improved functionality.
* [django-suit](https://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Drop-in replacement of Django admin comes with lots of goodies.
* [flask-admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask.
* [flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django).
* [wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.

## Algorithms and Design Patterns

*Python implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms](https://github.com/tayllan/awesome-algorithms).*

* Algorithms
    * [algorithms](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms.
    * [python-ds](https://github.com/prabhupant/python-ds) - A collection of data structure and algorithms for coding interviews.
    * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - Fast and pure-Python implementation of sorted collections.
    * [TheAlgorithms](https://github.com/TheAlgorithms/Python) - All Algorithms implemented in Python.
* Design Patterns
    * [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns.
    * [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python.
    * [transitions](https://github.com/pytransitions/transitions) - A lightweight, object-oriented finite state machine implementation.

## ASGI Servers

*[ASGI](https://asgi.readthedocs.io/en/latest/)-compatible web servers.*

* [daphne](https://github.com/django/daphne) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP.
* [uvicorn](https://github.com/encode/uvicorn) - A lightning-fast ASGI server implementation, using uvloop and httptools.

## Asynchronous Programming

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)
* [trio](https://github.com/python-trio/trio) - A friendly library for async concurrency and I/O.
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast asyncio event loop.

## Audio

*Libraries for manipulating audio and its metadata.*

* Audio
    * [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
    * [audioFlux](https://github.com/libAudioFlux/audioFlux) - A library for audio and music analysis, feature extraction.
    * [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
    * [kapre](https://github.com/keunwoochoi/kapre) - Keras Audio Preprocessors.
    * [librosa](https://github.com/librosa/librosa) - Python library for audio and music analysis.
    * [matchering](https://github.com/sergree/matchering) - A library for automated reference audio mastering.
    * [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
    * [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Audio feature extraction, classification, segmentation and applications.
    * [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
    * [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework.
* Metadata
    * [beets](https://github.com/beetbox/beets) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
    * [eyeD3](https://github.com/nicfit/eyeD3) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
    * [mutagen](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata.
    * [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [authlib](https://github.com/lepture/authlib) - JavaScript Object Signing and Encryption draft implementation.
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works."
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth 2 goodies for Django.
    * [oauthlib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic.
    * [python-oauth2](https://github.com/joestump/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers.
    * [python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism.
* JWT
    * [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.
    * [python-jose](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - A module for generating and verifying JSON Web Tokens.

## Build Tools

*Compile software from source code.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - A make-like build tool for embedded Linux.
* [buildout](http://www.buildout.org/en/latest/) - A build system for creating, assembling and deploying applications from multiple parts.
* [PlatformIO](https://github.com/platformio/platformio-core) - A console tool to build code with different development platforms.
* [pybuilder](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python.
* [SCons](http://www.scons.org/) - A software construction tool.

## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [attrs](https://github.com/python-attrs/attrs) - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions.
* [bidict](https://github.com/jab/bidict) - Efficient, Pythonic bidirectional map data structures and related functionality..
* [Box](https://github.com/cdgriffith/Box) - Python dictionaries with advanced dot notation access.
* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - (Python standard library) Data classes.
* [DottedDict](https://github.com/carlosescri/DottedDict) - A library that provides a method of accessing lists and dicts with a dotted path notation.

## CMS

*Content Management Systems.*

* [django-cms](https://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [feincms](https://github.com/feincms/feincms) - One of the most advanced Content Management Systems built on Django.
* [indico](https://github.com/indico/indico) - A feature-rich event management system, made @ [CERN](https://en.wikipedia.org/wiki/CERN).
* [Kotti](https://github.com/Kotti/Kotti) - A high-level, Pythonic web application framework built on Pyramid.
* [mezzanine](https://github.com/stephenmcd/mezzanine) - A powerful, consistent, and flexible content management platform.
* [plone](https://plone.org/) - A CMS built on top of the open source application server Zope.
* [quokka](https://github.com/rochacbruno/quokka) - Flexible, extensible, small CMS powered by Flask and MongoDB.
* [wagtail](https://wagtail.io/) - A Django content management system.

## Caching

*Libraries for caching data.*

* [beaker](https://github.com/bbangert/beaker) - A WSGI middleware for sessions and caching.
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models.
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
* [dogpile.cache](http://dogpilecache.readthedocs.io/en/latest/) - dogpile.cache is a next generation replacement for Beaker made by the same authors.
* [HermesCache](https://pypi.org/project/HermesCache/) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](https://libmemcached.org/libMemcached.html) interface.
* [python-diskcache](http://www.grantjenks.com/docs/diskcache/) - SQLite and file backed cache backend with faster lookups than memcached and redis.

## ChatOps Tools

*Libraries for chatbot development.*

* [errbot](https://github.com/errbotio/errbot/) - The easiest and most popular chatbot to implement ChatOps.

## Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* Code Analysis
    * [coala](https://github.com/coala/coala/) - Language independent and easily extendable code analysis application.
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    * [prospector](https://github.com/PyCQA/prospector) - A tool to analyse Python code.
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application.
    * [vulture](https://github.com/jendrikseipp/vulture) - A tool for finding and analysing dead Python code.
* Code Linters
    * [flake8](https://pypi.org/project/flake8/) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
        * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
    * [pylama](https://github.com/klen/pylama) - A code audit tool for Python and JavaScript.
    * [pylint](https://www.pylint.org/) - A fully customizable source code analyzer.
    * [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide) - The strictest and most opinionated python linter ever.
* Code Formatters
    * [black](https://github.com/python/black) - The uncompromising Python code formatter.
    * [isort](https://github.com/timothycrosley/isort) - A Python utility / library to sort imports.
    * [yapf](https://github.com/google/yapf) - Yet another Python code formatter from Google.
* Static Type Checkers, also see [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
    * [mypy](http://mypy-lang.org/) - Check variable types during compile time.
    * [pyre-check](https://github.com/facebook/pyre-check) - Performant type checking.
    * [typeshed](https://github.com/python/typeshed) - Collection of library stubs for Python, with static types.
* Static Type Annotations Generators
    * [MonkeyType](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types.
    * [pytype](https://github.com/google/pytype) - Pytype checks and infers types for Python code - without requiring type annotations.

## Command-line Interface Development

*Libraries for building command-line applications.*

* Command-line Application Development
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [cliff](https://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [python-fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A library for building powerful interactive command lines.
* Terminal Rendering
    * [alive-progress](https://github.com/rsalmei/alive-progress) - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - A package to create full-screen text UIs (from interactive forms to ASCII animations).
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal.
    * [colorama](https://pypi.org/project/colorama/) - Cross-platform colored terminal text.
    * [rich](https://github.com/willmcgugan/rich) - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
    * [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI.

## Command-line Tools

*Useful CLI-based tools for productivity.*

* Productivity Tools
    * [copier](https://github.com/pykong/copier) - A library and command-line utility for rendering projects templates.
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
    * [doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal.
    * [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers via the command line.
    * [Invoke](https://github.com/pyinvoke/invoke#readme) - A tool for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
    * [PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output.
    * [percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX.
    * [thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command.
    * [tmuxp](https://github.com/tony/tmuxp) - A [tmux](https://github.com/tmux/tmux) session manager.
    * [try](https://github.com/timofurrer/try) - A dead simple CLI to try out python packages - it's never been easier.
* CLI Enhancements
    * [httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement.
    * [iredis](https://github.com/laixintao/iredis) - Redis CLI with autocompletion and syntax highlighting.
    * [kube-shell](https://github.com/cloudnativelabs/kube-shell) - An integrated shell for working with the Kubernetes CLI.
    * [litecli](https://github.com/dbcli/litecli) - SQLite CLI with autocompletion and syntax highlighting.
    * [mycli](https://github.com/dbcli/mycli) - MySQL CLI with autocompletion and syntax highlighting.
    * [pgcli](https://github.com/dbcli/pgcli) - PostgreSQL CLI with autocompletion and syntax highlighting.
    * [saws](https://github.com/donnemartin/saws) - A Supercharged [aws-cli](https://github.com/aws/aws-cli).

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [python-future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [modernize](https://github.com/PyCQA/modernize) - Modernizes Python code for eventual Python 3 migration.
* [six](https://pypi.org/project/six/) - Python 2 and 3 compatibility utilities.

## Computer Vision

*Libraries for Computer Vision.*

* [EasyOCR](https://github.com/JaidedAI/EasyOCR) - Ready-to-use OCR with 40+ languages supported.
* [Face Recognition](https://github.com/ageitgey/face_recognition) - Simple facial recognition library.
* [Kornia](https://github.com/kornia/kornia/) - Open Source Differentiable Computer Vision Library for PyTorch.
* [OpenCV](https://opencv.org/) - Open Source Computer Vision Library.
* [pytesseract](https://github.com/madmaze/pytesseract) - A wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [SimpleCV](https://github.com/sightmachine/SimpleCV) - An open source framework for building computer vision applications.
* [tesserocr](https://github.com/sirfz/tesserocr) - Another simple, Pillow-friendly, wrapper around the `tesseract-ocr` API for OCR.

## Concurrency and Parallelism

*Libraries for concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
* [scoop](https://github.com/soravux/scoop) - Scalable Concurrent Operations in Python.
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of `asyncio` event loop on top of `libuv`.

## Configuration

*Libraries for storing and parsing configuration options.*

* [configobj](https://github.com/DiffSK/configobj) - INI file parser with validation.
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.
* [hydra](https://github.com/facebookresearch/hydra) - Hydra is a framework for elegantly configuring complex applications.
* [profig](https://profig.readthedocs.io/en/latest/) - Config from multiple formats with value conversion.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code.

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [paramiko](https://github.com/paramiko/paramiko) - The leading native Python SSHv2 protocol library.
* [passlib](https://passlib.readthedocs.io/en/stable/) - Secure password storage/hashing library, very high level.
* [pynacl](https://github.com/pyca/pynacl) - Python binding to the libsodium library.

## Data Analysis

*Libraries for data analyzing.*

* [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler) - Pandas on AWS.
* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data.
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Pandas interface.
* [Optimus](https://github.com/ironmussa/Optimus) - Agile Data Science Workflows made easy with PySpark.
* [Orange](https://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or scripts.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](https://github.com/pyeve/cerberus) - A lightweight and extensible data validation library.
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
* [jsonschema](https://github.com/Julian/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python.
* [schema](https://github.com/keleshev/schema) - A library for validating Python data structures.
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation.
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library.
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python.
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [bqplot](https://github.com/bloomberg/bqplot) - Interactive Plotting Library for the Jupyter Notebook.
* [Cartopy](https://github.com/SciTools/cartopy) - A cartographic python library with matplotlib support.
* [Dash](https://plot.ly/products/dash/) - Built on top of Flask, React and Plotly aimed at analytical web applications.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash)
* [diagrams](https://github.com/mingrammer/diagrams) - Diagram as Code.
* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [plotnine](https://github.com/has2k1/plotnine) - A grammar of graphics for Python based on ggplot2.
* [Pygal](http://www.pygal.org/en/latest/) - A Python SVG Charts Creator.
* [PyGraphviz](https://pypi.org/project/pygraphviz/) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.
* [VisPy](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL.

## Database

*Databases implemented in Python.*

* [pickleDB](https://github.com/patx/pickledb) - A simple and lightweight key-value store for Python.
* [tinydb](https://github.com/msiemens/tinydb) - A tiny, document-oriented database.
* [ZODB](https://github.com/zopefoundation/ZODB) - A native object database for Python. A key-value and object graph database.

## Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork).
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) - A pure Python MySQL driver compatible to mysql-python.
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
    * [queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL.
* SQlite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite)
    * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQlite interface compliant with DB-API 2.0
    * [SuperSQLite](https://github.com/plasticityai/supersqlite) - A supercharged SQLite library built on top of [apsw](https://github.com/rogerbinns/apsw).
* Other Relational Databases
    * [pymssql](https://pymssql.readthedocs.io/en/latest/) - A simple database interface to Microsoft SQL Server.
    * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) - Python driver with native interface for ClickHouse.
* NoSQL Databases
    * [cassandra-driver](https://github.com/datastax/python-driver) - The Python Driver for Apache Cassandra.
    * [happybase](https://github.com/wbolster/happybase) - A developer-friendly library for Apache HBase.
    * [kafka-python](https://github.com/dpkp/kafka-python) - The Python client for Apache Kafka.
    * [py2neo](https://py2neo.org/) - A client library and toolkit for working with Neo4j.
    * [pymongo](https://github.com/mongodb/mongo-python-driver) - The official Python client for MongoDB.
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Python client for Redis.
* Asynchronous Clients
    * [motor](https://github.com/mongodb/motor) - The async Python driver for MongoDB.

## Date and Time

*Libraries for working with dates and times.*

* [Arrow](https://arrow.readthedocs.io/en/latest/) - A Python library that offers a sensible and human-friendly approach to creating, manipulating, formatting and converting dates, times and timestamps.
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - A Python 3 library for parsing human-written times and dates.
* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes.
* [maya](https://github.com/timofurrer/maya) - Datetimes for Humans.
* [moment](https://github.com/zachwill/moment) - A Python library for dealing with dates/times. Inspired by [Moment.js](http://momentjs.com/).
* [Pendulum](https://github.com/sdispater/pendulum) - Python datetimes made easy.
* [PyTime](https://github.com/shinux/PyTime) - An easy-to-use Python module which aims to operate date/time/datetime by string.
* [pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.
* [when.py](https://github.com/dirn/When.py) - Providing user-friendly functions to help perform common date and time actions.

## Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
    * [ipdb](https://github.com/gotcha/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
    * [pdb++](https://github.com/antocuni/pdb) - Another drop-in replacement for pdb.
    * [pudb](https://github.com/inducer/pudb) - A full-screen, console-based Python debugger.
    * [wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets.
* Tracing
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) for Python programs.
    * [manhole](https://github.com/ionelmc/python-manhole) - Debugging UNIX socket connections and present the stacktraces for all threads and an interactive prompt.
    * [pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes.
    * [python-hunter](https://github.com/ionelmc/python-hunter) - A flexible code tracing toolkit.
* Profiler
    * [line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling.
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code.
    * [py-spy](https://github.com/benfred/py-spy) - A sampling profiler for Python programs. Written in Rust.
    * [pyflame](https://github.com/uber/pyflame) - A ptracing profiler For Python.
    * [vprof](https://github.com/nvdv/vprof) - Visual Python profiler.
* Others
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django.
    * [django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
    * [icecream](https://github.com/gruns/icecream) - Inspect variables, expressions, and program execution with a single, simple function call.
    * [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information.

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning..
* [keras](https://github.com/keras-team/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano.
* [mxnet](https://github.com/dmlc/mxnet) - A deep learning framework designed for both efficiency and flexibility.
* [pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [SerpentAI](https://github.com/SerpentAI/SerpentAI) - Game agent framework. Use any video game as a deep learning sandbox.
* [tensorflow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.
* [Theano](https://github.com/Theano/Theano) - A library for fast numerical computation.
* [lightning](https://github.com/Lightning-AI/lightning) - Deep learning framework to train, deploy, and ship AI products Lightning fast.

## DevOps Tools

*Software and libraries for DevOps.*

* Configuration Management
    * [ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform.
    * [cloudinit](https://cloudinit.readthedocs.io/en/latest/) - A multi-distribution package that handles early initialization of a cloud instance.
    * [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
    * [pyinfra](https://github.com/Fizzadar/pyinfra) - A versatile CLI tools and python libraries to automate infrastructure.
    * [saltstack](https://github.com/saltstack/salt) - Infrastructure automation and management system.
* SSH-style Deployment
    * [cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric.
    * [fabric](https://github.com/fabric/fabric) - A simple, Pythonic tool for remote execution and deployment.
    * [fabtools](https://github.com/fabtools/fabtools) - Tools for writing awesome Fabric files.
* Process Management
    * [honcho](https://github.com/nickstenning/honcho) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for managing Procfile-based applications.
    * [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.
* Monitoring
    * [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module.
* Backup
    * [BorgBackup](https://www.borgbackup.org/) - A deduplicating archiver with compression and encryption.
* Others
    * [docker-compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* Batch Processing
    * [dask](https://github.com/dask/dask) - A flexible parallel computing library for analytic computing.
    * [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs.
    * [mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services.
    * [PySpark](https://pypi.org/project/pyspark/) - [Apache Spark](https://spark.apache.org/) Python API.
    * [Ray](https://github.com/ray-project/ray/) - A system for parallel and distributed Python that unifies the machine learning ecosystem.
* Stream Processing
    * [faust](https://github.com/robinhood/faust) - A stream processing library, porting the ideas from [Kafka Streams](https://kafka.apache.org/documentation/streams/) to Python.
    * [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data via [Apache Storm](http://storm.apache.org/).

## Distribution

*Libraries to create packaged executables for release distribution.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - Build and distribute a virtualenv as a Debian package.
* [Nuitka](http://nuitka.net/) - Compile scripts, modules, packages to an executable or extension module.
* [py2app](http://pythonhosted.org/py2app/) - Freezes Python scripts (Mac OS X).
* [py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [pyarmor](https://github.com/dashingsoft/pyarmor) - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform).
* [pynsist](http://pynsist.readthedocs.io/en/latest/) - A tool to build Windows installers, installers bundle Python itself.
* [shiv](https://github.com/linkedin/shiv) - A command line utility for building fully self-contained zipapps (PEP 441), but with all their dependencies included.

## Documentation

*Libraries for generating project documentation.*

* [sphinx](https://github.com/sphinx-doc/sphinx/) - Python Documentation generator.
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc)
* [pdoc](https://github.com/mitmproxy/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries.
* [pycco](https://github.com/pycco-docs/pycco) - The literate-programming-style documentation generator.

## Downloader

*Libraries for downloading.*

* [akshare](https://github.com/jindaxiang/akshare) - A financial data interface library, built for human beings!
* [s3cmd](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront.
* [s4cmd](https://github.com/bloomreach/s4cmd) - Super S3 command line tool, good for higher performance.
* [you-get](https://you-get.org/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](https://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## E-commerce

*Frameworks and libraries for e-commerce and payments.*

* [alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python.
* [Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine.
* [django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [django-shop](https://github.com/awesto/django-shop) - A Django based shop system.
* [forex-python](https://github.com/MicroPyramid/forex-python) - Foreign exchange rates, Bitcoin price index and currency conversion.
* [merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors.
* [money](https://github.com/carlospalol/money) - `Money` class with optional CLDR-backed locale-aware formatting and an extensible currency exchange.
* [python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies.
* [saleor](https://saleor.io/) - Headless open-source e-commerce platform.
* [shoop](https://www.shuup.com/en/) - An open source E-Commerce platform based on Django.

## Editor Plugins and IDEs

* Emacs
    * [elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment.
* Sublime Text
    * [anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE.
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi.
* Vim
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python.
    * [python-mode](https://github.com/python-mode/python-mode) - An all in one plugin for turning Vim into a Python IDE.
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python.
* Visual Studio
    * [PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio.
* Visual Studio Code
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - The official VSCode extension with rich support for Python.
* IDE
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
    * [spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE.

## Email

*Libraries for sending and parsing email.*

* Mail Servers
    * [modoboa](https://github.com/modoboa/modoboa) - A mail hosting and management platform including a modern Web UI.
    * [salmon](https://github.com/moggers87/salmon) - A Python Mail Server.
* Clients
    * [imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans.
    * [yagmail](https://github.com/kootenpv/yagmail) - Yet another Gmail/SMTP client.
* Others
    * [flanker](https://github.com/mailgun/flanker) - An email address and Mime parsing library.
    * [mailer](https://github.com/marrow/mailer) - High-performance extensible mail delivery framework.

## Enterprise Application Integrations

*Platforms and tools for systems integrations in enterprise environments*

* [Zato](https://zato.io) - ESB, SOA, REST, APIs and Cloud Integrations in Python.

## Environment Management

*Libraries for Python version and virtual environment management.*

* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management.
* [virtualenv](https://github.com/pypa/virtualenv) - A tool to create isolated Python environments.

## File

*Libraries for file manipulation and MIME type detection.*

* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html).
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) An cross-platform, object-oriented path library.
* [PyFilesystem2](https://github.com/pyfilesystem/pyfilesystem2) - Python's filesystem abstraction layer.
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library.
* [Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations.
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.

## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [cffi](https://pypi.org/project/cffi/) - Foreign Function Interface for Python calling C code.
* [ctypes](https://docs.python.org/3/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## Forms

*Libraries for working with forms.*

* [Deform](https://github.com/Pylons/deform) - Python HTML form generation library influenced by the formish form generation library.
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 integration with Django.
* [django-bootstrap4](https://github.com/zostera/django-bootstrap4) - Bootstrap 4 integration with Django.
* [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) - A Django app which lets you create beautiful forms in a very elegant and DRY way.
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - A platform independent Django form serializer.
* [WTForms](https://github.com/wtforms/wtforms) - A flexible forms validation and rendering library.

## Functional Programming

*Functional Programming with Python.*

* [Coconut](https://github.com/evhub/coconut) - A variant of Python built for simple, elegant, Pythonic functional programming.
* [CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of `Toolz`: High performance functional utilities.
* [fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP.
* [funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools.
* [more-itertools](https://github.com/erikrose/more-itertools) - More routines for operating on iterables, beyond `itertools`.
* [returns](https://github.com/dry-python/returns) - A set of type-safe monads, transformers, and composition utilities.
* [Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries.

## GUI Development

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/3/library/curses.html) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [Eel](https://github.com/ChrisKnott/Eel) - A library for making simple Electron-like offline HTML/JS GUI apps.
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declarative Syntax like QML.
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering.
* [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line.
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://github.com/pyglet/pyglet) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3).
* [PyQt](https://doc.qt.io/qtforpython/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
* [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - Wrapper for tkinter, Qt, WxPython and Remi.
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component.
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit.
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](https://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.
* [DearPyGui](https://github.com/RaylockLLC/DearPyGui/) - A Simple GPU accelerated Python GUI framework

## GraphQL

*Libraries for working with GraphQL.*

* [graphene](https://github.com/graphql-python/graphene/) - GraphQL framework for Python.
* [tartiflette-aiohttp](https://github.com/tartiflette/tartiflette-aiohttp/) - An `aiohttp`-based wrapper for Tartiflette to expose GraphQL APIs over HTTP.
* [tartiflette-asgi](https://github.com/tartiflette/tartiflette-asgi/) - ASGI support for the Tartiflette GraphQL engine.
* [tartiflette](https://tartiflette.io) - SDL-first GraphQL engine implementation for Python 3.6+ and asyncio.

## Game Development

*Awesome game development libraries.*

* [Arcade](https://api.arcade.academy/en/latest/) - Arcade is a modern Python framework for crafting games with compelling graphics and sound.
* [Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications.
* [Harfang3D](http://www.harfang3d.com) - Python framework for 3D, VR and game development.
* [Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney.
* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [PySDL2](https://pysdl2.readthedocs.io) - A ctypes based wrapper for the SDL2 library.
* [RenPy](https://www.renpy.org/) - A Visual Novel engine.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides a country field for models and forms.
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database.
* [geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON.
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox.

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [bleach](https://github.com/mozilla/bleach) - A whitelist-based HTML sanitization and text linkification library.
* [cssutils](https://pypi.org/project/cssutils/) - A CSS library for Python.
* [html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments.
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python.
* [pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML.
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access.
* [WeasyPrint](http://weasyprint.org) - A visual rendering engine for HTML and CSS that can export to PDF.
* [xmldataset](https://xmldataset.readthedocs.io/en/latest/) - Simple XML Parsing.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.

## HTTP Clients

*Libraries for working with HTTP.*

* [grequests](https://github.com/spyoungtech/grequests) - requests + gevent for asynchronous HTTP requests.
* [httplib2](https://github.com/httplib2/httplib2) - Comprehensive HTTP client library.
* [httpx](https://github.com/encode/httpx) - A next generation HTTP client for Python.
* [requests](https://github.com/psf/requests) - HTTP Requests for Humans.
* [treq](https://github.com/twisted/treq) - Python requests like API built on top of Twisted's HTTP client.
* [urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly.

## Hardware

*Libraries for programming with hardware.*

* [ino](http://inotool.org/) - Command line toolkit for working with [Arduino](https://www.arduino.cc/).
* [keyboard](https://github.com/boppreh/keyboard) - Hook and simulate global keyboard events on Windows and Linux.
* [mouse](https://github.com/boppreh/mouse) - Hook and simulate global mouse events on Windows and Linux.
* [Pingo](http://www.pingo.io/) - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo, etc.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard.
* [scapy](https://github.com/secdev/scapy) - A brilliant packet manipulation library.

## Image Processing

*Libraries for manipulating images.*

* [hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping.
* [imgSeek](https://sourceforge.net/projects/imgseek/) - A project for searching a collection of images using visual similarity.
* [nude.py](https://github.com/hhatto/nude.py) - Nudity detection.
* [pagan](https://github.com/daboth/pagan) - Retro identicon (Avatar) generation based on input string and hash.
* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
* [python-barcode](https://github.com/WhyNotHugo/python-barcode) - Create barcodes in Python with no extra dependencies.
* [pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters.
* [PyMatting](http://github.com/pymatting/pymatting) - A library for alpha matting.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator.
* [pywal](https://github.com/dylanaraps/pywal) - A tool that generates color schemes from images.
* [pyvips](https://github.com/libvips/pyvips) - A fast image processing library with low memory needs.
* [Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees.
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
* [wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.

## Implementations

*Implementations of Python.*

* [CLPython](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp.
* [CPython](https://github.com/python/cpython) - **Default, most widely used implementation of the Python programming language written in C.**
* [Cython](http://cython.org/) - Optimizing Static Compiler for Python.
* [Grumpy](https://github.com/google/grumpy) - More compiler than interpreter as more powerful CPython2.7 replacement (alpha).
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C#.
* [Jython](https://hg.python.org/jython) - Implementation of Python programming language written in Java for the JVM.
* [MicroPython](https://github.com/micropython/micropython) - A lean and efficient Python programming language implementation.
* [Numba](http://numba.pydata.org/) - Python JIT compiler to LLVM aimed at scientific Python.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python.
* [Pyjion](https://github.com/Microsoft/Pyjion) - A JIT for Python based upon CoreCLR.
* [PyPy](https://foss.heptapod.net/pypy/pypy) - A very fast and compliant implementation of the Python language.
* [Pyston](https://github.com/pyston/pyston/) - A Python implementation using JIT techniques.
* [Stackless Python](https://github.com/stackless-dev/stackless) - An enhanced version of the Python programming language.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [bpython](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter.
* [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
    * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
* [ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).

## Internationalization

*Libraries for working with i18n.*

* [Babel](http://babel.pocoo.org/en/latest/) - An internationalization library for Python.
* [PyICU](https://github.com/ovalhub/pyicu) - A wrapper of International Components for Unicode C++ library ([ICU](http://site.icu-project.org/)).

## Job Scheduler

*Libraries for scheduling jobs.*

* [Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows.
* [APScheduler](http://apscheduler.readthedocs.io/en/latest/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django.
* [doit](http://pydoit.org/) - A task runner and build tool.
* [gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface.
* [Joblib](https://joblib.readthedocs.io/) - A set of tools to provide lightweight pipelining in Python.
* [Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm.
* [Prefect](https://github.com/PrefectHQ/prefect) - A modern workflow orchestration framework that makes it easy to build, schedule and monitor robust data pipelines.
* [schedule](https://github.com/dbader/schedule) - Python job scheduling for humans.
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python.
* [TaskFlow](https://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## Logging

*Libraries for generating and working with logs.*

* [logbook](http://logbook.readthedocs.io/en/stable/) - Logging replacement for Python.
* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.
* [loguru](https://github.com/Delgan/loguru) - Library which aims to bring enjoyable logging in Python.
* [sentry-python](https://github.com/getsentry/sentry-python) - Sentry SDK for Python.
* [structlog](https://www.structlog.org/en/stable/) - Structured logging made easy.

## Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.
* [H2O](https://github.com/h2oai/h2o-3) - Open Source Fast Scalable Machine Learning Platform.
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metrics.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library.
* [MindsDB](https://github.com/mindsdb/mindsdb) - MindsDB is an open source AI layer for existing databases that allows you to effortlessly develop, train and deploy state-of-the-art machine learning models using standard queries.

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [Python(x,y)](http://python-xy.github.io/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR).
* [PyWin32](https://github.com/mhammond/pywin32) - Python Extensions for Windows.
* [WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system.
* [boltons](https://github.com/mahmoud/boltons) - A set of pure-Python utilities.
* [itsdangerous](https://github.com/pallets/itsdangerous) - Various helpers to pass trusted data to untrusted environments.
* [magenta](https://github.com/magenta/magenta) - A tool to generate music and art using artificial intelligence.
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python.
* [tryton](http://www.tryton.org/) - A general purpose business framework.

## Natural Language Processing

*Libraries for working with human languages.*

- General
    * [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modeling for Humans.
    * [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
    * [nltk](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
    * [pattern](https://github.com/clips/pattern) - A web mining module.
    * [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages.
    * [pytext](https://github.com/facebookresearch/pytext) - A natural language modeling framework based on PyTorch.
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - A toolkit enabling rapid deep learning NLP prototyping for research.
    * [spacy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
    * [Stanza](https://github.com/stanfordnlp/stanza) - The Stanford NLP Group's official Python library, supporting 60+ languages.
- Chinese
    * [funNLP](https://github.com/fighting41love/funNLP) - A collection of tools and datasets for Chinese NLP.
    * [jieba](https://github.com/fxsjy/jieba) - The most popular Chinese text segmentation library.
    * [pkuseg-python](https://github.com/lancopku/pkuseg-python) - A toolkit for Chinese word segmentation in various domains.
    * [snownlp](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [mininet](https://github.com/mininet/mininet) - A popular network emulator and API written in Python.
* [napalm](https://github.com/napalm-automation/napalm) - Cross-vendor API to manipulate network devices.
* [pox](https://github.com/noxrepo/pox) - A Python-based SDN control applications, such as OpenFlow SDN controllers.

## News Feed

*Libraries for building user's activities.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - Generating generic activity streams from the actions on your site.
* [Stream Framework](https://github.com/tschellenbach/Stream-Framework) - Building news feed and notification systems using Cassandra and Redis.

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - The Django ORM.
    * [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL.
    * [orator](https://github.com/sdispater/orator) -  The Orator ORM provides a simple yet beautiful ActiveRecord implementation.
    * [orm](https://github.com/encode/orm) - An async ORM.
    * [peewee](https://github.com/coleifer/peewee) - A small, expressive ORM.
    * [pony](https://github.com/ponyorm/pony/) - ORM that provides a generator-oriented interface to SQL.
    * [pydal](https://github.com/web2py/pydal/) - A pure Python Database Abstraction Layer.
* NoSQL Databases
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis.
    * [mongoengine](https://github.com/MongoEngine/mongoengine) - A Python Object-Document-Mapper for working with MongoDB.
    * [PynamoDB](https://github.com/pynamodb/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.

## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The package installer for Python.
    * [pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh.
    * [PyPI](https://pypi.org/)
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
* [poetry](https://github.com/sdispater/poetry) - Python dependency management and packaging made easy.

## Package Repositories

*Local PyPI repository server and proxies.*

* [bandersnatch](https://github.com/pypa/bandersnatch/) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
* [devpi](https://github.com/devpi/devpi) - PyPI server and packaging/testing/release tool.
* [localshop](https://github.com/jazzband/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi).
* [warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI).

## Penetration Testing

*Frameworks and tools for penetration testing.*

* [fsociety](https://github.com/Manisso/fsociety) - A Penetration testing framework.
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) - A toolkit for social engineering.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.

## Permissions

*Libraries that allow or deny users access to data or functionality.*

* [django-guardian](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions for Django 1.2+
* [django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

## Processes

*Libraries for starting and communicating with OS processes.*

* [delegator.py](https://github.com/amitt001/delegator.py) - [Subprocesses](https://docs.python.org/3/library/subprocess.html) for Humans 2.0.
* [sarge](https://sarge.readthedocs.io/en/latest/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

## Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
* [fastFM](https://github.com/ibayer/fastFM) - A library for Factorization Machines.
* [implicit](https://github.com/benfred/implicit) - A fast Python implementation of collaborative filtering for implicit datasets.
* [libffm](https://github.com/guestwalk/libffm) - A library for Field-aware Factorization Machine (FFM).
* [lightfm](https://github.com/lyst/lightfm) - A Python implementation of a number of popular recommendation algorithms.
* [spotlight](https://github.com/maciejkula/spotlight) - Deep recommender models using PyTorch.
* [Surprise](https://github.com/NicolasHug/Surprise) - A scikit for building and analyzing recommender systems.
* [tensorrec](https://github.com/jfkirk/tensorrec) - A Recommendation Engine Framework in TensorFlow.

## Refactoring

*Refactoring tools and libraries for Python*

 * [Bicycle Repair Man](http://bicyclerepair.sourceforge.net/) - Bicycle Repair Man, a refactoring tool for Python.
 * [Bowler](https://pybowler.io/) - Safe code refactoring for modern Python.
 * [Rope](https://github.com/python-rope/rope) -  Rope is a python refactoring library.

## RESTful API

*Libraries for building RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions.
    * [flask-api](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
* Pyramid
    * [cornice](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid.
* Framework agnostic
    * [apistar](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3.
    * [falcon](https://github.com/falconry/falcon) - A high-performance framework for building cloud APIs and web app backends.
    * [fastapi](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs with Python 3.6+ based on standard Python type hints.
    * [hug](https://github.com/hugapi/hug) - A Python 3 framework for cleanly exposing APIs.
    * [sandman2](https://github.com/jeffknupp/sandman2) - Automated REST APIs for existing database-driven systems.
    * [sanic](https://github.com/huge-success/sanic) - A Python 3.6+ web server and web framework that's written to go fast.
    * [vibora](https://vibora.io/) - Fast, efficient and asynchronous Web framework inspired by Flask.

## Robotics

*Libraries for robotics.*

* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - This is a compilation of various robotics algorithms with visualizations.
* [rospy](http://wiki.ros.org/rospy) - This is a library for ROS (Robot Operating System).

## RPC Servers

*RPC-compatible servers.*

* [RPyC](https://github.com/tomerfiliba/rpyc) (Remote Python Call) - A transparent and symmetric RPC library for Python
* [zeroRPC](https://github.com/0rpc/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/).

## Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists).*

* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - Providing best-practice pipelines for fully automated high throughput sequencing analysis.
* [bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis.
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [Colour](http://colour-science.org/) - Implementing a comprehensive number of colour theory transformations and algorithms.
* [Karate Club](https://github.com/benedekrozemberczki/karateclub) - Unsupervised machine learning toolbox for graph structured data.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [NIPY](http://nipy.org) - A collection of neuroimaging toolkits.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [ObsPy](https://github.com/obspy/obspy/wiki/) - A Python toolbox for seismology.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [PyDy](http://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
* [PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit.
* [QuTiP](http://qutip.org/) - Quantum Toolbox in Python.
* [RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [SimPy](https://gitlab.com/team-simpy/simpy) -  A process-based discrete-event simulation framework.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
* [Zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django.
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [pysolr](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for [Apache Solr](https://lucene.apache.org/solr/).
* [whoosh](http://whoosh.readthedocs.io/en/latest/) - A fast, pure Python search engine library.

## Serialization

*Libraries for serializing complex data types*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) - A lightweight library for converting complex objects to and from simple Python datatypes.
* [pysimdjson](https://github.com/TkTech/pysimdjson) - A Python bindings for [simdjson](https://github.com/lemire/simdjson).
* [python-rapidjson](https://github.com/python-rapidjson/python-rapidjson) - A Python wrapper around [RapidJSON](https://github.com/Tencent/rapidjson).
* [ultrajson](https://github.com/esnme/ultrajson) - A fast JSON decoder and encoder written in C with Python bindings.

## Serverless Frameworks

*Frameworks for developing serverless Python code.*

* [python-lambda](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying Python code in AWS Lambda.
* [Zappa](https://github.com/zappa/Zappa) - A tool for deploying WSGI applications on AWS Lambda and API Gateway.

## Shell

*Shells based on Python.*

* [xonsh](https://github.com/xonsh/xonsh/) - A Python-powered, cross-platform, Unix-gazing shell language and command prompt.

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [tablib](https://github.com/jazzband/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
* Office
    * [docxtpl](https://github.com/elapouya/python-docx-template) - Editing a docx document by jinja2 template
    * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files.
    * [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
    * [python-pptx](https://github.com/scanny/python-pptx) - Python library for creating and updating PowerPoint (.pptx) files.
    * [unoconv](https://github.com/unoconv/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice.
    * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel .xlsx files.
    * [xlwings](https://github.com/ZoomerAnalytics/xlwings) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files.
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
    * [ReportLab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown.
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML implementations for Python.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV.
* Archive
    * [unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily.

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [lektor](https://github.com/lektor/lektor) - An easy to use static CMS and blog engine.
* [mkdocs](https://github.com/mkdocs/mkdocs/) - Markdown friendly documentation generator.
* [makesite](https://github.com/sunainapai/makesite) - Simple, lightweight, and magic-free static site/blog generator (< 130 lines).
* [nikola](https://github.com/getnikola/nikola) - A static website and blog generator.
* [pelican](https://github.com/getpelican/pelican) - Static site generator that supports Markdown and reST syntax.

## Tagging

*Libraries for tagging items.*

* [django-taggit](https://github.com/jazzband/django-taggit) - Simple tagging for Django.

## Task Queues

*Libraries for working with task queues.*

* [celery](https://docs.celeryproject.org/en/stable/) - An asynchronous task queue/job queue based on distributed message passing.
* [dramatiq](https://github.com/Bogdanp/dramatiq) - A fast and reliable background task processing library for Python 3.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - A distributed worker task queue in Python using Redis & gevent.
* [rq](https://github.com/rq/rq) - Simple job queues for Python.

## Template Engine

*Libraries and tools for templating and lexing.*

* [Genshi](https://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language.
* [Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis) - Hypothesis is an advanced Quickcheck style property based testing library.
    * [nose2](https://github.com/nose-devs/nose2) - The successor to `nose`, based on `unittest2.
    * [pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool.
    * [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework.
    * [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
* Test Runners
    * [green](https://github.com/CleanCut/green) - A clean, colorful test runner.
    * [mamba](http://nestorsalceda.github.io/mamba/) - The definitive testing tool for Python. Born under the banner of BDD.
    * [tox](https://tox.readthedocs.io/en/latest/) - Auto builds and tests distributions in multiple Python versions
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
    * [Schemathesis](https://github.com/kiwicom/schemathesis) - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
    * [Selenium](https://pypi.org/project/selenium/) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework.
    * [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
* Mock
    * [doublex](https://pypi.org/project/doublex/) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [mocket](https://github.com/mindflayer/python-mocket) - A socket mock framework with gevent/asyncio/SSL support.
    * [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
* Object Factories
    * [factory_boy](https://github.com/FactoryBoy/factory_boy) - A test fixtures replacement for Python.
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django.
* Code Coverage
    * [coverage](https://pypi.org/project/coverage/) - Code coverage measurement.
* Fake Data
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
    * [faker](https://github.com/joke2k/faker) - A Python package that generates fake data.
    * [mimesis](https://github.com/lk-geimfari/mimesis) - is a Python library that help you generate fake data.
    * [radar](https://pypi.org/project/radar/) - Generate random datetime / time.

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector.
    * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically.
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching.
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity.
    * [pangu.py](https://github.com/vinta/pangu.py) - Paranoid text spacing.
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python.
    * [pypinyin](https://github.com/mozillazg/python-pinyin) - Convert Chinese hanzi (漢字) to pinyin (拼音).
    * [textdistance](https://github.com/orsinium/textdistance) - Compute distance between sequences with 30+ algorithms.
    * [unidecode](https://pypi.org/project/Unidecode/) - ASCII transliterations of Unicode text.
* Slugify
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode.
    * [python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII.
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency.
* Unique identifiers
    * [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
    * [shortuuid](https://github.com/skorokithakis/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs.
* Parser
    * [ply](https://github.com/dabeaz/ply) - Implementation of lex and yacc parsing tools for Python.
    * [pygments](http://pygments.org/) - A generic syntax highlighter.
    * [pyparsing](https://github.com/pyparsing/pyparsing) - A general purpose framework for generating parsers.
    * [python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components.
    * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers.
    * [python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser.
    * [sqlparse](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser.

## Third-party APIs

*Libraries for accessing third party services APIs. Also see [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) - One Python library for all clouds.
* [boto3](https://github.com/boto/boto3) - Python interface to Amazon Web Services.
* [django-wordpress](https://github.com/istrategylabs/django-wordpress) - WordPress models and views for Django.
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook Platform Python SDK.
* [google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python.
* [gspread](https://github.com/burnash/gspread) - Google Spreadsheets Python API.
* [twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API.

## URL Manipulation

*Libraries for parsing URLs.*

* [furl](https://github.com/gruns/furl) - A small Python library that makes parsing and manipulating URLs easy.
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation.
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib.
* [webargs](https://github.com/marshmallow-code/webargs) - A friendly library for parsing HTTP request arguments with built-in support for popular web frameworks.

## Video

*Libraries for manipulating video and GIFs.*

* [moviepy](https://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.
* [vidgear](https://github.com/abhiTronix/vidgear) - Most Powerful multi-threaded Video Processing framework.

## Web Asset Management

*Tools for managing, compressing and minifying website assets.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file.
* [django-pipeline](https://github.com/jazzband/django-pipeline) - An asset packaging library for Django.
* [django-storages](https://github.com/jschneier/django-storages) - A collection of custom storage back ends for Django.
* [fanstatic](http://www.fanstatic.org/en/latest/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [fileconveyor](http://wimleers.com/fileconveyor) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [flask-assets](https://github.com/miracle2k/flask-assets) - Helps you integrate webassets into your Flask app.
* [webassets](https://github.com/miracle2k/webassets) - Bundles, optimizes, and manages unique cache-busting URLs for static resources.

## Web Content Extracting

*Libraries for extracting web contents.*

* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans.
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs.
* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python.
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool.
* [requests-html](https://github.com/psf/requests-html) - Pythonic HTML Parsing for Humans.
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages.
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc.
* [toapi](https://github.com/gaojiuli/toapi) - Every web site provides APIs.

## Web Crawling

*Libraries to automate web scraping.*

* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* [feedparser](https://pythonhosted.org/feedparser/) - Universal feed parser.
* [grab](https://github.com/lorien/grab) - Site scraping framework.
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - A Python library for automating interaction with websites.
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [robobrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.
* [scrapy](https://scrapy.org/) - A fast high-level screen scraping and web crawling framework.

## Web Frameworks

*Traditional full stack web frameworks. Also see [RESTful API](https://github.com/vinta/awesome-python#restful-api).*

* Synchronous
    * [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
        * [awesome-django](https://github.com/shahraizali/awesome-django)
        * [awesome-django](https://github.com/wsvincent/awesome-django)
    * [Flask](http://flask.pocoo.org/) - A microframework for Python.
        * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
    * [Pyramid](https://pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
        * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)
    * [Masonite](https://github.com/MasoniteFramework/masonite) - The modern and developer centric Python web framework.
* Asynchronous
    * [Tornado](http://www.tornadoweb.org/en/latest/) - A web framework and asynchronous networking library.

## WebSocket

*Libraries for working with WebSocket.*

* [autobahn-python](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
* [channels](https://github.com/django/channels) - Developer-friendly asynchrony for Django.
* [websockets](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients with a focus on correctness and simplicity.

## WSGI Servers

*WSGI-compatible web servers.*

* [bjoern](https://github.com/jonashaag/bjoern) - Asynchronous, very fast and written in C.
* [gunicorn](https://github.com/benoitc/gunicorn) - Pre-forked, ported from Ruby's Unicorn project.
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.
* [waitress](https://github.com/Pylons/waitress) - Multi-threaded, powers Pyramid.
* [werkzeug](https://github.com/pallets/werkzeug) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

# Resources

Where to discover learning resources or new Python libraries.

## Books

- [Fluent Python](https://www.oreilly.com/library/view/fluent-python/9781491946237/)
- [Think Python](https://greenteapress.com/wp/think-python-2e/)

## Websites

* Tutorials
    * [Full Stack Python](https://www.fullstackpython.com/)
    * [Python Cheatsheet](https://www.pythoncheatsheet.org/)
    * [Real Python](https://realpython.com)
    * [The Hitchhiker’s Guide to Python](https://docs.python-guide.org/)
    * [Ultimate Python study guide](https://github.com/huangsam/ultimate-python)
* Libraries
    * [Awesome Python @LibHunt](https://python.libhunt.com/)
* Others
    * [Python ZEEF](https://python.zeef.com/alan.richmond)
    * [Pythonic News](https://news.python.sc/)
    * [What the f*ck Python!](https://github.com/satwikkansal/wtfpython)

## Newsletters

* [Awesome Python Newsletter](http://python.libhunt.com/newsletter)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Tricks](https://realpython.com/python-tricks/)
* [Python Weekly](http://www.pythonweekly.com/)

## Podcasts

* [Django Chat](https://djangochat.com/)
* [Podcast.\_\_init__](https://podcastinit.com/)
* [Python Bytes](https://pythonbytes.fm)
* [Running in Production](https://runninginproduction.com/)
* [Talk Python To Me](https://talkpython.fm/)
* [Test and Code](https://testandcode.com/)
* [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/vinta/awesome-python/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.

- - -

If you have any question about this opinionated list, do not hesitate to contact me [@VintaChen](https://twitter.com/VintaChen) on Twitter or open an issue on GitHub.

