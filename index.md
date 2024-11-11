@def title = "My Franklin Sandbox"
@def hasmath = true
@def hascode = true

# Examples

## Update file config.md
* change author
* add site name for Github 

## create a table of contents

\toc

## test
こんばんは

$$
y = ax^2+bx+c
$$
2次関数．

$$
y = a\exp(-bM)
$$

## Julia code samples

```julia:./ex11
println("Hello world!")
```

\show{./ex11}

```julia:./ex12
a = 3 + 4
```

\show{./ex12}

random numbers

```julia:./ex15
rand(5, 5)
```
\show{./ex15}


<!--
# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex.
-->
