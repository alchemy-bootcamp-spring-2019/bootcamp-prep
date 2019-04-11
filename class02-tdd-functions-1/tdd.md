Test Driven Development and Design (TDD)
===

1. Clone the project [bc1-config](git@github.com:alchemy-bootcamp-spring-2019/bootcamp-prep.git). Rename `bc1-config` directory to `tdd-experiment`.

2. Install the Live Server extension in VSCode.

3. Right-click (Windows) or Control-click (Mac) on the index.html file in the tests folder. This opens a QUnit browser window.

4. Your tests are in the tests.js file. This is where you'll focus all your coding.

**TDD Flow**

1. Write the simplest possible failing test (RED)
  - write sudo code 
  // Arrange
  // Act 
  // Assert
2. Make it pass with smallest amount of code. (GREEN)
3. Clean up - remove duplication, comments, etc. (REFACTOR)
4. Do it all again.

**Challenge**

1. TDD a function that returns a Boolean.
  - write the test first
2. Make the function return the Boolean.
  - write a function that passes the test

**Stretch Challenges**

Square A Number Challenge
1. TDD a function that squares a number.
2. Make it only square even numbers.
3. Return this as a string. 

Combine Two Strings Challenge
1. TDD a function that takes 2 strings.
2. Expect the function to combine the 2 strings and return them as one

Print Fizz if a number is divisible by 3
1. TDD a function that takes a number.
2. IF the number is divisible by 3 with no remainder
3. Expect the function to return the string 'Fizz'
4. ELSE return the number

Print Buzz if a number is divisible by 5
1. TDD a function that takes a number.
2. IF the number is divisible by 5 with no remainder
3. Expect the function to return the string 'Buzz'
4. ELSE return the number

Print FizzBuzz if a number is divisible by 3 & 5
1. TDD a function that takes a number.
2. IF the number is divisible by 3 && 5
3. Expect the function to return the string 'FizzBuzz'
4. ELSE return the number
