# What is the statick keyword?

```Java
// 1. Static Method Bulunduran Sınıf
class StaticMethodClass {
    // Static method örneği
    static void staticMethod() {
        System.out.println("Bu bir static methodtur.");
    }
}

// 2. Static Olmayan Method Bulunduran Sınıf
class NonStaticMethodClass {
    // Non-static method örneği
    void nonStaticMethod() {
        System.out.println("Bu bir static olmayan methodtur.");
    }
}

// 3. Main Sınıfı
public class MainClass {
    public static void main(String[] args) {
        // Static method çağrısı
        StaticMethodClass.staticMethod();

        // Static olmayan method çağrısı
        NonStaticMethodClass nonStaticObj = new NonStaticMethodClass();
        nonStaticObj.nonStaticMethod();
    }
}
```