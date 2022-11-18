# Flaskr - Intro to Flask, Test-Driven Development, and JavaScript
This project was created by following the tutorial from https://github.com/mjhea0/flaskr-tdd.
## Lab 6 TDD - Janelle Law
### Pros and Cons of TDD

#### Pros
Test Driven Development (TDD) promotes iterative design by combining test first development and refactoring. Writing a test, then writing enough code to pass a test, then creating a test for another use case, and repeating these steps follows the Agile practice of making small changes frequently to minimize risk while improving on a design quickly. TDD also helps developers verify and validate their software designs. In general, verification checks if developers are implementing the product design correctly, while validation checks if the developed product correctly meets the user needs and system requirements/specifications. This process will reveal bugs, assess quality and clarify specifications and documentation.

#### Cons
There are several pitfalls to be mindful of when executing TDD. The first is the street light effect, where developers will only look for quality attributes in places that are easy to do so. However, metrics that are easy to measure may not reliably indicate your desired quality attributes. This is related to the McNamara fallacy, where developers may use the wrong metrics to measure project success. In addition, some important factors that indicate a successful software engineering product are difficult to quantify with tests, including quality, risk, security, and public image.
When testing, one must also be careful with code coverage targets - just because a project has 100% test coverage, it doesn't always mean the tests are checking for the right behaviour. It is up to the developer to design tests that will produce meaningful results.