# Spring MVC + REST

If you want to intercept your requests before/after they reach your _Controller_, Spring offers support for it: have a look at the _org.springframework.web.servlet.HandlerInterceptor_ interface and its implementing classes.

Write a REST Controller which supports JSR-303 validation on its entities. How does Spring return validation errors to the client?

Explore the different options Spring offers you for exception handling:
* ```@ResponseStatus```
* ```@ExceptionHandler```
* ```@ControllerAdvice```

It’s easy to get lost when you need to choose between these options: refer to https://spring.io/blog/2013/11/01/exception-handling-in-spring-mvc for guidance
