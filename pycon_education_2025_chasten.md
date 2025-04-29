# "Automated and Configurable Programming Project Checking with Chasten"

## Abstract

Instructors who invite their students to complete programming assignments often
need automated tools to confirm that a submission meets the stated requirements.
Although it is possible to use regular expressions or abstract syntax tree
parsing to perform these types of checks, these approaches are often either
error-prone or time-consuming to build. This talk presents Chasten, a Python
tool that offers an elegant solution by leveraging XPath expressions to search
Python's abstract syntax tree, making static code analysis both powerful and
accessible. This presentation explains how teachers can implement custom linting
rules, enforce coding standards, and perform sophisticated pattern matching on a
student's Python programming project. More details about freely available and
open-source Chasten tool are available at:
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
