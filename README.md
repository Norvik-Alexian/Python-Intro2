# Python-Intro2

## Computer Science
* `Computer Science` - is the study of both computer hardware and software design
* `Computer Science` encompasses both the study of theoretical algorithms and the study of implementing them through 
computer hardware and software
* Computer Science includes such fields as software development, security, networking, databases, computer graphics,
artificial, etc.

## Python as Imperative Programming Language
* Python is imperative programming language
* Imperative is programming paradigm in which program statements define steps that describe how to solve the problem
* Declarative is programming paradigm in which program statements define the desired output of program
* Different programming languages are good for different cases.

## Program
* `Algorithm` - finite sequence of instructions that should be performed to solve a particular problem
* `Program` - implements some algorithm. Thus, Program contains instructions that are some operations on values. Program
is set of data and operations on that data.

## Python Program Elements
* Program is represented by modules
* Modules contain statements
* Statements contains expressions
* Expressions create or modify objects

## Why Python?
* High development speed (scripting, no defined types, fewer efforts required)
* Code quality (better readability, better for modifications and code reuse, using different programming methodologies like 
OOP, usually one minimalistic way to write some code)
* Universality (coding for different platforms and different tasks, can be used for everyday tasks)
* Cross-platform (interpreter for different OS)
* Reach set of libraries (NumPy, Matplotlib, etc.)
* Powerful Community

## Python Weaknesses
* Low Performance (program runnin on Python is slower than on many other languages)
* Different types of developers
* Possible different code style at same project or file  can decrease code quality

## Python Platform Features
* OOP support (Polymorphism, multiple inheritance, operators overriding, etc.)
* Procedural programming support
* Free and open-source
* Portable

## Python Programming Features
* Dynamic typing (no type explicit definitions, no variable declaration)
* Automatic memory control (garbage collection)
* Modular Architecture (modules, classes and exceptions)
* Embedded Data Types (lists, strings, dictionaries)
* Embedded operations (sorting, cutting, concatinating, etc.)
* Embedded library (regular expressions, files, etc.)
* External libraries

## Interpreting & Compiling Code
* Compilation - is the process of translating the whole program into some another language 
* Interpretation - is process of translation and execution of program statement by statement using Virtual Machine
* Each platform can have its own interpreter

## How Python Code is Executed
1. Python code is translated into bytecode
2. Bytecode is transferred to PVM (Python Virtual Machine) for interpreting

## Bytecode vs Machine Code
* Machine code - set of instructions which can be directly executed by processor (low level)
* Bytecode - set of instructions which can be executed by some virtual machine (intermediate level)
* Python Bytecode - is special optimized format for storing python code
* Interpreter interprets bytecode
* Bytecode is platform independent
* Bytecode works faster than original Python code.

## PVM
PVM - Python Virtual Machine (interpreter), PVM executes Python bytecode interpreting it, CPython is standard implementation 
of PVM.

## JIT
* JIT (Just In Time Compilation)
* Sometimes it's better to convert code to Machine code and execute it without conversion each time.
* JIT compiler allows to perform such execution
* There are some implementations of JIT for Python like Numba

## Python Performance
Before running program it should be first translated into bytecode, than interpreter will send instructions by instructions
to process that affects performance lose

## GIT Basics
* GIT - is distributed version control system
* Versions control systems allow to store versions of files and handle them
* In case of git such files are stored in local and remote repositories 
* GitHub - is one of remote repositories 

## What is Program?
* Data
* Operations

## What is Python Program?
* Program in Python is set of operations on some object
* Data is represented by Python objects.

## Operations
* Operations in Python are represented by operators and functions

## Data Types
* Data type is a pair of set of values and set of operaitons 
* <{set of values}, {set of operations}>

## Python Embedded Data Types
* Python has reach of predefined data types
* To get type of object we can use type() function
* Better to perform embedded data type than create custom ones
* If we need custom data type better to build it extending some predefined type.

## Objects
* Python is highly object-oriented programming language
* Every value in python is object

## Primitive vs Non-Primitive (Reference) Data Types
* Primitive Data types are mostly created as data type simplification
* Primitive Data type are mostly atomic types, that cannot be composed of other Data types or has no connection to other 
types and have fixed size of memory for values (useful for memory optimization)
* Number Types are Primitive Type in many programming languages, but not in python.
* Python works with Non-Primitive Data types
* Non-primitive Data types are also called Reference Data type as we work with their values by reference not by values.

## Mutable / Immutable Objects
* Mutable are objects which value can change
* Immutable objects value cannot change, new object is created instead.
* Numbers and Strings, for instance are Immutable Data types.
* Immutability brings safety and optimisation possibility
* Mutability brings usage freedom

## Creating New Objects vs Reusing Existent
* Immutable objects are safe for usage by multiple variable as there will be only reading operation for them

## Container Data Types
* Objects that can contain reference to other objects are called container objects
* Array type objects are container objects.