# While / Do while

_As of Indev 454f37d_

While is a loop statement that repeats to execute its body 0 or more times
by checking if the condition is true at first.

```
while(<condition>){
    <body>
}
```
```
do{
    <body>
} while(<condition>);
```

Do/while is a loop statement that is similar to while, except it will execute
at least once by executing the body at first, and then repeating it while
the condition evaluates true.

### Arguments

\<condition> returns boolean value.

### Returns

Void.

### Examples

```
while(a < 10){
    print a;
    a += 1;
}
```
```
while(true) print "Infinite loop!";
```
```
do{
    name = names[0];
    print "Hello, ".name;
    names.pop;
} while(names != []);
```
