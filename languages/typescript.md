# TypeScript Coding Conventions

This document provides coding standards and best practices for TypeScript projects.

## Style Guide

- Follow the [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) and [TSLint](https://palantir.github.io/tslint/) rules.
- Use 2 spaces for indentation.
- Limit lines to 80-100 characters.
- Use semicolons consistently.
- Prefer `const` and `let` over `var`.

## Typing

- Use explicit types where possible.
- Avoid using `any` unless absolutely necessary.
- Use interfaces and type aliases to define complex types.
- Use enums for fixed sets of values.

## Naming Conventions

- Use `camelCase` for variables and functions.
- Use `PascalCase` for classes and interfaces.
- Prefix interfaces with `I` only if it improves clarity.

## Code Structure

- Organize code into modules.
- Use async/await for asynchronous code.
- Avoid deeply nested callbacks.
- Use strict null checks.

## Testing

- Use frameworks like Vitest or Playright.
- Write tests for all public functions and classes.
- Mock dependencies where appropriate.

## Documentation

- Use TSDoc for documenting APIs.
- Include examples in documentation comments.
