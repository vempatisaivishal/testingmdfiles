1. True or False: An expression always returns a value.

   - [ ] True
   - [x] False (Right Answer)
   - Explanation: Expressions can return values, but not all of them do. For example, a simple assignment expression does not return a value.

2. True or False: A statement can be used as an operand in an expression.

   - [ ] True
   - [x] False (Right Answer)
   - Explanation: Statements are not meant to be used as operands in expressions. Expressions yield values, while statements do not.

3. Which of the following is not a valid Java statement?

   - [ ] `if (x > 5) { }`
   - [x] `x + 5;` (Right Answer)
   - [ ] `System.out.println("Hello, world!");`
   - [ ] `int x = 10;`
   - Explanation: `x + 5;` is not a valid statement because it does not have any side effects or assignment. It's a valid expression but not a statement.

4. What is the purpose of a block in Java code?

   - [ ] To define a variable
   - [ ] To declare a method
   - [ ] To terminate a program
   - [x] To group multiple statements together (Right Answer)
   - Explanation: Blocks are used to group multiple statements together and define a scope.

5. In Java, which statement is used to exit a loop prematurely?

   - [ ] `return`
   - [ ] `break`
   - [ ] `continue`
   - [x] `break` (Right Answer)
   - Explanation: The `break` statement is used to exit a loop prematurely.

6. What will be the value of `result` after the following code is executed?

```java
int x = 5;
int y = 7;
int result = x + (y = 3);
```

- [ ] 15
- [x] 8 (Right Answer)
- [ ] 10
- [ ] 7
- Explanation: The code assigns 3 to `y`, and then adds the value of `x` to the updated `y`, resulting in `8`.

7. What is the output of the following code?

```java
int x = 10;
if (x > 5) {
    System.out.println("Hello");
} else {
    System.out.println("World");
}
```

- [ ] "Hello"
- [x] "Hello" (Right Answer)
- [ ] "World"
- [ ] "Hello\\nWorld"
- Explanation: Since `x` is greater than 5, it will print "Hello."

8. Which of the following code snippets contains a valid Java block?

   - [ ] `if (x > 5) {}`
   - [x] `{ int y = 10; }` (Right Answer)
   - [ ] `int z = 15;`
   - [ ] `while (true) { return; }`
   - Explanation: `{ int y = 10; }` is a valid block with a variable declaration.

9. In Java, what is the result of the expression `10 / 3`?

   - [ ] 3
   - [ ] 3.0
   - [x] 3 (Right Answer)
   - [ ] 3.333
   - Explanation: In Java, when both operands are integers, division results in an integer, truncating the fractional part.

10. What is the value of `result` after the following code is executed?

```java
int x = 5;
int result = (x > 3) ? 10 : 20;
```

- [ ] 5
- [ ] 3
- [x] 10 (Right Answer)
- [ ] 20
- Explanation: The conditional (ternary) operator assigns 10 to `result` because the condition `x > 3` is true.

11. True or False: All code within a block is executed, regardless of whether the block is inside a conditional statement.

- [ ] True
- [x] False (Right Answer)
- Explanation: Code within a block is executed only when the condition associated with the block is true.

12. True or False: An expression can be a standalone statement in Java.

- [ ] True
- [x] False (Right Answer)
- Explanation: Expressions can be part of statements, but they cannot be standalone statements in Java.

13. What is the purpose of the `return` statement in Java?

- [ ] To print a value to the console
- [x] To exit a method and return a value (Right Answer)
- [ ] To terminate the program
- [ ] To declare a variable

14. In Java, what is the role of the `default` label in a `switch` statement?

- [ ] It defines a default method for the class.
- [x] It specifies the code to be executed when no `case` matches (Right Answer)
- [ ] It is used to define a default constructor.
- [ ] It represents the highest access modifier.

15. What is the purpose of the `try`, `catch`, and `finally` blocks in exception handling?

- [ ] `try` is used to handle exceptions, `catch` is for normal code execution, and `finally` is for loop control.
- [ ] `try` is used to terminate the program, `catch` is for handling exceptions, and `finally` is used to define a class constructor.
- [x] `try` is for code that may throw exceptions, `catch` is for handling exceptions, and `finally` contains code that runs regardless of whether an exception is thrown (Right Answer)
- [ ] `try` is used to start a loop, `catch` is for conditional statements, and `finally` is for variable declarations.

16. What is the value of `result` after the following code is executed?

```java
int a = 7;
int b = 5;
int result = a % b;
```

- [ ] 2
- [ ] 3
- [ ] 1
- [x] 2 (Right Answer)
- Explanation: The modulus operator `%` returns the remainder of the division of `a` by `b`, which is 2.

17. What is the output of the following code?

```java
int x = 10;
if (x > 20) {
    System.out.println("A");
} else if (x > 15) {
    System.out.println("B");
} else {
    System.out.println("C");
}
```

