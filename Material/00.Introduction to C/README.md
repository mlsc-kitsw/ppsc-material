# Introduction to C

C is a general purpose, statically typed computer programming language created by Dennis Ritchie at Bell Labs in 1970s.

C was designed to be a high level language but also have low level access to hardware, making it suitable for bare metal programming and operating systems.

C is used everywhere and C is the most fundamental programming language because most of the languages that we use today are derived from C. 

C is used widely in operating systems, embedded systems and other places where perfect execution speed is necessary.

C is a compiled language which means that we have to convert our C code into machine code or binary code that the computer can understand using a compiler.

There are various compilers avaliable in the market for compiling C but the one which we will be using the most is GNU GCC Compiler or MingW

## Why C?

You might wonder what's the use of learning a primitive language like C when we have advanced and more modern languages like Python. 

The thing is, C is bare bones. It lacks a lot of features and is a very basic language meaning that you have to do most of the hardwork yourself which something like Python doesn't offer.

Since you'll be doing everything from the scratch, you'll get to know the inner mechanisms of programming and how computers work, thereby, making your CS fundamentals strong.

Let's dive into the basics of C

## Structure of a C program

Everything in the world needs a uniform structure or a skeleton to hold itself together and exist as an entity. 

Just like humans need skeleton to exist, C program, too, needs its own skeleton or structure to exist.

The basic structure of a C program is as follows:

```c
#include <stdio.h>

int main(){
    printf("Hello world");
}
```

The mandatory elements are:

1. `#include` --> It lets us include necessary functions from header files that are required to run the program. The basic header file in C is stdio.h which includes standard input and output methods.

2. `int main()` --> This is called the main function and it acts as the starting point of the program. The code that you need to run needs to be run from here

3. Statements --> Statements are the necessary lines of code that perform some action inside the program and these are the basic items necessary for a program to do something

