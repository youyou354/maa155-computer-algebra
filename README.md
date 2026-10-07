# MAA155 — Computer algebra with applications (Mälardalen University, spring 2025)

My solutions from the Erasmus semester in Västerås: the INL1 problem sets (by hand and in Sage) and two Sage
projects. (Private archive: the assignment texts and the lecture notes belong to the course and are not included.)

| Item | What it is |
|------|-----------|
| [INL1 problem 1](INL1/problem1-integer-division-DIVINT.pdf) | `DIVINT`: integer division with remainder, by repeated subtraction, all sign cases |
| [INL1 problem 2](INL1/problem2-ideals-and-divisibility.pdf) | ideals of ℤ, the intersection of two ideals, transitivity of divisibility |
| [INL1 problem 4](INL1/problem4-polynomial-division-DIVPOL-EXTEUC.pdf) | `DIVPOL` and `EXTEUC` over ℚ[x] |
| [INL1 problem 5](INL1/problem5-gcd-in-two-variables.pdf) | gcd in ℤ[X, Y], by hand and checked with Sage |
| [INL1 problem 6](INL1/problem6-relations-and-monomial-orders.pdf) | relations, sets in the plane, admissible monomial orders |
| [INL1 problem 7](INL1/problem7-groebner-basis-warm-up.pdf) | a small Gröbner basis by hand, then the same system solved in Sage |
| [INL1 problem 10](INL1/problem10-openmath-encoding.pdf) | an equation encoded in OpenMath XML |
| [Gröbner basis project](projects/groebner-basis-project.pdf) | `spol`, Buchberger's algorithm, two plotted curves, then a four-variable system with 16 real solutions |
| [Linear algebra project](projects/linear-algebra-in-sage.pdf) | vectors, linear systems (`solve`, `solve_right`, Cramer's rule), spans, Gram–Schmidt, linear maps, eigenvectors |

The Sage code is inside the PDFs (each shows the code and its output).

## On the portfolio

The “Computer algebra lab” on [my portfolio](https://youyou354.github.io/) re-runs these computations in the
browser with a small exact-arithmetic kernel: Buchberger's algorithm gives the same reduced bases as Sage did
for all three systems, and the integer/polynomial division, extended Euclid, Cramer's rule and Gram–Schmidt are there too.
