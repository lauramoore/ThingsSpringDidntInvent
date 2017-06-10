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

So if you're working with Spring, you're working with a curated set of best practices:
the paradigms, concepts, techniques and tools that have been evolving since the
dawn of programming.   You are seeing the current state of accumulated knowledge,
wisdom built up from decades of experience, and more than a few ongoing debates.

It's a toolbox, and like any toolbox, you can't use it effectively if you don't
also study how and where each tool applies.  In this case, the tools are intended
to speed up development in large enterprise applications.  Spring bills itself
as plumbing or wiring tools that free your development time to focus on the
business logic of your domain.   It's like me buying command strips to hang pictures
on my wall so that I don't have to get good at fixing nail holes later.

## DI is only the tip of the Iceberg

The first thing almost any developer can tell you about Spring is that it uses
Dependency Injection / Inversion of Control to build applications.  While true,
it is also incomplete.

Spring actually uses the whole acronym!  [S.O.L.I.D](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
Those famous 5 principles, named first by [Robert C. Martin (Uncle Bob)](http://cleancoder.com).

<table>
<tr>
<th> S </th>
<td> SRP</td>
<td> The Single Responsibility Principle</td>
<td>A class should have one, and only one, reason to change.</td>
</tr>
<tr>
<th>  O </th><td> OCP	</td><td>The Open Closed Principle	</td><td> You should be able to extend a classes behavior, without modifying it. </td></tr>
<tr>
<th>  L </th><td> LSP	</td><td> The Liskov Substitution Principle	</td><td> Derived classes must be substitutable for their base classes. </td></tr>
<tr>
<th>  I </th><td> ISP	</td><td> The Interface Segregation Principle	</td><td> Make fine grained interfaces that are client specific. </td></tr>
<tr>
<th>  D </th><td> DIP	</td><td> The Dependency Inversion Principle	</td><td> Depend on abstractions, not on concretions. </td></tr>
</table>

## Want To Know More?
[OCP + DIP = Never Rewrite!](https://www.youtube.com/watch?v=DJF_sGOs2V4)
