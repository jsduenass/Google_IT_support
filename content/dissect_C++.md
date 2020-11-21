
# Dissect C++
C++ is a compiled language, type safety
the standar library 
programs are intended fo tow audiences the computer and the programmers that is why comments are so important.

## Know the tools
Build tools: three important characteristics chache values so not everything needs to be recompile, parallel working making it faster and support parameters that specify what ought to be build

### compilers
* GCC
* Microsoft Visual C++ (MSVC) 
* Clang
* Intel C++
* MinGW  compiler for windows



GDB is a portable command-line based debugging platform
 to get it on linux 
    sudo apt-get install build-essential gdb
g++ is a command line interface for the MinGW compiler


### parsers

> C  is  by  far  the  most  successful  language  providing  the  programmer  with  a  programming  model  thatclosely  matches  the  machine  model

pointers and memory

__header:__ are files containing definitions end with the suffix .h

### text editor

visual studio code

    g++ --help
    g++ --version
    g++ -print-search-dirs
    g++ -dumpmachine
    g++ -o /bin/hola.exe hola.cpp
    gdb --version
    
    .\bin\hola.exe
    start ./bin/hola.exe
    

### debbuger

> Only well-designed code has a chance of becoming part of a correct, reliable, and maintainable system.
> --- stroustrup, Programming: Principles and Practice using C++

headers

executable or machine code

### linking

error types:
* compile error
* linker erros
* run-time
* logic errors


### libraries
device_driver

### Cmake
relevance
what is build on what 

## data types and standar library
vector vs array, vector allows to have a collection of values of unspecified size where elements can be added or remove when using vector one needs to ```#include vector```
```
vector <int>v;
```
vector range [0:v.size() ) 
<...> are used when a type is being specified


## error handling

## error assumptions
Unless specified otherwise we asume that a program:
1. Should produce the desired results for all ligal inputs
2. Should give reasonable error messages for all ilegal inputs
3. Need not worry about misbehaving hardware
4. Need not worry about misbehaving software
5. Is allow to terminate after finding an error

## source of error checklist
* Poor Specification: it is no clearly define what the program should do. how does this relate with machine learning where the problem by is not well defined? 
* Incomplete programs
* Unexpected input
* Unexpected state
* Logic erros

> A program consists of several separately compiled parts, called _translation units_. Every function in a pogram must be declared with exactly the same type in  every translation unit in which it is used.
error check to approaches error check in the function and error check in the caller when the function is not accesible, like for example it being part of a library

__containers:__ "collection of data"



tokens



# Embedded systems programming
resource and memorymanagment 
>no bugs are allowed while the ship is in a major storm in the middle of the Pacific
concurrency
undereducated programmers: who does not know the the must appropiate lenguage and library features



[An Overview of the C++ Programming Language](https://www.stroustrup.com/crc.pdf)
[Programming: Principles and Practice using C++ ](https://ptgmedia.pearsoncmg.com/images/9780321992789/samplepages/9780321992789.pdf)
[The Design and Evolution of C++ ]()
[Thriving in a Crowded and Changing World: C++ 2006–2020 ](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)


