# language features
## compiled langauge / interpreted language
[1] Programming Concepts: Compiled and Interpreted Languages <br>
https://thesocietea.org/2015/07/programming-concepts-compiled-and-interpreted-languages/ <br>

[2] The Basics of Compiled Languages, Interpreted Languages, and Just-in-Time Compilers <br>
https://www.upwork.com/hiring/development/the-basics-of-compiled-languages-interpreted-languages-and-just-in-time-compilers/ <br>

[3] Interpreter Vs Compiler : Difference Between Interpreter and Compiler <br>
https://www.programiz.com/article/difference-compiler-interpreter

[4] Javascript
http://web.stanford.edu/class/cs98si/slides/overview.html

- JavaScript’s syntax is heavily inspired by C++ and Java. If you have experience in C++ or Java, JavaScript’s syntax will seem familiar to you. However, the inner workings of JavaScript is closer to a dynamically-typed, interpreted language such as Python or Ruby.

- JavaScript is **an interpreted language**, not a compiled language. A program such as C++ or Java needs to be compiled before it is run. The source code is passed through a program called a compiler, which translates it into bytecode that the machine understands and can execute. In contrast, JavaScript has **no compilation step**. Instead, **an interpreter in the browser reads over the JavaScript code**, interprets each line, and runs it. More modern browsers use a technology known as **Just-In-Time (JIT)** compilation, which compiles JavaScript to executable bytecode just as it is about to run.

[5] [TODO] How to write a simple interpreter in JavaScript
https://www.codeproject.com/Articles/345888/How-to-write-a-simple-interpreter-in-JavaScript <br>

<br><br>

## type system
[1] Programming Concepts: Static vs. Dynamic Type Checking <br>
https://thesocietea.org/2015/11/programming-concepts-static-vs-dynamic-type-checking/ <br>

- Static type checking / dynamic type checking
  - The process of verifying and enforcing the constraints of types—type checking—may occur either at compile-time (a static check) or at run-time.
  - A language is statically-typed if the type of a variable is known at compile time instead of at runtime.
  - Dynamic type checking is the process of verifying the type safety of a program at runtime.
  <br>
- type safety
  - What is type safety?
  http://www.pl-enthusiast.net/2014/08/05/type-safety/ 
  - In computer science, type safety is the extent to which a programming language discourages or prevents type errors. A type error is erroneous or undesirable program behaviour caused by a discrepancy between differing data types for the program's constants, variables, and methods (functions)
  <br>
- strongly-type language / weakly-typed language
  - A `strongly-typed` language is one in which variables are bound to specific data types, and will result in type errors if types to not match up as expected in the expression – regardless of when type checking occurs.
  - ruby, python, and javascript (all of which are dynamically-typed) are also `strongly-typed` languages and the developer makes no verbose statement of data type when declaring a variable.
  - ruby, python, and javascript which do not require manually defining a type when declaring a variable make use of **type inference**.
  - Some programmers automatically use the `term weakly` typed to refer to languages that make use of `type inference`, often without realizing that the type information **is present but implicit**. Type inference is a separate feature of a language that is unrelated to any of its type systems.
  - A `weakly-typed` language on the other hand is a language in which variables are **not bound to a specific data type**; they still have a type, but type safety constraints are **lower** compared to `strongly-typed` languages.

<br><br>


## garbage collection
[1] Programming Concepts: Garbage Collection
https://thesocietea.org/2017/01/programming-concepts-garbage-collection/ <br>

- The garbage collector is a tool that removes the burden of manually managing the heap. Most modern languages such as Java, the .NET framework, Python, Ruby, Go, etc. are all garbage collected languages; C and C++, however, are not – and in languages such as these, manual memory management by the developer is an extremely important concern.
- Garbage Collection Algorithms
  todo
<br>

[2] [todo] Visualizing Garbage Collection Algorithms
https://spin.atomicobject.com/2014/09/03/visualizing-garbage-collection-algorithms/ <br>

<br><br>

