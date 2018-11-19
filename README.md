# ANZ Reverse Polish Notation Calulator

## ANZ Assignment

- The Solution has been implemented and tested using Java 7.

- User Input to the calculator is accepted as string contatinig whitespace separated lists of numbers and operators. 

- The Soltuion currently supports 7 operations: `+`, `-`, `*`, `/`, `sqrt`, `undo`, `clear`

- The calculation happens based on Reverse Polish Notation (Post Fix Notation) Algorithm.
 
- `sqrt`: Solution performs a square root on the top item from the stack.

# Project Dependecies are managed by Maven

## Compile, Test, Run and Packaging using Maven 

- Compile: `mvn compile`

- Test: `mvn test`, Test Requires JUnit

- Run (Run the program directly using maven instead of jar using mojo plugin): `mvn exec:java`

- Packaging: `mvn package`
