# Inside the Spring Container

Imagine you have multiple implementations of the _BeanFactoryPostProcessor_ interface which have been enabled. What about the order in which they get executed? Does it matter? How can you influence it?

One of the _BeanPostProcessor_’s implementations is the _BeanValidationPostProcessor_. What does it do? Think of a possible use case.

Imagine you need a Spring Bean instance of a 3rd party library which is final and doesn’t implement an interface. Unfortunately, Spring is not able to proxy it. How would you work around this?
