# An implementation of a Scheme interpreter

This implementation is in Python. I implemented it as the final project of
the [CS61A UC Berkeley course](https://cs61a.org/). I love this course, it is good
introduction to Computer Science with Python. The lecturer(**John DeNero**) is
really good at transfering knowledge to his students. I love the content of the
course and I will recommend any course from this lecturer

# Features implemented

* **REPL (read eval print loop)** - this helps you use the interpreter in an
interactive manner.
* **Lexical and Syntactic Analyzer** for parsing expressions and representing them
as trees that the *evaluator* can evaluate.
* Basic math expressions (x, /, +, -), conditional expression with if and cond,
boolean expressions, procedure definition, lambda expressions and special forms like
the define and mu form.

# How to run it

* Open a terminal window on your system.
* Download the repository with `git clone [THIS-REPOSITORY]`
* Move to the project repository from the terminal and run `python scheme.py` to start
an interactive session of the scheme interpreter.
* If you want execute a scheme file, run `python scheme.py [SCHEME-FILe]`

# Challenge

If you are interested in interpreters or compilers and want to implement
your own Scheme interpreter, go [here](http://inst.eecs.berkeley.edu/~cs61a/fa13/proj/scheme/scheme.html)
to read about how to get started.
