# "Chasten Your Python Program: Configurable Program Analysis and Linting with XPath"

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
needs.

## Key Takeaways

- Create custom linting rules through simple YAML configuration
- Practical examples of enforcing code standards like docstrings and type annotations
- Analyze results through interactive dashboards with Datasette
- Integrate Chasten into your development workflow and CI/CD pipelines

## Talk Outline

### Introduction: The Problem with Static Analysis (3 minutes)

- The limitations of regex for code analysis
- The complexity of traditional AST analysis frameworks
- What makes Chasten different: comparison to Ruff and Pylint

### Understanding AST Analysis (8 minutes)

- What is an Abstract Syntax Tree?
  - Python's AST module (2 minutes)
  - How AST represents code structure (2 minutes)
- XPath as a query language for trees
  - XPath basics for programmers (2 minutes)
  - Why XPath works well for AST analysis (2 minutes)

### Getting Started with Chasten (5 minutes)

- Installation and basic setup
- Understanding the configuration files
- Finding missing docstrings (2 minutes)
- Detecting improper nesting of control structures (3 minutes)
- Enforcing type annotations (2 minutes)
- Identifying complex code patterns (3 minutes)

### Analyzing Chasten's Results (2 minutes)

- Saving and integrating results (2 minutes)
- Using the Datasette dashboard (2 minutes)
- Interpreting the findings (3 minutes)

### Integration into Workflows (5 minutes)
- Using Chasten in CI/CD pipelines (2 minutes)
- Incorporating into development practices (2 minutes)
- Teaching scenarios (1 minute)
