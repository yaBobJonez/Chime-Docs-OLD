# If/Else

_As of Alpha_

If is a control flow designed to check for a condition,
and evaluate the body if it's true. Otherwise, if the result
is false, then the body of else statement is evaluated.

```
if(<condition>){
    <if body>
} else{
    <else body>
}
```
It is possible to chain if/else flows to check for different
results of the condition.

### Arguments

\<condition> returns boolean value;
\<if body>, \<else body> are blocks or statements.

### Returns

Void.

### Examples

```
if(money > 20) print "You're good to go!";
else print "Not enough money.";
```
```
if(a == 1){
    a += 9;
    print a;
}
```
```
if(ticket == 1) print "$2";
else if(ticket == 2) print "$5";
else if(ticket == 3) print "$10";
```
