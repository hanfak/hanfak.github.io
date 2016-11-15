---
layout: post
title: Design Principles
---

**Well designed code is when it is easy to maintain, reuse, extend and read**

Why?

In short, **because everything changes**. Thus need to change code, match these changes.

The following principles below will help in producing well designed code.

As time progresses, I will write a blog post(s) for each one with code examples.

There will be conflict between some of these, but the aim of an engineer is not to implement everything only to make the code better designed.

Sometimes these rules can be broken, as Sandi Metz says:

`“You should break these rules only if you have a good reason or your pair lets you.”`

### Sandi Metz Rules

- Classes can be no longer than one hundred lines of code.
- Methods can be no longer than five lines of code.
- Pass no more than four parameters into a method.
  - Hash options are parameters.
- Controllers can instantiate only one object. Therefore, views can only know about one instance variable and views should only send messages to that object (@object.collaborator.value is not allowed).

### SOLID Principles

- Single Responsibility Principle (SRP)
  - A class should have only one reason to change
- Open/closed principle (OCP)
- Liskov substitution principle (LSP)
- Interface segregation principle (ISP)
- Dependency inversion/Injection principle (DIP)

### General Principles

- DRY (Don't Repeat Yourself)
- KISS (Keep It Simple Silly)
- YAGNI (You Are Not Gonna Need It)
- Delegate, Delegate, Delgate (Ask, Dont Tell)
- Composition over Inheritence
- Law of Demeter
- Encapsulate Change
- Programming for Interface not implementation
- Aim for High Cohesion and Loose Coupling
