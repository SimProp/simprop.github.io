# Installation

## Prerequisites

The following packages are required to build and use the SimProp library, and can be probably installed from your favorite package manager:

- C++ compiler with C++11 support
- [gsl](http://www.gnu.org/software/gsl/) (>= 1.15)

## Basic installation procedure 

Quick procedure for those who know their way around:
```sh
mkdir build
cd build
cmake ..
make -j
```

Unit tests to verify correct behaviour can be run using:

```sh
make test
```







