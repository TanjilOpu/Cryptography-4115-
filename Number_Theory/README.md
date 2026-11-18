IT23044 Md Tanjil Islam Opu
https://jupyter.org/try-jupyter/lab/

# Number Theory for Cryptography

This repository contains Python implementations and basic explanations of important Number Theory concepts used in Cryptography.

## Topics Covered

### 1. Greatest Common Divisor (GCD)
GCD is the largest positive integer that divides two or more numbers without leaving a remainder. Euclid's Algorithm is used to calculate GCD efficiently.

### 2. Least Common Multiple (LCM)
LCM is the smallest positive integer that is exactly divisible by two or more numbers. It can be calculated using the GCD formula.

### 3. Modular Inverse
The modular inverse of a number `a` modulo `m` is a number `x` such that `(a * x) % m = 1`. It is an important operation in RSA encryption.

### 4. Sieve of Eratosthenes
An efficient algorithm for finding all prime numbers up to a given limit by eliminating multiples of prime numbers.

### 5. Prime Factorization
Prime factorization is the process of expressing a number as a product of its prime factors. It is an important concept in RSA cryptography.
# Day 2: Prime Numbers

## 📚 Topics Covered

### 1. Prime Numbers
A prime number is a natural number greater than 1 that has exactly two divisors: 1 and itself.

### 2. Distribution of Prime Numbers
Explores how prime numbers are distributed among natural numbers and different mathematical proofs showing that infinitely many primes exist.

### 3. Infinitude of Primes
Studies different proofs that there are infinitely many prime numbers, including Euclid's proof, Fermat numbers, and Filip Saidak's proof.

### 4. Dirichlet's Theorem
States that an arithmetic sequence `ak + b` contains infinitely many primes if `gcd(a, b) = 1`.

### 5. Prime Number Theorem
Explains the approximate distribution of prime numbers. The number of primes up to `x` is approximately `x / log(x)`.

### 6. Prime Number Conjectures
Introduces important unsolved mathematical problems, including the Goldbach Conjecture and Waring's Prime Number Conjecture.

### 7. Prime Number Generating
Explores mathematical expressions and polynomials that generate prime numbers, such as `n² + n + 41`.

### 8. Primality Testing
Introduces techniques for determining whether a given number is prime or composite.

### 9. Sieve of Eratosthenes
An efficient algorithm for finding all prime numbers up to a given limit by repeatedly eliminating multiples of prime numbers.

### 10. Trial Division
A basic primality-testing technique that checks whether a number is divisible by integers up to its square root.

### 11. Wheel Factorization
An optimization technique that reduces unnecessary divisibility checks by skipping numbers divisible by small primes.

### 12. Pseudoprimes
Composite numbers that satisfy certain mathematical properties of prime numbers, making them difficult to identify using simple tests.

### 13. Fermat's Primality Test
Uses Fermat's Little Theorem to determine whether a number is probably prime or composite.

### 14. Carmichael Numbers
Special composite numbers that satisfy Fermat's Little Theorem for every integer base, making them difficult cases for Fermat's primality test.

### 15. Euler's Totient Function
A number-theoretic function `φ(n)` that counts the positive integers up to `n` that are relatively prime to `n`.

### 16. Modular Arithmetic and Primitive Roots
Studies arithmetic under a modulus, including modular inverses, generators, multiplicative order, periodicity, and primitive roots.

### 17. Lucas's Theorem
Introduces a primality-testing method based on modular exponentiation and the prime factors of `n - 1`.

### 18. The n-1 Test
A primality-testing technique that uses partial factorization of `n - 1` to prove whether a number is prime.

### 19. Lucas-Lehmer Test
A specialized primality test used to determine whether certain Mersenne numbers are prime.

### 20. Mersenne Primes
Prime numbers of the form `2^n - 1`. They are important in the study of large prime numbers and perfect numbers.

### 21. Perfect Numbers
A positive integer equal to the sum of all its positive divisors except itself. Examples: 6, 28, 496, and 8128.

### 22. Antiprimes (Highly Composite Numbers)
Numbers that have more divisors than any smaller positive integer.

### 23. Fundamental Theorem of Arithmetic
States that every integer greater than 1 can be expressed uniquely as a product of prime numbers, apart from the order of factors.

### 24. Applications of Prime Numbers in Cryptography
Explains how prime numbers are used in cryptographic systems. Multiplying two large primes is easy, but factoring their product is computationally difficult.

### 25. Algebraic Number Theory and Ring Theory
Introduces advanced mathematical structures involving integers, prime elements, irreducible elements, and polynomial rings.

---

## 🎯 Learning Objectives

- Understand prime numbers and their mathematical properties.
- Learn different algorithms for generating prime numbers.
- Implement primality-testing techniques.
- Understand modular arithmetic and number-theoretic functions.
- Explore important prime number theorems and conjectures.
- Understand the role of prime numbers in modern cryptography.

## 🛠️ Practical Implementation

Topics suitable for programming practice:
- Prime Number Checking
- Sieve of Eratosthenes
- Prime Factorization
- GCD and LCM
- Modular Exponentiation
- Fermat Primality Test
- Euler's Totient Function
- Lucas-Lehmer Primality Test


