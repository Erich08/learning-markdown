## JavaScript loops

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

> for (let step = 0; step <5; step++) {
> console.log('Walking east one step');
> }

The above loop example will run 5 times total. Keep in mind that JavaScript startes indexing at 0 which is why this is the case. The loop will continue to run **WHILE** step is less than 5. Once step is equal to 5 the loop terminates. You must be careful when creating a loop to ensure that it can be satisfied (evaluate to false). Otherwise you will create an infinite loop which _will_ lead to all sorts of other problems.

## For loop

When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

## Example of an infinite loop

As I mentioned above earlier.. you must ensure that the loop eventually evaluates to _false_. The below code example is an ifinite loop.

> while (true) {
> console.log('Hello, world!');
> }

## List of loops in JavaScript

- [for statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for_statement)
  - A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
- [do...while statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#do...while_statement)
  - The do...while statement repeats until a specified condition evaluates to false.
- [while statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement)
  - A while statement executes its statements as long as a specified condition evaluates to true.
- [labeled statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#labeled_statement)
  - A label provides a statement with an identifier that lets you refer to it elsewhere in your program. For example, you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.
- [break statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#break_statement)
  - Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.
- [continue statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#continue_statement)
  - The continue statement can be used to restart a while, do-while, for, or label statement.
- [for...in statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for...in_statement)
  - The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements.
- [for...of statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for...of_statement)
  - The for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.
