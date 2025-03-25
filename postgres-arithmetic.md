## Arithmetic Operators in PostgreSQL

PostgreSQL is an advanced relational database system that supports both relational (SQL) and non-relational (JSON) queries. It is free and open-source. One of the most fundamental properties of database systems is arithmetical operations, without which a multitude of tasks, from simple arithmetic to complex analysis, are unfeasible.

The arithmetic operators are fundamental in doing the calculations in PostgreSQL, by which you can be sure that the process will be fast and correct. In this article, we are going to discuss different arithmetical operators in PostgreSQL.

Introduction to Arithmetic Operators
In PostgreSQL, these are arithmetic operators that are symbols or keywords used for doing mathematical operations over numerical data types that are stored in the database. A user can carry out such expressions using these operators including addition, subtraction, multiplication, and division operations, enabling many data manipulation tasks.

Various Arithmetic Operators in PostgreSQL
Given below are the most commonly used arithmetic operators in PostgreSQL:
```psql

Operators

Names

Description

+

Addition

Add the two values

-

Subtraction

Subtracts right-hand operand from left-hand operand

*

Multiplication

Multiply two values

/

Division

Divide one value by another

%

Modulo

Returns the remainder of a division operation

^

Raised To

This gives the exponent value of the right-hand operand

|\

Square Root

Calculates the square root

!

Factorial

Calculates the factorial of a non-negative integer

@

Absolute Value

This operator returns the absolute value of a number

&

Bitwise AND

It performs a bitwise AND operation on two integers, returning a new integer where each bit position is the result of the AND operation of the corresponding bits in the input integers.

|

Bitwise OR

It performs a bitwise OR operation on two integers, returning a new integer where each bit position is the result of the OR operation of the corresponding bits in the input integers.

#

Bitwise XOR

It performs a bitwise XOR (exclusive OR) operation on two integers, returning a new integer where each bit position is the result of the XOR operation of the corresponding bits in the input integers.

~

Bitwise NOT

It performs a bitwise negation operation on an integer, returning a new integer where each bit is flipped.

<<

Bitwise shift right

It shifts the bits of an integer to the left by a specified number of positions, adding zeros at the right end.

>>

Bitwise shift left

It shifts the bits of an integer to the right by a specified number of positions, adding zeros at the left end for positive numbers and sign bits for negative numbers.
```