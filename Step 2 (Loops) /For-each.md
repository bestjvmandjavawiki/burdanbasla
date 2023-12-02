## Foreach Loops

```Java
import java.util.ArrayList;
import java.util.List;

public class ModernForEachExample {
    public static void main(String[] args) {
        // Modern for-each loop with List
        List<String> names = new ArrayList<>();
        names.add("Alice");
        names.add("Bob");
        names.add("Charlie");

        for (String name : names) {
            System.out.println(name);
        }

        // Modern for-each loop with array
        int[] numbers = {1, 2, 3, 4, 5};

        for (int number : numbers) {
            System.out.println(number);
        }

        // Modern for-each loop with Iterable
        Iterable<Integer> iterable = List.of(1, 2, 3, 4, 5);

        for (int value : iterable) {
            System.out.println(value);
        }
    }
}
```