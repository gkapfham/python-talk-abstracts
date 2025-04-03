# Teaching About Type Annotation and Type Checking in Python

## Speaker Details

- Presenter: Gregory M. Kapfhammer (Department of Computer and Information
Science, Allegheny College)

## Abstract

## Key Takeaways

- Practical ways to demonstrate the benefits of type annotations
- Overview of a tool ecosystem for teaching about types in Python
- Introduction to a GitHub-based workflow for creating projects and examinations
- Suggestions for ways to empirically study the benefits of type annotations
- A wishlist of features for enhancing the usability of type checks for learners

## Talk Outline

### Demonstrating the Benefits of Typing

- Courses from which lessons arise
    - Software engineering
    - Algorithm analysis
    - Next semester: Computing Theory
- Projects that use frameworks benefiting from type annotations
    - FastAPI
    - Typer
    - Hypothesis
    - Pydantic
    - LSP in VSCode
    - Fuzzers

### Overview of the Chosen Tool Ecosystem

- Tools from the Python ecosystem:
    - Package and project management with Poetry or uv
    - Ruff for linting
    - Mypy for type checking
    - Symbex for basic static analysis

- Bespoke tools that we created and maintain:
    - Chasten for configurable static analysis
    - Alchemast for source code transformation
    - GatorGrader for assessment and feedback
    - ExecExam for creating and grading examinations

### Introduction to a GitHub-based Workflow

- Instructor creates a solution with passing checks

### Current Solutions and their Limitations

- Description of automated test rerunning techniques
- Limitations of traditional detection methods
- Concrete examples from open-source Python projects

### Tools and Next Steps (2 minutes)

- Available open-source tools for handling flaky tests
- Practical steps for maintainers to get started
- Resources for learning more about test flakiness



## Speaker Intro

The lead presenter, Gregory M. Kapfhammer, is an Associate Professor of Computer
Science at Allegheny College. Along with conducting and publishing research on
flaky tests, he regularly develops and maintains open-source Python projects on
GitHub. Gregory is a host of the popular Software Engineering Radio podcast,
where he interviews industry-leading experts from Google and Anthropic and
maintainers of popular open-source Python projects like FastAPI, Hypothesis,
Conda, and Pixi. He has spoken at both the PyCon Education Summit and a PyCon
lightning talk session and presented posters in the PyCon Poster Symposium, in
addition to giving presentations at PyOhio and PyGotham. He has also appeared as
a guest on podcasts such as Software Engineering Radio, Talk Python, Stack
Overflow Podcast, and Hanselminutes.

