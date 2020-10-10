# Functions

_As of Indev 6240896_

Functions are the most useful elements of Chime. Functions provide functionality
to the language, execute complex tasks, do something that is impossible to do only
with statements and operators. Pre-defined functions are packed into modules (such
as std i.e. standard). You can define your own functions using `function` keyword.
A function can accept 0 or more arguments — input values which actions are performed
on. ~~A function can belong to a class. Hence you must use the access operator to
use this function.~~

Calling a function:
```
<functionName>(<arguments>);
```

Defining a function:
```
function <functionName>(<defArgs>){
    <body>
}
```

Functions as objects are called anonymous. They don't have a name, and assigned
to a container:
```
<objectName> = function(<defArgs>){
    <body>
}
```

Functions may return any value, i.e. result of execution. To do this, we use
`return` keyword:

```
return <expr>;
```

### Arguments

- <functionName>, <objectName> are keywords,
- <arguments> are 0 or more expressions that return values,
- <defArgs> are 0 or more keywords,
- <body> is a statement or block,
- <expr> returns value.

### Returns

\<expr> value OR true (default).

### Examples

```
use "std";
wait(5000);
```
```
function test() print "Hi!";
test();
```
```
function sum(a,b) return a + b;
print sum(2, 3);
```
