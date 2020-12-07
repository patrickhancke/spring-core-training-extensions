# Security

Does your project already make use of secured service methods? Why (not)? If you think it’s hard to test, think again and have a look at the “spring-security-test” dependency. It offers annotations to inject a security context.

Authorize your requests using the MVC matchers. Write a _MockMVC_ test which verifies that access to your _Controller_ methods is properly authorized.

A popular protocol for authorization nowadays is OAuth 2.0. Explore some of its key concepts like
* Scope
* Grant Type
* Client Type (confidential, public)
* Bearer Token

Do some research and find out how the Spring Security module can support you.
