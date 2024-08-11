$e^(xyz)$






# Taylor and Maclaurin Series





[view](./README2.md)

This section shows how functions that are infinitely differentiable generate power series called Taylor series. In many cases, these series can provide useful polynomial approximations of the generating functions.

### Series Representations

We know that within its interval of convergence, the sum of a power series is a continuous function with derivatives of all orders. But what about the other way around? If a function $(f(x)$ has derivatives of all orders on an interval $I$, can it be expressed as a power series on $I$? And if it can, what will its coefficients be?

We can answer the last question readily if we assume that $f(x)$ is the sum of a power series

$$ 
f(x) = \sum_{n=0}^{\infty} a_n (x - a)^n = a_0 + a_1 (x - a) + a_2 (x - a)^2 + \cdots + a_n (x - a)^n + \cdots 
$$

with a positive radius of convergence. By repeated term-by-term differentiation within the interval of convergence $I$, we obtain

$$
f'(x) = a_1 + 2a_2 (x - a) + 3a_3 (x - a)^2 + \cdots + n a_n (x - a)^{n-1} + \cdots,
$$

$$ 
f''(x) = 2 \cdot 1 \cdot 2a_2 + 3 \cdot 2 a_3 (x - a) + 4 \cdot 3 a_4 (x - a)^2 + \cdots,
$$

$$ 
f'''(x) = 2 \cdot 1 \cdot 3a_3 + 3 \cdot 2 \cdot 3 a_3 + 4 \cdot 3 a_4 (x - a) + \cdots + 4 \cdot 3 \cdot 4 \cdot 5 a_5 (x - a)^2 + \cdots 
$$

with the $n$ th derivative, for all $n$, being

$$ 
f^{(n)}(x) = n! a_n + \text{a sum of terms with } (x - a) \text{ as a factor.} 
$$



Since these equations all hold at $x = a$, we have

$$ 
f'(a) = a_1, 
$$

$$ 
f''(a) = 1 \cdot 2a_2, 
$$

$$ 
f'''(a) = 1 \cdot 2 \cdot 3a_3, 
$$

and, in general,

$$ 
f^{(n)}(a) = n! a_n. 
$$

These formulas reveal a marvelous pattern in the coefficients of any power series $\sum_{n=0}^{\infty} a_n (x - a)^n$ that converges to the values of $f$ on I ("represents $f$ on I," we say). If there is such a series (still an open question), then there is only one such series and its $n$ th coefficient is

$$
a_n = \frac{f^{(n)}(a)}{n!}. 
$$

If $f$ has a series representation, then the series must be

$$
f(x) = f(a) + f'(a)(x - a) + \frac{f''(a)}{2!} (x - a)^2 + \cdots + \frac{f^{(n)}(a)}{n!} (x - a)^n + \cdots.
$$

But if we start with an arbitrary function $f$ that is infinitely differentiable on an interval I centered at $x = a$ and use it to generate the series in Eq. (1), will the series then converge to $f(x)$ at each $x$ in the interior of I? The answer is maybe—for some functions it will but for other functions it will not, as we will see.

### Taylor and Maclaurin Series

#### Definitions
Let $f$ be a function with derivatives of all orders throughout some interval containing $a$ as an interior point. Then the Taylor series generated by $f$ at $x = a$ is

$$
\sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!} (x - a)^n = f(a) + f'(a)(x - a) + \frac{f''(a)}{2!} (x - a)^2 + \cdots + \frac{f^{(n)}(a)}{n!} (x - a)^n + \cdots. 
$$

The Maclaurin series generated by $f$ is

$$
\sum_{n=0}^{\infty} \frac{f^{(n)}(0)}{n!} x^n = f(0) + f'(0)x + \frac{f''(0)}{2!} x^2 + \cdots + \frac{f^{(n)}(0)}{n!} x^n + \cdots.
$$

