# C Programming Quick Reference

C is a general purpose, procedural programming language. It is ideal for system programming. C has the ability to manipulate bits, bytes and addresses.

## Features of C

- Structured language
- General purpose language
- Portability
- Code Re-usability
- Limited number of keywords

## Things to consider while coding in c

- Every C statement must end with a ;.
- There are only 32 reserved keywords.
- These keywords cannot be used for variable names.
- File should have the extension .code
- Program need to compiled before execution.

## Getting started

To get started with C programming you need two important things

- An IDE
- A Compiler


## Basic structure of a C program

```C
#include<stdio.h>     // Preprocessor Directives

void main()           // Entry point to the program
{
  printf("Hello World!");
}
```
## Data types

C offers 5 basic built-in data types
They are...
- int : integer
- char - character
- long - long Integer
- float - fractional number
- double - long float

## Placeholders

- %c - character
- %d - Integer
- %f - floating point number
- %s - string
- %p - pointer

## Control Characters


- \n - New line
- \b - Backspace
- \t - horizontal tab
-  \\ - Backslash is used as escape Character


## Receiving input from the user

**scanf** function is used to receive input from the user.
A **&** sign comes before each variable name that comes in variable listing. Character strings are exceptions from this rule.

Example:

```c
int a;
float b;
scanf("%d%f",a,b);

```
## Expressions and Operators

Note:

> **&** is used to indicate starting address of the variable
