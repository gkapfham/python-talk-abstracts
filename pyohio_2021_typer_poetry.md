# PyOhio Presentation

## Proposal Title

Great On Their Own, Even Better Together: Easily Creating Sophisticated Command-Line Applications with Typer and Poetry

## Description

Have you ever tried to create a command-line application with an extensive
command-line interface and then upload it to PyPI? If your experience is like
mine, then you might have found the process confusing because there are so many
different tools and configurations from which to choose! The good news is that
there is a "sweet spot" that this presentation will introduce: using Typer to
create the command-line interface and Poetry to manage application dependencies
and virtual environments and upload the project to PyPI. Software developers who
follow the steps outlined in this talk will be able to quickly and repeatably
create command-line applications in Python that are available for everyone to
install and use through programs like `pip` and `pipx`.

After briefly overviewing the challenges associated with other approaches to
creating and uploading Python-based command-line applications, this presentation
will introduce the key ideas behind the use of both Typer and Poetry. The
presentation will then explain each command that a software developer must use
to start a Python project with Poetry and to install dependencies like the Typer
package. Along with sketching the idea for an application that has a
command-line interface and showing how to implement it in Typer, the talk will
explain how to use Poetry to upload the application to PyPI and use `pipx` to
install and run it in an isolated environment. People who watch this talk will
gain the knowledge that they need to easily create full-fledged command-line
applications in Python.

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
