`for` is the key word for a "for loop"

`for (var i =0 ; i <= 12; i = i + 1) {`
    `document.write(i);`
`}`

    This example is a loop. the condition is a counter that counts to 10. the result would write "0123456789" to the page

To break down above example...
    `var i = 0;` this is the initialization that creats the variable named "i"
    `i < 10;` The condition runs the loop until the counter reaches 10 since the value of i is set to 10.
    `i++` update... everytime the loop has run the statement in the curly braces, it adds one to the counter. you can count down as well using `i--`

["this", "is", "an", "array"]

While LOOPS!

while( count ==='' || isNaN(count)){
    count = prompt('Please enter a number. How many do you want')
}

`||` <=== THIS MEANS "OR"
`===` this is `true` or `false` also strict equal to. this operator compares two values ato check both data type and value are the same.
`==` is equal to
`!=` is not equal to
`!==` same as its counter only checks to see if they are not the same 
`>` Greater than
`<` less than
`>=` greater than or equal
`<=` less than or equal

`&&` tests more then one condition.
        ex. `( (2<5) && (3>=2) ) <==== returns true
        if both expressions return true then the whole expression returns true. 
        if one or both return false then the whole expression returns false.

`||` Tests atleast one condition.
        ex. `( (2<5) && (3>=2) ) <===== returns true
        if either expression returns true then the whole expression is true.
        if both return false then the whole expression is false.

`!` Logical Not, this operator takes a single Boolean value and inverts it
        ex. `!(2<1) <=== returns true
        this reverses the state of an expression. It returns true when without the "!" it would be false.
        ex !true returns false and vice versa.

170-173, 176 pages in book for review of Loops!

Keywords for loops!

break
This keyword causes the termination of the loop and tells the interpreter to go onto the next statement of code outside of the loop. (You may also see it used in functions.)

continue
This keyword te lls the interpreter to continue with the current iteration, and then check the condition again. (If it is true, the code runs again.)

LOOPS & ARRAYS
Loops are very helpful when dealing with arrays if you want to run the same code for each item in the array. For example, you might want to write the value of each item stored in an array into the page. You may not know how many items will be in an array when writing a script, but. when the code runs, it can check the total number of items in a loop. That figure can then be used in the counter to control how many times a set of statements is run. Once the loop has run the right number of t imes, the loop stops.

PERFORMANCE ISSUES
It is important to remember that when a browser comes across JavaScript, it will stop doing anything else until it has processed that script. If your loop is dealing with only a small number of items, this will not be an issue. If, however your loop contains a lot of items, it can make the page slower to load. If the condition never returns false, you get what is commonly referred to as an infinite loop. The code will not stop running until your browser runs out of memory (breaking your script). Any variable you can define outside of the loop and that does not change within the loop should be defined outside of it. If it were declared inside the loop, it would be recalculated every time the loop ran, needlessly using resources.

