# Variables

###  Normal
```Java
import java.util.concurrent.atomic.AtomicInteger;

public class VariableExample {
    // Primitive variable types
    private static byte byteVariable = 127; // 8-bit signed integer
    private static short shortVariable = 32767; // 16-bit signed integer
    private static int integerVariable = 2147483647; // 32-bit signed integer
    private static long longVariable = 9223372036854775807L; // 64-bit signed integer

    private static float floatVariable = 3.14f; // 32-bit floating point
    private static double doubleVariable = 3.14; // 64-bit floating point

    private static char charVariable = 'A'; // Represents a single character
    private static boolean booleanVariable = true; // Represents true or false

   

    public static void main(String[] args) {
        // Using primitive variables
        System.out.println("Byte Variable: " + byteVariable);
        System.out.println("Short Variable: " + shortVariable);
        System.out.println("Integer Variable: " + integerVariable);
        System.out.println("Long Variable: " + longVariable);
        System.out.println("Float Variable: " + floatVariable);
        System.out.println("Double Variable: " + doubleVariable);
        System.out.println("Char Variable: " + charVariable);
        System.out.println("Boolean Variable: " + booleanVariable);

    }
}
```

### Atmoic Variables

```Java