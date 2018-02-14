## Algorithms Hands On

---

## Search Algorithm 

> A ***search algorithm*** is the step-by-step procedure used to locate specific data among a collection of data.

---
## Search Examples in Computers

- Amazon Search for Products
- Netflix Search for movies.
- Google Search for anything in the internet.

---

## What is Flowchart?

> A Flowchart is a type of diagram used to represent algorithms.

+++

### Flowchart Shapes

<img src="assets/image/flowchart-shapes.png" alt="Flowchart Shapes" width="500px" height="450px">

+++

### Quiz: Match flowchart an Algorithm

<img src="assets/image/flowchart-quiz.png" alt="Match flowchart to algorithms" width="600px" height="400px">

## What are variables?

---

## How to represent collection of items?


---
## Problem : Check if a number is prime

Let's say we have all prime numbers stored in a collection `primes`

```java

Array primes = [2, 3, 5, 7, 11,
				13, 17, 19, 23, 29,
				31, 37, 41, 43, 47,
				53, 59, 61, 67, 71, 
				73, 79, 83, 89, 97]
```
+++

@title[Check if a number is prime contd..]

which can be looked up using : 

```java
primes[0] = 2
primes[1] = 3
....
primes[i] = n

where 0 <= i <= 25

```
Now, Given any number N ( N < 100), tell if the number isPrime by searching the array `primes`

---

## Sequencial Search Algorithm

<img src="assets/image/prime-sequential-search.png" alt="Sequential Search Algorithm" width="500px" height="450px">

---
## Binary Search Algorithm

<img src="assets/image/prime-binary-search.png" alt="Binary Search Algorithm" width="650px" height="500px">

