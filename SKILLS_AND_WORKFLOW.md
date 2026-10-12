# Skills and Development Workflow

This page describes general working practices that can be demonstrated without exposing private projects.

## AI-assisted development

I use AI coding assistants to support:
- Understanding unfamiliar code and error messages
- Planning focused implementation steps
- Exploring alternative approaches
- Reviewing code for potential issues
- Designing test cases and interpreting failures
- Writing and improving technical documentation

AI output is a proposal, not proof of correctness. Changes need review and relevant tests.

## Testing and quality

When reporting work, distinguish:
- What was actually implemented
- What was tested, and the scope of those tests
- What failed or remains uncertain
- What requires external verification
- What is planned but not implemented

A passing test suite is evidence about the tested scope, not proof that an entire application is secure or production-ready.

## Safe public demonstrations

Prefer small, self-contained examples written specifically for the portfolio, such as:
- A generic REST API client with mock responses
- A small Python utility with tests
- A toy CRUD application using synthetic data
- A demonstration of retry handling against a local mock service

Do not use private application code, real user data, production endpoints, secrets, or business-specific rules in public examples.
