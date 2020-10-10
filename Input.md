# Input

_As of Indev 5c5a1e7_

Input is a statement language construct used to input a value from
the default I/O stream (stdin) into a variable. Optionally, it is
possible to print a message before taking input with `in`.

```
input <var>;
```
```
input <var> in <expr>;
```

### Arguments

- <var> is an identifier,
- <expr> returns string value.

### Returns

Void.

### Examples

```
input x;
```
```
input x in "Enter a number:";
```
```
input var in "Enter a ".type;
```
