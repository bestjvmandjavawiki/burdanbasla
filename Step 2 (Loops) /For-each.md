## Foreach Loops

```Java
import java.util.ArrayList;
import java.util.List;

public class ModernForEachWithLambdaExample {
    public static void main(String[] args) {
        // Modern for-each loop with List and Lambda
        List<String> names = new ArrayList<>();
        names.add("Alice");
        names.add("Bob");
        names.add("Charlie");

        names.forEach(name -> System.out.println(name));

        // Modern for-each loop with array and Lambda
        int[] numbers = {1, 2, 3, 4, 5};

        for (int number : numbers) {
            System.out.println(number);
        }

        // Modern for-each loop with Iterable and Lambda
        Iterable<Integer> iterable = List.of(1, 2, 3, 4, 5);

        iterable.forEach(value -> System.out.println(value));
    }
}
```