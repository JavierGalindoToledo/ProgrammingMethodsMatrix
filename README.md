# Programming Methods 2: Matrices on Templates

[![Build Status](https://travis-ci.org/UNN-VMK-Software/mp2-lab1-set.svg)][travis]

<!-- TODO
  -
-->

## Goals and objectives

As part of the laboratory work, the task is to create software that supports the efficient storage of matrices and the performance of basic operations on them:

- addition/subtraction;
- copying;
- comparison.

Performing the work involves solving the following tasks:

  1. Implementation of methods of the template class `TVector` according to the specified interface.
  2. Implementation of methods of the template class `TMatrix` according to the specified interface.
  3. Ensuring the functionality of the tests and example of use.
  4. Implementation of test templates covering all methods of the `TVector` and `TMatrix` classes.
  5. Modification of the use case into a test application that allows you to specify matrices and perform basic operations on them.
     
## Tools used

  - Version control system [Git][git].
    - [Git](https://git-scm.com/downloads)
    - [GitHub Desktop](https://desktop.github.com)
  - - Framework for writing automated tests [Google Test][gtest].
  - Microsoft Visual Studio development environment.
  - tility [CMake](http://www.cmake.org) for generating projects based on assembly of source codes.

## General project structure

  - `docs` — instructions for performing laboratory work, useful documents.
  - `gtest` — Google Test library.
  - `include` — directory for placing header files.
  - `samples` — directory for placing demo applications.
  - `src` — directory with source codes (cpp files).
  - `test` — directory with unit tests and the main application,
     initializing the launch of tests.
  - `README.md` — information about the project that you are currently reading.
  - `.gitignore` — list of file extensions ignored by Git when adding files to the repository.
  -  `CMakeLists.txt` — is the root file for building a project using CMake.Can be used to generate a project in a development environment other than Microsoft Visual Studio.
  - `travis.yml` — configuration file for the automatic
       testing Travis-CI. Tests included in the template project
       regularly run on remote [infrastructure][travis].

<!-- LINKS -->

[git]:         https://git-scm.com/book/ru/v2
[gtest]:       https://github.com/google/googletest
[travis]:      https://travis-ci.org/UNN-VMK-Software/mp2-lab1-set

