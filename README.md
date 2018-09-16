# Ruby Notes

## Dynamic
A dynamic programming language is one that can execute many common programming behaviors at runtime (when the interpreter executes the program) that static programming languages perform during compilation, when a program--the compiler--translates high-level source code to a lower-level language (e.g., assembly language or machine code). Dynamic programming languages can compile code at runtime and execute code during compile-time; the compilation and runtime phases are muddled. Though this flexibility enables meta-programming, more abstraction, and less code, it comes at the expense of execution speed.

Ruby, like most dynamic programming languages, is also dynamically typed. In dynamically typed languages, the language enforces type constraints at runtime; whereas, in statically typed languages, the language enforces type constraints at compile-time. The following method invocation in Ruby runs successfully at runtime:

## Reflective

Reflection is common among dynamic programming languages. Unlike mere type introspection, which refers to the ability of a program to examine the type and state of an object at runtime, reflection refers to ability of a program to manipulate its own structure and behavior as data. In object-oriented reflective languages like Ruby, reflection permits not only the examination of classes, modules, and methods, but also instantiation and method invocation. Reflection makes possible much of meta-programming.

## Object-Oriented

Object-oriented programming is a programming paradigm that privileges objects rather than actions and data rather than functions or logic. Adherents to OOP conceive of a program as a society of objects that receive messages that they then use to perform their own discrete operations. Objects typically contain data in fields known as attributes and a set of associated methods that may access and manipulate these attributes.

The most popular object-oriented languages, such as Java, Perl, Python, Ruby, Objective-C, Smalltalk and Swift are class-based. Objects are instances of classes, which usually determine type. Classes define the data format and methods available to their instances or to themselves.

Classes often inherit from other classes in an "is-a-type-of" relationship. The Dog class (the child class) might inherit from the Pet class (the parent class). The child class inherits data definitions and methods from the parent class, allowing for recycling. The child class may overwrite these definitions and methods as well as add its own, thereby customizing and extending its parent.

Encapsulation is a principle of object-oriented design. It dictates that the programmer:

1. Place all code concerned with a particular set of data in one class.
2. Hide methods and data essential only to a class's internal workings (this technique is called information hiding). Conversely, the programmer should expose via methods only what's necessary to a class's relationships with other classes, thereby preventing external interference and misuse.

## Multi-Paradigm
Although Ruby is perhaps the object-oriented programming language par excellence, it also supports procedural and functional programming.

Procedural programming privileges procedure invocations, i.e., method calls. In procedural programming, the programmer specifies a series of procedures that operate on data structures in systematic order. Object-oriented programming joins data structures and methods into "objects" that operate on themselves. Defining and invoking methods outside of a class in Ruby approximates procedural programming because these methods are part of a single root object, limiting object-oriented design.

Functional programming privileges pure functions, those whose return value is only determined by the input, without side effects such as changes in state. Adherents of functional programming conceive of computation as the evaluation of mathematical functions. Via blocks, Ruby shares many features of functional programming languages. Ruby features anonymous functions, lexical closures (functions that capture variables in the context where they're defined), and higher-order functions (functions that can accept functions as arguments and/or return functions). As of Ruby 2.0, Ruby even supports lazy enumeration!

## Philosophy
In 2008, Matz declared that the primary purpose of Ruby is to "help every programmer in the world to be productive, and to enjoy programming, and to be happy." He elaborated:

Often people, especially computer engineers, focus on the machines. They think, "By doing this, the machine will run fast. By doing this, the machine will run more effectively. By doing this, the machine will something something something." They are focusing on machines. But in fact we need to focus on humans, on how humans care about doing programming or operating the application of the machines. We are the masters. They are the slaves.

Ruby follows the Principle of Least Astonishment: it attempts to minimize confusion for experienced users. Much of Ruby reads like English. It's designed to be expressive, powerful, elegant, and flexible. There are myriad ways to do almost anything in Ruby, a design decision inherited from Perl.

Ruby vs. Python
Python is perhaps the most similar language to Ruby. Both are dynamic, reflective, object-oriented, multi-paradigm scripting languages. They even use similar syntax! Here are the primary linguistic differences:

Python doesn't support blocks.
Python has a richer set of data structures.
Python is inflexible: there's one best way of doing things!
Whitespace is syntactically significant in Python.
Python is less object-oriented. It has primitive data types, which are more fundamental than objects (not everything in Python is an object!), and many of its object-oriented features were late additions.
Ruby values elegance and "magic" over clarity.

Python developers tend to be more conservative in general. Rubyists enjoy many new linguistic features before Python developers catch on.

Because of the popularity of Rails, the fact that Python is older, and the early porting of statistical libraries in R to Python, Python has a more diverse community, including many more proponents in data science and academia. Ruby has no equivalent to Python's SciPy, NumPy, Matplot lib, or NLTK (Natural Language Toolkit) libraries.


## Vocabulary
Test-Driven Development (TDD)
TDD is a process for writing software. Its basic steps are as follows:

1. Add a test
2. Run all the tests and make sure the new test fails
3. Write code
4. Run all the tests and make sure the new test passes
5. Refactor the code.

## Behavior-Driven Development (BDD)
BDD is an extension of TDD. It structures the testing process through the use of user stories - a description of the user's use of the feature being developed. The goal of the user story is to help focus the developer on what to test and what not to test.

## Unit Test
Unit testing is a way of testing an application by breaking the application down into its smallest constituent parts and testing each part in isolation. In order to test parts of an application that rely on other code, unit tests typically use mock objects to make sure that problems elsewhere in the code won't cause the tests to mistakenly fail.

Unit testing is often automated at larger or more sophisticated companies.

## Integration Test
Integration testing is a form of testing in which units of code are combined ("integrated") and the results of their interactions are tested. This type of testing is done after each of the individual units has been tested.

## Test Coverage
"Test coverage" refers to how much of a software program has been tested. This can refer to several things, including the percentage of functions that have been called by the test suite, or the percentage of statements in the code that have been executed by the test suite.
