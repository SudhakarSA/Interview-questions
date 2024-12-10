# Buddy Deals
1. Is Node Js running in sigle core? then explain
2. How to do Serach text in Mongodb
3. Difference between filter and query in Elastic search 
4.  

# HID Global
1. How Nodejs handles cuncurrency
2. Explain Node.Js event loop
3. How do you write APIs like use of swagger or postman

# Content stack
1. How do you use redis for caching
2. Generic type in type script
3. mongoDB scaling
4. Which database will be better for social media application
5. Create custom stream in nodejs

# Msys

1. Program to count occurance of each letters in a string. Ignore space
2. How to define routes in express. they asked import statement
3. How do you use redis
4. Queuing system like rabbitmq
5. Read content of a file and append something and new content to same file
6. Callback hell
7. Deference between promise and async/await
8. What if i not use await keyword
9. Closure in Javascript
10. ES5 and Es6. Any advantages in ES6
11. Clustering in mongodb
12. Execution of bellow code
```js
    setTimeout(() => {
        console.info('Execution of Timeout Callback Function'); 
    }, 10);
    setImmediate(() => {
        console.info('Execution of Immediate Callback Function'); 
    });
    process.nextTick(() => {
        console.info('Execution of NextTick Callback Function');
    })
    console.info('Execution of Main Module Ends');
```
13. Explain Event loop
14. Deference between $in and $all in mongodb
15. const and object.freeze
16. How to ignore some routes in express middleware
17. 

# CloudSense
```
Write a boolean returning function that takes 2 string arguments - 
filename and pattern - that returns whether the filename matches the
 pattern. The pattern is in the form used in dos/windows/unix shell 
 where * matches any number of characters (0-n).
 
 Filename, pattern -> expected output
'abc', 'a*' -> true
'abc', '*bc' -> true
'abc', 'a*c' -> true
'text.json', 'sample*' -> false
'text.json', 'json*' -> false
'asdsasseacdvscg', '*vscg' -> true
'asdsasseacdvscg', 'abc*' -> false
'asdsasseacdvscg', 'a*s*v*g' -> true
'asdsasseacdvscg', 'a*s*m*g' -> false
'asdsasseacdvscg', '*ds*vs*' -> true
'asdsasseacdvscg', 'a*g*' -> false
'asdsasseacdvscg', '**c*g' -> true

js code to match pattern. not use regex
```
# Coverforce
```
/**
 * Problem: You're tracking the daily price of a stock and need to figure out how many consecutive days, including today, the stock's price has been less than or equal to today's price. This is called the "span."
Each time you get a new price, you return the span of that day.
Class StockSpanner() { 
….
    Func next(int price) //needs to be implemented.
}
Example:
Input:
StockSpanner spanner = new StockSpanner(); 
spanner.next(100) // Returns 1 
spanner.next(80) // Returns 1
 spanner.next(60) // Returns 1 
spanner.next(70) // Returns 2 
spanner.next(60) // Returns 1 
spanner.next(75) // Returns 4 
spanner.next(85) // Returns 6
Output:
[1, 1, 1, 2, 1, 4, 6]

*/

js code for this. i need solution in optimized way with time and space complexity
```
# Infosys

# Ease Commerce

# TCS
1. Event loop
2. Callback hell
3. difference between promise.all and promise.race
4. How would you handle high volume requests
5. difference between import and require
6. How middleware works
7. How do you define database schema
8. State of promises
9. Await usecase

# Cloud destination
1. WHat is API in general
2. What is non blocking
3. How Does JavaScript Work Behind the Scenes
```
Input
let str = `hihelloworldwelcom`;

Output
Find occurrence of each character
```

```
let amounts = [1200, 400, 300, 2000, 1500];
let maxWithdrawLimit = 400;

You are given an array amounts where each element represents the initial amount of money in a person’s wallet. Another variable maxWithdrawLimit specifies the maximum amount a person can withdraw in a single transaction. There are 5 people in a queue, and they take turns withdrawing money one by one. If a person’s remaining balance becomes 0 or negative after a withdrawal, they leave the queue.

Task:
Simulate this withdrawal process and produce two output arrays:

Exit order: The order in which the people leave the queue.
Withdrawal queue: The sequence of people’s indexes who make withdrawals during the process.

The output should be two array that have order of exit and withdrawal queue
exitOrder = [2, 3, 1, 5, 4]
queue = [1, 2, 3, 4, 5, 1, 4, 5, 1, 4, 5, 4, 5, 4]

```

# Clarity TTS
1. Why nodejs single threaded
2. What is Event loop
3. Difference between Process.nextTick() and setImmediate()
4. How to handle CPU intensive task in nodejs
5. What if concurrent CPU intensive requests incoming? should we create separate worker thread for each and every task
6. How to handle memory leak issue in nodejs
7. what is middleware
8. how user authendicated in nodejs
9. Sharding in mongodb
10. replicaset in mongodb
11. Program to find second largest integer in array
12. Remove those values if they are duplicated in array
```
Input: [1,2, 3, 4, 1, 5, 5, 6]
Output: [2, 3, 4, 6]
```

# Altimetrik interview questions
1. How would you optimize nodejs performance
2. What are the types of communication protocol in microservices
3. How to fix memory leak issue in nodejs
4. What are the phase event loops
5. what is callback
6. Indexing in SQL
7. What is composite index in SQL
8. Table create query and alter query
9. Premitive and non premitive type in nodejs
10. Output of following
```js
const [a = 1] = [];
const { b = 2 } = { b: undefined };
const { c = 2 } = { c: null };    
console.log(a, b, c)

let a, b, rest;
 [a, b, ...rest] = [10, 20, 30, 40, 50];
 console.log(rest);
```
```js
// Implement a function that takes multidimensional arrays as input  and return single dimensional array. Result must contains alternative elements from each array item.

let input = [ [1,2,3], [22,33,44,99], [66,77], [6,7,8,9] ]

// output : [1,22,66,6,2,33,77,7,3,44, 8,99,9]
 
 
 function convertArray(arr) {
   let output = [];
   
   
   for (let i = 0; i < arr.length; i++) {
     
     let j = 0;
     
     while (j < arr.length) {
       if (arr[j].length > i) {
         output.push(arr[j][i]);
       
       }
        
      j++;
     }
   }
   
   return output
 }
 
 console.log(convertArray(input))
```
11. What are the services you use in AWS
12. Purpose of AWS S3
13. What is EC2
14. How would integrate 3rd party service with your nodejs service
15. What is oauth and how would you implement it
16. OAuth Grant Types
