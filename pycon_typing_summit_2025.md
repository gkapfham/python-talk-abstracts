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
    - Mutation testing

### Overview of the Chosen Tool Ecosystem

- Tools from the Python ecosystem:
    - Package and project management with Poetry or uv
    - Ruff for linting
    - Mypy for type checking
    - Symbex for basic static analysis
    - Pytest for automated testing
    - Coverage.py for test coverage analysis
    - Mutmut for mutation testing

- Bespoke tools that we created and maintain:
    - Chasten for configurable static analysis
    - GatorGrader for assessment and feedback
    - ExecExam for creating and grading examinations
    - Alchemast for source code transformation

### Introduction to a GitHub-based Workflow

- Instructor creates a solution with passing checks
    - Create a complete implementation of project or examination
    - Configure checking tools and integrate them with GatorGrader
    - Confirm that all checks pass locally and in GitHub Actions
- Instructor creates a starter with purposefully failing checks
    - Use Alchemast to transform source code of the solution:
        - Weaken or remove type annotations
        - Remove assertions and type checks
        - Remove method bodies, comments, and docstrings
    - Confirm that designated checks fail locally and in GitHub Actions
- Create a new project configuration in GitHub Classroom
- Invite students to the project or examination through GitHub Classroom
- Students complete project while running checks locally and in GitHub Actions

### Studying the Benefits of Typing

- Is there evidence to share with students that typing is beneficial?
    - Gopinath and Walkingshaw, Mutation 2017 workshop paper: "(1) the mutants
    killed by the type checker were a strict subset of the mutants killed by
    the test suite, and (2) simple type annotations were just as effective at
    killing mutants as more sophisticated type annotations."
    - Di Grazia and Pradel, ESEC/FSE 2022 conference paper: "Most projects have
    statically detectable type errors, and type errors seem to not prevent
    developers from committing code. A few kinds of mistakes account for most
    type errors."
    - These studies largely present results suggesting that types are not
    better than tests and that, moreover, programmers commit code that has
    statically detectable type errors. Can we conduct new experiments to look
    at the benefits of type annotations from a different perspective?
- How can we empirically study whether or not typing enhances either the
productivity of Python learners and/or their ability to write correct code?
    - Does type checking detect defects introduced by learners?
    - Does type checking detect defects created by mutation testing tools?
    - What is the correlation between real-world defects and mutants?
    - Are open-source Python projects configured to automatically detect
      common linting and type checking errors?

### Tools and Next Steps (2 minutes)

- Available open-source tools for handling flaky tests
- Practical steps for maintainers to get started
- Resources for learning more about test flakiness

## Speaker Intro

Gregory M. Kapfhammer is an Associate Professor of Computer and Information
Science at Allegheny College. Along with conducting and publishing research on
flaky tests, he regularly develops and maintains open-source Python projects on
GitHub. Gregory is a host of the popular Software Engineering Radio podcast,
where he interviews industry-leading experts from Google and Anthropic and
maintainers of popular open-source Python projects like FastAPI, Hypothesis,
Conda, and Pixi. He has spoken at both the PyCon Education Summit and a PyCon
lightning talk session and presented posters in the PyCon Poster Symposium, in
addition to giving presentations at PyOhio and PyGotham. He has also appeared
as a guest on podcasts such as Software Engineering Radio, Talk Python, the
Stack Overflow Podcast, and Hanselminutes.

## Research Paper References

- Rahul Gopinath and Eric Walkingshaw. 2017. How Good Are Your Types? Using
Mutation Analysis to Evaluate the Effectiveness of Type Annotations. In
Mutation 2017. 122–127. https://doi.org/10.1109/ICSTW.2017.28

- Lukas Lazarek, Ben Greenman, Matthias Felleisen, and Christos Dimoulas. 2021.
How to evaluate blame for gradual types. Proc. ACM Program. Lang. 5, ICFP,
Article 68 (August 2021), 29 pages. https://doi.org/10.1145/3473573

- Luca Di Grazia and Michael Pradel. 2022. The evolution of type annotations in
python: an empirical study. In Proceedings of the 30th ACM Joint European
Software Engineering Conference and Symposium on the Foundations of Software
Engineering (ESEC/FSE 2022). Association for Computing Machinery, New York, NY,
USA, 209–220. https://doi.org/10.1145/3540250.3549114

- Yimeng Guo, Zhifei Chen, Lin Chen, Wenjie Xu, Yanhui Li, Yuming Zhou, and
Baowen Xu. 2024. Generating Python Type Annotations from Type Inference: How
Far Are We? ACM Trans. Softw. Eng. Methodol. 33, 5, Article 123 (June 2024), 38
pages. https://doi.org/10.1145/3652153
