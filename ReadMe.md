pyMetakit [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
=========
![GitLab Build Status](https://gitlab.com/KOLANICH/pyMetakit/badges/master/pipeline.svg)
![GitLab Coverage](https://gitlab.com/KOLANICH/pyMetakit/badges/master/coverage.svg)
[![Coveralls Coverage](https://img.shields.io/coveralls/KOLANICH/pyMetakit.svg)](https://coveralls.io/r/KOLANICH/pyMetakit)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/pyMetakit.svg)](https://libraries.io/github/KOLANICH/pyMetakit)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://github.com/KOLANICH-tools/antiflash.py)

Just a pure python library for parsing metakit4 databases.

Requirements
------------
* [`Python >=3.4`](https://www.python.org/downloads/). [`Python 2` is dead, stop raping its corpse.](https://python3statement.org/) Use `2to3` with manual postprocessing to migrate incompatible code to `3`. It shouldn't take so much time. For unit-testing you need Python 3.6+ or PyPy3 because their `dict` is ordered and deterministic. Python 3 is also semi-dead, 3.7 is the last minor release in 3.
