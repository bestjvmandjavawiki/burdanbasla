**What is a Method?**

A method is a named block of code in programming that performs a specific task. It enhances code reusability and contributes to modular and readable code. Methods consist of a series of statements that execute a particular operation.

**Creating a Method in Java:**

To create a method in Java, follow these steps:

1. **Method Declaration:**
```java
public class MyClass {
    // Method declaration
    public static void myMethod() {
        // Method body
        System.out.println("This is an example method.");
    }

    public static void main(String[] args) {
        // Method call
        myMethod();
    }
}
```

In this example, a method named `myMethod` is declared, and it is called within the `main` method. When the program is executed, the text "This is an example method." will be printed to the console.

2. **Return Type and Parameters:**
```java
public class Calculator {
    // Method with parameters and return type
    public static int add(int num1, int num2) {
        return num1 + num2;
    }

    public static void main(String[] args) {
        // Method call with arguments
        int result = add(5, 3);
        System.out.println("Sum: " + result);
    }
}
```

In this example, the `add` method takes two parameters (`num1` and `num2`) and returns their sum. The `main` method calls the `add` method with arguments, and the result is printed.

3. **Method Overloading:**
```java
public class Printer {
    // Method overloading
    public static void printMessage(String message) {
        System.out.println("Message: " + message);
    }

    public static void printMessage(int number) {
        System.out.println("Number: " + number);
    }

    public static void main(String[] args) {
        // Method calls with different parameter types
        printMessage("Hello, World!");
        printMessage(42);
    }
}
```

In this example, the `printMessage` method is overloaded to accept either a `String` or an `int` parameter. The `main` method demonstrates calling the overloaded methods with different types of arguments.

These aspects cover the basics of methods in Java, including declaration, usage, parameters, return types, and method overloading.
