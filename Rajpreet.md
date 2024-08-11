
## 3.1 Functions of Several Variables: Limit and Continuity

The area of an ellipse is πab. It depends on two variables *a* and *b*; The total surface area of a rectangular parallelepiped is 2(xy + yz + zx) and it depends on 3 variables x, y, z; The velocity v of a fluid particle moving in space depends on 4 variables x, y, z, t. In transportation problems in operations research, the cost function to be minimized is a function of several (m: n; running into hundreds) variables (where m is the number of origins and n is the number of destinations). Thus, functions of several variables play a vital role in advanced Mathematics.


If u = f(x, y, z, t) then x, y, z, t are known as the independent variables or arguments and u is known as the 'dependent variable' or 'value' of the function. In this section, we restrict to functions of two and three variables, although the analysis can easily be extended to several variables.

#### Function of Two Variables

If for every x and y a unique value f(x, y) is associated, then f is said to be a function of the two independent variables x and y and is denoted by:

z = f(x, y)

Geometrically, in three-dimensional xyz-coordinate space (1) represents a surface. The values of x and y for which the function is defined is known as the domain of definition of the function:

Example:

$z = \sqrt{a² - x² - y²}$

Domain: x² + y² ≤ a²

Function not defined when x² + y² > a².

Example:

z = x^y + yx

Domain: x > 0 and y > 0.

The δ-neighbourhood of a point (a, b) in the xy-plane is a square with center at (a, b) bound by the four lines x = a - δ, x = a + δ, y = b - δ, y = b + δ, i.e.,

a - δ ≤ x ≤ a + δ  
b - δ ≤ y ≤ b + δ.      
           
Note: Neighbourhood of a point (a, b) may also be defined as a circular disk with center at (a, b) and of radius δ given by

$$
(x - a)² + (y - b)² < δ²
$$

The concept of limit is paramount in defining continuity and differentiability of a function. Note that all three concepts of limit, continuity and differentiability are point concepts i.e., defined at a point.

#### Limit:
A function $f(x, y)$ is said to have a limit $L$ as the point $(x, y)$ approaches $(a, b)$ and is denoted as

$$
\lim_{{(x, y) \to (a, b)}} f(x, y) = L
$$

if the value of $f(x, y)$ can be made as close (as we please) to the given finite number $L$ for all those $(x, y)$ in an appropriately chosen δ-neighbourhood of $(a, b)$, i.e., for a given $\epsilon > 0$ we can find δ such that

$$
|f(x, y) - L| < \epsilon
$$

for all $(x, y)$ in the δ-neighbourhood

$$
|x - a| < \delta \quad \text{and} \quad |y - b| < \delta
$$

