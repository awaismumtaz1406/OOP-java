
# Object-Oriented Programming (OOP) Concepts

## Introduction

Object-Oriented Programming (OOP) is a programming paradigm based on the concept of **objects**, which contain **data (variables)** and **behavior (methods)**.
Java is a pure object-oriented language (except primitives) and heavily uses OOP principles to build scalable, reusable, and maintainable software.

---

## Core Concepts of OOP

OOP is built on **four main pillars**:

1. Encapsulation
2. Inheritance
3. Polymorphism
4. Abstraction

---

## 1. Encapsulation

### Definition

Encapsulation is the process of **wrapping data and methods together** into a single unit (class) and **restricting direct access** to data.

### Key Points

* Achieved using `private` variables
* Access provided via `public` getters and setters
* Improves data security and control
* Helps in validation of data

### Real-Life Example

Bank account balance is hidden and can only be accessed through deposit or withdrawal operations.

### Benefits

* Data hiding
* Better control over data
* Improves maintainability

---

## 2. Inheritance

### Definition

Inheritance allows one class (child) to **acquire properties and methods** of another class (parent).

### Key Points

* Achieved using `extends` keyword
* Supports code reusability
* Represents **IS-A** relationship
* Parent class cannot access child class methods

### Types of Inheritance in Java

* Single
* Multilevel
* Hierarchical
  (Java does not support multiple inheritance with classes)

### Real-Life Example

A `Car` is a `Vehicle`.

### Benefits

* Code reuse
* Reduced redundancy
* Easier maintenance

---

## 3. Polymorphism

### Definition

Polymorphism means **one method name with multiple behaviors**.

### Types of Polymorphism

#### Compile-Time Polymorphism

* Method Overloading
* Same method name
* Different parameters

#### Run-Time Polymorphism

* Method Overriding
* Achieved through inheritance
* Decided at runtime

### Key Points

* Parent reference can refer to child object
* Method call depends on object type, not reference type

### Real-Life Example

Payment can be done via UPI, Card, or Cash — same action, different behavior.

### Benefits

* Flexibility
* Loose coupling
* Improved scalability

---

## 4. Abstraction

### Definition

Abstraction is the process of **hiding implementation details** and showing only essential features.

### Achieved Using

* Abstract classes
* Interfaces

### Key Points

* Focuses on **what** an object does, not **how**
* Abstract methods have no body
* Cannot create object of abstract class

### Real-Life Example

ATM machine shows withdrawal option but hides internal process.

### Benefits

* Reduces complexity
* Improves security
* Enhances maintainability

---

## Additional OOP Concepts

### Class

A blueprint from which objects are created.

### Object

An instance of a class that represents real-world entities.

### Constructor

A special method used to initialize objects.

### Method

A block of code that performs a specific task.

---

## OOP vs Procedural Programming

| Feature          | OOP          | Procedural     |
| ---------------- | ------------ | -------------- |
| Approach         | Object-based | Function-based |
| Data Security    | High         | Low            |
| Code Reusability | Yes          | Limited        |
| Scalability      | High         | Low            |

---

## Advantages of OOP

* Modularity
* Reusability
* Scalability
* Security
* Easy maintenance

---

## One-Line Interview Summary

* Encapsulation → Data hiding
* Inheritance → Code reuse
* Polymorphism → One interface, many forms
* Abstraction → Hide implementation

---

## Conclusion

OOP provides a structured way to design programs using real-world concepts.
Understanding these principles is essential for **Java development**, **system design**, and **technical interviews**.


## Installation
```bash
git clone https://github.com/your-username/your-project.git
cd your-project
