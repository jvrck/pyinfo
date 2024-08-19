# pyinfo

## Overview
`pyinfo` is a shell script that provides detailed information about your Python environment, including the current Python version, interpreter path, installed packages, and more.

## Requirements
- MacOS or Linux
- Bash
- Python

## Installation
Use the install script to install the `pyinfo` script to your system and make it executable.

```sh
curl -s https://raw.githubusercontent.com/jvrck/pyinfo/master/install | sudo bash
```


## Usage
Simply run the `pyinfo` script to get information about your Python environment.

```sh
pyinfo
```

The script will display:
- Whether you are in a virtual environment and its path
- Python version
- Python interpreter path
- Python 3 version (if available)
- Python 3 interpreter path (if available)
- Installed Python packages
- Python `sys.path`
- Python executable location
- Detailed Python version info
