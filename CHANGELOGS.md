# CHANGELOGS

## Table of Contents
+ [2023-12-21](#2023-12-21)
+ [2024-01-05](#2024-01-05)
+ [2024-01-30](#2024-01-30)

## Logs
### 2023-12-21
#### 2211H
+ Initial Commit

- New
    - .gitignore
    - CHANGELOGS.md
    - README.md
    - USAGE.md
    - unittest.py
    - src/
        - packages/
            - __init__.py
            - frameworks/
                - README.md
                - __init__.py
            - libraries/
                - README.md
                - __init__.py
                - sqlite_lib.py

### 2024-01-05
#### 1115H
- New
    - Added new python package library 'apg.py' in 'src/packages/libraries/' - Android Project Generator library
    - Added new directory 'scripts/' in 'src/packages/' for standalone python scripts

### 2024-01-30
#### 1608H
- New
    - Added new source file 'setup.py' in root directory
        + This is the setuptools setup.py python packaging configuration file
    - Added new source file '__init__.py' in 'src/'
    - Added new document 'README.md' in 'src/packages/scripts'
    - Added new source file '__init__.py' in 'src/packages/scripts' to initialize the package as importable

- Updates
    modified:   src/packages/scripts/de-duplicator.p
