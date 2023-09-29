# CustomRacketCompiler
## Description
This project is a custom compiler for the Racket language that adds some extra features/queries for a user. Although not as extensive as the original, this custom library includes a variety of features including:
-Integer, string, and boolean operations.
-LISP lists with car/cdr and append functionality.
-Variable bindings in the form of let and let*, including functionality for arity-checking and rest arguments.
-Lambda and case-lambda functionality
Overall, this project helped me to learn the fundamentals when it comes to compiler design, and helped to further my understanding of how compilers translate user-readable code to machine language.
## How to run this program
All of these files must be saved under a single directory, and your device must be able to run Racket, a86 assembly, and C. In order to run this custom compiler, you have to open the compile.rkt file, and enter commands into the read-eval-print loop either using the tell() command or show() functions. In order to input commands, simply put your racket line in parenthesis and put it in the tell() and show() function to produce an output in the REPL or print the assembly of the command respectively.
## Credits
This project was inspired by my compilers class at UMD, which taught me a lot of the ins and outs when it comes to understanding how compilers work and how to write them. 
