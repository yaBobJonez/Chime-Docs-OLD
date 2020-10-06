# Foreach

_As of Alpha_

Foreach is a loop statement that executes its body for each element
in iterated container, such as an array.
Foreach loop can also iterate several value from the container, such
as key:value pairs in an associative array.

```
foreach(<element> in <container>){
    <body>
}
```

### Arguments

\<element> is a variable, or a pair of variables separated with a colon;
\<container> returns container access.

### Returns

Void.

### Examples

```
foreach(el in ["Oh", "hi", "Thomas!"])
    print el;
```
```
foreach(value in arrayOfNums){
    arrayOfSquares[] = value ^ 2;
} print arrayOfSquares;
```
```
foreach(k:v in array) print k." is ".v;
```
