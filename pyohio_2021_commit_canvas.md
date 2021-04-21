# PyOhio Presentation

## Proposal Title

Committing to Writing Good Commit Messages: Supporting the Creation of Human and
Machine-Readable Commit Messages with Python and Machine Learning

## Description

Have you ever read the commit messages that you previously wrote for a Python
project that you maintain on GitHub? If you are like me, then you might find
that some of these commit messages are confusing, incorrect, or downright
hilarious! Since many software developers find it difficult to write a succinct,
yes descriptive commit message, there are a number of standards that constrain
the format a Git commit message should take. Many of these standards, such as
the one called Conventional Commits or the one adopted by the Angular project,
require a programmer to attach a label, like `fix` or `feat`, to designate that
a specific commit, for instance, fixes a defect or adds a new feature.

Since it is often difficult for programmers to confidently pick the right label
for a commit, this presentation introduces a tool that we built, called
[CommitCanvas](https://github.com/CommittedTeam/CommitCanvas), that uses
machine learning to automatically predict the most suitable label for a commit
message. After overviewing the techniques that CommitCanvas uses to predict the
best label for a commit message, this talk will show people how to integrate it
into their workflow as either a pre-commit hook or as a command-line
application. The presentation will also share insights into the effectiveness of
CommitCanvas, thereby helping developers to understand the situations in which
it works best. People who watch this talk will gain the knowledge that the need
to start using CommitCanvas to automatically label their own commit messages.

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
realistic Python program. This third GitHub repository will include, for
instance, the instructions needed to install the project's dependencies, run
`mypy` to statically analyze the program's types, and then add types to
resolve the issues raised by the type checker.

## Talk Objectives

- The benefits and challenges of using type annotations in Python
- The first step to take when adding type annotations to a function in a Python program
- How to use the `typing` package to annotate variables with complex types
- Examples of defects that static type analysis can find when a program has type annotations
- How to handle the situation in which an imported external package does not have type annotations

## Presenter Biography

Gregory M. Kapfhammer is an Associate Professor of Computer Science at Allegheny
College. Along with conducting research in the field of software engineering, he
teaches classes in a variety of technical and scientific areas and enjoys
programming in Python. In the Python community, Gregory has previously given
talks at PyGotham and PyOhio, presented posters at PyCon, and presented at
PyCon's Education Summit. You can learn more about Gregory by visiting his web
site at https://www.gregorykapfhammer.com/, checking out several of his Python
projects at https://github.com/gkapfham, and viewing the slides of his previous
presentations at https://speakerdeck.com/gkapfham.
