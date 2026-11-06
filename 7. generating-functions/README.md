# Generating Functions

My solutions for the [Generating Functions](https://eulercircle.com/classes/generating-functions/) course at Euler Circle (fall 2026). This course treats generating functions as a language for counting: building them directly from combinatorial constructions with the symbolic method, using exponential generating functions for labeled objects, inverting them to count trees, and applying them to probability.

## Problem Sets

| File | Date | Topics |
|------|------|--------|
| Generating Functions 1 | Sep 2026 | Symbolic method for unlabeled classes: sequences, multisets (M(z) = product of P(z^(2^n))), cycles via Burnside's lemma, unimodal permutations (2^(n-1)), compositions into 1s and 2s give Fibonacci numbers, partial sums via A(z)/(1-z), ternary strings where a 2 cannot follow a 0 (1/(1-3z+z^2)) |
| Generating Functions 2 | Oct 2026 | Partitions and compositions: n*p_n = sum sigma(j)*p_(n-j) by log-differentiation, compositions into k parts of size at most r, Euler's pentagonal number theorem and the partition recurrence, the product of (1 - 10^(-n)) has only the digits 0, 1, 8, 9, lattice points of Z^d within squared distance n |
| Generating Functions 3 | Oct 2026 | Lagrange inversion for trees whose nodes have 0, 1 or 2 children, the same trees by substitution into binary trees (M(z) = (1 - z - sqrt(1 - 2z - 3z^2))/(2z)), pointing as differentiation with combinatorial product and chain rules, indecomposable permutations (I(z) = 1 - 1/P(z)), first-return lattice walks in Z^2 |
| Generating Functions 4 | Oct 2026 | Exponential generating functions and labeled constructions: rankings with ties (1/(2 - e^z)), set partitions with no singletons (e^(e^z - 1 - z)), iterated set partitions, recovering an OGF from its EGF with an integral, permutations whose cycle lengths are all divisible by k ((1 - z^k)^(-1/k)), permutations that have a square root |
| Generating Functions 5 | Oct 2026 | Probability with generating functions: words using exactly k of r letters (Stirling numbers of the second kind), E(B) = sum P(B > n), a generalized birthday problem (about 88.74 people until some birthday occurs 3 times), permutations with sigma^m = id, only-even and only-odd cycles, the 100 prisoners problem (success about 0.3118, tending to 1 - log 2) |
| Generating Functions 6 | Oct 2026 | Parking functions: counting them ((n+1)^(n-1)) with a circular argument, bijections with labeled trees and rooted forests (Cayley's theorem), labeled and binary hierarchies (M(z) = 1 - sqrt(1 - 2z)), partial functions via functional graphs ((n+1)^n), a bijection between permutations with k minima and permutations with k cycles |

## Paper Summary

**Generating Functions Paper Summary** (Oct 2026) -- a short preview of my expository paper for this course, on how many children the root of a large random tree has. Topics include:

- Plane trees: T(z) = z/(1 - T(z)), with a bivariate generating function marking the root's degree; in the limit, P(root has k children) = k/2^(k+1)
- Cayley trees (labeled, children unordered): T(z) = z*e^(T(z)); in the limit, P(root has k children) = e^(-1)/(k-1)!
- Simply generated trees T(z) = z*Phi(T(z)), following Flajolet and Sedgewick: one limiting formula for the root degree that recovers both cases above

## Course Info

- **Course page:** https://eulercircle.com/classes/generating-functions/
- **Duration:** Fall 2026 (in progress)
- **Format:** Weekly lectures + problem sessions with written problem sets
