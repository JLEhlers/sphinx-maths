# Sphinx Maths Documentation

## Project Overview

This project contains Python functions for performing basic mathematical operations. Sphinx is used to generate documentation for the Python files.

The project includes functions for:

- **Addition** – adds two numbers.
- **Subtraction** – subtracts one number from another.
- **Multiplication** – multiplies two numbers.
- **Division** – divides one number by another.

## Requirements

- Python
- Sphinx

## Installation

1. Open PowerShell or a terminal in the project directory.
2. Activate your virtual environment if you have one.
3. Install Sphinx if it is not already installed:

```bash
python -m pip install sphinx
```

## Generating the Documentation

To generate the HTML documentation, run the following command from the directory containing `conf.py`:

```bash
python -m sphinx -b html . _build/html
```

This command builds the documentation and saves the generated HTML files in the `_build/html/` directory.

If GNU Make is installed and configured, you can also use:

```bash
make html
```

On Windows, you can alternatively use the `make.bat` file if it is included in your project.

## Viewing the Documentation

After generating the documentation, open the following file in your web browser:

```text
_build/html/index.html
```

## Python Documentation

Each mathematical function includes a docstring describing its purpose, parameters, return value, and return type. The docstrings follow a consistent format so Sphinx can use them when generating the project documentation.

