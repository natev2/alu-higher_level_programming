# alu-higher_level_programming - python-hello_world

This repository contains a simple Python project demonstrating how to run a Python script using a Bash script.

## Files

- main.py – Python script that prints "Best School".
- 0-run – Bash script that runs the Python file specified in the environment variable $PYFILE.
- README.md – Project description and instructions.

## Usage

1. Make files executable:
chmod +x main.py 0-run

2. Set the environment variable $PYFILE:
export PYFILE=main.py

3. Run the Bash script:
./0-run
# Output: Best School

## Notes

- The Bash script 0-run uses $PYFILE to determine which Python script to execute.
- Tested with Python 3.8.5.
- Follows pycodestyle standards and is executable.
