## LHopital Rule

>___
>
>If $\lim_{x \to a} f(x)$ ln *f(x) = L*, then
>
>  $\lim_{x \to a} f(x)$ = $\lim_{x \to a}$  $\( e^{ln f(x)} )\$ = $\ e^L \$.
>
>Here $\( \alpha \)$ may be either finite or infinite.
>
>___

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

$\ \lim_{x \to \infty}$ ln *f(x)* = $\ \lim_{x \to \infty}$ $(\frac{ln x}{x} \)$         $\( \frac{infty}{infty} \)$

=$\ \lim_{x \to \infty} $(\frac{1/x}{1} \)$

= $(\frac{0}{1} \)$ = 0.

Therefore,

$\ \lim_{x \to \infty}$ $\( (x)^{\frac{1}{x}} )\$ = $\ \lim_{x \to \infty}$ *f(x)* = $\ \lim_{x \to \infty}$ $\( e^{ln f(x)} )\$ =  $\ e^0 \$
= 1



## EXERCISE 6.6

> ### Applying l'Hopital's Rule
> Use l'Hopital's rule to find the limits in Exercise 1-42.
>
> ## 1.
