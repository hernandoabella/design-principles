# Design Principles 🎨

## Table of Contents

1. [Introduction](#introduction)
2. [SOLID Principles](#solid-principles)
    - [Single Responsibility Principle](#single-responsibility-principle)
    - [Open/Closed Principle](#openclosed-principle)
    - [Liskov Substitution Principle](#liskov-substitution-principle)
    - [Interface Segregation Principle](#interface-segregation-principle)
    - [Dependency Inversion Principle](#dependency-inversion-principle)
3. [DRY Principle](#dry-principle)
4. [KISS Principle](#kiss-principle)
5. [YAGNI Principle](#yagni-principle)
6. [Composition Over Inheritance](#composition-over-inheritance)
7. [Law of Demeter](#law-of-demeter)
8. [Encapsulation](#encapsulation)
9. [Modularity](#modularity)
10. [Separation of Concerns](#separation-of-concerns)
11. [Resources and Further Reading](#resources-and-further-reading)
12. [Conclusion](#conclusion)

## Introduction

Welcome to the Design Principles guide! This document covers essential design principles that help in creating robust, maintainable, and scalable software.

## SOLID Principles

### Single Responsibility Principle

A class should have only one reason to change, meaning it should only have one job or responsibility.

### Open/Closed Principle

Software entities should be open for extension but closed for modification.

### Liskov Substitution Principle

Objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program.

### Interface Segregation Principle

Clients should not be forced to depend on interfaces they do not use.

### Dependency Inversion Principle

High-level modules should not depend on low-level modules. Both should depend on abstractions.

## DRY Principle

### DRY (Don't Repeat Yourself)

Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.

## KISS Principle

### KISS (Keep It Simple, Stupid)

Systems should be as simple as possible. Simplicity is the key to good design.

## YAGNI Principle

### YAGNI (You Aren't Gonna Need It)

Always implement things when you actually need them, never when you just foresee that you need them.

## Composition Over Inheritance

Favor composition over inheritance to achieve code reuse and flexibility.

## Law of Demeter

A module should not know about the internal details of the objects it manipulates. Also known as the principle of least knowledge.

## Encapsulation

Encapsulation hides the internal state of an object and requires all interaction to be performed through an object's methods.

## Modularity

Design systems to be divided into distinct modules that can be developed, tested, and maintained independently.

## Separation of Concerns

Separate a computer program into distinct features that overlap in functionality as little as possible.

## Resources and Further Reading

- [Clean Architecture: A Craftsman's Guide to Software Structure and Design](https://www.amazon.com/dp/0134494164)
- [The Pragmatic Programmer: Your Journey to Mastery](https://www.amazon.com/dp/0135957052)
- [Refactoring: Improving the Design of Existing Code](https://www.amazon.com/dp/0134757599)

## Conclusion

Understanding and applying design principles is crucial for building high-quality software. These principles provide guidelines that help improve the readability, maintainability, and scalability of your codebase.
