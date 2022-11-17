# Class 8 Notes - Operators and loops

## Why this topic matters?

- Loops offer a quick and simple way to do something repeatedly.  

## Summary of topics

- assignment operators = assigns value to left operand based on value of right operand
- comparison operators = compares its operands and returns a logical value based on whether the comparison is true
- for loop = repeats until a specified condition evaulates to false
    for ([initialExpression]; [conditionExpression]; [incrementExpression])
        statement

    for (let step = 0; step < 5; step++) {
        // Runs 5 times, with values of step 0 through 4.
        console.log('Walking east one step');
    }

- while statement = executes its statments as long as a specified condition evaluates to true
    while (condition)
        statement
    
    let n = 0;
    let x = 0;
    while (n < 3) {
        n++;
        x += n;
    }