# spring-boot QNA

# springboot vs springmvc vs spring

# spring 
Spring framework is all about dependency injection. It's about defining the dependencies, identifying the dependencies and auto adding them in.You can define dependencies using variety of annotations @component @service, and there are a lot of others.Once you have defined your dependencies, you need to identify them.

That's where components Scan is useful.You can do a component scan on a specific package and identify all the components which are defined in there.
Once you have all the components and the dependencies identified, you can auto wired them together. That's the core work of spring framework.

However, just dependency injection is not sufficient to build applications. You need other frameworks.
Spring modules and spring projects extend the spring ecosystem.
So if you want to talk to a database, Spring provides really good integration with Hibernate and JPA.If you want to write a unit test, Spring also provides good integration with Unit and Marketo.
So the core of spring framework is dependency injection and spring modules and spring projects helpyou to extend the spring ecosystem and integrate easily with other frameworks.

# spring mvc
Spring MVC is a spring module.The focus of spring MVC is on simplifying building of web applications and rest API.It only focuses on web apps and rest API.

With Spring MVC, you can make use of annotations like @Controller at @Restcontroller @Requestmapping.These are all the things that I defined as part of Spring MVC.

We saw that there is a lot of configuration that is needed in your pom.XML in your web.XML in your applicationcontext.XML whenever you'd want to build even a simple application with spring and spring MVC.


# SpringBoot
Spring Boot is a spring project The goal is to help you build production ready applications quickly. The key features of spring boot are startup projects and auto configuration. 

if you want to develop a web application, the web starter would bring in all the dependencies that are needed, and auto configuration would eliminate the need to set up spring, spring, MVC and other frameworks.

It automatically provides a default configuration based on whatever is in your class path.In addition, Springboot also enables a number of non-functional requirements.If you want to monitor your application, you have actuator and embedded servers simplifies the deploymentof your applications.
And Springboard also provides default logging and error handling. Springboot simplifies application configuration through profiles and configuration properties.
