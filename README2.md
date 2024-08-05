## LHopital Rule

If $\lim_{x \to a} f(x)$ ln *f(x) = L*, then

$\lim_{x \to a} f(x)$ = $\lim_{x \to a}$  $\( e^{ln f(x)} )\$ = $\ e^L \$.

Here $\( \alpha \)$ may be either finite or infinite.



## __*EXAMPLE 8*__

Show that $\lim_{x \to 0^+}$  $\( (1+x)^{\frac{1}{x}} )\$ = *e*.

### __*Solution:-*__   
The limit leads to the indeterminate form  $\( 1^\infty \)$. We let *f(x)* = $\( (1+x)^{\frac{1}{x}} )\$ 

and find $\lim_{x \to 0^+}$ ln *f(x)*. Since

ln *f(x)* = ln $\( (1+x)^{\frac{1}{x}} )\$

 = $\( \frac{1}{x} \)$ ln (1+x),
 

 l'hopital's rule now applies to give    
 
 $\lim_{x \to 0^+}$ ln *f(x)* =  $\lim_{x \to 0^+}$  $(\frac{ln(1+x)}{x} \)$         $\( \frac{0}{0} \)$

= $\lim_{x \to 0^+}$ $(\frac{ln(1/1+x)}{x} \)$

= $(\frac{1}{1} \)$  = 1.

Therefore,

$\lim_{x \to 0^+}$  $\( (1+x)^{\frac{1}{x}} )\$ = $\lim_{x \to 0^+}$ *f(x)* =  $\lim_{x \to 0^+}$ $\( e^{ln f(x)} )\$  = $\ e^1 \$
= e

## __*EXAMPLE 9*__

Find $\ \lim_{x \to \infty}$ $\( (x)^{\frac{1}{x}} )\$.

### __*Solution:-*__
The limit leads to the indeterminate form $\( \infty^0 \)$. We let *f(x)* = $\( (x)^{\frac{1}{x}} )\$ and

find  $\ \lim_{x \to \infty}$ ln *f(x)*. Since 

ln*f(x)* = ln $\( (x)^{\frac{1}{x}} )\$

=  $(\frac{ln x}{x} \)$ ,

L'Hopital's rule gives

$\ \lim_{x \to \infty}$ ln *f(x)* = $\ \lim_{x \to \infty}$ $(\frac{ln x}{x} \)$                    $\( \frac{infty}{infty} \)$

= $\ \lim_{x \to \infty}$  $(\frac{1/x}{1} \)$

= $(\frac{0}{1} \)$ = 0.

Therefore,

$\ \lim_{x \to \infty}$ $\( (x)^{\frac{1}{x}} )\$ = $\ \lim_{x \to \infty}$ *f(x)* = $\ \lim_{x \to \infty}$ $\( e^{ln f(x)} )\$ =  $\ e^0 \$
= 1



## EXERCISE 6.6

