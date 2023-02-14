# The Comparison Operators
in JavaScript are used to compare the values of two operands and return a boolean value (true or false) based on the result of the comparison. The comparison can be between numerical, string, logical, or object values.

There are two types of comparison operators in JavaScript: equality comparison operators and relational comparison operators.

### The equality comparison operators are:

* (equal to): returns true if the operands are equal. This operator performs type conversion to make the comparison if the operands are of different types.
*  (not equal to): returns true if the operands are not equal. This operator performs type conversion to make the comparison if the operands are of different types.
The strict equality comparison operators are:

* (strict equal to): returns true if the operands are equal and of the same type. This operator does not perform type conversion.
* (strict not equal to): returns true if the operands are not equal or are of different types. This operator does not perform type conversion.
* 
### The relational comparison operators are:

* (greater than): returns true if the left operand is greater than the right operand.
* (greater than or equal to): returns true if the left operand is greater than or equal to the right operand.
* (less than): returns true if the left operand is less than the right operand.
* (less than or equal to): returns true if the left operand is less than or equal to the right operand.
It's important to note that when comparing strings, JavaScript uses standard lexicographical ordering, which means it compares the Unicode values of each character in the strings.



# Assignment Operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

There are also compound assignment operators that are shorthand for the operations listed in the following table:

Name	Shorthand operator	Meaning
* Assignment	x = f()	x = f()
* Addition assignment	x += f()	x = x + f()
* Subtraction assignment	x -= f()	x = x - f()
* Multiplication assignment	x *= f()	x = x * f()
* Division assignment	x /= f()	x = x / f()
* Remainder assignment	x %= f()	x = x % f()
* Exponentiation assignment	x **= f()	x = x ** f()
* Left shift assignment	x <<= f()	x = x << f()
* Right shift assignment	x >>= f()	x = x >> f()
* Unsigned right shift assignment	x >>>= f()	x = x >>> f()
* Bitwise AND assignment	x &= f()	x = x & f()
* Bitwise XOR assignment	x ^= f()	x = x ^ f()
* Bitwise OR assignment	x	= f()
* Logical AND assignment	x &&= f()	x && (x = f())
* Logical OR assignment	x	
* Nullish coalescing assignment	x ??= f()	x ?? (x = f())
### Assigning to properties
If an expression evaluates to an object, then the left-hand side of an assignment expression may make assignments to properties of that expression. For example:

javascript
const obj = {};

* obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
* If an expression does not evaluate to an object, then assignments to properties of that expression do not assign:

const val = 0;
val.x = 3;

console.log(val.x); // Prints undefined.
console.log(val); // Prints 0.
* In strict mode, the code above throws, because one cannot assign properties to primitives.
 It is an error to assign values to unmodifiable properties or to properties of an expression without properties (null or undefined).

## Destructuring
For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.
