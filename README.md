# The RoboCup Soccer Simulator Users Manual

## Setup instruction for authors

The users manual is maintained using [Sphinx](http://www.sphinx-doc.org/), a documentation tool written in
Python.
The easiest way to setup Sphinx (and Python) environment is to install
[Anaconda](https://www.anaconda.com/download/), which enables you to install Sphinx package using Anaconda
navigator.

## Editing document sources

The `source` directory contains all of the documentation sources as `.rst` files.
The document sources must be written in reStructuredText format.
If you are not familiar with reStructuredText, please refere [this document](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html).

## Build the document

To build html files, type the following command in the top of working directory:
```
  $ make html
```
The outputs are generated under the `build/html` directory.
If successfully built, you can browse the local html files by your favorite web browser.

## Publish the document

Please do not commit any files generated by Sphinx.
If changes of `.rst` files are pushed or merged to the master branch, the documentation pages will be automatically published as https://rcsoccersim.readthedocs.io/.

