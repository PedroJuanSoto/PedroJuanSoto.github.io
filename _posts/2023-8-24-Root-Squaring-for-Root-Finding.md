---
title: "Root-Squaring for Root-Finding"
categories:
  - conference publication
tags:
  - Symbolic-numeric computing
  - Root-finding
  - Polynomial algorithms
  - Computer algebra
---

The root-squaring iterations of Dandelin (1826), Lobachevsky (1834), and Gräffe (1837) recursively produce the coefficients of polynomials whose zeros are the th powers of the zeros of an input polynomial p(x) for The iterations have been the main tool for univariate polynomial root-finding in the 19th century and well beyond but became obsolete later because of severe numerical stability problems observed already in a few iterations. To circumvent this deficiency we apply root-squaring to Newton’s Inverse Ratios and compute no coefficients of p(x) or for , assuming that p(x) is a black box polynomial, represented by an oracle or subroutine for its evaluation rather than by its coefficients. Accordingly, our algorithm accelerates root-squaring for a polynomial p(x) that can be evaluated fast as well as for polynomial for a complex number c and a positive by performing root-squaring without computing the coefficients of . Our extensive experiments demonstrate efficiency of application of our algorithms to estimation of extremal root radii, that is, the maximal and minimal distances from a point on the complex plane to the zeros of p(x). This is a well-known ingredient of various efficient polynomial root-finders, immediately extended to deciding whether a fixed disc on the complex plane contains any zero of p(x). The latter decision, called exclusion test for a disc, is the basic step of all efficient root-finders using subdivision iterations, in particular, of the recent polynomial root-finder by the second author, made nearly optimal due to a distinct application of root-squaring iterations.
<cite><a href="https://link.springer.com/chapter/10.1007/978-3-031-41724-5_6">Link to the Publication</a></cite>