(or alternatively when $(x - a)² + (y - b)² < \delta²$.

Important Note: The limit of a function $f(x, y)$ of two variables is said to exist *only when* the same value is obtained for the limit along any path in the xy-plane from $(x, y)$ to $(a, b)$ say along $x \to a$ and $y \to b$ or along $y \to b$ and $x \to a$, etc.

Limit may or may not exist. If it exists the limit must be unique.

#### Method of Obtaining Limit

- Step I: Evaluate $\lim_{{x \to a}} f(x, y)$ along path I: $x \to a$ and $x \to b$.
- Step II: Evaluate $\lim_{{x \to a}} f(x, y)$ along path II: $y \to b$ and $x \to a$.

  If the limit values along path I and II are same, the limit exists. Otherwise not.

- Step III: If $a = 0, b = 0$, evaluate limit along say path $y = mx²$ also.

Results: If 

$$
\lim_{{(x, y) \to (a, b)}} f(x, y) = L
$$

and

$$
\lim_{{(x, y) \to (a, b)}} g(x, y) = M,
$$

then:

1. $\lim_{{(x, y) \to (a, b)}} (f + g) = L \pm M$
2. $\lim_{{(x, y) \to (a, b)}} (f \cdot g) = L \cdot M$
3. $\lim_{{(x, y) \to (a, b)}} \left(\frac{f}{g}\right) = \frac{L}{M}, \text{ provided } M \neq 0.$

#### Continuity

A function $f(x, y)$ is said to be continuous at a point $(a, b)$ if

# Continuity

A function $f(x, y)$ is said to be continuous at a point $(a, b)$ if 

$$
\lim_{{(x, y) \to (a, b)}} f(x, y) = f(a, b)
$$

i.e., the limit of $f$ as $(x, y)$ tends to $(a, b)$ is the value of $f$ at $(a, b)$.

A function is said to be continuous in a domain if it is continuous at every point of the domain. Equation (2) can also be written as 

$$
\lim_{{(x, y) \to (a, b)}} f(a + h, b + k) = f(a, b)
$$

If $f$ is not continuous at $(a, b)$, it is said to be discontinuous at $(a, b)$.

Result: If $f(x, y)$ and $g(x, y)$ are continuous at $(a, b)$, then $f \pm g$, $f \cdot g$ and $\frac{f}{g}$ are continuous at $(a, b)$.

#### Test for Continuity at a Point $(a, b)$

- Step I: $f(a, b)$ should be well defined.
- Step II: $\lim_{{(x, y) \to (a, b)}} f(x, y)$ should exist (must be unique and same along any path).
- Step III: The limit of $f =$ value of $f$ at $(a, b)$.

### Worked Out Examples

Limits

Example 1: Evaluate $\lim_{{(x, y) \to (0, 0)}} (x² + y²)$

Solution:

$$
\lim_{{(x, y) \to (0, 0)}} (x² + y²) = 0
$$

Taking $y = mx$, we get

$$
\lim_{{x \to 0}} (x²(1 + m²)) = 0
$$

Taking $x = 0$, we get

$$
\lim_{{y \to 0}} y² = 0
$$

Similarly, taking $y = 0$, we get

$$
\lim_{{x \to 0}} x² = 0
$$
 

#### Along $y = mx$

$$
\lim_{x \to 0} \left( x^2 + y^2 \right) = \lim_{x \to 0} \left( x^2 + m^2x^2 \right) 
$$

$$
= \lim_{x \to 0} \left(1 + m^2\right) x^2 = \left(1 + m^2\right) \lim_{x \to 0} x^2 = 0
$$

#### Along $y = mx^2$

$$
\lim_{x \to 0} \left( x^2 + y^2 \right) = \lim_{x \to 0} \left( x^2 \left(1 + m^2x^2 \right) \right) = 0
$$ 

Since the value of the limit along any path is the same, the limit exists and the limit value is zero.

Example 2: If $f(x, y) = \frac{y^2 - x^2}{x^2 + y^2}$, show that

$$
\lim_{(x, y) \to (0, 0)} \left| f(x, y) \right| \neq \lim_{(x, y) \to (0, 0)} f(x, y)
$$

Solution:

L.H.S. of the inequality:

$$
\lim_{x \to 0} \lim_{y \to 0} \left| f(x, y) \right| = \lim_{x \to 0} \lim_{y \to 0} \left| \frac{y^2 - x^2}{x^2 + y^2} \right| = \lim_{x \to 0} \frac{x^2 - x^2}{x^2 + y^2}
$$

$$
= \lim_{x \to 0} \frac{x^2}{x^2} \times \lim_{y \to 0} 1 - 1 = 1 - 1 = 0
$$

R.H.S. of the inequality:

$$
\lim_{y \to 0} \lim_{x \to 0} \left| f(x, y) \right| = \lim_{y \to 0} \lim_{x \to 0} \frac{y^2 - x^2}{x^2 + y^2} = \lim_{y \to 0} \frac{x^2}{x^2 + y^2}
$$

$$
= \lim_{y \to 0} \left[ \frac{x^2}{x^2 + y^2} \right] = 1 - 1 = 0
$$

Thus L.H.S. $= -1 \neq 1 =$ R.H.S.  

$$
\text{[Note: Since the limits along two different paths are not the same, the limit does not exist.]}
$$

Example 3: Evaluate  

$$
\lim_{(x, y) \to (0, 0)} \frac{x^2y}{(x^2 + y^2)^2} 
$$

Solution:

1. I.
2. 
$$
\lim_{y \to 0} \frac{x^2y}{(x^2 + y^2)^2} = \lim_{y \to 0} 0 = 0
$$

3. II.
4.   
$$
\lim_{x \to 0} \frac{x^2y}{(x^2 + y^2)^2} = \lim_{x \to 0} 0 = 0
$$

5. III.  

$$
\lim_{x \to 0} \lim_{y \to 0} \frac{mx^3}{\left(1 + m^2x^2\right)^2} = \lim_{x \to 0} \frac{mx^3}{\left(1 + m^2x^2\right)^2} = 0
$$

Since the limit along the last path \( y = mx^2 \) depends on \( m \), the limit does not exist.

