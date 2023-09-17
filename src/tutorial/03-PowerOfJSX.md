# Python Operators and Expressions

In Python, operators are symbols used to perform operations on values or variables. Expressions are combinations of operators and operands (values or variables) that result in a single value.

## Arithmetic Operators

Arithmetic operators are used for mathematical operations:

- `+` (Addition): Adds two values.
- `-` (Subtraction): Subtracts the right operand from the left operand.
- `*` (Multiplication): Multiplies two values.
- `/` (Division): Divides the left operand by the right operand.
- `%` (Modulus): Returns the remainder of the division.
- `**` (Exponentiation): Raises the left operand to the power of the right operand.
- `//` (Floor Division): Returns the integer part of the division result.

Example:

```python
a = 10
b = 3
```
```python
addition = a + b
subtraction = a - b
multiplication = a * b
division = a / b
modulus = a % b
exponentiation = a ** b
floor_division = a // b

print(f"Addition: {addition}")
print(f"Subtraction: {subtraction}")
print(f"Multiplication: {multiplication}")
print(f"Division: {division}")
print(f"Modulus: {modulus}")
print(f"Exponentiation: {exponentiation}")
print(f"Floor Division: {floor_division}")

```
## Comparison Operators

Comparison operators are used to compare two values or expressions.

* `==` (Equal): Checks if two operands are equal.
* `!=` (Not Equal): Checks if two operands are not equal.
*  `<` (Less Than): Checks if the left operand is less than the right operand.
*  `>` (Greater Than): Checks if the left operand is greater than the right operand.
*  `<=` (Less Than or Equal To): Checks if the left operand is less than or equal to the right operand.
*  `>=` (Greater Than or Equal To): Checks if the left operand is greater than or equal to the right operand.

Example:
```python
x = 5
y = 10

is_equal = x == y         # False
not_equal = x != y        # True
less_than = x < y         # True
greater_than = x > y      # False
less_than_or_equal = x <= y  # True
greater_than_or_equal = x >= y  # False
```

## Logical Operators

Logical operators are used to combine multiple conditions.

* and (Logical AND): Returns True if both conditions are True.
* or (Logical OR): Returns True if at least one condition is True.
* not (Logical NOT): Inverts the value of the condition.

Example:
```python
age = 25
is_student = True

is_adult_student = age >= 18 and is_student  # True
is_adult_or_student = age >= 18 or is_student  # True
is_not_student = not is_student              # False
```

