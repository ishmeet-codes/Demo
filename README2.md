

# L'HOPITAL RULE 

This rule was discovered by John Bernoulli for calculating limits of fractions whose numerators and denomerators both approach zero .

# Indeterminate Quotient 

If functions $f(x)$ and $g(x)$ are both zero at $x=0$ , then $lim_{x→a} f(x)/g(x)$ cannot be found by substituting $x=a$. The substitution produces $0/0$ , a meaningless expression known as an *indeterminate form*. Our experience so far has been that limits that lead to indeterminate forms may or may not be hard to find . It took a lot of work to find $lim_{x→0} (sin x)/x$ . But we have had remarkable success with the limit 

 $$
 f'(a) = lim_{x→a} \frac {f(x)-f(a)} {x-a}
 $$

from which we can calculate derivatives . 


# Theorem 2

Suppose that $f(a) = g(x) = 0$ , that $f'(a)$ and $g'(a)$ exist, and that $g'(a) ≠ 0$ . Then 

$$
  lim_{x→0} \frac {f(x)} {g(x)} = \frac {f'(a)} {g'(a)}
$$

___________________________________

# Example 1

(A) $lim_{x→a} \frac{3x-Sin x} {x}= $\frac {3-Cos x} {1}$ = 2$

(B) $lim_{x→a}$

$\sqrt[1+x-1]{x}$

  $$
  = \frac {1} {2 
    \sqrt[1+x]
    {1}
    =$\frac {1} {2}
   $$

(C) lim_{x→0} 
$\frac {x-Sin x} {$x^3$}$ 
    = $\frac{1-Cos x} {3$x^2}$
    = $\frac{sin x} {6x}$ 
    = $\frac{cos x} {6}$
    = $\frac{1} {6}$

___________________________________

# Theorem 3

L'HOPITAL RULE (Stronger form)

Suppose that f(a) = g(a) = 0 and f & g are differentiable on an open interval I containing a . Suppose also that g'(a) ≠ 0 on I if x ≠ a. Then 

lim_{x→a} $\frac {f(x)} {g(x)}$ = lim_{x→a} $\frac {f'(x)} {g'(x)}$

if the limit on the right exists (or is infinity or minus infinity).


# Example 2

  lim_{x→0}
  $$
  \sqrt[1+x] {-1} - (x/2)
  $$
  $\frac {x²}$

  = lim_{x→0}
  $\frac {(1/2) (1+x)^-½ - (1/2)} {2x}$

  = lim_{x→0}
  $\frac {-(1/4)
 
  $$
 
  (1+x)^-3/2
 
  $$
 
  }$ $\frac {2}$ = -1/8

When you apply L'HOPITAL rule, look for a change from 0/0 to something else. This is where the limit is revealed .


  # Example 3

 lim_{x→0} $\frac {1-cos x } {x+x²}$

  = lim_{x→0} $\frac {sin x} {1+2x}$ = 0/1 = 0

If we continue to differentiate in an attempt to apply L'HOPITAL rule once more then,

  lim_{x→0} $\frac {1-cos x} {x+x²}$ = lim_{x→0} $\frac {sin x} {1+2x}$ = lim_{x→0} $\frac {cos x}{2}$ = 1/2 

which is wrong 


# Example 4 

  lim_{x→0^+} $\frac {sin x} {x²}$
      
        *0/0 form*
 
  = lim_{x→0^+} $\frac {cos x} {2x}$ = ∞

L'HOPITAL rule also applies to quotients that lead to the indeterminate form ∞/∞ . If f(x) and g(x) both approach infinity as x→a , then 

  lim_{x→a} $\frac {f(x)} {g(x)}$   = lim_{x→a} $\frac {f'(x)} {g'(x)}$

 provided the latter limit exists. The a here may itself be either finite or infinite. 


 # Example 5

(a) lim_{x→ -π/2} $\frac {sec x} {1+tan x}$       *∞/∞ form*
    
    = lim_{x→ -π/2} $\frac {sec x tan x} {sec² x}$ 
    
    = lim_{x→ -π/2} sin x = 1

 (b) lim_{x→∞} $\frac {ln x} {2√x}$ = lim_{x→∞} $\frac {1/x} {1/√x}$ = lim_{x→∞} 1/√x = 0

__________________________________ 
 
# Indeterminate Products and Differences

We can sometimes handle the indeterminate form 0•∞ and ∞-∞ by using algebra to get 0/0 or ∞/∞ instead. Here again, we do not mean to suggest that there is a number 0•∞ or ∞/∞ any more than we mean to suggest that there is a number 0/0 or ∞/∞ . These forms are not numbers but descriptions of function's behaviour. 

# Example 6 

  lim_{x→0+} x cot x  
  
 $$
       *0•∞ form* ,rewrite x cot x
                    cot x = 1/tan x
                    Now, 0/0
                  
                    
  = lim_{x→0+} x•1/tan x

  = lim_{x→0+} x/tan x 

  = lim_{x→0+} 1/sec²x = 1/1 = 1
  $$

  
**EXAMPLE 7** Find $\lim_{x \to 0} \left( \frac{1}{\sin x} - \frac{1}{x} \right)$

**Solution** If $x \to 0^+1$ , then $\sin x \to 0^+$ and

$$
\frac{1}{\sin x} - \frac{1}{x} \to \infty - \infty.
$$

Similarly, if $x \to 0^-1$, then $\sin x \to 0^-1$ and

$$
\frac{1}{\sin x} - \frac{1}{x} \to -\infty - (-\infty) = -\infty + \infty.
$$

Neither form reveals what happens in the limit. To find out, we first combine the fractions.

$$
\frac{1}{sin x} - \frac{1}{x} = \frac{x - sin x}{x sin x}. \quad \text{(Common denominator is \(x sin x.)}
$$

and then apply l'Hôpital's rule to the result:

$$
\lim_{x \to 0} \left( \frac{1}{\sin x} - \frac{1}{x} \right) = \lim_{x \to 0} \frac{x - \sin x}{x \sin x}
$$

$$
= \lim_{x \to 0} \frac{1 - \cos x}{\sin x + x \cos x}
$$

$$
= \lim_{x \to 0} \frac{sin x}{2 cos x - x sin x} = \frac{0}{2} = 0
$$

**Indeterminate Powers**

Limits that lead to the indeterminate forms \(1^\infty\), \(0^0\), and \(\infty^0\) can sometimes be handled by taking logarithms first. We use l'Hôpital's rule to find the limit of the logarithm and then exponentiate to find the original function behavior.

  







  








 






 

 

 





 









 

