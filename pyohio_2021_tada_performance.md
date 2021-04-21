# PyOhio Presentation

## Proposal Title

TaDa it's Magic: Predicting the Performance of Python Functions through Automated Doubling Experiments

## Description

Have you ever tried to understand the performance of a function in your Python
program only to find yourself overwhelmed with the number of performance
evaluation tools? If your experience is anything like mine, then you might have
found the process confusing since, even though many tools have a significant
number of configurations, they often don't share performance results in a
helpful fashion. Faced with the challenge of understanding the performance of a
Python function as its inputs grow bigger, we built a tool called
[TaDa](https://github.com/Tada-Project/tada) that automatically conducts an
experiment and determines the likely "order of growth" for a Python function.

For example, TaDa can help you to pick between two different implementations of
the same function. If TaDa predicts that the order-of-growth for one
implementation is logarithmic for one implementation and quadratic for another,
then a developer should pick the function with a logarithmic order-of-growth.
TaDa can also help developers to better understand the performance of a specific
function by revealing that its performance is, for instance, likely to be cubic
and thus in need of significant improvements in speed. Although these concepts
may, at first glance, seem both confusing and to good to be true, this
presentation will help viewers to gain an eye-opening understanding of how to
use TaDa to gain insights into the performance of Python functions.

## Additional Details

To ensure that the content in this presentation is most beneficial to the people
who watch it, this talk will be accompanied by three GitHub repositories in
addition to the video presentation. First, the presenter will share a repository
that contains the Open Broadcaster Software templates that were used to create
the video. The second GitHub repository to accompany this talk will include the
source code for the presentation slides. Both of these repositories will make it
possible for the people who watch the presentation to recreate all aspects of it
for their own talks and videos. The presenter will also offer another repository
that contains all the presented source code segments in the context of a
realistic Python program that uses both Typer and Poetry. This third GitHub
repository will include, for instance, the instructions needed to install the
project's dependencies with Poetry, run the program to illustrate the
command-line interface built with Typer, and use Poetry to first build the project's
binary source and wheel archives and then publish the project to PyPI.

## Talk Objectives

- The challenges associated with using alternative programs for interface creation and packaging
- How to use Poetry to create a Python package for a program with a command-line interface
- The way in which Typer connects a function's type annotations to a program's command-line interface
- Examples of the commands needed to complete each project step, from creation and building to publishing on PyPI
- The common pitfalls associated with using Typer and Poetry and easy-to-follow steps for resolving them
