# C Programming
## Prof. Shiburaj
### Rizvi College of Engineering

Hello everyone,

These set of pages are the materials used by me for the delivery of the lectures in the course of C Programming. 

## Syllabus
- Module 1
    -  Introduction
        -   Introduction to components of a Computer System
        -   Introduction to Algorithm and Flowchart
    -  Fundamentals of C Programming 
        -   Keywords, Identifiers, Constants and Variables
        -   Data types in C
        -   Operators in C
        -   Basic Input and Output Operations
        -   Expressions and Precedence of Operators
        -   In-built Functions 
- Module 2
    -   Control Structures
        -   Introduction to Control Structures
    -   Branching and looping structures
        -   If statement, If-else statement, Nested if-else, else-if Ladder
        -   Switch statement
        -   For loop, While loop
-   Module 3
    -   Functions
        -   Introduction to functions
        -   Function prototype, Function definition, Accessing a function and
parameter passing.
        -   Recursion.
- Module 4
    -   Arrays and Strings
        -   Introduction to Arrays
        -   Declaration and initialization of one dimensional and two-dimensional
arrays.
        -   Definition and initialization of String
        -   String functions 
-   Module 5
    -   Structure and Union
        -   Concept of Structure and Union
        -   Declaration and Initialization of structure and union
        -   Nested structures
        -   Array of Structures
        -   Passing structure to functions
-   Module 6
    -   Pointers 
        -   Fundamentals of pointers
        -   Declaration, initialization and dereferencing of pointers
        -   Operations on Pointers
        -   Concept of dynamic memory allocation

## Scheme

## Sections of a C Program
```c
\\ Comments

\\ Preprocessor Directives

\\ Globals & Constants

\\ Main Function

\\ User defined Functions

```

## C Compilers
-   GNU GCC [(Link 1)](https://gcc.gnu.org/) [(Link for Windows - Mingw)](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download)
-   Tiny C Compiler [(Link)](https://bellard.org/tcc/)
-   Portable C Compiler [(Link)](http://pcc.ludd.ltu.se/)
-   CLang [(Link)](http://releases.llvm.org/download.html)
-   Digital Mars Compiler [(Link)](https://digitalmars.com/download/freecompiler.html)


## IDE for C Programming
-   CodeBlocks [(http://www.codeblocks.org/)](http://www.codeblocks.org/)
-   Bloodshed Dev C++ [(https://www.bloodshed.net)](https://www.bloodshed.net/devcpp.html)
-   Notepad++ [(https://notepad-plus-plus.org)](https://notepad-plus-plus.org/downloads/) [(Use NppExec Plugin with Gcc Compiler)](https://gist.github.com/softon/0e4d48eb72119607d003c88197daa6d5)
-   Visual Studio Comunity Edition [(Link)](https://visualstudio.microsoft.com/vs/features/cplusplus/)
-   Turbo C++ [(Link to Website)](https://developerinsider.co/download-turbo-c-for-windows-7-8-8-1-and-windows-10-32-64-bit-full-screen/)

## GCC Compiler Parameters
-   -o name = Set the name of the output file eg: -o test.exe
-   -E  =   Used to return the preprocessor output (.i extention)
-   -S  =   Used to return assembly code  (.s extension)
-   -C  =   Used to create the object file (.o extension)
-   -save-temps =   To generate all the intermediate files during compilation.
-   -ansi   =   To enable the ANSI standard
-   -std=c89|c99|c9x = To change the standard
-   -pedantic-errors = Strict conformance to ISO standards
-   -Wall = Show errors and warnings

## Links
-   List of C Programs [(https://www.faceprep.in/c-programming-questions/)](https://www.faceprep.in/c-programming-questions/)
-   List of C Programs Link 2 [(https://www.studytonight.com/c/programs/)](https://www.studytonight.com/c/programs/)

## C Program Structure (Basic)
```
/*
    Aim: ...
    Author: ...
    Class: ...
*/

#include <stdio.h>

int main ()
{
    // Your code starts here


    return 0;
}

```

## C Program Structure (Advanced)
```
/* Documentation */
/*
    Aim: ...
    Author: ...
    Class: ...
*/

/* Libraries */
#include <stdio.h>

/* Function Declarations */
int example(int x);

/* Global Variables & Constants */
int x = 100;
#define PI 3.142 

/* Main Function */
int main ()
{
    // Your code starts here


    return 0;
}

/* Function Definitions */
int example(int x){

}

```