# Java OOP: Interface, Abstract Class, and Concrete Class

## Description
This project demonstrates the use of **interfaces**, **abstract classes**, and **concrete classes** in Java. It follows a structured approach to defining and implementing device behaviors using object-oriented programming (OOP) principles.

## Features
- Defines a `Device` interface with basic methods (`turnOn()` and `turnOff()`).
- Implements an abstract class `Computer` that provides a common feature (`runDiagnostics()`).
- Extends `Computer` into a concrete class `Laptop`, which implements all required behaviors.
- Tests the implementation in the `Main` class.

## Code Explanation

### `Device` Interface
```java
interface Device {
    void turnOn();  
    void turnOff(); 
}
