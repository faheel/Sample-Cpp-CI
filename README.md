# Sample C++ CI

[![Build Status](https://travis-ci.org/faheel/Sample-Cpp-CI.svg?branch=master)](https://travis-ci.org/faheel/Sample-Cpp-CI)

A sample C++ project with continuous integration.

## Directory structure

Directory | Contains
----------|---------
bin       | program and test binaries
build     | object and dependency files
include   | header files
src       | source code
test      | test code

### Tree

```
.
├── bin
│   ├── data_structures
│   └── number_theory
├── build
│   ├── data_structures
│   └── number_theory
├── include
│   ├── data_structures
│   │   ├── disjoint_set.cpp
│   │   └── disjoint_set.hpp
│   └── third_party
│       └── catch.hpp
├── Makefile
├── src
│   └── number_theory
│       └── fibonacci.cpp
└── test
    ├── data_structures
    │   └── disjoint_set.test.cpp
    └── number_theory
        └── fibonacci.test.cpp
```
