The `do-while` loop in programming is a control flow structure that executes a block of code repeatedly as long as a specified condition is true. The key difference between the `do-while` loop and the `while` loop is that the `do-while` loop guarantees that the block of code is executed at least once before checking the loop condition.

Here's the basic structure of a `do-while` loop:

```java
do {
    // Code to be executed
} while (condition);
```

The loop starts with the `do` keyword, followed by the code block to be executed. After the code block, the `while` keyword is used to specify the loop condition. The condition is evaluated after the code block, and if it is true, the loop iterates again. If the condition is false, the loop terminates, and the program continues with the next statement after the `do-while` loop.

Here's an example of a `do-while` loop in Java:

```java
public class DoWhileExample {
    public static void main(String[] args) {
        int count = 1;

        do {
            System.out.println("Count: " + count);
            count++;
        } while (count <= 5);
    }
}
```

In this example, the `do-while` loop prints the current value of `count` and increments it. The loop continues executing as long as `count` is less than or equal to 5. Since the code block is executed before checking the condition, the output includes "Count: 1" even though the condition is initially false.
