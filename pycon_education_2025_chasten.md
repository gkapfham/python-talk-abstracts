# "Automated and Configurable Program Analysis and Linting with Chasten"

## Abstract



Stop wrestling with regular expressions (regex) and complex abstract syntax tree
(AST)-based frameworks to analyze and lint your Python code! Chasten offers an
elegant solution by leveraging XPath expressions to search Python's abstract
syntax tree, making static code analysis both powerful and accessible. In this
talk, you'll discover how to implement custom linting rules, enforce coding
standards, and perform sophisticated pattern matching in your Python projects
using a tool designed for both simplicity and flexibility. Whether you're a
developer tired of writing fragile regex patterns, an instructor validating
student code, or a project maintainer who wants to ensure code quality, Chasten
provides the perfect balance of power and usability for your static analysis
needs. More details about chasten are available at:
https://github.com/AstuteSource/chasten.

## Key Takeaways

- Create custom linting rules through simple YAML configuration
- Practical examples of enforcing code standards on documentation and code
- Ways to analyze results through interactive dashboards with Datasette
- How to integrate Chasten into development workflow and CI/CD pipelines

## Talk Outline

### Introduction: The Problem with Static Analysis (3 minutes)

- The limitations of regex for code analysis
- The complexity of traditional AST analysis frameworks
- What makes Chasten different: comparison to Ruff and Pylint

### Understanding AST Analysis (3 minutes)

- What is an Abstract Syntax Tree (AST)
- XPath basics for programmers
- Using XPath to search the AST

### Getting Started with Chasten (5 minutes)

- Installation and basic setup
- Understanding the configuration files
- Concrete examples of linting rules:
    - Finding missing docstrings
    - Detecting improper nesting of control structures
    - Enforcing type annotations
    - Identifying complex code patterns

### Analyzing Chasten's Results (2 minutes)

- Saving and integrating results
- Using the Datasette dashboard
- Interpreting the findings

### Integration into Workflows (5 minutes)

- Using Chasten in CI/CD pipelines
- Incorporating into development practices
- How to use Chasten for educational purposes
