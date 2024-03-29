﻿# Sieve-of-Eratosthenes
# Definition 📜
_In mathematics, the **Sieve of Eratosthenes** is a simple, ancient **algorithm** for finding all **prime numbers** up to any given limit._

It does so by iteratively marking as composite (not prime) the multiples of each prime, starting with the first prime number, 2. The multiples of a given prime are generated as a sequence of numbers starting from that prime, with constant difference between them that is equal to that prime


# Overview 🎥

### History ⏳
The earliest known reference to the sieve (Ancient Greek: κόσκινον Ἐρατοσθένους, kóskinon Eratosthénous) is in Nicomachus of Gerasa's Introduction to Arithmetic,which describes it and attributes it to Eratosthenes of Cyrene, a Greek mathematician.

### Locution 💡
_"Sift the Two's and Sift the Three's,The Sieve of Eratosthenes.
When the multiples sublime,The numbers that remain are Prime._ ~Anonymous

### Prime number 🤔
_A **prime number** is a **natural number** greater than 1 that cannot be formed by multiplying two smaller natural numbers._

A natural number greater than 1 that is not prime is called a **composite number**. 

For example, 5 is prime because the only ways of writing it as a **product**, 1 × 5 or 5 × 1, involve 5 itself. However, 6 is composite because it is the product of two numbers (2 × 3) that are both smaller than 6. 

Primes are central in **number theory** because of the **fundamental theorem of arithmetic**: every natural number greater than 1 is either a prime itself or can be **factorized** as a product of primes that is unique **up to** their order._The property of being prime is called primality._

# Algorithm 🖥
The sieve of Eratosthenes can be expressed in **pseudocode**, as follows:
```
 Input: an integer n > 1. 

 Let A be an array of Boolean values, indexed by integers 2 to n,
 initially all set to true.

 for i = 2, 3, 4, ..., not exceeding √n:
   if A[i] is true:
     for j = i2, i2+i, i2+2i, i2+3i, ..., not exceeding n:
       A[j] := false.
 Output: all i such that A[i] is true.
```
This algorithm produces all primes not greater than n. It includes a common optimization, which is to start enumerating the multiples of each prime i from i^2. 

The **time complexity** of this algorithm is O(nloglogn), provided the array update is an O(1) operation, as is usually the case.

# Process 💻
### Compile 💾
_Run the **Prime.java** script, we must compile the code from an **integrated development environment** (IDE) for Java._
Or on command line with the following command:
```
javac Prime.java
```
If you compiled it in the IDE, the result should appear in the output window.

But if you compiled it in the terminal, you must run the file with the following commnad:

```
java Prime
```
### Result 🏆
The last number that generates the calculation of all prime numbers from 2 to 100 million will be:
 **99999989**
 
 **Note**⚠: You can modify the number of numbers you need to generate int the source code.


# Author ✒️

* **Nico Patalagua** - *Repository* - [Github](https://github.com/NicoPatalagua)

## If you liked this repostory 🎁
* Share it 📢
* Invite me a beer 🍺  
* Improve it 🤓.

---
## By 📌
[NicoPatalagua](https://www.instagram.com/nicopatalagua/) 😎
