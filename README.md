# PythonQt
[![License](https://img.shields.io/github/license/mevislab/pythonqt.svg?color=blue)](LICENSE)

PythonQt is a dynamic [Python](https://www.python.org) binding for [Qt](https://www.qt.io).
It offers an easy way to embed the Python scripting language into
your Qt applications.

# Documentation
API documentation is available at: https://mevislab.github.io/pythonqt

# Licensing
PythonQt is distributed under the `LGPL 2.1` license.

## Licensing of Generator
The build system of PythonQt makes use of a patched version of the LGPL'ed QtScript
generator, located in the `generator` directory.

See the `LICENSE.LGPL` file in the generator subdirectory for details.
Copyright (C) 2009 Nokia Corporation and/or its subsidiary(-ies)

See https://code.qt.io/cgit/qt-labs/qtscriptgenerator.git for the original project.
The PythonQt wrappers generated by the generator are distributed under the `LGPL`
as well.

The generated wrappers are pre-generated and checked-in, so you only
need to build and run the generator when you want to build additional wrappers
or you want to upgrade/downgrade to another Qt version, but this requires
updating the typesystems as well.

## How to upgrade Qt
As written above, the generator typesystems must be updated.
