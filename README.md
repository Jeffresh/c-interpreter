# C Interpreter
C interpreter in python (SLY) using an upward translator that accepts inputs in C style language


# Stage 1

The interpreter accepts:

- Assignment statements `(a = 5, a = b = c = 5)`
- Comparison operators `(==, <=, >=, !=)`
- Logical Operators `(&&, ||, !)`
- Arithmetic operators `(+, - , *, / and unary minus)`
- Variables and numerical constants `(a, 5)`


### Implementation

[notebook stage 1](src/c_interpreter.ipynb)

# Stage 2

The interpreter accepts:

- Conditional statements(if - else)

### Implementation (WIP)

[notebook stage 2](src/c_interpreter_stage2.ipynb)

# Stage 3

The interpreter accepts:
- printf function
- Add the AST for arithmetic, logic and relational operators. 

# Stage 4

The interpreter accepts:

- scanf functions from C language.
- general functions(Void) from C language.