# Svelte Coding Conventions

This document outlines best practices and coding standards for Svelte projects.

## Style Guide

- Use 2 spaces for indentation.
- Limit lines to 80-100 characters.
- Use kebab-case for component filenames.
- Use PascalCase for component names.
- Keep components small and focused.

## Script Section

- Use `<script lang="ts">` for TypeScript support.
- Declare reactive variables with `$:` syntax.
- Use stores for shared state management.
- Avoid side effects in reactive statements.

## Markup

- Use semantic HTML elements.
- Bind attributes and events using Svelte syntax.
- Use slots for component composition.
- Keep markup clean and readable.

## Styling

- Use scoped styles within components.
- Prefer CSS variables for theming.
- Avoid global styles unless necessary.

## Testing

- Use testing libraries like `@testing-library/svelte`.
- Write unit tests for components.
- Test user interactions and component outputs.

## Documentation

- Document components with comments.
- Provide usage examples.
