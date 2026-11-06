# p-adic Analysis

My solutions for the [p-adic Analysis](https://eulercircle.com/classes/p-adic-analysis/) course at Euler Circle (spring 2026). This course builds the p-adic numbers, a completion of the rationals where numbers are close when their difference is divisible by a high power of p, and then redoes analysis and algebra there: convergence, Hensel's lemma, p-adic power series, Newton polygons, field extensions, and the profinite integers.

I also wrote an expository paper on 2-adic numbers in cryptography as a final project.

## Problem Sets

| File | Date | Topics |
|------|------|--------|
| p-adic Analysis 1 | Apr 2026 | Metric spaces: triangle inequality in R^n via Cauchy-Schwarz, the metric \|e^x - e^y\| on R is not complete, the l^p metrics tend to the max metric, uniqueness of limits, Q is not complete under the p-adic metric, continuity iff preimages of open sets are open |
| p-adic Analysis 2 | Apr 2026 | p-adic expansions (1/7 in Z_3), lifting sqrt(-1) digit by digit in Z_5 and showing it does not exist in Z_7, unique decomposition x = p^n * r * u in Q_p, the product formula for absolute values on Q, a rational is a square iff it is a square in R and in every Q_p |
| p-adic Analysis 3 | Apr 2026 | Convergence in Q_p: n^n and 1/n! diverge, (1+p)^(p^n) -> 1 and (p-1)^(p^n) -> -1 for odd p, every element of Q_p is a limit of reciprocals 1/n, a sequence of rationals converging to pi in R and to 0 in every Q_p |
| p-adic Analysis 4 | Apr 2026 | Hensel's lemma: computing sqrt(-3) in Q_7, n-th roots of numbers that are 1 mod p, x^2 + x + a has a root in Z_2 iff a is even, counting the roots of a quartic in Z_7, a polynomial with roots in R and every Q_p but none in Q, Hensel's lemma for power series |
| p-adic Analysis 5 | May 2026 | p-adic analysis: the p-adic logarithm (log(-5/4) = log(5/4) since log(-1) = 0), e^p is not a p-th power in Z_p, a continuous function with derivative 0 everywhere that is not constant, periodic analytic functions are constant, the intermediate and mean value theorems fail p-adically |
| p-adic Analysis 6 | May 2026 | Newton polygons, when binom(sqrt(2), p) is p-integral, degree and ramification index of the extensions of Q_5 from x^2 - 2 (unramified) and the Eisenstein polynomial x^2 - 5 (totally ramified) |
| p-adic Analysis 7 | May 2026 | C_p: a bounded sequence of roots of unity with no Cauchy subsequence, closed balls are open, nested closed balls in a finite extension of Q_p intersect; Newton polygons of power series, including one that is only a vertical ray |
| p-adic Analysis 8 | May 2026 | Profinite integers Z-hat: 2 is neither a zero divisor nor a unit, the idempotents x^2 = x in Z-hat (2^aleph_0 of them), solving x^3 = x in Z_m via the product of Z_p over p dividing m, a series converges in Z_m iff its terms go to 0 |
| p-adic Analysis 9 | May 2026 | Linear recurrences and local methods: finding every n with a_n = 1 for a_n = 3a_(n-1) - 5a_(n-2) by 3-adic interpolation (n = 0, 2, 6), a quadratic form with no nontrivial zeros over Q, Q_3 or Q_5, why a Hensel argument fails at p = 2, a sieve estimate for n and n+2 with no small prime factors |

## Expository Paper

**2-adic Numbers in Cryptography** (May 2026) -- how feedback with carry shift registers (FCSRs), which generate keystreams for stream ciphers, are described naturally by 2-adic arithmetic. Reading the output bits as a 2-adic integer, the paper proves that every FCSR output is a rational number p/q whose denominator is the register's connection integer. Topics include:

- Stream ciphers: encrypting by adding a keystream mod 2
- 2-adic integers, and infinite bit strings as elements of Z_2 (111... = -1, 1010... = -1/3)
- Linear feedback shift registers (LFSRs), and why being linear makes them predictable
- FCSRs: taps, the carry value, and the connection integer q
- Main theorem: an FCSR's output is the 2-adic expansion of p/q, proved by telescoping the carry terms
- Worked example: connection integer q = 5 produces 11001100... = -1/5
- Security: 2-adic span and rational approximation attacks

I also gave a presentation on the paper, "From carries to stream ciphers" (in the `p-adic Cryptography Presentation` folder).

## Course Info

- **Course page:** https://eulercircle.com/classes/p-adic-analysis/
- **Duration:** Spring 2026 (April -- May)
- **Format:** Weekly lectures + problem sessions with written problem sets
