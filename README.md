# Integer sequences from the "Online Encyclopedia of Integer Sequences" ([OEIS](https://oeis.org/))

This repository is where I'll share the code that I made to generate some of the sequences in the OEIS.

### Table of Contents
+ **[A000010](https://oeis.org/A000010)** **Euler's totient function phi(n)**: counts numbers <= n and prime to n.
  - Currently available in **Python** / **C** / **C++**. Demonstration with 0.1 delay: 
  <p align="center">
    <img src="https://media.giphy.com/media/LRZWOzi1JKhYd9V4KP/giphy.gif">
  </p>

---

+ **[A000032](https://oeis.org/A000032)** **Lucas numbers** beginning at 2: L(n) = L(n-1) + L(n-2), L(0) = 2, L(1) = 1.
   - Currently available in **Python** / **C** / **C++** (containing both a recursive and bottom-up approach).

---

+ **[A000040](https://oeis.org/A000040)** **The prime numbers**.
  - Currently available in **Python** / **C** / **C++** (using [Sieve of Eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes) algorithm). Demonstration with 0.1 delay:
  <p align="center">
    <img src="https://media.giphy.com/media/RgzKjn78GsdWGenYt8/giphy.gif">
  </p>
  
---

+ **[A000043](https://oeis.org/A000043)** **Mersenne exponents**: primes p such that 2^p - 1 is prime. Then 2^p - 1 is called a Mersenne prime.
   - Currently available in **Python** (using [Lucas-Lehmer primality test](https://en.wikipedia.org/wiki/Lucas%E2%80%93Lehmer_primality_test)).

---

+ **[A000045](https://oeis.org/A000045)** **Fibonacci numbers**: F(n) = F(n-1) + F(n-2) with F(0) = 0 and F(1) = 1.
  - Currently available in **Python** / **C** / **C++** (containing both a recursive and a bottom-up approach). Demonstration with 0.1 delay:
  <p align="center">
    <img src="https://media.giphy.com/media/UpDraH9RuxjXyz5qy4/giphy.gif">
  </p>
  
---

+ **[A000217](https://oeis.org/A000217)** **Triangular numbers**: a(n) = binomial(n+1,2) = n(n+1)/2 = 0 + 1 + 2 + ... + n.
  - Currently available in **Python** (containing both a arithmetic and a binomial method) / **C** / **C++**. Demonstration with 0.1 delay:
  <p align="center">
    <img src="https://media.giphy.com/media/dVbo5vn5ktHLJig3nu/giphy.gif">
  </p>
  
---

+ **[A007318](https://oeis.org/A007318)** **Pascal's triangle** read by rows: C(n,k) = binomial(n,k) = n!/(k!*(n-k)!), 0 <= k <= n.
  - Currently available in **Python**.

---
