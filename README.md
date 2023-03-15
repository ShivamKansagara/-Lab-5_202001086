# -Lab-5_202001086
Static Analysis


IT314 - Software Engineering

Lab 5 - Static Analysis

Name: Shivam Kansagara
ID: 202001086

Static Analysis:

To perform the above analysis I have used python files from github repository and used pylint to do static analysis for the files.

Repository that i have used for static analysis:
https://github.com/ShivamKansagara/qxresearch-event-1

Pylint 

It’s been around for 13 years, and over that time it has included features like coding standards, error detection and refactoring by detecting duplicated code.

Out of the box Pylint is easy to set up, requiring a minimal amount of configuration, but it’s fully customizable if you want it to be — by editing a file you can select which errors and conventions are most relevant to you.

Most of the messages here will be self-explanatory.

Pylint is an incredibly useful tool for static code analysis. It provides a simple score out of 10, a detailed output on what to fix, and the ability to ignore things you do not believe in.

This is part one of three of a series I am doing on how I use pylint in my projects.
Part 1: Executing with Command Line vs Programmatically
Part 2: Pylint Runner Script with Changeable Threshold
Part 3: A Github Action for Failing Builds under a Pylint Threshold




$ pip install pylint

This should give you confirmation it is installed.

$ pylint src/ or py -m pylint file.py

Which should give you some output from the static code analysis followed by a score!

I have used a repository named qxresearch-event-1-master for stat analysis.

Here above attached is pylint been installed.










Now I will check for 6 different files for stat analysis 

File 1 -> passpdf


File 2 -> alarmtiming


File 3 -> calendar







File 4 -> paint




File 5 -> random pass







File 6 -> source-code







