#FizzBuzz


## How I solved it
1. First, I used a for loop to count from 1 to 10.

```javascript
for (let i = 1; i <= 100; i++) {
console.log(i);
}

- let i = 1 means start at 1.  
- i <= 100 means keep going until 100.  
- i++ means add 1 each time.  

2. To check if numbers are divisible by 3 or 5, I used the modulus operator (%):  
- i % 3 === 0 means the number divides evenly by 3.  
- i % 5 === 0 means the number divides evenly by 5.  

3. I checked if the number was divisible by both 3 and 5 first, otherwise "FizzBuzz" would not work correctly:

```javascript
if (i % 3 === 0 && i % 5 === 0) {
console.log("FizzBuzz");
}
```

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
 