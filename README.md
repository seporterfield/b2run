# B2Run Analytics

A data cleaning and analysis project using tables from the B2Run Bremen company race.

# Usage

## Java
You will need Java installed to use the tabula Python library, since it's just a wrapper for a Java library.
We recommend using a devcontainer setup for this. On Linux (and also in the container) you can run
```sudo apt-get install default-jre```
to install Java.

## Dependencies
Set up a virtual environment, name it "b2run" or add it to your .gitignore, and run `python -m pip install -r requirements.txt` to install the dependencies with pip.

## Pre-commit
Make sure you have pre-commit installed (`pip install pre-commit`) and run `pre-commit install` to prepare the pre-commit hooks.