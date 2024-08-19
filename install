#!/bin/bash

# Define the branch name
BRANCH="master"

# Define the URL of the pyinfo file on the specified branch of the GitHub repository
GITHUB_URL="https://raw.githubusercontent.com/jvrck/pyinfo/$BRANCH/pyinfo"

# Define the destination directory
DEST_DIR="/usr/local/bin"

# Download the file
curl -o "$DEST_DIR/pyinfo" -L "$GITHUB_URL"

# Make the file executable
chmod +x "$DEST_DIR/pyinfo"

echo "pyinfo has been downloaded from the '$BRANCH' branch to $DEST_DIR and made executable."
echo "You can now run 'pyinfo' from the command line to display Python version information."