Hi, today I want to talk about TypeScript.

#Slide 1

In 2012, Microsoft released the first public version of TypeScript, which was created by Anders Hejlsberg.

TypeScript is a compiled JavaScript superset.

And one important feature: any valid JavaScript code is a valid TypeScript code.

#Slide 2

Inside TypeScript can be represented in the form of four layers. In foundid, of course, is the core of the compiler.

On top of the kernel is the “Autonomous Compiler” and “Language Services”.

And finally, the compiler and language services are combined into the “Stand-alone server, which simplifies communication with the API of the underlying layers.

#Slide 3

A very important difference between TypeScript and JavaScript is that it supports static typing in TypeScript.

Static typing differs from dynamic typing in that in the first case, type checking is performed at compile time, and in the second, during execution of instructions.

#Slide 4

The main types given in TypeScript this: Boolean, number, string, arrays, tuple, enum, any, void, null and undefined, never. Consider each of them in more detail.

#Slide 4.1

The Boolean type represents a logical true or false.

The Number type represents numbers, with all numbers in TypeScript, as in JavaScript, being floating point numbers. TypeScript supports binary, octal, decimal and hexadecimal entries of numbers.

String represents strings. Like JavaScript, TypeScript strings can be enclosed in double, single and back quotes.

#Slide 4.2

Arrays are defined using the expression [] and <> and are also strongly typed. If the array initially contains strings, then in the future it will be able to work only with strings.

Tuples (Tuples) as well as arrays represent a set of elements for which the type is already known in advance.

#Slide 4.3

Enum. The enum type is intended to describe a set of numeric data using string constants. Since all elements of the enumeration represent numeric values. Although we can override these values.

Any. Any describes data whose type may not be known at the time of writing the application.

#Slide 4.4

If function without return, this is void; if we return null, then null. If return with no arguments, or explicitly return undefined - undefined.

#Slide 4.5

Never. Never - functions that will never be executed to the end. If the function is marked as never, but reached return, we get a compilation error.

#Slide 4.6

We can also set several possible types for variables.

And when using let in TypeScript without explicitly specifying the type, the variable will take the type of the first value written to it.

#Slide 5

An important advantage of TypeScript is support for OOP. So, the language supports the use of classes, interfaces, abstract classes, get and set, static properties and functions. Etc.

Consider some of them.

Interfaces in TypeScript play the role of naming types and are a powerful way to define contracts in code.

Interfaces serve as a template object. They cannot contain implementation of methods.

On the slide, secondBlock will give an error, because we did not pass the height value. But if you use optional fields, through the question mark, there will be no problems.

The readonly property, the field needs to be initialized, but cannot be changed.

#Slide 6

Classes. We describe the fields at the beginning, with an indication of the type. Also in the constructor, type is needed. Then class methods.

#Slide 7

Inheritance is performed using the extends keyword. We access the base class through the word super.

#Slide 8

When an interface interacts with a class, interfaces are more often used to explicitly indicate that a class conforms to a specific convention. Also in the interface you can describe the methods that are implemented inside the class.

#Slide 8.1

Use the interface, we can through the event, or implement. If you need to implement multiple interfaces, separate them with a comma.

#Slide 9

There are various access modifiers. Public, private, protected, readonly.

#Slide 9.1

Public fields are completely open to the user. They can be accessed directly by having a link to the object. Private are hidden from the user class, and are accessible only inside the class.

#Slide 9.2

Protected works as private, but is inherited.

Readonly works the same as in interfaces. We initialize it when declaring it in a class or in a constructor.

#Slide 10

The difference between the TS and JS functions is the typing of the arguments, and the return type. Also in TypeScript you need to pass the number of arguments that are written. More or less will cause an error.

#Slide 11

Advantages of TypeScript

• Strong typing. indicates errors at the compilation stage and can be corrected before the execution stage.

• OOP. Perfectly supported by all the basic principles of OOP.

• JavaScript superset. It is enough to copy the code from JavaScript and paste it into TS to make it work.

• Development of complex solutions. Thanks to the support of modularity large development teams can create large applications.

#Slide 12

TypeScript Disadvantages

• DefinitelyTyped - in some cases, there are no popular libraries.

• Two a large number of additional files after compiling the ts-file.

• And, Implicit static typing. If we declare an any type variable, we will not get any benefit from static typing.

#Slide 13

Thanks you for your attention!