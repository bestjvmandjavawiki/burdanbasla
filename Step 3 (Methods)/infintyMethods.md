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
public class InfiniteMethodExample {

    // Infinite method that uses different types of variables
    public static void performInfiniteOperation() {
        int counter = 0;
        double piValue = Math.PI;
        boolean status = true;
        char grade = 'A';

        while (status) {
            // Infinite loop
            System.out.println("Iteration " + counter);
            System.out.println("PI Value: " + piValue);
            System.out.println("Status: " + status);
            System.out.println("Grade: " + grade);
            System.out.println();

            // Some logic to break out of the loop after a certain condition
            if (counter == 5) {
                System.out.println("Breaking out of the loop!");
                break;
            }

            // Increment the counter
            counter++;
        }
    }

    public static void main(String[] args) {
        // Calling the infinite method
        performInfiniteOperation();
    }
}