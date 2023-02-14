# Expressions and Operators in JavaScript
This chapter describes JavaScript's expressions and operators, including:

 * Assignment operators
 * Comparison operators
 * Arithmetic operators
 * Bitwise operators
 * BigInt operators
 * Logical operators
 * BigInt operators
 * String operators
 * Conditional (ternary) operator
 * Comma operator
 * Unary operators
 * Relational operators





Relational operators
At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

# Precedence of Operators
The precedence of operators determines the order they are applied when evaluating an expression. For example:

javascript
const x = 1 + 2 * 3;
const y = 2 * 3 + 1;
Despite * and + coming in different orders, both expressions would result in 7 because * has precedence over +. You can override operator precedence by using parentheses (which creates a grouped expression).

# Binary and Unary Operators
JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator. All binary operators in JavaScript are infix.

A unary operator requires a single operand, either before or after the operator. ++ and -- are the only postfix operators in JavaScript — all other operators, like !, typeof, etc. are prefix.

Assignment Operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand.

There are also compound assignment operators that are shorthand for various operations:

* Addition assignment x += f() is shorthand for x = x + f()
* Subtraction assignment x -= f() is shorthand for x = x - f()
* Multiplication assignment x *= f() is shorthand for x = x * f()
* Division assignment x /= f() is shorthand for x = x / f()
* Remainder assignment x %= f() is shorthand for x = x % f()
* Exponentiation assignment x **= f() is shorthand for x = x ** f()
* Left shift assignment x <<= f() is shorthand for x = x << f()
* Right shift assignment x >>= f() is shorthand for x = x >> f()
* Unsigned right shift assignment x >>>= f() is shorthand for x = x >>> f()
* Bitwise AND assignment x &= f() is shorthand for x = x & f()
* Bitwise XOR assignment x ^= f() is shorthand for x = x ^ f()
* Bitwise OR assignment x |= f() is shorthand for x = x | f()
* Logical AND assignment x &&= f() is shorthand for x && (x = f())
* Logical OR assignment x ||= f() is shorthand for x || (x = f())
* Nullish coalescing assignment x ??= f() is shorthand for x ?? (x = f())
