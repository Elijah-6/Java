# Java Programming Language Syntax

Java is a popular, high-level programming language known for its simplicity and portability. Here are some basic concepts and syntax rules for beginners:

## 1. Basic Structure

A basic Java program consists of a class definition and a `main` method. The `main` method is the entry point of any Java application.

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## 2. Variables and Data Types

Java is a statically-typed language, which means you must declare the type of a variable before using it.

```java
int number = 10; // Integer
double price = 19.99; // Double
char letter = 'A'; // Character
boolean isJavaFun = true; // Boolean
String greeting = "Hello, Java!"; // String
```

## 3. Control Structures

Java provides several control structures for decision making and looping.

### If-Else Statement

```java
int age = 18;
if (age >= 18) {
    System.out.println("You are an adult.");
} else {
    System.out.println("You are a minor.");
}
```

### For Loop

```java
for (int i = 0; i < 5; i++) {
    System.out.println("Iteration: " + i);
}
```

### While Loop

```java
int count = 0;
while (count < 5) {
    System.out.println("Count: " + count);
    count++;
}
```

## 4. Methods

Methods are blocks of code that perform a specific task and can be called upon when needed.

```java
public class Calculator {
    public static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int sum = add(5, 3);
        System.out.println("Sum: " + sum);
    }
}
```

## 5. Object-Oriented Programming (OOP)

Java is an object-oriented language, which means it uses objects and classes to organize code.

### Class and Object

```java
public class Dog {
    String name;
    int age;

    public void bark() {
        System.out.println(name + " is barking.");
    }

    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.name = "Buddy";
        myDog.age = 3;
        myDog.bark();
    }
}
```

These are some of the fundamental concepts and syntax rules in Java. As you continue learning, you'll discover more advanced features and best practices.
