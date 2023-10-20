---
aliases: 
links: 
tags: 
---
# math-calculus-limits-and-continuity

## intro

we have this function:

$f(x)=\dfrac{x-1}{x-1}$

i hear you say, isn't this equivalent to $f(x)=1$?
that is mostly correct, but we need to add a constraint for $x$

$f(x)=\dfrac{x-1}{x-1}\text{ is the same as }f(x)=1, \text{for }x \neq 1$

because at $x=1$, $y$ is undefined.

as we approach x = 1 from the left hand side, we could get as close to x = 1 as we want, as long as we are not exactly at $x=1$, and $f(x)$ approaches 1

the same is true for the right hand side.

according to the definition of one-sided limits, the left hand one-sided limit of $f(x)$

‍

$\lim \limits_{x \to 1} f(x) = 1$

the above expression means that the bidirectional limit, (or just limit) as x approaches 1 of $f(x)$ is equal to 1.

‍

## calculating limits

### methods

#### factoring

the following flowchart can help you decide which methods to use when calculating limits

‍​
[[../assets/24f6433a6f8750bcf194188f5418e8e4_MD5.jpeg|Open: calculating-limits-flowchart.png]]
![[../assets/24f6433a6f8750bcf194188f5418e8e4_MD5.jpeg]]

### examples

*  link $\lim \limits_{x \to 6} \dfrac{x^2-10x+24}{x^2-4x-12}$

‍

## references

[https://www.khanacademy.org/math/ap-calculus-bc/bc-limits-new](https://www.khanacademy.org/math/ap-calculus-bc/bc-limits-new)

‍

‍

## continuity

definition is here

### continuity at a point

see [this video](https://www.khanacademy.org/math/ap-calculus-bc/bc-limits-new/bc-1-11/v/continuity-at-a-point)

‍

‍

## limits of combined functions

see [this video](https://www.khanacademy.org/math/ap-calculus-ab/ab-limits-new/ab-1-5a/v/limits-of-combined-functions-piecewise)

here are some formulas for limits of combined functions. <u>we assume that:</u>

$\lim \limits_{x \to c} f(x) = L$

$\lim \limits_{x \to c} g(x) = M$

if the above are satisfied, then

* $\lim \limits_{x \to c} \left( f(x)+g(x) \right) = \lim \limits_{x \to c} f(x) + \lim \limits_{x \to c} g(x) = L+M$

* $\lim \limits_{x \to c} \left( f(x)-g(x) \right) = \lim \limits_{x \to c} f(x) - \lim \limits_{x \to c} g(x) = L-M$

* $\lim \limits_{x \to c} \left( f(x)g(x) \right) = \lim \limits_{x \to c} f(x) * \lim \limits_{x \to c} g(x) = L*M$

* $\lim \limits_{x \to c} \left( \dfrac{f(x)}{g(x)} \right) = \dfrac{ \lim \limits_{x \to c} f(x) }{ \lim \limits_{x \to c} g(x) } = \dfrac{L}{M}$

* $\lim \limits_{x \to c} \left( f(x) \right) ^{\dfrac{a}{b}} = L^{\dfrac{a}{b}}$

‍
