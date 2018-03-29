### Clean working environment:
##### Source Code Checking Tools
- pylint
- autopep8
- pyflakes
- pycodestyle

- jupyter


for each commit in the .git/hooks/pre-commit the following commands are executed:
#!/bin/sh grep -L "test" *.py | xargs pylint flake8 .
