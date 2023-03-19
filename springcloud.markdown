Lately I've been excercising a little bit on my own with the Spring Framework.
In particular, I started leveraging Spring Boot as it's pretty fast so setup if you don't have that much time to spend in configuration and so on. I also wanted to check
what Spring Cloud is, and I have to admit I was pretty stunned: it's an intuitive, powerful framework whcih lets the programmer define some of the most
commonly spread paradigms (such as Load Balancers, API Gateways and, i general, anything related to Microservices architecture) in just a few minutes.

Here's a repository with everything I managed to write and deploy in a few hours: a simple service with a little configuration, and two microservices interacting with each other
through the help of an API Gateway. Pretty common and easy scenarios - even if in production environments, with multiple services, they are prone to fail - and Spring makes them even easier!

[here!](https://github.com/valgh/springboot-fun)
