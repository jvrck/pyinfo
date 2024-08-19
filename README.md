# pyinfo.sh

## Overview
`pyinfo.sh` is a shell script that provides detailed information about your Python environment, including the current Python version, interpreter path, installed packages, and more.

## Requirements
- MacOS or Linux
- Bash
- Python

## Installation
1. Clone the repository.
   ```sh
   git clone https://github.com/yourusername/your-repo.git
   ```
2. Navigate to the cloned directory.
   ```sh
   cd your-repo
   ```
3. Make sure the `pyinfo.sh` script has execute permissions.
   ```sh
   chmod +x pyinfo.sh
   ```

## Usage
Simply run the `pyinfo.sh` script to get information about your Python environment.

```sh
./pyinfo.sh
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
