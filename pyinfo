#!/bin/bash

# Check if inside a virtual environment
if [ -n "$VIRTUAL_ENV" ]; then
    echo "Virtual Environment: Activated"
    echo "Virtual Environment Path: $VIRTUAL_ENV"
else
    echo "Virtual Environment: Not activated"
fi

echo ""

# Print Python version
echo "Python Version:"
python --version
echo ""

# Print Python interpreter path
echo "Python Interpreter Path:"
which python
echo ""

# Print Python 3 version (if different)
if command -v python3 &> /dev/null; then
    echo "Python 3 Version:"
    python3 --version
    echo ""
fi

# Print Python 3 interpreter path
if command -v python3 &> /dev/null; then
    echo "Python 3 Interpreter Path:"
    which python3
    echo ""
fi

# Print installed packages
echo "Installed Python Packages:"
python -m pip freeze
echo ""

# Print sys.path
echo "Python sys.path:"
python -c "import sys; print('\n'.join(sys.path))"
echo ""

# Print Python executable location (virtual or local)
echo "Python Executable:"
python -c "import sys; print(sys.executable)"
echo ""

# Print Python version details
echo "Python Version Detailed Info:"
python -c "import sys; print(sys.version)"
echo ""
