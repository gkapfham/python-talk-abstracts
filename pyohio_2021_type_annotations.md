# PyOhio Presentation

## Proposal Title

Type Annotations in Python: Terribly Intimidating or Tremendously Informative?

## Description

Many software developers have written a Python program without explicitly
declaring the types of the parameters of a function's parameters or return
values. Since the Python programming language now supports type annotations,
many people in the community are exploring this way to explain the data that a
function accepts as input and produces as output. When you start to apply type
annotations in Python, their syntax and meaning can be confusing and it is
common to wonder whether or not there is any benefit to adding them at all!

This presentation will introduce Python's type annotations by iteratively
applying them to a function that does not have any types. After explaining how
to use the types available in the `typing` package, this talk will illustrate
the ways in which a static type checker like `mypy` can find bugs in a Python
program before it is executed. People who watch this talk will gain the
knowledge they need to start writing their first type annotations, use them to
improve their programs, and ultimately find them to be beneficial.

## Additional Details

To ensure that the content in this presentation is most beneficial to the people
who watch it, this talk will be accompanied by three GitHub repositories in
addition to the video presentation. First, the presenter will share a repository
that contains the Open Broadcaster Software templates that were used to create
the video. The second GitHub repository to accompany this talk will include the
source code for the presentation slides themselves. Both of these repositories
will make it possible for the people who watch the presentation to recreate all
aspects of it for their own talks and videos. The presenter will also offer
another repository that contains all the presented source code segments in the
context of a realistic Python program. This third GitHub repository will
include, for instance, the instructions needed to install the project
dependencies, run `mypy` to statically analyze the program's types, and then add
types to resolve the issues raised by the type checker.
