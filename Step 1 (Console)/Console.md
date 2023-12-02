```java
public class ConsoleLogExample {
    public static void main(String[] args) {
        // Using System.out.println to log messages to the console

        // Printing a simple message
        System.out.println("Hello, World!");

        // Concatenating variables with strings
        int number = 42;
        String message = "The answer is: ";
        System.out.println(message + number);

        // Formatting output
        String formattedMessage = String.format("The value of pi is approximately %.2f", Math.PI);
        System.out.println(formattedMessage);

        // New line in console output
        System.out.println("This is on the first line.\nThis is on the second line.");

        // Printing without a newline
        System.out.print("This is on the first line. ");
        System.out.print("This is still on the same line.");

        // Printing to the error stream
        System.err.println("This is an error message.");

        // Logging variables
        int x = 5;
        double y = 3.14;
        System.out.println("Values: x = " + x + ", y = " + y);
    }
}
```

Bu örnekte, `System.out.println` kullanarak farklı mesajları ve değişkenleri konsola yazdırmak için örnekler verdim. `System.err.println` ile hata mesajlarını yazdırmak da mümkündür. Ayrıca, `\n` yerine `System.out.println` kullanarak yeni satıra geçiş örneklendi.