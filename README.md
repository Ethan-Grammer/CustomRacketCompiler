# CustomRacketCompiler

This project is a custom compiler for the Racket language, adding extra features and queries for users. While not as extensive as the original, this custom compiler includes various features such as integer, string, and boolean operations, LISP lists with car/cdr and append functionality, variable bindings with let and let*, lambda and case-lambda functionality, and multiple return values. Overall, this project has helped me understand the fundamentals of compiler design and how compilers translate user-readable code to machine language.

## Functionality

### Integer Queries
- Negation: `(- e)`
- Absolute values: `(abs e)`
- Addition and subtraction: `(e + e2)`, `(e - e2)`, `(add1 e)`, `(add2 e)`, `(e1 + e2 + ... + en)`
- Multiplication: `(e * e2)`

### String Queries
- Append: `(append str str2)`
- Length: `(len str)`

### Boolean Queries
- Conditionals: `(cond cs e)`, `(case e cs e2)`
- Negation: `(not e)`
- Logic gates: `(and e1 e2 ... en)`, `(or e1 e2 ... en)`, `(xor e1 e2 ... en)`

### Bindings
- Let functions: `(let (x y) e)`
- Let* functions: `(let* ((x1 y1) (x2 y2) ... (xn yn)) e)`

### Multiple Return Values
- Functions can return multiple values.
- Functions accept functions with multiple return values as valid input.

## How to Run the Program

Save all files under a single directory, and ensure your device can run Racket, a86 assembly, and C. To run the custom compiler, open the `compile.rkt` file and enter commands into the read-eval-print loop using the `tell()` command or `show()` functions.

To input commands, put your Racket line in quotations and place it in the `tell()` and `show()` function to produce an output in the REPL or print the assembly of the command respectively.

## Credits

This project was inspired by my compilers class at UMD, which taught me the intricacies of understanding how compilers work and how to write them.
