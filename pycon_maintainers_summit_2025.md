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

### Introduction (2 minutes)

- Definition of flaky tests
- Impact on software maintenance
- Brief overview of the "flaky test fiasco"

### The Scale of the Problem (2 minutes)

- Survey results: 59% of developers face flaky tests regularly
- Real costs that flaky tests introduce to development teams
- Common test flakiness anti-patterns in Python projects

### Real-world Examples of Flaky Tests (3 minutes)

- Example 1: Order and non-order dependent flaky tests
- Example 2: Test flakiness from resource race conditions
- Example 3: Flaky tests from external dependencies

### Current Solutions and their Limitations (3 minutes)

- Description of automated test rerunning techniques
- Limitations of traditional detection methods
- Concrete examples from open-source Python projects

### Machine Learning Approach (3 minutes)

- How machine learning can detect patterns in test failures
- Test case features that aid in flaky test detection
- Evaluating the success of machine learning models in Python projects

### Tools and Next Steps (2 minutes)

- Available open-source tools for handling flaky tests
- Practical steps for maintainers to get started
- Resources for learning more about test flakiness

## Full Names of Speakers

- Lead Presenter: Gregory M. Kapfhammer (Department of Computer and Information Science, Allegheny College)
- Research Collaborators:
    - Michael Hilton, School of Computer Science, Carnegie Mellon University, USA
    - Phil McMinn, Department of Computer Science, University of Sheffield, UK
    - Owain Parry, Department of Computer Science, University of Sheffield, UK

## Speaker Intro

The lead presenter, Gregory M. Kapfhammer, is an Associate Professor of Computer
Science at Allegheny College. Along with conducting and publishing research on
flaky tests, he regularly develops and maintains open-source Python projects on
GitHub. Gregory is a host of the popular Software Engineering Radio podcast,
interviewing industry-leading experts from Google and Anthropic and maintainers
of popular open-source Python projects like FastAPI, Hypothesis, Conda, and
Pixi. He has spoken at both the PyCon Education Summit and a PyCon lightning
talk session and presented posters in the PyCon Poster Symposium, in addition to
giving presentations at PyOhio and PyGotham. He has also appeared as a guest on
podcasts such as Software Engineering Radio, Talk Python, Stack Overflow
Podcast, and Hanselminutes.

## Links to Blog Posts and Articles

### Research Papers

- "Beyond test flakiness: A manifesto for a holistic approach to test suite
health", https://www.gregorykapfhammer.com/research/papers/mcminn2025/

- "Empirically evaluating flaky test detection techniques combining test case
rerunning and machine learning models",
https://www.gregorykapfhammer.com/research/papers/parry2023/

- "A survey of flaky tests",
https://www.gregorykapfhammer.com/research/papers/parry2022/

- "Evaluating features for machine learning detection of order- and
non-order-dependent flaky tests",
https://www.gregorykapfhammer.com/research/papers/parry2022a/

- "https://www.gregorykapfhammer.com/research/papers/parry2022b/",
https://www.gregorykapfhammer.com/research/papers/parry2022b/

- "What do developer-repaired flaky tests tell us about the effectiveness of
automated flaky test detection?",
https://www.gregorykapfhammer.com/research/papers/parry2022c/

- "Flake it till you make it: Using automated repair to induce and fix latent
test flakiness", https://www.gregorykapfhammer.com/research/papers/parry2020/

### Blog Posts

- "Finding flaky tests with machine learning and the FLAKE16 feature set",
https://www.gregorykapfhammer.com/blog/flake16-new-frontier-flaky-tests/

- "What do developers say about flaky tests? Well ... 'They Suck'!",
https://www.gregorykapfhammer.com/blog/flaky-test-developer-survey/

- "You gotta flake it till you make it! Tackling flaky tests with FITTER",
https://www.gregorykapfhammer.com/blog/flake-it-till-you-make-it/

## GitHub Repositories

- Gregory Kapfhammer's GitHub Profile: https://github.com/gkapfham
- CANNIER Tool for Flaky Test Detection: https://github.com/flake-it/cannier-framework 
- CANNIER's Pytest Plugin: https://github.com/flake-it/pytest-cannier
- TestInspect Pytest Plugin: https://github.com/flake-it/testinspect
- ShowFlakes Pytest Plugin: https://github.com/flake-it/showflakes
- Annotated Bibliography on Flaky Tests: https://github.com/flake-it/flaky-tests-bibliography

## Social Media

- Mastodon: https://fosstodon.org/@gkapfham
- LinkedIn: http://www.linkedin.com/in/GregKapfhammer
- Google Scholar: https://scholar.google.com/citations?user=g0eDPjYAAAAJ
- Web: https://www.gregorykapfhammer.com/

## Links to Slides or Videos of Previous Presentations

- Research Papers by Gregory M. Kapfhammer: https://www.gregorykapfhammer.com/research/papers/
- Presentations by Gregory M. Kapfhammer: https://www.gregorykapfhammer.com/research/presentations/
- Podcast Episodes hosted by Gregory M. Kapfhammer on Software Engineering Radio: https://se-radio.net/team/gregory-kapfhammer/
- SpeakerDeck for Gregory M. Kapfhammer: https://speakerdeck.com/gkapfham
- Podcast Episodes hosted by Gregory M. Kapfhammer on Software Engineering Radio: https://se-radio.net/team/gregory-kapfhammer/
