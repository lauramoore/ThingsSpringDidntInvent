# On the shoulders of giants

[Spring](http://spring.io) has a rap for being complex.   Developers just starting out with
Java, and new to Java in an Enterprise application easily mistake the challenges
the find on the framework.  But in reality, the complexity they malign is really
just software development in a large, heterogeneous, complex environment.

If you've ever had to deploy, maintain, develop and test apps in an enterprise
without Spring you know what I mean.

As the [Spring Overview](http://docs.spring.io/spring-framework/docs/current/spring-framework-reference/html/overview.html) states
>Although the Java platform provides a wealth of application development functionality,
>it lacks the means to organize the basic building blocks into a coherent whole,
>leaving that task to architects and developers.
>Although you can use design patterns such as Factory, Abstract Factory, Builder, Decorator, and Service Locator
>to compose the various classes and object instances that make up an application,
>these patterns are simply that: best practices given a name,
>with a description of what the pattern does, where to apply it,
>the problems it addresses, and so forth.
>Patterns are formalized best practices that you must implement yourself in your application.

The first thing almost any developer can tell you about Spring is that it uses
Dependency Injection / Inversion of Control to build applications.  While true,
it is also incomplete.

Spring actually uses the whole acronym!  [S.O.L.I.D](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
This the famous 5 principles, named first by Robert "Uncle Bob" Martin.

| SRP	| The Single Responsibility Principle	| A class should have one, and only one, reason to change. |
| OCP	| The Open Closed Principle	| You should be able to extend a classes behavior, without modifying it. |
| LSP	| The Liskov Substitution Principle	| Derived classes must be substitutable for their base classes. |
| ISP	| The Interface Segregation Principle	| Make fine grained interfaces that are client specific. |
| DIP	| The Dependency Inversion Principle	| Depend on abstractions, not on concretions. |
