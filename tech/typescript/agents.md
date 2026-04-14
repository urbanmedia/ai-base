# TypeScript Guidelines

## Overview
This file defines guidelines specific to TypeScript projects.

## Type Safety
- Use strict mode (`"strict": true` in tsconfig)
- Avoid `any` type; use `unknown` when type is truly unknown

## Code Style
- Follow the project's ESLint and Prettier configuration
- Use ES modules (import/export)
- Prefer const over let, avoid var
- Use arrow functions for callbacks
- Enable and fix all linting errors

## Naming Conventions
- PascalCase for classes, interfaces, types, enums
- camelCase for variables, functions, methods
- SCREAMING_SNAKE_CASE for constants
- Use short descriptive, meaningful names

## Async/Await
- Avoid unhandled promise rejections


## Dependencies
- Keep dependencies minimal and up to date
- Audit dependencies for vulnerabilities regularly
- Use lock files (package-lock.json, yarn.lock)
