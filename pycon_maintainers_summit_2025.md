# Flaky Tests are a Fiasco! Practical Strategies for Maintainers to Handle of Test Flakiness

## Abstract

When test cases fail inconsistently without changes to the code under test they
are flaky. These flaky tests do not clearly indicate the presence or absence of
software bugs and thus limit the effectiveness of software maintainers. After
giving concrete examples of flaky tests in real-world Python projects, this talk
overviews the results from a developer survey finding that 59% claimed to deal
with flaky tests on a monthly, weekly, or daily basis. After explaining why
automated test rerunning may not find flaky tests, this talk shows how machine
learning techniques can automatically find flaky tests, thereby taming the
fiasco of flaky tests for software maintainers.

## Key Takeaways

- Developers often deal with flaky tests on a monthly, weekly, or daily basis
- Concrete examples of flaky tests in real-world Python projects
- Limitations of using automated test rerunning to find flaky tests
- Machine learning techniques can automatically find flaky tests
- Use of open-source tools that find flaky tests in Python projects

## Talk Outline

### Introduction (1 min)

- Definition of flaky tests
- Impact on software maintenance
- Brief overview of the problem scope

### The Scale of the Problem (2 min)

- Survey results: 59% of developers face flaky tests regularly
- Real costs to development teams
- Common patterns in Python projects

### Real-world Examples of Flaky Tests (2 min)

- Example 1: Order and non-order dependent flaky tests
- Example 2: Test flakiness from resource race conditions
- Example 3: Flaky tests from external dependencies

### Current Solutions and their Limitations (2 min)

- Limitations of traditional detection methods
- Concrete examples from open-source Python projects
- Cost of manual investigation

### Machine Learning Approach (2 min)

- How ML can detect patterns in test failures
- Key indicators ML models look for
- Success metrics in real projects

### Tools and Next Steps (2 min)

- Available open-source tools for handling flaky tests
- Practical steps for maintainers to get started
- Resources for learning more about test flakiness