- [ ] "A"
- [ ] "B"
- [x] "C" (Right Answer)
- [ ] "B\\nC"
- Explanation: Since none of the conditions are true, it will print "C."

18. Which of the following code snippets contains a valid Java block?

- [ ] `if (x > 5) {}`
- [ ] `int y = 15;`
- [x] `{ System.out.println("Hello"); }` (Right Answer)
- [ ] `for (int i = 0; i < 10; i++) { return; }`
- Explanation: `{ System.out.println("Hello"); }` is a valid block containing a statement.

19. In Java, what is the result of the expression `5.0 / 2`?

- [ ] 2.5
- [ ] 2
- [x] 2.5 (Right Answer)
- [ ] 2.0
- Explanation: When one or both operands are floating-point numbers, the result is also a floating-point number.

20. What is the value of `result` after the following code is executed?

```java
int x = 5;
int y = 10;
int result = (x < y) ? x : y;
```

- [ ] 5
- [ ] 10
- [ ] 15
- [x] 5 (Right Answer)
- Explanation: The conditional (ternary) operator assigns the value of `x` to `result` because the condition `x < y` is true.

21. True or False: In Java, a variable declared within a block is accessible only within that block.

- [ ] True
- [x] False (Right Answer)
- Explanation: Variables declared within a block are accessible only within that block's scope, but they can be accessed by inner blocks.

22. True or False: The `do-while` loop in Java always executes the loop body at least once.

- [x] True (Right Answer)
- [ ] False
- Explanation: The `do-while` loop first executes the loop body and then checks the condition, ensuring at least one execution.

23. What is the primary purpose of the `break` statement in Java?

- [ ] To skip the current iteration of a loop and continue with the next iteration.
- [x] To exit a loop prematurely or terminate a `switch` statement (Right Answer)
- [ ] To create a new code block.
- [ ] To jump to a specific label within a method.

24. What does the term "scope" refer to in Java programming?

- [ ] The order in which methods are called.
- [ ] The type of data a variable can store.
- [ ] The number of parameters in a method.
- [x] The region of code where a variable is accessible (Right Answer)

25. In Java, what is the purpose of the `continue` statement in a loop?

- [ ] To exit the loop prematurely.
- [x] To skip the rest of the current iteration and continue with the next iteration (Right Answer)
- [ ] To terminate the program.
- [ ] To create an infinite loop.

26. What is the value of `result` after the following code is executed?

```java
int x = 6;
int result = 3 * x--;
```

- [ ] 18
- [ ] 15
- [x] 18 (Right Answer)
- [ ] 15
- Explanation: The expression `3 * x--` first multiplies `x` by 3 and then decrements `x`, resulting in 18.

27. What is the output of the following code?

```java
int count = 0;
while (count < 5) {
    System.out.print(count + " ");
    count += 2;
}
```

- [ ] "0 1 2 3 4 "
- [ ] "0 2 4 "
- [x] "0 2 4 " (Right Answer)
- [ ] "0 1 2 3 4 5 "
- Explanation: The `while` loop prints values from 0 to 4 in steps of 2.

28. Which of the following code snippets contains a valid Java block?

- [ ] `int x = 10;`
- [ ] `if (x > 5) {}`
- [ ] `{ x++; }`
- [x] `{ int y = 15; }` (Right Answer)
- Explanation: `{ int y = 15; }` is a valid block with a variable declaration.

29. In Java, what is the result of the expression `(5 + 2) / 3`?

- [ ] 2
- [ ] 2.33
- [x] 2 (Right Answer)
- [ ] 2.0
- Explanation: The expression evaluates to 7 / 3, which is 2 in integer division.

30. What is the value of `result` after the following code is executed?

```java
int x = 5;
int y = 7;
int result = (x > y) ? x + y : x - y;
```

- [ ] 12
- [ ] -2
- [ ] 5
- [x] -2 (Right Answer)
- Explanation: The conditional (ternary) operator assigns `x - y` to `result` because the condition `x > y` is false.

31. True or False: In Java, a block can have its own local variables with the same names as variables in an outer scope.

- [x] True (Right Answer)
- [ ] False
- Explanation: A block can have local variables with the same names as variables in an outer scope, and the inner variable will shadow the outer one.

32. True or False: The `return` statement is used to terminate the execution of a method in Java.

- [x] True (Right Answer)
- [ ] False
- Explanation: The `return` statement is used to exit a method and optionally return a value to the caller.

33. What is the purpose of the `switch` statement in Java?

- [ ] To perform mathematical operations.
- [ ] To define a custom class.
- [x] To provide a way to select one of many code blocks to execute based on a value (Right Answer)
- [ ] To terminate the program.

34. What is the difference between an expression statement and a block in Java?

- [ ] An expression statement is used to group multiple expressions, while a block is used to execute code conditionally.
- [ ] An expression statement contains a single expression, while a block can contain multiple statements.
- [x] An expression statement contains an expression that is executed for its side effects, while a block defines a scope and contains multiple statements (Right Answer)
- [ ] An expression statement is only used in loops, while a block is used in conditional statements.

