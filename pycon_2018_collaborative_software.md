# Using GitHub, Travis CI, and Python to Introduce Collaborative Software Development

## Abstract

Real-world software engineering is collaborative, commonly involving the use of
Git, GitHub, and continuous integration with Travis CI. This presentation will
explain how to use these technologies and platforms to teach interdisciplinary
and introductory courses in computer programming and software engineering. This
presentation will first show how to create a GitHub organization connected to a
GitHub Classroom with unlimited private repositories that contain instructor
solutions and starter kits and assignment submissions for both individual and
team-based programming assignments. The talk will next explain how to connect
GitHub repositories to continuous integration servers hosted by Travis CI, thus
supporting the cloud-based execution of tests and checks.

The presentation will subsequently introduce a Python program, called
[GatorGrader](https://github.com/gkapfham/gatorgrader), that supports the local
and cloud-based checking of a student's source code and technical writing for a
programming project. GatorGrader can check, for example, that a submission
contains the required number of comments and produces the correct number of
lines of console output. Suitable for use on either a local workstation or a
cloud-based server provided by Travis CI, GatorGrader can, for instance, ensure
that a student makes the requisite number of commits to a GitHub repository and
structures a program in a specified fashion. GatorGrader can also invoke
external programs that ensure the quality of a student's technical writing.
Finally, since most of the aforementioned assignments are designed to be
completed in teams, this presentation introduces
[GatorGrouper](https://github.com/GatorGrouper/gatorgrouper), another Python
program that uses student responses on a Google Form to create suitable groups
of students who collaboratively complete programming projects with GitHub.
