# Automatic Detection of Pseudo-tested Methods Using Python and Pytest

## Description

A test suite can help a software engineer ensure that a program is working as
anticipated. Given the central role of test suites, it is important to ensure
that they are working effectively. One way to measure the effectiveness of a
test suite is to track its code coverage, under the expectation that it is not
possible to find a bug in a region of a program that is not executed. However,
code coverage information may be misleading. For instance, a method is called
pseudo-tested if a test case calls it and passes even when the method's body is
elided during testing.

Since the existence of a pseudo-tested method means that tests are creating a
false sense of confidence in a program's correctness, it is important to detect
them with an accurate and automated technique.
[Function-Fiasco](https://github.com/Function-Fiasco/Function-Fiasco) is an
automatic detection tool that finds pseudo-tested methods in Python programs
that are tested with Pytest test suite. This tool instruments a method so that
it returns a random value instead of the one resulting from the expected
computation. If a test case passes after being instrumented by Function-Fiasco,
then this means that it is pseudo-tested. In addition to explaining how
Function-Fiasco works, this poster presents a preliminary study showing that
pseudo-tested methods exist in all of the chosen Python programs.
