
By definition, this is also the Maclaurin series for cos $x$. In Section 1.10, we will see that the series converges to cos $x$ at every $x$.

Because $f^{(2n+1)}(0) = 0$, the Taylor polynomials of orders $2n$ and $2n+1$ are identical:

$$ P_{2n}(x) = P_{2n+1}(x) = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots + (-1)^n \frac{x^{2n}}{(2n)!} $$

Figure 1.18 shows how well these polynomials approximate $f(x) = \cos(x)$ near $x = 0$. Only the right-hand portions of the graphs are given because the graphs are symmetric about the y-axis.

**EXAMPLE 4**: A function $f$ whose Taylor series converges at every $x$ but converges to only  $f(x)$ at $x = 0$

It can be shown (though not easily) that

$$ f(x) = \begin{cases} 
0, & x = 0 \\ 
e^{-1/x^2}, & x \neq 0 
\end{cases} $$

(Fig. 1.19) has derivatives of all orders at $x = 0$ and that $f^{(n)}(0) = 0$ for all $n$. This means that the Taylor series generated by $f$ at $x = 0$ is

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

# Exercises 1.9

## Finding Taylor Polynomials

In Exercises 1-8, find the Taylor polynomials of orders 0, 1, 2, and 3 generated by $f$ at $a$.

1. $f(x) = \ln x$, $a = 1$
2. $f(x) = \ln (1 + x)$, $a = 0$
3. $f(x) = 1/x$, $a = 2$
4. $f(x) = 1/(x + 2)$, $a = 0$
5. $f(x) = \sin x$, $a = \pi/4$
6. $f(x) = \cos x$, $a = \pi/4$
7. $f(x) = \sqrt{x}$, $a = 4$
8. $f(x) = \sqrt{x + 4}$, $$ a = 0$

## Finding Maclaurin Series
Find the Maclaurin series for the functions in Exercises 9-20.
9. $e^x$

10. $e^{x / 2}$

11. $\frac{1}{1 + x}$

12. $\frac{1}{1 - x}$

13. $\sin 3x$

14. $\sin \frac{x}{2}$

15. $\cos (x / 2)$

16. $5 \cos \pi x$

17. $\cosh x = \frac{e^x + e^{-x}}{2}$

18. $\sinh x = \frac{e^x - e^{-x}}{2}$

19. $x^4 - 2x^3 - 5x + 4$

20. $(x + 1)^2$

## Finding Taylor Series
In Exercises 21-28, find the Taylor series generated by $f$ at $x = a$.

21. $f(x) = x^3 - 2x + 4, \ a = 2$

22. $f(x) = 2x^3 + x^2 + 3x - 8, \ a = 1$

23. $f(x) = x^4 + x^2 + 1, \ a = -2$

24. $f(x) = 3x^5 - x^4 + 2x^3 + x^2 - 2, \ a = -1$

25. $f(x) = \frac{1}{x^2}, \ a = 1$

26. $f(x) = \frac{x}{(1 - x)}, \ a = 0$

27. $f(x) = e^x, \ a = 2$

28. $f(x) = 2^x, \ a = 1$

#### Theory and Examples
29. Use the Taylor series generated by $e^x$ at $x = a$ to show that 
$e^x = e^a \left[ 1 + (x - a) + \frac{(x - a)^2}{2!} + \ldots \right]$

30. (Continuation of Exercise 29.) Find the Taylor series generated by $e^x$ at $x = 1$. Compare your answer with the formula in Exercise 29.

31. Let $f(x)$ have derivatives through order $n$ at $x = a$. Show that the Taylor polynomial of order $n$ and its first $n$ derivatives have the same values that $f$and its first $n$ derivatives have at $x = a$.


32. Of all polynomials of degree ≤ n, the Taylor polynomial of order n gives the best approximation. Suppose that $f(x)$ is differentiable on an interval centered at $x = a$ and that $g(x) = b_0 + b_1(x-a) + \cdots + b_n(x-a)^n$ is a polynomial of degree n with constant coefficients $b_0, \cdots, b_n$. Let $E(x) = f(x) - g(x)$. Show that if we impose on $g$ the conditions

a) $E(a) = 0$     The approximation error is zero at $x = a$.

b) $\lim_{{x \to a}} \frac{E(x)}{(x-a)^n} = 0$  The error is negligible when compared to $(x-a)^n$.

then
$$ g(x) = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \cdots + \frac{f^{(n)}(a)}{n!}(x-a)^n. $$

Thus, the Taylor polynomial $P_n(x)$ is the only polynomial of degree less than or equal to n whose error is both zero at $x = a$ and negligible when compared with $(x-a)^n$.

## Quadratic Approximations

The Taylor polynomial of order 2 generated by a twice-differentiable function $f(x)$ at $x = a$ is called the quadratic approximation of $f$ at $x = a$. In Exercises 33-38, find the (a) linearization (Taylor polynomial of order 1) and (b) quadratic approximation of $f$ at $x = 0$.

33. $f(x) = \ln(\cos x)$ 

34. $f(x) = e^{x^2}$

35. $f(x) = \frac{1}{\sqrt{1 - x^2}}$

36. $f(x) = \cosh x$

37. $f(x) = \sin x$

38. $f(x) = \tan x$

Here is the content from the second image written in Markdown:


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
