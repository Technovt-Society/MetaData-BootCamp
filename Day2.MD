# March 09' 2023 (Day 2)

## Introduction to Python

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

### It is used for:
1. web development (server-side),
2. software development,
3. mathematics,
4. system scripting.

### What can Python do?
1. Python can be used on a server to create web applications.
2. Python can be used alongside software to create workflows.
3. Python can connect to database systems. It can also read and modify files.
4. Python can be used to handle big data and perform complex mathematics.
5. Python can be used for rapid prototyping, or for production-ready software development.

### Why Python?
1. Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
2. Python has a simple syntax similar to the English language.
3. Python has syntax that allows developers to write programs with fewer lines than some other 4. programming languages.
4. Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
5. Python can be treated in a procedural way, an object-oriented way or a functional way.

### Good to know
1. The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
2. In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

### Python Syntax compared to other programming languages
1. Python was designed for readability, and has some similarities to the English language with influence from mathematics.
2. Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
3. Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.

## Environment Setup

### Windows Installation
Here are the steps to install Python on Windows machine.

Open a Web browser and go to https://www.python.org/downloads/.

Follow the link for the Windows installer python-XYZ.msi file where XYZ is the version you need to install.

To use this installer python-XYZ.msi, the Windows system must support Microsoft Installer 2.0. Save the installer file to your local machine and then run it to find out if your machine supports MSI.

Run the downloaded file. This brings up the Python install wizard, which is really easy to use. Just accept the default settings, wait until the install is finished, and you are done.

### Macintosh Installation
Recent Macs come with Python installed, but it may be several years out of date. See http://www.python.org/download/mac/ for instructions on getting the current version along with extra tools to support development on the Mac. For older Mac OS's before Mac OS X 10.3 (released in 2003), MacPython is available.

Jack Jansen maintains it and you can have full access to the entire documentation at his website − http://www.cwi.nl/~jack/macpython.html. You can find complete installation details for Mac OS installation.

### Setting up PATH
Programs and other executable files can be in many directories, so operating systems provide a search path that lists the directories that the OS searches for executables.

The path is stored in an environment variable, which is a named string maintained by the operating system. This variable contains information available to the command shell and other programs.

The path variable is named as PATH in Unix or Path in Windows (Unix is case sensitive; Windows is not).

In Mac OS, the installer handles the path details. To invoke the Python interpreter from any particular directory, you must add the Python directory to your path.

### Running Python
There are three different ways to start Python −

#### Interactive Interpreter
You can start Python from Unix, DOS, or any other system that provides you a command-line interpreter or shell window.

Enter python the command line.

Start coding right away in the interactive interpreter.

`$python # Unix/Linux`
or
`python% # Unix/Linux`
or
`C:> python # Windows/DOS`

## Data Types in Python

### Built-in Data Types
In programming, data type is an important concept.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

|Data Type | Symbol|
|---------|---------|
|Text Type:|	str|
|Numeric Types:|	int, float, complex|
|Sequence Types:|	list, tuple, range|
|Mapping Type:|	dict|
|Set Types:|	set, frozenset|
|Boolean Type:|	bool|
|Binary Types:|	bytes, bytearray, memoryview|
|None Type:|	NoneType|

## Operators in Python
Operators are used to perform operations on variables and values.
Python divides the operators in the following groups:

1. Arithmetic operators
2. Assignment operators
3. Comparison operators
4. Logical operators
5. Identity operators
6. Membership operators
7. Bitwise operators

[Learn More](https://www.w3schools.com/python/python_operators.asp)

## Conditional Statements
Python supports the usual logical conditions from mathematics:

1. Equals: `a == b`
2. Not Equals: `a != b`
3. Less than: `a < b`
4. Less than or equal to: `a <= b`
5. Greater than: `a > b`
6. Greater than or equal to: `a >= b`

These conditions can be used in several ways, most commonly in "if statements" and loops.
[Learn More](https://www.w3schools.com/python/python_conditions.asp)

## Introduction to  Git repositories and GitHub
### What is Git?
Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then.

### It is used for:
1. Tracking code changes
2. Tracking who made changes
3. Coding collaboration

### What does Git do?
1. Manage projects with Repositories
2. Clone a project to work on a local copy
3. Control and track changes with Staging and Committing
4. Branch and Merge to allow for work on different parts and versions of a project
5. Pull the latest version of the project to a local copy
6. Push local updates to the main project

### Working with Git
1. Initialize Git on a folder, making it a Repository
2. Git now creates a hidden folder to keep track of changes in that folder
3. When a file is changed, added or deleted, it is considered modified
4. You select the modified files you want to Stage
5. The Staged files are Committed, which prompts Git to store a permanent snapshot of the files
6. Git allows you to see the full history of every commit.
7. You can revert back to any previous commit.
8. Git does not store a separate copy of every file in every commit, but keeps track of changes made in each commit!

### Why Git?
1. Over 70% of developers use Git!
2. Developers can work together from anywhere in the world.
3. Developers can see the full history of the project.
4. Developers can revert to earlier versions of a project.

### What is GitHub?
1. Git is not the same as GitHub.
2. GitHub makes tools that use Git.
3. GitHub is the largest host of source code in the world, and has been owned by Microsoft since 2018.

[Learn More](https://www.w3schools.com/git/git_intro.asp?remote=github)