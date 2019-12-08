---
author: "Ragesh R"
date: 2019-08-18
title: Design Patterns
image: 'design-patterns.jpg'
draft: false
---
## Design Patterns

In software engineering, there are few problems that are repetitive in nature. This may be as simple as creating a file name to a complex operation such as appling transactions for database operations. Every such problem needs a solution. If the problems are repeatable, then we could reuse the solutions repeatably as well.

Definition for Software Design Pattern from [wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)


*A software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design. It is not a finished design that can be transformed directly into source or machine code. It is a description or template for how to solve a problem that can be used in many different situations. Design patterns are formalized best practices that the programmer can use to solve common problems when designing an application or system.*


Design patterns are broadly classified into the following categories:

- Creational Patterns
- Structural Patterns
- Behavioural Patterns
- Concurrency Patterns

## Creational Design Patterns

Creational design patterns deal with object creation mechanisms, trying to create objects in a manner suitable to the situation. The basic form of object creation could result in design problems or in added complexity to the design. Creational design patterns solve this problem by somehow controlling this object creation.

Creational design patterns are composed of two dominant ideas. 
- First is encapsulating knowledge about which concrete classes the system uses.
- Second is hiding how instances of these concrete classes are created and combined.

Creational design patterns are further categorized into 
- Object-creational patterns - deal with Object creation. This pattern defer part of its object creation to another object 
- Class-creational patterns - deal with Class-instantiation. This pattern defer its object creation to subclasses.

Five well-known design patterns that are parts of creational patterns are the

 1. [Abstract factory pattern](design-patterns/abstract-factory-pattern)
 2. [Builder pattern](design-patterns/builder-pattern.md)
 3. Factory method pattern 
 4. Prototype pattern
 5. Singleton pattern
 