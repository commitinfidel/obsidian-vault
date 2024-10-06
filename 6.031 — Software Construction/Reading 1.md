**Objectives**
- static typing
- big three properties of good software
## Static typing
Java is a **statically-typed language**, which _means the type of all variables are known at compile time_ (before the program runs), and therefore the compiler can deduce the type of all expressions as well. In **dynamically-typed languages** such as Python, _this kind of checking is deferred until runtime_ (while the program is running). Static typing is a particular kind of **static checking**, which means checking for bugs at compile time. Static typing prevents a large class of bugs from infecting your program: to be precise, bugs caused by applying an operation to the wrong types of arguments. For example, multiplying two strings.
```
"2" * "3"
```
Here static typing will catch this error while you’re still programming, rather than waiting until the line is reached during execution.
