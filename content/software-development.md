# Objectives as a programmer
> our job as a programmer is to express computation 

take into account room of improvement making it understandable
 
question: programming in a globalized world with many different languanges both natural and programming languages. how do this programs intertac and operate in an incresingly complicated and entagled globlal system?.
> Concerns about correctness, simplicity, and efficiency become ours the minute we start writting code for others and accept the responsability to do that well, that is, we must accept that responsability when we decide to become professinonals.

>almost all of the time we are just interested in knowing how to call a function - seeing the definition would just be a distracting



recognize pausible answers

comments 
* name of the program
* the porpuse 
* who wrote it and when
* version number 
* how the source code is organized
* what assumptions are made about the inputs
* what parts of the code are still missing or not being handle
 
> "a poor craftsman curses his tools." A good craftsman knows the strengths and weaknesses of his tools and adjusts his work accordingly

>programming is understanding -- Krsiten Nygaard

human computer interface is the channel that allows the communication between them. applications tend to become very restrictive on its use.
holistic approach to software development and the computer systems

overrelience on informatic systems
development life cycle

# Know the tools

Where to start 


## programming languages
interpret vs compiple

# Dissect C++
C++ is acompiled language, type safety
the standar library 
programs are intended fo tow audiences the computer and the programmers that is why comments are so important.

## compilers

* GCC
* Microsoft Visual C++ (MSVC) 
* Clang
* Intel C++
* MinGW  compiler for windows



GDB is a portable command-line based debugging platform
 to get it on linux 
    sudo apt-get install build-essential gdb
g++ is a command line interface for the MinGW compiler




parsers

> C  is  by  far  the  most  successful  language  providing  the  programmer  with  a  programming  model  thatclosely  matches  the  machine  model

pointers and memory

__header:__ are files containing definitions end with the suffix .h

# text editor

visual studio code

    g++ --help
    g++ --version
    g++ -print-search-dirs
    g++ -dumpmachine
    g++ -o /bin/hola.exe hola.cpp
    gdb --version
    
    .\bin\hola.exe
    start ./bin/hola.exe
    

debbuger

> Only well-designed code has a chance of becoming part of a correct, reliable, and maintainable system.
> --- stroustrup, Programming: Principles and Practice using C++

headers

executable or machine code

linking

error types:
* compile error
* linker erros
* run-time
* logic errors

vector vs array, vector allows to have a collection of values of unspecified size where elements can be added or remove when using vector one needs to ```#include vector```
```
vector <int>v;
```
vector range [0:v.size() ) 
<...> are used when a type is being specified



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


[An Overview of the C++ Programming Language](https://www.stroustrup.com/crc.pdf)
[Programming: Principles and Practice using C++ ](https://ptgmedia.pearsoncmg.com/images/9780321992789/samplepages/9780321992789.pdf)
[The Design and Evolution of C++ ]()
[Thriving in a Crowded and Changing World: C++ 2006–2020 ](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)



tokens

# Embedded systems programming
resource and memorymanagment 
>no bugs are allowed while the ship is in a major storm in the middle of the Pacific
concurrency
undereducated programmers: who does not know the the must appropiate lenguage and library features

## libraries
device_driver

#Cmake
relevance
what is build on what 

statistics on what computer languages are application build on

computer systems engineer

how are the hirechical 
stack
rigth now a computer seems like an magic black box to the user. he/she has no grasp on how the machine is structured  and the layers that interface with one another, therefore the user is limited to interact with the computer in a very narrow way channel trhough  graphical interface. The hability to pick 
inside and look to the structure on how the different application interacts wil allow the user to use the tool the computer represents, by being able to draw its on to interecat with the machine and this will inturn allow him/her to link toguether different application and enhance interoperability.


automation being thougth as replacement of the human loses it's true potential, the real focus of automation should be to build tools that empower humans allowing them to realize their ideas in a more efficient and effective manner. 
stack


# Dissect java

SDK 

virtual machine

# Dissect python




