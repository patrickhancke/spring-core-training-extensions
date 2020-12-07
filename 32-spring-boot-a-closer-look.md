# Spring Boot - a Closer Look

Suppose you have more than 1 active profile. In which order does Spring Boot load the various ```application-{profile}.properties``` files? Try overriding properties, which one takes precedence?

Convert your existing properties file(s) into a single YAML file. Do you need to tell Spring Boot you’re now using YAML configuration?

Open the “spring.factories” file from within the ```spring-boot-autoconfigure-{version}.jar```’s META-INF directory. Choose your favourite library or framework (mongo, redis, amqp,...) and dive into its _AutoConfiguration_ classes. Try to understand which beans will be created for you.

Imagine your Spring Boot application makes use of the JDBC or JPA starter, but requires 2 _DataSource_’s. How do you define these 2 beans?
Hint: have a look at the ```@Primary``` annotation
