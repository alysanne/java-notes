# Java 101

## Classes

A program in Java is made of classes:
  - The most minimal program would be made of one class.
  - We can have many classes in our program. We save each class in its own file, with the name of the file matching the name of the class.

A class definition is made of the following parts:

```java
// In MyClass.java
public class MyClass {
  /* CLASS BODY */
}
```

The class body may contain variables and methods in it. They are not required to make a class, unless it's the main class of a program. In this case, the class should contain at least the `main` method to ensure the program runs.

```java
public class MyProgram {
  public static void main (String[] args) {
    /* Do something */
  }
}
```

## Printing

In order to print to the console, we need to use one of the methods in `System.out`. For example, we can use the `print` method to print without a line break at the end, and `println` to print with a line break.

```java
System.out.println("Hello World!");
// Hello World!
```

```java
System.out.print("Hello");
System.out.print(" World!");
// Hello World!
```

## Variables

A variable in Java is made of it's name, type and value. The type of the variable defines what kind of data we can store in it, and is specified before the variable name. We can assign the value when the variable is defined, or later. Also, we can declare many variables with the same type in a single line.

```java
int age = 5;
String name;
name = "Yoko";

int one, two, three;
```