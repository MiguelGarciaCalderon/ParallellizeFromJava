## Synopsis

Java library for run any process in parallel

## Code Example

```
 //configs -> list of argument for the same program
 String [] arguments = new String[configs.size()];
 arguments = (String[])configs.toArray(arguments);
 runHilos r = new runHilos(arguments, "java -jar "+JAR, Runtime.getRuntime().availableProcessors());
 r.ejecuta();//run command java -jar JAR with the list of arguments
```

## Motivation

I used to write code in C, but now I'm only write code in Java, I needed to run in parallel my old projects written in C.
I like process optimization but I don't have time for parallelize all my projects

## Build

You can clone this repository and compile the sources using any Java IDE or compile from command line with:
javac -d bin -sourcepath src -cp src/com/example/Application.java

##Installation

You only need to add generated build file to your Java project.

## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Attribution Requirements

As an open source project, attribution is critical from a legal, practical and motivational perspective in my opinion.

## Tests

Describe and show how to run the tests with code examples.

## Contributors
Miguel Ángel García Calderón
Please report bugs to tonsquemike@outlook.com 

## License

Code licensed under the MIT License: http://opensource.org/licenses/MIT
