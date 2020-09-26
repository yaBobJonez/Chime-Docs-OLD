# Print

_As of Alpha_

Print is a statement language construct used to output a value to
the default I/O stream (stdout).
That value must be an access expression and castable to string.

```
print <expression>;
```

### Arguments

\<expression> returns string value.

### Returns

Void.

### Examples

```
print "Hello World!";
```
```
print 3 + 7;
```
```
print var;
```
