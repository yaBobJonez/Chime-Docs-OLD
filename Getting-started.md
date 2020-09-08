# Getting started

## Installation

#### Normal (simple)

Just [Download](#) the Chime interpreter and run it using:

```bash
java -jar Chime.jar <path-to-file> [arguments...]
```

#### Build from source

1. Create a new project in your Java IDE (Eclipse recommended).
    - Use `src` folder only for sources
    - Separate sources from builds
2. Clone the Chime source into `src` directory.
    - `cd` into "src" folder
    - `git clone` + repository Git link
3. Build .jar from source

## Basics

#### Value types

In Chime, there are several data types:

Name | Type
-----------
Integer | int
Double | double
Boolean | bool
String | string
Array | array
Associative array | map
Function | function

As Chime is a dynamic language, there's no need to specify the type.

#### Variables

Variables can be defined in several ways.
Although, unlike in other languages, you can't define an empty one. You have to assign a value:

```
myVar = "Hello, variable!";
```

Also, Chime supports "destructuring assignment":

```
[var1, var2, anotherVar] = [3, "Hi", true];
```

#### Basic statements

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

#### TBA...
