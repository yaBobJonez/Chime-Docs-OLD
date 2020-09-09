# Getting started

## Installation

### Normal (simple)

Just [Download](#) the Chime interpreter and run it using:

```bash
java -jar Chime.jar <path-to-file> [arguments...]
```

### Build from source

1. Create a new project in your Java IDE (Eclipse recommended).
    - Use `src` folder only for sources
    - Separate sources from builds
2. Clone the Chime source into `src` directory.
    - `cd` into "src" folder
    - `git clone` + repository Git link
3. Build .jar from source

## Basics

### Value types

In Chime, there are several data types:

Name | Type
-----|-----
Integer | int
Double | double
Boolean | bool
String | string
Array | array
Associative array | map
Function | function

As Chime is a dynamic language, there's no need to specify the type.

### Variables

Variables can be defined in several ways.
Although, unlike in other languages, you can't define an empty one. You have to assign a value:

```
myVar = "Hello, variable!";
```

Also, Chime supports "destructuring assignment":

```
[var1, var2, anotherVar] = [3, "Hi", true];
```

### Basic statements

Of course, one of the most important things is I/O.
You can output any value that is convertible to string as simple as:

```
print "Hello, World!";
```

And you can take a user input in two ways:

One is simple, just take an input and put it as string into the variable.

*As of Not-Available +*
```
input myVar;
```

The second way is "prompting" to input, by asking a text before input.

*As of Not-Available +*
```
input "Enter your answer:" in myVar;
```

### Operators

In Chime, there are lots of operations with different data types.
The most common number operations, we all know are:

```
print 2 + 2;
print 10 - 5;
print 5 * 8;
print 10 / 2;
```
**Warning**: _When performing a number operation, the factors are casted into doubles!_

There are some more advanced number operations:

```
print 17 % 5; # Remainder #
print 3!; # Factorial #
a += 2; # Same as a = a + 2 #
b *= 3; # Same as b = b * 3 #
```
Please, note that `#` is used for comments. You can type anything in a comment,
Chime will ignore it. 

`#<your_comment>#`

Sure there are some string operations too!

```
print "Hello " . "world!"; # Concatenation #
print "smol" < "BIGGER"; # Length comparison #
```
And, as you see, some logical operators as well:

```
print a >= 2;
print b == c;
print !a != c;
print b && c;
print a || b;
```
Full list of operators can be found [here](#) :]

## Arrays

There are two types of arrays in Chime: associative, and usual.
Normal arrays look the same as in several other languages:

```
arr = ["hi", 5.2, false];
```
There, elements are stored by indexes starting 0.
"hi" is 0th element, 5.2 is 1st, and false is 2nd.

And also, associate arrays (AKA maps, "Hashtens") use key:value structure:

```
arr2 = {"key": "value", 10: true};
```
To access an array, we use arrayName[key]:

```
print arr[0];
print arr2["key"];
```

## TODO functions, modules
