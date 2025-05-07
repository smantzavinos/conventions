# Python Coding Conventions

This document outlines the coding conventions and best practices for Python projects.

## Style Guide

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for code style.
- Use 4 spaces per indentation level.
- Limit lines to 79 characters.
- Use descriptive variable and function names.
- Write docstrings for all public modules, functions, classes, and methods.

## Imports

- Imports should usually be on separate lines.
- Group imports in the following order:
  1. Standard library imports.
  2. Related third party imports.
  3. Local application/library specific imports.
- Use absolute imports whenever possible.

## Naming Conventions

- Use `snake_case` for functions and variables.
- Use `PascalCase` for classes.
- Use `UPPER_CASE` for constants.

## Code Structure

- Keep functions small and focused.
- Use list comprehensions and generator expressions where appropriate.
- Handle exceptions properly and avoid bare except clauses.

## Testing

- Write unit tests for all new features.
- Use `pytest` or `unittest` frameworks.
- Keep tests isolated and repeatable.

## Documentation

- Use docstrings with [reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html) or Google style.
- Document all public APIs.
