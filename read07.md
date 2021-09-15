## JavaScript Expressions and Operators

**Operators**

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

- Assignment operators
- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical Operators
- String operators
- Conditional (ternary) operators
- Comma operator
- Unary operators
- Relational operators

## **Assignment operators**

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

Below I will insert a table showing a small example of some of the assigment operators available in JavaScript.

| Name                      | Shorthand operator | Meaning    |
| ------------------------- | ------------------ | ---------- |
| Assignment                | x = y              | x = y      |
| Addition assignment       | x += y             | x = x + y  |
| Subraction assignment     | x -= y             | x = x - y  |
| Multiplication assignment | x \*= y            | x = x \* y |
| Division assignment       | x /= y             | x = x / y  |
| Remainder assignment      | x %= y             | x = x % y  |

## **Comparison operators**

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values.

Below is another table of some examples of comparison operators.

| Operator                   | Description                                                                                  |
| -------------------------- | -------------------------------------------------------------------------------------------- |
| Equal (==)                 | Returns _true_ if the operands are equal.                                                    |
| Not equal (!=)             | Returns _true_ if the operands are not equal.                                                |
| Strict equal (===)         | Returns _true_ if the operands are equal and of the same type.                               |
| Strict not equal (!==)     | Returns _true_ if the operands are of the same type but not equal, or are of different type. |
| Greater than (>)           | Returns _true_ if the left operand is greater than the right operand.                        |
| Greater than or equal (>=) | Returns _true_ if the left operand is greater than or equal to the right operand.            |
| Less than (<)              | Returns _true_ if the the left operand is less than the right operand.                       |
| Less than or equal (<=)    | Returns _true_ if the left operand is less than or equal to the right operand.               |

## **Arithmetic operators**

An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (\*), and division (/).

| Operator                       | Description                                                                                                                                                                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Remainder (%)                  | Binary operator. Returns the integer remainder of dividing the two operands.                                                                                                                                             |
| Increment (++)                 | Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one. |
| Decrement (--)                 | Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator.                                                                                                        |
| Unary negation (-)             | Unary operator. Returns the negation of its operand.                                                                                                                                                                     |
| Unary plus (+)                 | Unary operator. Attempts to convert the operand to a number, if it is not already.                                                                                                                                       |
| Exponentiation operator (\*\*) | Calculates the base to the exponent power, that is, base^exponent                                                                                                                                                        |
