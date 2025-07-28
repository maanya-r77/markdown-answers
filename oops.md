# OOP Concepts in Java

Java is based on Object-Oriented Programming.

- **Class**: Blueprint of an object
- **Object**: Instance of a class
- **Encapsulation**: Hiding data using private access and getters/setters
- **Inheritance**: Acquiring features from parent class
- **Polymorphism**: Same method, different forms (overloading/overriding)
- **Abstraction**: Hiding implementation using abstract classes or interfaces

## Example: Inheritance
```java
class Animal {
    void sound() {
        System.out.println("Animal makes sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }
}
