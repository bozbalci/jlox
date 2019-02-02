# jlox

This is an implementation of Lox from [Crafting Interpreters.](http://www.craftinginterpreters.com/) It is built as a
tree-walk interpreter on the Java runtime.

## Challenges from the book

I'll maybe work on these when I get the time.

* More standard library functions
* C-style block comments (`/* ... */`), possibly nested?
* Comma expression
* Conditional ternary operator
* Error productions for binary operators without left-hand operands
* Implicit type conversion of numbers to strings under the `+` operator
* Runtime error for division by zero
* Printing expressions without `print` statements (REPL only)
* Runtime error for accessing uninitialized variables
* `break` and `continue` statements in loop constructs
* Anonymous functions
* Warning for unused local variables
* More efficient local variable lookup using indexes (Chal. 11.4)
* Static methods, metaclasses?
* Read-only properties (getters, Chal. 12.2)
* More features as desired