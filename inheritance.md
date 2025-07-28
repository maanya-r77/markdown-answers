# Explain Java inheritance with examples

Inheritance in Java is a mechanism where one class acquires the properties (fields) and behaviors (methods) of another class. The class which inherits is called the **subclass** (or child class), and the class being inherited from is called the **superclass** (or parent class).

**Example:**

```java
// Superclass
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

// Subclass
class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }
}

public class TestInheritance {
    public static void main(String[] args) {
        Dog d = new Dog();
        d.sound(); // Output: Dog barks
    }
}
