# For

_As of Indev 168429d_

For is loop statement designed to execute the code in it's body for
each `i` with starting value (called initialization), meeting the
condition, and the increment/decrement expression.

For example, the for loop that outputs `i` with initialization value of 0,
condition i<5, and increment i+=1, will execute the body with `i` in range
0 to 4.

```
for(<init>, <cond>, <incr>){
    <body>
}
```

### Arguments

- \<init> is a variable initialization / assignment;
- \<cond> returns boolean for the variable;
- \<incr> is an incrementation for the variable.

### Returns

Void.

### Examples

```
for(i=0, i<5, i+=1) print i;
```
```
for(money=0, money<1000000, money+=money){
    print "Earning...";
    print "Total money: ".money;
}
```
