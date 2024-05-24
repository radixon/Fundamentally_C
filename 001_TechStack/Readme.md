# C Programming

The best way to learn C is by writing programs.  Thus, the goal of the first program is to make sure there is an environment that will successfully compile, load, and run a C program.  Additionally, once the program is run the output must be found. <br /><br />

There are many different environments capable of successfully writing, compiling, running, and producing an output using the C programming language. <br /><br />

Once your environment is setup, run this simple helloworld program.

```C
#include <stdio.h>

int main(void){
  printf("Hello, World!!!\n");
  return 0;
}
```

## IDE - Author's Choice

[VS Code](https://code.visualstudio.com/) <br />
An integrated development environment (IDE) is a software package that allows users to edit, compile, link, execute, and debug C programs in a single environment.

## Compiling and Linking - Author's Choice

[WSL 2 - Ubuntu](https://learn.microsoft.com/en-us/windows/wsl/install) <br />
To compile a program the .c extension is required by compilers.  Once a .c program is written, the compiler generally follow three steps:
1. Preprocessing:  The preprocessor processes directives which follow #.
2. Compiling:  The .c program in conjuction with the directives is translated into object code (machine instructions).
3. Linking:  A linker combines the object code produced by the compiler with any additional code necessary to produce an executable program.

## Make - Author's Choice

[Makefile Tutorial - YouTube](https://www.youtube.com/watch?v=yWLkyN_Satk) <br />
[Makefile Walkthrough - Stanford](https://web.stanford.edu/class/archive/cs/cs107/cs107.1174/guide_make.html)

![hello](https://github.com/radixon/Fundamentally_C/assets/59415488/4befdfba-eb2b-46c2-9d0a-8b713ac37ce6)
