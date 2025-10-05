# FizzBuzz


## How I made it
1. First, I used a for loop.

```javascript
for (let i = 1; i <= 100; i++) {
console.log(i);
}
```

- let i = 1 means start at 1.  
- i <= 100 means keep going until 100.  
- i++ means add 1 each time.  

2. Also, I used %:  
- i % 3 === 0 means the number divides evenly by 3.  
- i % 5 === 0 means the number divides evenly by 5.  

3. I checked if the number was divisible by both 3 and 5 first :

```javascript
if (i % 3 === 0 && i % 5 === 0) {
console.log("FizzBuzz");
}
```
so I could complete the final code.
I tested it on Eloquent Javascript and it worked well.

## Final Code

```javascript
for (let i = 1; i <= 100; i++) {
if (i % 3 === 0 && i % 5 === 0) {
console.log("FizzBuzz");
} else if (i % 3 === 0) {
console.log("Fizz");
} else if (i % 5 === 0) {
console.log("Buzz");
} else {
console.log(i);
}
}
```
 