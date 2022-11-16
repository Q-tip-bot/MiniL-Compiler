# MiniL-Compiler
 CS152 - Mini-L Compiler Project

The Specifications for the Language are specified in the below link:
https://www.cs.ucr.edu/~mafar001/compiler/webpages1/mini_l.html

In this project we created a compiler for the Turing-complete language MINI-L. The compiler receives the source language and generates intermediate code which is then interpreted by the MIL interpreter and finally executed. We included efficient error reporting that points out any syntax or semantic errors.

To start, run "make" from within the directory to produce an executable for the compiler.

Once the compiler is created run "./compiler program.min > program.mil" which will produce intermediate code and place it into a file.

Finally you will input the new intermediate code into the interpreter using "./mil_run program.mil".

Sample programs have been included in the programs folder for testing.