# Python Lab Worksheet

## Part A

### What the commands do

The `mkdir` command creates directories. The `cd` command changes the current working directory. The `New-Item` command creates files. Output redirection (`>`) writes text into a file. The `tree /F` command displays the complete folder structure including files.

### Why separate src, tests, and docs?

Separating code into `src`, `tests`, and `docs` improves organization. The `src` folder contains source code, `tests` contains testing files, and `docs` contains documentation. This structure makes projects easier to maintain and understand.

---

## Part B

### What does .gitignore do?

A `.gitignore` file tells Git which files and folders should not be tracked. This prevents unnecessary, temporary, or sensitive files from being uploaded to the repository.

### Why ignore **pycache** and *.pyc?

Python automatically creates cache folders and compiled bytecode files. These files can be regenerated and do not need to be stored in Git.

### What does commit history reveal?

Commit history shows the progression of a project over time. It records what changes were made, who made them, and when they were made.

---

## Part C

Python's import system allows code to be organized into separate modules. In this project, `utils.py` contains reusable functions, while `main.py` imports and uses them. The statement `from utils import square, is_even, celsius_to_fahrenheit` makes those functions available inside `main.py`, allowing the main program to call them without rewriting the code. This improves code organization, readability, and reusability.



The program was tested with three different inputs:

Input: 5

* Square: 25
* Odd number
* Fahrenheit: 41.0

Input: 8

* Square: 64
* Even number
* Fahrenheit: 46.4

Input: 10

* Square: 100
* Even number
* Fahrenheit: 50.0

All outputs matched the expected calculations, confirming that the functions work correctly.


---

## Part D

(We will add this section after completing the GitHub workflow.)
