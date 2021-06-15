# Building the Docs

## Prerequisites

- [Python 3.x](https://www.python.org/), pip, and venv

## Building the Docs

Run `build_docs.<ext>` in a terminal, where `<ext>` is either `bat` for 
Windows or `sh` for MacOS and Linux. located at 
`<repo_root>/build_docs.ext` . This script will use Sphinx to generate 
the organization website in `<repo_root>/build/html`.

**Note:** This script will install Sphinx and its dependencies into a virtual 
environment located at `<repo_root>/venv`. 
