# Terraform Guidelines

## Overview
This file defines guidelines specific to Terraform infrastructure-as-code projects.

## Code Structure
- Use modules to organize reusable infrastructure components
- Follow a consistent naming convention for resources
- Keep state files remote (S3, Terraform Cloud, etc.)
- Use workspaces for environment separation when appropriate

## Variables and Outputs
- Use descriptive variable names with clear descriptions
- Provide default values when sensible
- Document all outputs with descriptions

## State Management
- Never edit state files manually
- Use `terraform import` to import existing resources
- Lock state during operations
- Back up state before destructive operations

## Security
- Store secrets in environment variables or secret managers
- Never commit `.tfstate` files containing sensitive data
- Use sensitive flags for sensitive output values
- Follow least privilege principle for IAM roles

## Best Practices
- Use `terraform plan` before `terraform apply`
- Use `terraform fmt` to format code
- Pin provider versions for reproducibility

## Modules
- Keep modules focused and single-purpose
- Provide sensible defaults
