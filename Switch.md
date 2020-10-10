# Switch /case

_As of Indev 00099ab_

Switch is a control flow that evaluates the expression inside it and
compares the result to each case. If a case matches, it executes the
code inside its body and breaks out of the loop. **Warning**: _there
is no fall-through!_ ~~Otherwise, if no match found, the code inside
`default` statement is executed.~~ Switch/case is used as a shorthand
analog of `if/else` with `==` operators in each if.

```
switch(<value>){
    case <c1>: <c1body>;
    case <c2>: <c2body>;
    ...
    default: <defBody>;
}
```

### Arguments

- \<value> returns any non-null value,
- \<c1>, \<c2>, ... return any non-null values,
- \<c1body>, \<c2body>, ..., \<defBody> are blocks or statements.

### Returns

Void.

### Examples

```
switch(type){
    case "string": print "It's a string!";
    case "int": print "It's an integer!";
    default: print "Unknown type :(";
}
```
