# Assignment 13

Use `Math.random()` to generate a random number from 1 to 6 (inclusive) in order to simulate the roll of a die. Then, ask the user to guess the roll and tell them if they guessed correctly. If they guessed incorrectly, tell them if they were high or low and what the actual roll was.

You must account for edge cases (if user enters a number less than 1 or greater than 6) and you can use one class for this assignment, but you must use at least one method.

### Random Numbers Examples

For some random integer n, where `x <= n <= y`:

`int randNum = (int) ((y - x + 1) * Math.random() + x);`

In basic terms, (y - x + 1) is the number of possible integers you want to generate.

x is the minimum value, so it adjusts it from the minimum value from `Math.random()`, which is zero.

### Sample Outputs

```
Guess the number that will be rolled by the die: 4
You were too low. The roll was a 5
```

```
Guess the number that will be rolled by the die: 6
You were too high. The roll was a 2
```

```
Guess the number that will be rolled by the die: 4
You guessed correctly!
```

```
Guess the number that will be rolled by the die: -2
Invalid entry. You lose.
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

