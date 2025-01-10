#CS50x #C
# Syllabus

>C. Source Code. Machine Code. Compiler. Correctness, Design, Style. Visual Studio Code. Syntax Highlighting. Escape Sequences. Header Files. Libraries. Manual Pages. Types. Conditionals. Variables. Loops. Linux. Graphical User Interface (GUI). Command-Line Interface (CLI). Constants. Comments. Pseudocode. Operators. Integer Overflow. Floating-Point Imprecision.


# Notes


## Machine Code

```
#include<stdio.h> //standard io.h

int main(void) //void -no input
{
	printf("hello world\n")
}
```


The computer can onlrecy ognize the binary numbers so we need a compiler(编译器) to make the higher level language to a lower level language.

![[compiler.svg]]

use a cloud(best) [URL](https://cs50.dev) or you can use VS code in your computer

Some words you should know: GUI CLI


## Hello world

```
#include<stdio.h>
//pronounced "include standard io.h"

int main(void)
{
	printf("hello world\n")
}
```


Some little concepts:

`#include stdio.h` - include standard io.h
`curly braces` - 大括号{}
`printf` - F means formatted
`semicolon` - 分号;
`syntax` - 句法

In the terminal

```
$ code hello.c
$ make hello
// not need to input hello.c make can look the folder
// make to compile the file from source code to machine code
$ ./hello

and get the 
hello world$(\n)
```


## Library(header files) 

We can use the code others write before via library and for example we can find the stdio.h [here](https:/manual.cs50.io/#stdio.h) 

```
printf("hello, %s\n", answer)
```


Case 1
```
#include <stdio.h>

int main(void)
{
	string answer = get_string("What's your name?");
	printf("hello, &s\n", answer);
}
```

**Error:** get_string is not claimed.

Case 2
```
#include <cs50.h>
#include <stdio.h>

int main(void)
{
	string answer = get_string("What's your name?");
	printf("hello, &s\n", answer);
}
```

Here gets so many cases and we can design the programs so that it can be more efficient.




























