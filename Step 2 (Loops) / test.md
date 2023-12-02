# For Loops Old(Before java 4 )/Modern For Loop 
```java 
// Modern for loop (Java 5 and later):
// Used for iterating over collections and arrays
List<String> names = Arrays.asList("Alice", "Bob", "Charlie");

for (String name : names) {
    System.out.println(name);
}

// Old for loop (Java 5 and earlier):
// Used for iterating over arrays using index-based approach
String[] names = {"Alice", "Bob", "Charlie"};

for (int i = 0; i < names.length; i++) {
    System.out.println(names[i]);
}

// Modern for loop with iteration control:
// Demonstrates using 'break' to terminate the loop
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);

for (int number : numbers) {
    if (number == 3) {
        break; // Exits the loop
    }
    System.out.println(number);
}

// Old for loop with iteration control:
// Demonstrates using 'break' to terminate the loop
int[] numbers = {1, 2, 3, 4, 5};

for (int i = 0; i < numbers.length; i++) {
    if (numbers[i] == 3) {
        break; // Exits the loop
    }
    System.out.println(numbers[i]);
}

// Modern for loop with incrementing:
// Demonstrates incrementing the loop variable
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

// Modern for loop with decrementing:
// Demonstrates decrementing the loop variable
for (int i = 5; i > 0; i--) {
    System.out.println(i);
}
```

