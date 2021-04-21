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
for their own talks and videos. The third repository, currently available at
[CommitCanvas](https://github.com/CommittedTeam/CommitCanvas), will include a
full-featured implementation of the concepts presented in this talk. After
watching this presentation, people can use the `pre-commit` tool to integrate
CommitCanvas into their own Python project by pointing to this repository.

## Talk Objectives

- Introduction to the challenges associated with writing good Git commit messages
- How Conventional Commits and the Angular standard partially address the challenge of writing commit messages
- Explanation of how machine learning can automatically predict the label for a Git commit message
- How to integrate the CommitCanvas tool into real-world workflows for developing Python projects
- Insights into when the machine learning methods in CommitCanvas will and will not work well

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
