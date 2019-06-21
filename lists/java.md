# Java Resources

## Official docs and other resources
- [Java SE Official docs](https://docs.oracle.com/javase/7/docs)
- [Java SE Official Tutorials](https://docs.oracle.com/javase/tutorial/)
- [Java Code Ranch - Learning resources for beginners](http://www.coderanch.com/how-to/java/JavaBeginnersFaq)
- [Google - Java Development Tools](https://developers.google.com/java-dev-tools/)
- [Maven Central - The official Java package repository](http://mvnrepository.com/)


## Libraries and Frameworks
- [jUnit](http://junit.org/) - The standard unit testing tool in Java world, the inspiration behind `nunit`, the equivalent for unit testing used in the .NET world.
- [Apache Commons](http://commons.apache.org/) - The most popular and highly used libraries in the Java World.
- [Guava](https://github.com/google/guava) - Google core libraries for java.
- [google-gson](https://github.com/google/gson) - Helpful for converting java objects into json and vice versa.
- [Apache Tomcat](http://tomcat.apache.org/) - A popular web server and Servlet container, the standard way of hosting and developing web apps in the Java world. The official alternative to the `Java EE`.
- [Apache TomEE](http://tomee.apache.org/apache-tomee.html) - It so happens that Tomcat is great, but it doesn't stand up to some of the Oracle's certification standard for a web hosting platform. Hence `TomEE` was created, though its production usage is much less than `Tomcat`.
- [Spring.io](https://spring.io) - A comprehensive open-source web framework in Java that began to address some major drawbacks in the `Java EE` way of development. It pioneered the Dependency-Injection pattern in Java world and its modular approach of bundling components acted as guiding stones for other frameworks like the php symfony.
- [JHipster](https://jhipster.github.io/) - A development platform to generate, develop and deploy Spring Boot + Angular Web applications and Spring microservices.
- [Apache log4j](http://logging.apache.org/log4j) - The standard logging component in the Java world, inspired `log4net` for C# and `log4php` for PHP.
- [hibernate-ORM](http://hibernate.org/orm/) - An object relational mapper. It’s used for persisting of data in relational databases.
- [mockito](http://site.mockito.org/) - Mocking framework for java.
- [selenium](https://github.com/SeleniumHQ/selenium) - A variety of tools and libraries enabling web browser automation.
- [Takes](http://www.takes.org/) - Takes is an open source object-oriented and immutable Java web framework.
- [snmp4j](http://www.snmp4j.org) - An industry standard SNMP library for Java. It allows creation of both SNMP agents and admins thorough its extensive API.


## IDE and other tools
- [Eclipse](http://www.eclipse.org) - The standard and most popular Java IDE used by most Java professionals. Though it appears to be bloated and sometimes slow and not so well designed, it is presently the best available alternative in the Java world. It's pros, however, far far outweigh its cons - it has a plugin-based modular architecture covering not just Java, but PHP, Python, C/C++ and several other langauges. There is also an ADT plugin to develop Android Apps. Personally, I'm a big fan.
- [Apache Netbeans](http://www.netbeans.org/) - Another great IDE, second only to Eclipse. This has an additional advantage of being supported by Oracle and it comes with a Swing/JavaFX designer built-in. However, it is less flexible than Eclipse when it comes to supporting a wide range of projects. It also lacks a python plugin and its android plugin isn't much evolved.
- [BlueJ](http://www.bluej.org/) - An IDE specifically designed for the teaching of Java concepts to students. It doesn't have all the bells and whistles of Eclipse and others, just a plain IDE to easily help understand OOP concepts.
- [IntelliJ](https://www.jetbrains.com/idea/) - A commercial IDE developed by Jetbrains Inc.. Evangelists say that its a better IDE than Eclipse, personally I'm not a huge fan.
- [jEdit](http://www.jedit.org/) - jEdit is more of a Programmer's Editor than a fully fledged IDE. Though it lacks the RAD features in Eclipse/Netbeans, it works pretty well as a lightweight text Editor.
- [Apache Ant](http://ant.apache.org/) - The standard build testing tool in Java world, the inspiration behind `nant`, the .NET equivalent. Often used in conjunction with Maven or Gradle packaging tools.
- [Apache Maven](https://maven.apache.org) - The standard package management tool in Java world, though to be very honest, this department is very fragmented and convoluted with `Gradle` emerging as an unofficial alternative and the [maven central](http://search.maven.org/), not being the only official source. Since Java is enterprise driven, a lot of them have their own maven centrals.
- [Qulice](http://www.qulice.com/) - Qulice is a Quality policing tool for Java which performs all kinds of checks and validations on your Java code. There is a [maven plugin](http://www.qulice.com/qulice-maven-plugin/) available which is very helpful.
- [Gradle](http://www.gradle.org/) - A strong and popular replacement for Maven, especially because of its terse syntax that allows you to do away with Maven's verbose XML.


## Online tutorials, books and puzzles
- [WSIT Tutorial](https://docs.oracle.com/cd/E17802_01/webservices/webservices/reference/tutorials/wsit/doc/Examples_glassfish6.html) - Useful tutorial on creating a `WSDL` client using core Java tools itself like `wsimport`.
- [Java practice tests](http://www.javatpoint.com/examaccess)
- [Reddit r/Java](http://www.reddit.com/r/java)
- [Oracle Java community](https://home.java.net/forums)

## New in Java 8
- [Lambda Expressions](http://cr.openjdk.java.net/~briangoetz/lambda/lambda-state-final.html)
- [Lambda related library enhancements](http://cr.openjdk.java.net/~briangoetz/lambda/lambda-libraries-final.html)
- [Default interface methods](http://zeroturnaround.com/rebellabs/java-8-explained-default-methods)
- [Concurrency Updates](http://openjdk.java.net/jeps/155)
- [New DateTime API (JSR 310)](http://sourceforge.net/apps/mediawiki/threeten/index.php?title=User_Guide)
- [Type Annotations & Pluggable Type Systems](http://docs.oracle.com/javase/tutorial/java/annotations/type_annotations.html)
