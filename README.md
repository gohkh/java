# A Brief Guide to Java

This guide serves as a quick reference to programming in Java. It is not a tutorial. For more information, refer to the [Java documentation](https://docs.oracle.com/en/java/) or the latest [Java SE API](https://docs.oracle.com/en/java/javase/12/docs/api/index.html).

[comment]: # (update)

## Hello World!

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

This is a Java program that prints "Hello World!" to the console.

### Java Development Kit

A Java Development Kit (JDK) is required to compile and run the Java code that you will be writing. Download either the [Oracle JDK](https://www.oracle.com/technetwork/java/javase/downloads/index.html) or the [OpenJDK](https://jdk.java.net/) and install it.

### How to write and run a Java program

1. Use an Integrated Development Environment (IDE)

    An IDE typically includes an editor to write your code, and a compiler or interpreter, which allows you to run your program within the IDE. It may have other useful features to make it easier to write programs. Some popular IDEs used by Java developers are [Eclipse](https://www.eclipse.org/downloads/), [IntelliJ](https://www.jetbrains.com/idea/download/) and [NetBeans](https://netbeans.apache.org/download/index.html).

2. Use a text editor

    - Write the Java program using a text editor such as Notepad on Windows, TextEdit on Mac OS, [Atom](https://atom.io/), [Sublime Text](https://www.sublimetext.com/), [vim](https://www.vim.org/download.php), [emacs](https://www.gnu.org/software/emacs/), etc.

    - Open the command prompt on Windows, or the terminal on Mac OS or Linux.

    - Compile the program using the `javac` command: ```javac HelloWorld.java```

    - Run the program using the `java` command: ```java HelloWorld```

### Basic features of a Java program

All Java code must be in a class.

## Variables

Variables have a name, data type and value. A variable must be declared with its type, and may be initialised with a value of the appropriate type. Declare a variable as follows: [type] [variable name] = [value]

eg. `int count = 2` declares a variable named `count` assigned to an initial value of 2

If the variable is not initialised, it takes on the default value for its data type.

eg. `int count` declares a variable named `count` assigned to an initial value of 0, which is the default value for the type `int`

## Methods

## Program flow

### For loops

### While loops

## Object-Oriented Programming

[comment]: # "Object-oriented programming (OOP) is a programming paradigm in which programs are organised around collections of objects and interactions between them, as opposed to following a set of instructions step by step. An object consists of its identity, state, and behaviour."

## Data Structures and Algorithms

## Graphics with Processing