### Applying l'Hopital's Rule
 Use l'Hopital's rule to find the limits in Exercise 1-42.
 
 ## 1. $\lim_{x \to 2}$ $\ \frac{(x-2)}{x^2 - 4} \$

 ## 2. $\lim_{x \to -5}$ $\ \frac{(x^2-25)}{(x+5)} \$
 
 ## 3. $\lim_{t \to -3}$ $\ \frac{(t^3-4t+15)}{(t^2-t-12)} \$
 
 ## 4. $\ \lim_{t \to 1}$ $\ \frac{(t^3-1)}{(4t^3-t-3)} \$

 ## 5. $\ \lim_{x \to \infty}$ $\ \frac{(5x^2-3x)}{(7x^2+1)} \$

 ## 6. $\ \lim_{x \to \infty}$ $\ \frac{(8-x^2)}{(12x^2+5x)} \$

 ## 7. $\ \lim_{t \to 0}$ $\ \frac{(sint^2)}{(t)} \$

 ## 8. $\ \lim_{t \to 0}$ $\ \frac{(sin5t)}{(t)} \$

 ## 9. $\ \lim_{x \to 0}$ $\ \frac{(8x^2)}{(cos x-1)} \$

 ## 10. $\ \lim_{x \to \infty}$ $\ \frac{(sinx-x)}{(x^3)} \$

 ## 11. $\lim_{\theta \to \frac{x}{2}}$ $\frac{2\theta - \pi}{\cos(2\pi - \theta)}$

 ## 12. $\lim_{\theta \to \frac{x}{3}}$ $\frac{3\theta + \pi}{\sin(\theta + \{(\pi/3)})}$

 ## 13. $\lim_{\theta \to \frac{x}{2}}$ $\frac{1-sin\theta}{1+cos 2\theta}$

 ## 14. $\ \lim_{x \to 1}$ $\frac{x-1}{ln x-sin\pi x}$

 ## 15. $\ \lim_{x \to 0}$ $\ \frac{(x^2)}{(ln(sec x))} \$

 ## 16. $\lim_{x \to \frac{x}{2}}$ $\frac{x}{(x- (\pi/2))^2}$

 ## 17. $\ \lim_{t \to 0}$ $\ \frac{t(1-cost)}{t-sint} \$

 ## 18. $\ \lim_{t \to 0}$ $\ \frac{t sint}{1-cost} \$

 ## 19. $\lim_{x \to \frac{\pi}{2}^-} (x - \frac{\pi}{2}) \sec(x)$

 ## 20. $\lim_{x \to \frac{\pi}{2}^-} \left( \frac{\pi}{2} - x \right) \tan(x)$

 ## 21. $\lim_{\theta \to 0}$ $\frac{3^{\sin \theta} - 1}{\theta}$

 ## 22. $\lim_{\theta \to 0}$ $\frac{\left(\frac{1}{2}\right)^\theta - 1}{\theta}$

 ## 23. $\ \lim_{x \to 0}$ $\frac{x 2^x}{2^x - 1}$

 ## 24. $\ \lim_{x \to 0}$ $\frac{3^x - 1}{2^x - 1}$

 ## 25. $\ \lim_{x \to \infty}$ $\frac{\ln(x+1)}{\log_2 x}$

 ## 26. $\ \lim_{x \to \infty}$ $\frac{\log_2 x}{\log_3 (x+3)}$

 ## 27. $\ \lim_{x \to 0^+}$ $\frac{ln(x^2 + 2x)}{ln x}$

 ## 28. $\ \lim_{x \to 0^+}$ $\frac{ln(e^x - 1)}{ln x}$

 ## 29. $\ \lim_{y \to 0}$ $\frac{\sqrt{5y + 25} - 5}{y}$

 ## 30. $\ \lim_{y \to 0}$ $\frac{\sqrt{ay + a^2} - a}{y}$   , a>0

 ## 31. $\ \lim_{x \to \infty}$ $(\ln2x - \ln(x + 1))$

 ## 32. $\ \lim_{x \to 0^+}$ $(lnx - \ln sinx)$

 ## 33. $\ \lim_{x \to 0^+}$ $(\frac{1}{x} - \frac{1}{\sin x})$

 ## 34. $\ \lim_{x \to 0^+}$ $(\frac{3x+1}{x} - \frac{1}{\sin x})$

 ## 35. $\ \lim_{x \to 1^+}$ $(\frac{1}{x-1} - \frac{1}{ln x})$

 ## 36. $\ \lim_{x \to 0^+}$ $(\csc x - \cot x + \cos x)$

 ## 37. $\ \lim_{x \to \infty}$ $\int_{x}^{2x} \frac{1}{t} \ dt$

 ## 38. $\ \lim_{x \to \infty}$ $\frac{1}{x \ln x} \int_{1}^{x} \ln t \ dt$

 ## 39. $\lim_{\theta \to 0}$ $\frac{cos\theta - 1}{e^\theta - \theta - 1}$

 ## 40. $\lim_{h \to 0}$ $\frac{e^h-(1+h)} {h^2}$

 ## 41. $\ \lim_{t \to \infty}$ $\frac{e^t+t^2} {e^t-t}$

 ## 42. $\ \lim_{x \to \infty}$ $x^2 e^{-x}$


 ### Limits Involving Bases and Exponents
 Find the limits in Exercise 43-52.

 ## 43. $\ \lim_{x \to 1^+}$ $x^{\frac{1}{1-x}}$

 ## 44. $\ \lim_{x \to 1^+}$ $x^{\frac{1}{x-1}}$

 ## 45. $\ \lim_{x \to \infty}$ $\left(\ln x\right)^{\frac{1}{x}}$

 ## 46. $\ \lim_{x \to e^+}$ $\left(\ln x\right)^{\frac{1}{x-t}}$

 ## 47. $\ \lim_{x \to 0^+}$ $\left(x\right)^{\frac{-1}{ln x}}$

 ## 48. $\ \lim_{x \to \infty}$ $\left(x\right)^{\frac{1}{ln x}}$

 ## 49. $\ \lim_{x \to \infty}$ $\left(1+2x\right)^{\frac{1}{2 ln x}}$

 ## 50. $\ \lim_{x \to 0}$ $\left(e^x + x\right)^{\frac{1}{x}}$

 ## 51. $\ \lim_{x \to 0^+}$ $x^x$

 ## 52. $\ \lim_{x \to 0^+}$ $\left(1 + \frac{1}{x}\right)^x$


 ### Theory and Applications
 L'Hopital's Rule does not help with the limits in Exercise 53-56. Try
 it--you just keep on cycling. Find the limits some other way.

 ## 53. $\ \lim_{x \to \infty}$ $\(\frac{\sqrt{9x + 1}}{\sqrt{x + 1}}\)$

 ## 54. $\ \lim_{x \to 0^+}$ $\(\frac{\sqrt{x}}{\sqrt{sin x}}\)$

 ## 55. $\ \lim_{x \to \left(\frac{\pi}{2}\right)^-} \frac{\sec x}{\tan x} \$

 ## 56. $\ \lim_{x \to 0^+}$ $\( \frac{\cot x}{\csc x} \)$

 ## 57. Which one is correct,and which one is wrong? Give reasons for your answers.

 ## a. $\ \lim_{x \to 3}$ $\( \frac{x - 3}{x^2 - 3} \)$ = $\ \lim_{x \to 3}$ $\( \frac{1}{2x} \)$ = $\(\frac{1}{6}\)$

 ## b. $\ \lim_{x \to 3}$ $\( \frac{x - 3}{x^2 - 3} \)$ = $\(\frac{1}{6}\)$ = 0

 ## 58. Which o