35. What is the role of the `else` clause in an `if-else` statement in Java?

- [ ] To specify the condition for entering the `if` block.
- [x] To define the code block that is executed when the `if` condition is false (Right Answer)
- [ ] To create a new variable.
- [ ] To terminate the program.

36. What is the value of `result` after the following code is executed?

```java
int x = 10;
int result = (x % 3 == 0) ? (x / 3) : (x * 2);
```

- [ ] 10
- [ ] 20
- [x] 3 (Right Answer)
- [ ] 6
- Explanation: The conditional (ternary) operator assigns `x / 3` to `result` because the condition `x % 3 == 0` is true.

37. What is the output of the following code?

```java
int i = 0;
do {
    System.out.print(i + " ");
    i++;
} while (i < 5);
```

- [ ] "0 1 2 3 4 5 "
- [ ] "0 1 2 3 4 "
- [ ] "1 2 3 4 5 "
- [x] "0 1 2 3 4 " (Right Answer)
- Explanation: The `do-while` loop prints values from 0 to 4.

38. Which of the following code snippets contains a valid Java block?

- [x] `{ int y = 15; }` (Right Answer)
- [ ] `int x = 10;`
- [ ] `if (x > 5) {}`
- [ ] `for (int i = 0; i < 10; i++) { return; }`
- Explanation: `{ int y = 15; }` is a valid block with a variable declaration.

39. In Java, what is the result of the expression `10 % 3`?

- [ ] 0
- [ ] 3
- [x] 1 (Right Answer)
- [ ] 10
- Explanation: The modulus operator `%` returns the remainder of the division of 10 by 3, which is 1.

40. What is the value of `result` after the following code is executed?

```java
int x = 5;
int y = 7;
int result = (x < y) ? (x + y) : (x - y);
```

- [ ] 12
- [ ] -2
- [ ] 5
- [x] 12 (Right Answer)
- Explanation: The conditional (ternary) operator assigns `x + y` to `result` because the condition `x < y` is true.

41. True or False: In Java, a variable declared as `final` can be reassigned to a different value after its initial assignment.

- [ ] True
- [x] False (Right Answer)
- Explanation: A `final` variable in Java cannot be reassigned after its initial assignment.

42. True or False: The `default` case in a `switch` statement is optional.

- [ ] True
- [x] False (Right Answer)
- Explanation: The `default` case is optional, but it's often used to provide a default action when none of the `case` values match.

43. What is the primary purpose of the `continue` statement in a loop in Java?

- [ ] To exit the loop prematurely.
- [ ] To jump to a specific label within a method.
- [ ] To terminate the program.
- [x] To skip the rest of the current iteration and continue with the next iteration (Right Answer)

44. In Java, what is a compound statement?

- [ ] A statement involving financial transactions.
- [ ] A statement that combines two expressions into one.
- [x] A block of code enclosed in curly braces `{}` that groups multiple statements (Right Answer)
- [ ] A statement with multiple return values.

45. What is the purpose of the `break` statement within a `switch` case in Java?

- [ ] To exit the method.
- [ ] To terminate the program.
- [ ] To restart the loop.
- [x] To exit the `switch` statement and continue with the code after the `switch` (Right Answer)

46. What is the value of `result` after the following code is executed?

```java
int x = 5;
int y = 2;
int result = x % y;
```

- [ ] 2
- [ ] 2.5
- [ ] 3
- [x] 1 (Right Answer)
- Explanation: The modulus operator `%` returns the remainder of the division of 5 by 2, which is 1.

47. What is the output of the following code?

```java
int i = 0;
while (i < 5) {
    System.out.print(i + " ");
    i++;
}
```

- [ ] "0 1 2 3 4 "
- [ ] "0 1 2 3 4 5 "
- [ ] "1 2 3 4 5 "
- [x] "0 1 2 3 4 " (Right Answer)
- Explanation: The `while` loop prints values from 0 to 4.

48. Which of the following code snippets contains a valid Java block?

- [ ] `if (x > 5) {}`
- [x] `{ int y = 15; }` (Right Answer)
- [ ] `int x = 10;`
- [ ] `for (int i = 0; i < 10; i++) { return; }`
- Explanation: `{ int y = 15; }` is a valid block with a variable declaration.

49. In Java, what is the result of the expression `6 / 4`?

- [ ] 1
- [ ] 1.5
- [ ] 2
- [x] 1 (Right Answer)
- Explanation: In Java, integer division truncates the fractional part, so the result is 1.

50. What is the value of `result` after the following code is executed?

```java
int x = 5;
int y = 7;
int result = (x < y) ? (x * y) : (x + y);
```

- [ ] 12
- [ ] 35
- [ ] 5
- [x] 35 (Right Answer)
- Explanation: The conditional (ternary) operator assigns `x * y` to `result` because the condition `x < y` is true.
