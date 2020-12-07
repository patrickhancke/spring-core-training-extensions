# Testing

Write a JUnit 5 test using the ```@ParameterizedTest``` annotation. Which advantages or disadvantages do you see? Would you use this often?


Assuming you know and use popular mocking libraries like for example _Mockito_, write a unit test which makes use of a **stub** instead of a mock. Advantages, disadvantages? What if the stub is a:
* interface
* regular class
* final class


How does Spring Test behave when you inject a prototype bean in multiple test methods? Take for example, this signature:

```
@Test
void prototype_1(@Autowired MyPrototypeBean myPrototypeBean) {
//your assertions here
}
@Test
void prototype_2(@Autowired MyPrototypeBean myPrototypeBean) {
//your assertions here
}
```

Write a JUnit 5 test using the _assertThrows(...)_ method. Do you know how this was done in JUnit 4?

For a richer set of assertion methods, have a look at https://assertj.github.io/doc/ and its various modules.