# PyOhio Presentation

## Proposal Title

Natural Language Processing with Stars in Your Eyes: How to Build a Chatbot Using Python, spaCy, and Streamlit

## Description

A software developer who wants to create a Python program with a natural
language interface (e.g., a chatbot) is immediately confronted with a confusing
variety of packages, configurations, and tutorials. After overviewing why many
of these options are either difficult to implement or likely to result in a
sub-standard experience for both developers and the people who interact with the
chatbot, this presentation will introduce version 3 of the spaCy package for
natural language processing. Along with explaining why a chatbot needs to
perform text classification to determine human intent, this talk will highlight
how spaCy v3 and its new project templates support this challenging task.

The presentation will show how to use Python, spaCy, and Streamlit to convert
labelled text data to the appropriate format, use this data set to train a
convolutional neural network for text classification and evaluate the accuracy
of the learned model. The talk will also explain both how to package the model
so that others can install it with `pip` and how to create an web-based
dashboard that supports rapid interaction with the trained text classifier. Even
though natural language processing is a challenging area, the people who watch
this talk will gain the knowledge that they need to rapidly create a fast and
easy-to-use text classifier that integrates into a chatbot.

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