# prabjot



# L'HOPITAL RULE 

This rule was discovered by John Bernoulli for calculating limits of fractions whose numerators and denomerators both approach zero .

# Indeterminate Quotient 

If functions $f(x)$ and $g(x)$ are both zero at $x=0$ , then $lim_{x→a} f(x)/g(x)$ cannot be found by substituting $x=a$. The substitution produces $0/0$ , a meaningless expression known as an *indeterminate form*. Our experience so far has been that limits that lead to indeterminate forms may or may not be hard to find . It took a lot of work to find $lim_{x→0} (sin x)/x$ . But we have had remarkable success with the limit 

 $$
 f'(a) = lim_{x→a} $\frac {f(x)-f(a)} {x-a}
 $$

from which we can calculate derivatives . 


# Theorem 2

Suppose that $f(a) = g(x) = 0$ , that $f'(a)$ and $g'(a)$ exist, and that $g'(a) ≠ 0$ . Then 

$$
  lim_{x→0} $\frac {f(x)} {g(x)}$ = $\frac {f'(a)} {g'(a)}
$$

___________________________________

# Example 1

(A) lim_{x→a} $\frac{3x-Sin x} {x}$

    = $\frac {3-Cos x} {1}$ = 2

(B) lim_{x→a}

$$ 
\sqrt[1+x-1] 
{x}
$$

    = $\frac {1} {2 
    $$ 
    \sqrt[1+x]
    {1}
    $$
    =$\frac {1} {2}$

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

       [*0•∞ form* ,rewrite x cot x
                    cot x = 1/tan x
                    Now, 0/0  ]
                    
  = lim_{x→0+} x•1/tan x

  = lim_{x→0+} x/tan x 

  = lim_{x→0+} 1/sec²x = 1/1 = 1

  


  







  








 






 

 

 





 









 

