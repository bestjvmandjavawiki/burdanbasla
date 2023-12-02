## Infinty Methods.

### This only Variables Exmp.
```java

public class UnlimitedInputExample {

    // Method that takes an unlimited number of input parameters
    public static void printValues(String... values) {
        System.out.println("Entered Values:");

        // Printing input values using a for-each loop
        for (String value : values) {
            System.out.println(value);
        }
    }

    public static void main(String[] args) {
        // Calling the method, you can pass as many values as you want
        printValues("Java", "C++", "Python", "JavaScript");
    }
}
```
## Others

```Java
public class VariableArgumentsExample {

    // Method with variable arguments of type Object
    public static void printObjects(Object... objects) {
        System.out.println("Printing Objects:");

        for (Object obj : objects) {
            System.out.println(obj);
        }
    }

    public static void main(String[] args) {
        // Calling the method with different types and numbers of arguments
        printObjects("String Object", 42, 3.14, true);
        printObjects(1, "Another String", false);
        // You can provide as many objects of different types as needed
    }
}