Example 1: Find the Taylor series generated by $f(x) = 1/x$ at $a = 2$. Where, if anywhere, does the series converge to $1/x$?



Solution: We need to find $f(2), f'(2), f''(2), \ldots$. Taking derivatives we get

$$ 
f(x) = x^{-1}, 
$$

$$ 
f'(x) = -x^{-2}, 
$$

$$ 
f''(x) = 2x^{-3}, 
$$

$$ 
f'''(x) = -3! x^{-4}, 
$$

$$ 
f^{(n)}(x) = (-1)^n n! x^{-(n+1)}. 
$$

$$ 
f(2) = 2^{-1} = \frac{1}{2}, 
$$

$$ 
f'(2) = -2^{-2} = -\frac{1}{4}, 
$$

$$ 
f''(2) = 2 \cdot 2^{-3} = \frac{1}{4}, 
$$

$$ 
f'''(2) = -3! \cdot 2^{-4} = -\frac{3}{8}, 
$$

$$ 
f^{(n)}(2) = (-1)^n n! \cdot 2^{-(n+1)}. 
$$

The Taylor series is

$$ 
f(x) = f(2) + f'(2)(x - 2) + \frac{f''(2)}{2!} (x - 2)^2 + \cdots 
$$

$$ 
= \frac{1}{2} - \frac{1}{4} (x - 2) + \frac{1}{4 \cdot 2} (x - 2)^2 - \frac{3}{8 \cdot 6} (x - 2)^3 + \cdots 
$$

This is a geometric series with the first term $1/2$ and ratio $r = - (x - 2)/2$. It converges absolutely for $|x - 2| < 2$ and its sum is

$$ 
\frac{1}{1 - r} = \frac{1/2}{1 + (x - 2)/2} = \frac{1}{2 + (x - 2)} = \frac{1}{x}. 
$$

In this example, the Taylor series generated by $f(x) = 1/x$ at $a = 2$ converges to $1/x$ for $|x - 2| < 2$ or $0 < x < 4$.

### Taylor Polynomials

The linearization of a differentiable function $f$ at a point $a$ is the polynomial

$$ 
P_1(x) = f(a) + f'(a)(x - a). 
$$

If $f$ has derivatives of higher order at $a$, then it has higher order polynomial approximations as well, one for each available derivative. These polynomials are called the Taylor polynomials of $f$.

#### Definition
Let $f$ be a function with derivatives of order $k$ for $k = 1, 2, \ldots, N$ in some interval containing $a$ as an interior point. Then for any integer $n$ from 0 through $N$, the Taylor polynomial of order $n$ generated by $f$ at $x = a$ is the polynomial

$$ 
P_n(x) = f(a) + f'(a)(x - a) + \frac{f''(a)}{2!} (x - a)^2 + \cdots + \frac{f^{(n)}(a)}{n!} (x - a)^n. 
$$


Just as the linearization of $f$ at $x = $ provides the best linear approximation of $f$ in the neighborhood of $a$, the higher order Taylor polynomials provide the best polynomial approximations of their respective degrees. (See Exercise 32.)

### EXAMPLE 2
Find the Taylor series and the Taylor polynomials generated by $f(x) = e^x$ at $x = 0$.

**Solution**: Since

$$ 
f(x) = e^x, 
$$

$$ 
f'(x) = e^x, 
$$

$$ 
f''(x) = e^x, 
$$

$$ 
\ldots,
$$

$$ 
f^{(n)}(x) = e^x, 
$$

we have

$$ 
f(0) = e^0 = 1,
$$

$$ 
f'(0) = 1, 
$$

$$ 
\ldots, 
$$

$$ 
f^{(n)}(0) = 1.
$$

The Taylor series generated by $f$ at $x = 0$ is

$$ 
f(0) + f'(0)x + \frac{f''(0)}{2!} x^2 + \cdots + \frac{f^{(n)}(0)}{n!} x^n + \cdots
$$

