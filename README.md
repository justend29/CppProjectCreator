# cpp_proj

Generates the project structure and default files to run, build, and test C++ projects.

## Installation  

```bash
$ cd <location to install>
$ git clone https://github.com/justend29/CppProjectCreator.git
$ cd CppProjectCreator
$ chmod ug+x cpp_proj
$ sudo ln -s <location you installed>/CppProjectCreator/cpp_proj /usr/local/bin/cpp_proj
```

## Requirements

**Of course you're using arch/manjaro linux**

1. Get CMake

```bash
$ yay -S cmake
```

2. Get Ninja (platform agnostic Make alternative)

```bash
$ yay -S ninja
```

## Run script

```bash
$ cpp_proj <proj> <target>
```
Subsequent runs will ask before modifying

## Great CMake Resources

* [modern-cmake](https://cliutils.gitlab.io/modern-cmake/chapters/basics/structure.html)
* [quick cheat-sheet](http://www.brianlheim.com/2018/04/09/cmake-cheat-sheet.html)
* [basic project example](https://raymii.org/s/tutorials/Cpp_project_setup_with_cmake_and_unit_tests.html)

## TODO

* Add default cmake install rules
* Add conan support
* Get rid of the single giant, gross script
