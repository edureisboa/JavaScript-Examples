# JavaScript-Examples

Write a function that returns the sum of two numbers.

Example

For param1 = 1 and param2 = 2, the output should be
solution(param1, param2) = 3.

Input/Output

[execution time limit] 4 seconds (js)

[input] integer param1

Guaranteed constraints:
-1000 ≤ param1 ≤ 1000.

[input] integer param2

Guaranteed constraints:
-1000 ≤ param2 ≤ 1000.

[output] integer

The sum of the two inputs.

[JavaScript] Syntax Tips

// Prints help message to the console
// Returns a string
function helloWorld(name) {
    console.log("This prints to the console when you Run Tests");
    return "Hello, " + name;
}

def add(param1, param2):
    return param1+param2
    
    
    
    
    
    
    
    
#ANSWER    
param1: 1;
param2: 2;
function solution(param1, param2){
        return (param1+param2);
}
solution(1,2);  // output in console 3













Given a year, return the century it is in. The first century spans from the year 1 up to and including the year 100, the second - from the year 101 up to and including the year 200, etc.

Example

For year = 1905, the output should be
solution(year) = 20;
For year = 1700, the output should be
solution(year) = 17.
Input/Output

[execution time limit] 4 seconds (js)

[input] integer year

A positive integer, designating the year.

Guaranteed constraints:
1 ≤ year ≤ 2005.

[output] integer

The number of the century the year is in.

[JavaScript] Syntax Tips

// Prints help message to the console
// Returns a string
function helloWorld(name) {
    console.log("This prints to the console when you Run Tests");
    return "Hello, " + name;
}

#ANSWER 
function solution(year) { 
    return Math.ceil(year/100)
}
