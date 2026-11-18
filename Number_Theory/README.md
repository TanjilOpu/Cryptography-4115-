IT23044 Md Tanjil Islam Opu
https://jupyter.org/try-jupyter/lab/
# Number Theory & Cryptography Foundations

This repository contains lecture slides, notes, and Python implementations covering the mathematical foundations of Number Theory and Public-Key Cryptography.

---

## 📚 Course Topics Breakdown

### 📅 Day 0: Foundations of Integers & Modular Arithmetic
* **Number Systems & Inverse Operations**
  * Natural numbers, integers, and rational numbers
  * Limitations of subtraction and division in basic sets
  * Role of Number Theory in high-speed computing and cryptography
* **Divisibility**
  * Formal definition of divisibility ($b \mid a$)
  * Linear combinations and divisibility properties ($c \mid a \text{ and } c \mid b \implies c \mid (a \pm b)$)
* **Division with Remainders**
  * Quotient ($q$) and remainder ($r$) theorem ($a = q \times b + r$, $0 \le r < b$)
  * Connection between remainders and divisibility
* **Modular Arithmetic**
  * Congruence relations ($a \equiv b \pmod m$)
  * Preservation of congruence under addition and multiplication
  * Applications: Finding last digits of large powers (e.g., $99^{99} \bmod 100$) and divisibility rules (divisibility by 3)
* **Operations on Remainders**
  * Modular addition and multiplication tables (e.g., modulo 6 vs. modulo 7)
  * Modular subtraction and introduction to modular division

---

### 📅 Day 1: Euclidean Algorithms, Diophantine Equations & Theorems
* **Greatest Common Divisor (GCD)**
  * Definition, properties, and real-world applications (fraction reduction, modular inverses)
  * Naive algorithm and time complexity analysis ($O(\min(a,b))$)
* **Euclid’s Algorithm**
  * Euclid's Lemma ($\gcd(a, b) = \gcd(b, a \bmod b)$)
  * Iterative and recursive implementations
  * Logarithmic runtime analysis ($O(\log a + \log b)$)
* **Extended Euclid’s Algorithm**
  * Bézout's identity ($ax + by = \gcd(a, b)$) as a certificate of optimality
  * Recursive derivation and coefficient calculation
* **Least Common Multiple (LCM)**
  * Definition and naive computation
  * Efficient calculation via GCD: $\text{lcm}(a, b) = \frac{a \cdot b}{\gcd(a, b)}$
* **Linear Diophantine Equations**
  * Existence condition: $ax + by = c$ has integer solutions iff $\gcd(a, b) \mid c$
  * Finding a particular solution $(x_0, y_0)$ using Extended Euclid's Algorithm
  * Generating all general integer solutions: $x = x_0 + t\frac{b}{d}, \quad y = y_0 - t\frac{a}{d}$
* **Modular Division & Multiplicative Inverses**
  * Existence and uniqueness of modular inverses ($\gcd(a, n) = 1$)
  * Computing $b / a \pmod n$ via Extended Euclid's Algorithm
* **Cryptography Overview**
  * Symmetric vs. Public-Key Cryptography (Alice, Bob, and Mallory/Eve)
  * Key exchange and RSA encryption motivation
* **Chinese Remainder Theorem (CRT)**
  * Dependent vs. independent remainders ($\gcd(a, b) = 1$)
  * Constructive proof and algorithm for solving systems of congruences
  * Extension to multiple pairwise coprime moduli and large-integer arithmetic
* **Modular Exponentiation & Euler's Theorem**
  * Fast Modular Exponentiation (Binary Exponentiation / Exponentiation by Squaring in $O(\log e)$)
  * **Fermat’s Little Theorem:** $a^{p-1} \equiv 1 \pmod p$ for prime $p \nmid a$
  * **Euler’s Totient Function ($\phi(n)$):** Counting coprime integers, formulas for $\phi(p)$ and $\phi(pq)$
  * **Euler’s Theorem:** Generalization $a^{\phi(n)} \equiv 1 \pmod n$ for $\gcd(a, n) = 1$

---

### 📅 Day 2: Prime Numbers & Primality Testing
* **Introduction & Distribution of Primes**
  * Fundamental definitions and the Fundamental Theorem of Arithmetic
  * Proofs of the infinitude of primes (Euclid's proof, $n!+1$, divergence of Harmonic series, Goldbach's Fermat numbers proof, Filip Saidak's proof)
  * Dirichlet's Theorem on arithmetic progressions ($ak + b$)
  * The Prime Number Theorem ($\pi(x) \sim \frac{x}{\ln x}$)
* **Famous Conjectures & Patterns**
  * Goldbach's Conjecture and Waring's Prime Number Conjecture
  * Twin Prime Conjecture, Chebyshev's bias, and Prime Spirals
  * Prime-generating polynomials (e.g., Euler's $n^2 + n + 41$)
* **Primality Testing & Pseudoprimes**
  * Sieve of Eratosthenes and Wheel Factorization (Wheel of 30)
  * Fermat Primality Test and Fermat Pseudoprimes
  * **Carmichael Numbers:** Composite numbers passing Fermat's test for all bases (e.g., 561, 1105, 1729)
* **Advanced Theorems & Special Primes**
  * Primitive roots, order, and periodicity modulo $p$
  * Lucas's Theorem, the $n-1$ test, and the Lucas-Lehmer test
  * **Mersenne Primes** ($2^n - 1$) and their connection to **Perfect Numbers**
  * **Antiprimes (Highly Composite Numbers):** Divisor function $d(n) = \prod(a_i + 1)$ and Ramanujan's properties

---

## 🛠️ Files in this Repository
* `Day 0.pdf` — Lecture slides on Divisibility and Basic Modular Arithmetic
* `Day 1.pdf` — Lecture slides on GCD, Diophantine Equations, CRT, and Euler's Theorem
* `Day 2.pdf` — Lecture slides on Prime Numbers, Conjectures, and Primality Testing
* `number_theory_lab.ipynb` — Jupyter Notebook containing executable Python implementations
```[cite: 1, 309, 466]