$$
= 1 + x + \frac{x^2}{2!} + \cdots + \frac{x^n}{n!} + \cdots 
$$

$$ 
= \sum_{k=0}^{\infty} \frac{x^k}{k!}.
$$

By definition, this is also the Maclaurin series for $e^x$. In Section 8.10 we will see that the series converges to $e^x$ at every $x$.

The Taylor polynomial of order $n$ at $x = 0$ is

$$ 
P_n(x) = 1 + x + \frac{x^2}{2!} + \cdots + \frac{x^n}{n!}.
$$

See Fig. 8.17.

### EXAMPLE 3
Find the Taylor series and Taylor polynomials generated by $f(x) = \cos x$ at $x = 0$.

**Solution**: The cosine and its derivatives are

$$
f(x) = \cos x,
$$

$$ 
f'(x) = -\sin x,
$$

$$
f''(x) = -\cos x,
$$

$$ f'''(x) = \sin x,
$$

$$
\ldots 
$$

$$
f^{(2n)}(x) = (-1)^n \cos x, 
$$

$$f^{(2n+1)}(x) = (-1)^n \sin x.
$$

At $x = 0$, the cosines are 1 and the sines are 0, so

$$
f^{(2n)}(0) = (-1)^n, 
$$

$$ 
f^{(2n+1)}(0) = 0.
$$

The Taylor series generated by $f$ at $x = 0$ is

$$ 
f(0) + f'(0)x + \frac{f''(0)}{2!} x^2 + \cdots + \frac{f^{(2n)}(0)}{(2n)!} x^{2n} + \cdots 
$$

$$ 
= 1 + 0 \cdot x - \frac{x^2}{2!} + 0 \cdot x^3 + \frac{x^4}{4!} + \cdots
$$

$$ 
= \sum_{n=0}^{\infty} \frac{(-1)^n x^{2n}}{(2n)!}. 
$$










By definition, this is also the Maclaurin series for cos $x$. In Section 1.10, we will see that the series converges to cos $x$ at every $x$.

Because $f^{(2n+1)}(0) = 0$, the Taylor polynomials of orders $2n$ and $2n+1$ are identical:

$$ P_{2n}(x) = P_{2n+1}(x) = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots + (-1)^n \frac{x^{2n}}{(2n)!} $$


**EXAMPLE 4**: A function $f$ whose Taylor series converges at every $x$ but converges to only  $f(x)$ at $x = 0$

It can be shown (though not easily) that

$$ f(x) = \begin{cases} 
0, & x = 0 \\ 
e^{-1/x^2}, & x \neq 0 
\end{cases} $$


$$
f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \cdots + \frac{f^{(n)}(0)}{n!}x^n + \cdots 
$$

 $$
 = 0 + 0 \cdot x + 0 \cdot x^2 + \cdots + 0 \cdot x^n + \cdots 
 $$

 $$
 = 0 + 0 + \cdots + 0 + \cdots
 $$

The series converges for every $x$ (its sum is 0) but converges to $f(x)$ only at $x = 0$.

Two questions still remain.

1. For what values of $x$ can we normally expect a Taylor series to converge to its generating function?

2. How accurately do a function's Taylor polynomials approximate the function on a given interval?

The answers are provided by a theorem of Taylor in the next section.


## Convergence of Taylor Series; Error Estimates

This section addresses the two questions left unanswered by Section 8.9:

1. When does a Taylor series converge to its generating function?
2. How accurately do a function’s Taylor polynomials approximate the function on a given interval?

### Taylor’s Theorem

We answer these questions with the following theorem.

#### Theorem 16
**Taylor’s Theorem**

If $f$ and its first $n$ derivatives $f', f'', \ldots, f^{(n)}$ are continuous on $[a, b]$ or on $[b, a]$, and $f^{(n)}$ is differentiable on $(a, b)$ or on $(b, a)$, then there exists a number $c$ between $a$ and $b$ such that
$f(b) = f(a) + f'(a)(b - a) + \frac{f''(a)}{2!}(b - a)^2 + \cdots + \frac{f^{(n)}(a)}{n!}(b - a)^n + \frac{f^{(n+1)}(c)}{(n+1)!}(b - a)^{n+1}.$

Taylor's theorem is a generalization of the Mean Value Theorem (Exercise 39). There is a proof of Taylor’s theorem at the end of this section.

When we apply Taylor’s theorem, we usually want to hold a fixed and treat $b$ as an independent variable. Taylor’s formula is easier to use in circumstances like these if we change $b$ to $x$. Here is how the theorem reads with this change.


# Corollary to Taylor's Theorem

## Taylor's Formula
If $f$ has derivatives of all orders in an open interval $I$ containing $a$, then for each positive integer $n$ and for each $x$ in $I$,

$$
f(x) = f(a) + f'(a)(x - a) + \frac{f''(a)}{2!}(x - a)^2 + \cdots + \frac{f^{(n)}(a)}{n!}(x - a)^n + R_n(x),
$$

where

$$ 
R_n(x) = \frac{f^{(n+1)}(c)}{(n + 1)!}(x - a)^{n+1} 
$$

for some $c$ between $x$ and $a$.

When we state Taylor's theorem this way, it says that for each $x$ in $I$,

$$ 
f(x) = P_n(x) + R_n(x). 
$$

Pause for a moment to think about how remarkable this equation is. For any value of $$n$$ we want, the equation gives both a polynomial approximation of $$f$$ of that order and a formula for the error involved in using that approximation over the interval $I$.

Equation (1) is called **Taylor's formula**. The function $R_n(x)$ is called the remainder of order $n$ or the error term for the approximation of $f$ by $P_n(x)$ over $I$. If $R_n(x) \to 0$ as $n \to \infty$ for all $x$ in $I$, we say that the Taylor series generated by $f$ at $x = a$ converges to $f$ on $I$, and we write

$$ 
f(x) = \sum_{k=0}^{\infty} \frac{f^{(k)}(a)}{k!}(x - a)^k. 
$$

#### Example 1: The Maclaurin Series for $e^x$

Show that the Taylor series generated by $f(x) = e^x$ at $x = 0$ converges to $f(x)$ for every real value of $x$.

**Solution:**
The function has derivatives of all orders throughout the interval $I = (-\infty, \infty)$. Equations (1) and (2) with $f(x) = e^x$ and $a = 0$ give

$$ 
e^x = 1 + x + \frac{x^2}{2!} + \cdots + \frac{x^n}{n!} + R_n(x), 
$$

and

$$ 
R_n(x) = \frac{e^c x^{n+1}}{(n + 1)!} 
$$   

for some $c$ between 0 and $x$.

Since $e^x$ is an increasing function of $x$, $e^c$ lies between $e^0 = 1$ and $e^x$. When $x$ is negative, so is $c$, and $e^c < 1$. When $x$ is zero, $c = 0$ and $R_n(x) = 0$. When $x$ is positive, so is $c$, and $e^c < e^x$. Thus,

$$ 
|R_n(x)| \leq \frac{|x|^{n+1}}{(n + 1)!}
$$  

where $x \leq 0$.


and

$$ 
|R_n(x)| < e^x \frac{x^{n+1}}{(n + 1)!} \quad \text{when } x > 0. 
$$

Finally, because

$$
\lim_{n \to \infty} \frac{x^{n+1}}{(n + 1)!} = 0 \quad \text{for every } x,
$$

$$
\lim_{n \to \infty} R_n(x) = 0,
$$

and the series converges to $e^x$ for every $x$.

$$
e^x = \sum_{k=0}^{\infty} \frac{x^k}{k!} = 1 + x + \frac{x^2}{2!} + \cdots + \frac{x^k}{k!} + \cdots.
$$



