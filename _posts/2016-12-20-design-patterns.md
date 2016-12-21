---
layout: post
title: Design Patterns
---

# What are they?

Design patterns are a set of common situations in code where to implment good code design.

use design prinicples to solve common problems

# History

Gang of four came up with 28 common patterns in the 90's.

# Why use them?

Avoid having to spend time figuring out the best way to design the code for a problem that has already been done.

Although the draw back means, you have to learn when to use them and where to use them. Also over reliance on them or using as many as possible (YAGNI).

[http://softwareengineering.stackexchange.com/questions/9219/are-design-patterns-generally-a-force-for-good-or-bad](http://softwareengineering.stackexchange.com/questions/9219/are-design-patterns-generally-a-force-for-good-or-bad)
[http://www.yegor256.com/2016/02/03/design-patterns-and-anti-patterns.html](http://www.yegor256.com/2016/02/03/design-patterns-and-anti-patterns.html)

Shared langauge in discussing design of software and avoid ambiguity when communicating about code.


#List of patterns

- Abstract factory pattern groups object factories that have a common theme.
- Builder pattern constructs complex objects by separating construction and representation.
- Factory method pattern creates objects without specifying the exact class to create.
- Prototype pattern creates objects by cloning an existing object.
- Singleton pattern restricts object creation for a class to only one instance.
- Adapter allows classes with incompatible interfaces to work together by wrapping its own interface around that of an already existing class.
- Bridge decouples an abstraction from its implementation so that the two can vary independently.
- Composite composes zero-or-more similar objects so that they can be manipulated as one object.
- [Decorator](/decorator-pattern/) dynamically adds/overrides behaviour in an existing method of an object.
- Facade provides a simplified interface to a large body of code.
- Flyweight reduces the cost of creating and manipulating a large number of similar objects.
-Proxy provides a placeholder for another object to control access, reduce cost, and reduce complexity.
- Chain of responsibility delegates commands to a chain of processing objects.
- Command creates objects which encapsulate actions and parameters.
- Interpreter implements a specialized language.
- Iterator accesses the elements of an object sequentially without exposing its underlying representation.
- Mediator allows loose coupling between classes by being the only class that has detailed knowledge of their methods.
- Memento provides the ability to restore an object to its previous state (undo).
- [Observer](/#/) is a publish/subscribe pattern which allows a number of observer objects to see an event.
State allows an object to alter its behavior when its internal state changes.
- [Strategy](/#/) allows one of a family of algorithms to be selected on-the-fly at runtime.
-Template method defines the skeleton of an algorithm as an abstract class, allowing its subclasses to provide concrete behavior.
- Visitor separates an algorithm from an object structure by moving the hierarchy of methods into one object.


# Books and code

[Design Patterns in Ruby by Russ Olsen](https://www.amazon.co.uk/Design-Patterns-Ruby-Addison-Wesley-Professional/dp/0321490452/ref=sr_1_1?ie=UTF8&qid=1482308076&sr=8-1&keywords=design+patterns+in+ruby)
and his [code](https://github.com/russolsen/design_patterns_in_ruby_code)

[Head First Design Patterns](https://www.amazon.co.uk/Head-First-Design-Patterns-Freeman/dp/0596007124/ref=sr_1_1?ie=UTF8&qid=1482308147&sr=8-1&keywords=design+patterns+head+first) and the [code](https://github.com/bethrobson/Head-First-Design-Patterns)
- Read the chapter from Head first design patterns (uses java for examples)

[Gang of four design patterns](https://github.com/bethrobson/Head-First-Design-Patterns)

[Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)

[Other good link](https://sourcemaking.com/design_patterns)

[https://www.tutorialspoint.com/design_pattern/design_pattern_overview.htm](https://www.tutorialspoint.com/design_pattern/design_pattern_overview.htm)
