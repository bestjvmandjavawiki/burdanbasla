** Variables **
```
import java.util.concurrent.atomic.AtomicInteger;

public class VariableExample {
    // Primitive variable types
    private static int integerVariable = 5; // Represents whole numbers, e.g., count

    private static double doubleVariable = 3.14; // Represents floating-point numbers, e.g., measurements

    private static char charVariable = 'A'; // Represents a single character, e.g., grade

    private static boolean booleanVariable = true; // Represents true or false, e.g., status

    // Atomic variable
    private static AtomicInteger atomicInteger = new AtomicInteger(10);
    // Represents an integer value that can be atomically updated, ensuring thread safety

    public static void main(String[] args) {
        // Using primitive variables
        System.out.println("Integer Variable: " + integerVariable);
        System.out.println("Double Variable: " + doubleVariable);
        System.out.println("Char Variable: " + charVariable);
        System.out.println("Boolean Variable: " + booleanVariable);

        // Using an atomic variable
        System.out.println("Atomic Integer Before Increment: " + atomicInteger.get());
        atomicInteger.incrementAndGet();
        System.out.println("Atomic Integer After Increment: " + atomicInteger.get());
    }}
