# PHP Guidelines

## Overview
This file defines guidelines specific to PHP projects.

## Code Standards
- Follow PSR-12 coding standard
- Use strict types where possible (`declare(strict_types=1);`)
- Type hint all function parameters and return types

## Architecture
- Use modern PHP features (namespaces, traits, interfaces)
- Follow SOLID principles
- Prefer dependency injection over static calls
- Prefer maps to switch statements
- Use a configuration file for application settings
- Use Composer for dependency management

## Database
- Store credentials in environment variables

## Testing
- Aim for meaningful test coverage
- Use mocking for external dependencies

## Security
- Sanitize and validate all user input
- Escape output appropriately (HTML, SQL, shell)
