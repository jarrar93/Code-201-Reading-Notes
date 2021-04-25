# summary:

*  ![](https://www.jungledisk.com/blog/content/images/blog/div-soup-vs-semantic-html.png)

## Structural markup:
 the elements that you can use to
describe both headings and paragraphs
## Semantic markup:
 which provides extra information; such
as where emphasis is placed in a sentence, that something
you have written is a quotation (and who said it), the
meaning of acronyms, and so on.



![](https://www.schudio.com/wp-content/uploads/2016/10/html-headings.png?x43850)

## (P)
To create a paragraph, surround
the words that make up the
paragraph with an opening
tag and closing  tag .

## (sup)&(sub):
![](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-11-07-at-1.38.26-PM.png )

The< blockquote > element is
used for longer quotes that take
up an entire paragraph. Note
how the < p> element is still
used inside the < blockquote>
element.

ARRAYS

An array is a special type of variable. It doesn't just store one value; it stores a list of values. You should consider using an array whenever you are working with a list or a set of values that are related to each other.

Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold. If you don't know how many items a list will contain, rather than creating enough variables for a long list (when you might only use a small percentage of them), using an array is considered a better solution .

 (Links to an external site.)CREATING AN ARRAY :
You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array. This technique for creating an array is known as an array literal. It is usually the preferred method for creating an array. You can also write each value on a separate line: colors= ['white', 'black', 'custom'];

 (Links to an external site.)Operators and Loops
A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. The following table describes the comparison operators in terms of this sample code:

Operator	Description
Equal (==)	Returns true if the operands are equal
Not equal (!=)	Returns true if the operands are not equal.
Strict equal (===)	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.
Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type.
Greater than (>)	Returns true if the left operand is greater than the right operand.
Greater than or equal (>=)	Returns true if the left operand is greater than or equal to the right operand.
Less than (<)	Returns true if the left operand is less than the right operand.
Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand.
 (Links to an external site.)Loops and iteration
## for statement
![](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([ initial Expression]; [ condition Expression]; [ increment Expression]) statement

When a for loop executes, the following occurs: 1.The initializing expression initial Expression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables. 2. The condition Expression expression is evaluated. If the value of condition Expression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.) 3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements. 4. If present, the update expression increment Expression is executed. 5. Control returns to Step 2.

## while statement

![](https://www.w3resource.com/w3r_images/javascript-do-while.gif)

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition) statement

If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ .. . }) to group those statements.

 (Links to an external site.)loops:
loops check a condition, if it's true, a code block will run, then the condition will be checked again and if it's still true, the code block will run again and again until the condition is false. There are three common types of loops, for, while, and do while:

for loop for
A for loop is a repetition control structure that allows you to write a loop that needs to run a specific number of times. for example, if you want to execute a loop for 12 time, the code will be like that:

for( i = 0; a < 12; i++ )

while loop while
you can use it if you don't know how many times the code should run, the code will continue to loop as long as the condition is true.


