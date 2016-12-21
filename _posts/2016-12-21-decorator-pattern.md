---
layout: post
title: Decorator Pattern
---

# What is it:


Create one class (concrete class) that covers the basic functionality and a set of decorators to extend this functionality. Using a combination of concrete and decorators at runtime to increase functionality specific to what is needed.


# Used for/ motivation:


Have a combinations features at run time. Thus reducing the excess of features that are not needed.


Uses delegation, passing on functionality to other classes. A lot of compartmentalization and code clarity.


Adds responsibility dynamically.


Avoid inheritance, by avoiding designing all possible features up front at design time (when compiled). Inheritance would override the method, but this would happen a lot for different combinations of features.


Avoid creating a God class that does everything.


Adds modification without changing the original class


# Downside:


Can end up with a lot of classes which has to be instantiated in other objects instantiation. Thus a lot of objects are created


Implementing at run time could be made easier by using a builder for common instantiations.


# Design principle:


Helps code adhere to single responsibility principle and open closed principle, favoring composition over inheritance


# Notes:


Similar to the mathematical concept of function composition, in terms of notation.


# Links:


[https://sourcemaking.com/design_patterns/decorator](https://sourcemaking.com/design_patterns/decorator)
[https://en.wikipedia.org/wiki/Decorator_pattern](https://en.wikipedia.org/wiki/Decorator_pattern)
[https://www.tutorialspoint.com/design_pattern/decorator_pattern.htm](https://www.tutorialspoint.com/design_pattern/decorator_pattern.htm)
[http://www.oodesign.com/decorator-pattern.html](http://www.oodesign.com/decorator-pattern.html)
[http://www.journaldev.com/1540/decorator-design-pattern-in-java-example](http://www.journaldev.com/1540/decorator-design-pattern-in-java-example)
[https://dzone.com/articles/design-patterns-decorator](https://dzone.com/articles/design-patterns-decorator)
[https://code.tutsplus.com/tutorials/design-patterns-the-decorator-pattern--cms-22641](https://code.tutsplus.com/tutorials/design-patterns-the-decorator-pattern--cms-22641)
[https://www.youtube.com/watch?v=j40kRwSm4VE](https://www.youtube.com/watch?v=j40kRwSm4VE)
[https://www.youtube.com/watch?v=NtXGDTgrTMI](https://www.youtube.com/watch?v=NtXGDTgrTMI)
[https://www.youtube.com/watch?v=aqoDUI5ujmE](https://www.youtube.com/watch?v=aqoDUI5ujmE)
