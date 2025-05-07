# Rust Coding Conventions

This document describes coding standards and best practices for Rust projects.

## Style Guide

- Follow the [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/).
- Use `rustfmt` for automatic formatting.
- Use 4 spaces for indentation.
- Limit lines to 100 characters.
- Use snake_case for variables and functions.
- Use CamelCase for types and traits.

## Modules and Crates

- Organize code into modules and crates logically.
- Use `mod` and `use` statements appropriately.
- Keep modules small and focused.

## Error Handling

- Use `Result` and `Option` types for error handling.
- Avoid panics in library code.
- Use `?` operator for propagating errors.

## Ownership and Borrowing

- Follow ownership and borrowing rules strictly.
- Use references to avoid unnecessary cloning.
- Prefer immutable references when possible.

## Testing

- Write unit tests using the built-in test framework.
- Use integration tests for public APIs.
- Use `cargo test` to run tests.

## Documentation

- Use Rustdoc comments (`///`) for public APIs.
- Document all public functions, types, and modules.
