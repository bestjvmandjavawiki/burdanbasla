# Understanding the `static` Keyword in Java

In Java, the `static` keyword is used to define a class-level (or static) member. When a member (variable or method) is declared as static, it belongs to the class rather than an instance of the class. Here's how it is used:

## Static Variables

Static variables are shared among all instances of a class. They are declared using the `static` keyword and are initialized only once, at the start of the execution. All instances of the class share the same static variable.

```java
public class Example {
    // Static variable
    static int staticVariable;

    // Rest of the class code...
}
``` 

## Static Methods

Similar to static variables, static methods belong to the class rather than an instance. They can be called using the class name, without creating an object of the class.

javaCopy code

public class Example {
    // Static method
    static void staticMethod() {
        // Method code...
    }

    // Rest of the class code...
}

## When to Use `static`

Use the `static` keyword when you want a member to be associated with the class itself, rather than with instances of the class. Common use cases include utility methods, constants, or variables that need to be shared among all instances.

public class MathUtils {
    // Constant
    public static final double PI = 3.14159;

    // Static method for calculations
    public static double calculateArea(double radius) {
        return PI * radius * radius;
    }
}
