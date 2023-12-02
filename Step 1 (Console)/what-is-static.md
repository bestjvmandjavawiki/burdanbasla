# What is the statick keyword?

```Java
// Static Method class
class StaticMethodClass {
    // Static method exmp.
    static void staticMethod() {
        System.out.println("this wiki is awsome ");
    }
}

// Non statick method in class
class NonStaticMethodClass {
    // Non-static method exmp.
    void nonStaticMethod() {
        System.out.println("Bu bir static olmayan methodtur.");
    }
}

//  Main Class
public class MainClass {
    public static void main(String[] args) {
        // Static method howto Call?
        StaticMethodClass.staticMethod();

        //Non Static method howto call?
        NonStaticMethodClass nonStaticObj = new NonStaticMethodClass();
        nonStaticObj.nonStaticMethod();
    }
}
```