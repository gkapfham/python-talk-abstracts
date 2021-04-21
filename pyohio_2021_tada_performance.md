# PyOhio Presentation

## Proposal Title

TaDa it's Magic: Predicting the Performance of Python Functions through Automated Doubling Experiments

## Description

Have you ever tried to understand the performance of a function in your Python
program only to find yourself overwhelmed by the number of performance
evaluation tools? If your experience is anything like mine, then you might have
found the process confusing since, even though many tools have a significant
number of configurations, they often don't share performance results in the most
helpful fashion. Faced with the challenge of understanding the performance of a
Python function as its inputs grow bigger, we built a tool called
[TaDa](https://github.com/Tada-Project/tada) that automatically conducts an
experiment and determines the likely "order of growth" for a Python function.

For example, TaDa can help you to pick between two different implementations of
the same function. If TaDa predicts that the order-of-growth for one
implementation is logarithmic for one implementation and quadratic for another,
then a developer should pick the function that TaDa identifies as having a
logarithmic order-of-growth. TaDa can also help developers to better understand
the performance of a specific function by revealing that its order-of-growth is,
for instance, likely to be cubic when inputs increase in size and thus in need
of significant improvements in speed. Although these concepts may, at first
glance, seem both confusing and to good to be true, this presentation will
help viewers to gain an eye-opening understanding of how to use TaDa to gain
insights into the performance of Python functions.

## Additional Details

To ensure that the content in this presentation is most beneficial to the people
who watch it, this talk will be accompanied by four GitHub repositories in
addition to the video presentation. First, the presenter will share a repository
that contains the Open Broadcaster Software templates that were used to create
the video. The second GitHub repository to accompany this talk will include the
source code for the presentation slides. Both of these repositories will make it
possible for the people who watch the presentation to recreate all aspects of it
for their own talks and videos. The third repository, currently available at
[TaDa](https://github.com/Tada-Project/tada), will include the full source code
and documentation for the TaDa tool. The final repository, currently available
at [Speed-Surprises](https://github.com/Tada-Project/speed-surprises), will
include sample Python functions for use with the TaDa tool. These final two
GitHub repositories will make it possible for viewers of the presentation to try
out the presented ideas and gain hands-on experience in using TaDa to understand
the performance of a Python function.

## Talk Objectives

- The challenges associated with using alternative programs for evaluating a Python program's performance
- The concept of order-of-growth as illustrate through examples of Python functions and their inputs
- The ways in which the TaDa tool helps a programmer to automatically predict the order-of-growth for a Python function
- Examples of the commands that a programmer would type to run the TaDa tool on their own Python functions
- How to integrate TaDa into a realistic workflow for the Python programming and performance evaluation
