# Lox
An interpreter for the Lox programming language, as described in [Crafting Interpreters](http://craftinginterpreters.com/).

Specifically, this is the Java-based interpreter from Part II of the book.

## Additional Features

In addition to the core language features described in Crafting Interpreters, this interpreter supports:

- Block-style comments. e.g. `/* Some comment */`.
- As long as one operand is a string, the `+` operator can be used to concatenate operands of any type into a string
e.g. `"This makes " + 1 + " string."`.
- `break` statements in loops.