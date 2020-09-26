# Operators

An operator is a special symbol or group of symbols that take one, two, or more values, apply some operation to it's factors and returns another value.
There are unary (one value, for example !a), binary (two values, like a+b), and other operators, such as trinary.
Operators have their own precedence, which means that some operations will be executed first, and some last.

Here is the full list of currently available operators, their scope, and use.
Note that "number" stands for numeric types i.e. int and double.
"Any" means any number of factors, like operator chaining.

Operator | Name                   | Use
---------|------------------------|-----------
=        | Assignment             | a = b
+        | Addition               | a + b
-        | Subtraction            | a - b
*        | Multiplication         | a * b
/        | Division               | a / b
^        | To the power of        | a ^ b
%        | Modulo                 | a % b
.        | Concatenation          | a . b
+=       | Add-assign             | a += b
-=       | Subtract-assign        | a -= b
\*=      | Multiply-assign        | a \*= b
/=       | Divide-assign          | a /= b
?:       | Ternary                | a ? t : f
==       | Equals                 | a == b
!=       | Not equals             | a != b
!        | Not                    | !a
>        | Greater than           | a > b
<        | Less than              | a < b
>=       | Greater than or equals | a >= b
<=       | Less than or equals    | a <= b
|        | Inclusive or           | a | b
&        | And                    | a & b
