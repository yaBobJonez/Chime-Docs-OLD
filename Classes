# Classes

_As of Indev ba13088_

Classes are templates for objects. Classes are the heart of Object-Orientired Programming conception, this includes Chime too! A class itself is a structure that
contains [functions](Functions) that are called methods and variables (properties of a class) that are called fields. Objects are instances of a class. When an object
is created, it has all the same methods as it's class and properties, which are null's by default. A class can have a constructor — a special method that is called
on the class creation. ~~You can have as many constructors as you want, as long as they have different arguments.~~

Declaring a class:

```
class <className> {
    <body>
}
```
Declaring a class constructor:

```
...
function constructor(<constrArgs>){
    <body>
}
...
```
Creating an object (instance of a class):

```
<objName> = new <className>(<args>);
```
Access an object field:

```
<objName>-><fieldName>
```
Call class method from an object:

```
<objName>-><methodName>(<args>)
```
Access a field inside the class:

```
this.<fieldName>
```

~~Classes can have static methods and field, allowing you to call/access them directly from the class without creating its object.~~

_TBA static_

~~It is possible to define the scope of a method or a field using `public` or `private` keywords before the "function" keyword or the name of a field perspectively.~~

_TBA scope_

### Arguments

- <className>, <objName>, <fieldName>, <methodName> are identifiers,
- <constrArgs> are 0 or more identifiers,
- <args> are 0 or more values,
- <body> is a block or a statement.

### Returns

Void.

### Examples

```
class Message {
    mes = "Hello world!";
    function constructor(){
        print this.mes;
    }
}
SMS = new Message();
```

```
class TestClass {
    field;
    function method(arg){ return arg; }
}
Object = new TestClass();
print Object->field;
Object->field = "Changed!";
print Object->method(25);
```
    
