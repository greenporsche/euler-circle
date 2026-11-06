# Infinite Series

My solutions for the [Infinite Series](https://eulercircle.com/classes/infinite-series/) course at Euler Circle (winter 2026). This course is about techniques for evaluating infinite series and products in closed form -- going far beyond the geometric and telescoping series from calculus into complex analysis, Fourier methods, special functions, and algebraic number theory.

## Problem Sets

| File | Date | Topics |
|------|------|--------|
| Infinite Series 1 | Jan 2026 | Telescoping via partial fractions, complex exponential method (summing cos(n*theta)/2^n using Euler's formula), arctan telescoping (sum = 3*pi/4), computing sum of (n+1)^3/n! = 15e, Fibonacci generating function S(x) = x/(1-x-x^2) |
| Infinite Series 2 | Jan 2026 | Zeros of sin(z) via complex exponentials, Riemann zeta function manipulations (relating sums over odd terms and alternating sums to zeta(k)) |
| Infinite Series 3 | Jan 2026 | Dirichlet kernel derivation (D_N(t) = sin((N+1/2)t) / (2*sin(t/2))), Fourier series integration |
| Infinite Series 4 | Feb 2026 | Irrationality of the prime reciprocal sum (via binary expansion and prime gaps), arccos(1/3)/pi is irrational (via Niven's theorem), algebraic integers, ring quotients, integral elements of number fields |
| Infinite Series 5 | Feb 2026 | Continued fractions, convergents |
| Infinite Series 6 | Feb 2026 | Infinite products: product of (n^2-1)/n^2 = 1/2, constructing sequences where the sum diverges but the product converges, rectangle packing recurrences yielding Wallis-type products (limiting aspect ratio = pi*r_1/2), evaluating a product via Riemann sums and the Gamma function reflection formula (final answer: 2) |
| Infinite Series 7 | Feb 2026 | Thue-Morse sequence (not periodic, no block repeated three times in a row), deterministic finite automata, 2-automatic sequences: Thue-Morse, paper-folding, parity of the number of factors of 2, Rudin-Shapiro, Baum-Sweet; k-automatic iff k^m-automatic |
| Infinite Series 8 | Mar 2026 | Continued fractions: rationals have finite expansions (via the Euclidean algorithm), eventually periodic continued fractions are quadratic irrationals, sqrt(x) = 1 + (x-1)/(2 + (x-1)/(2 + ...)), a continued fraction for log(2) via the integrals of x^n/(1+x) on [0, 1] |
| Infinite Series 9 | Mar 2026 | Nested radicals: p-th-root radicals solving x^p - x - k = 0 (monotone bounded sequences), radicals from functional equations like f(x)^2 = x + f(x+1), attracting vs. repelling cycles via the chain rule, power towers x^x^x... = -W(-log x)/log x via the Lambert W function and when they converge |

## Expository Paper

**Dobinski's Formula** -- two proofs of Dobinski's formula B_n = (1/e) * sum k^n/k! for the Bell numbers, and what it means probabilistically. Topics include:

- Bell numbers as counts of set partitions, and as sums of Stirling numbers of the second kind
- The exponential generating function sum B_n x^n/n! = e^(e^x - 1)
- An analytic proof (expanding e^(e^x - 1) and comparing coefficients) and a combinatorial proof (counting functions [n] -> [k])
- Bell numbers as the moments of a Poisson(1) random variable
- Estimating Bell numbers by random sampling

## Course Info

- **Course page:** https://eulercircle.com/classes/infinite-series/
- **Duration:** Winter 2026 (January -- March)
- **Prerequisite:** Calculus
- **Format:** Weekly lectures + problem sessions with written problem sets
