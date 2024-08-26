#### Continuity

Example 4: If $f(x, y) = \frac{x^3y}{x^2 + y^2}$ when $x \neq 0, y \neq 0$ and $f(x, y) = 0$ when $x = 0, y = 0$, find out whether the function $f(x, y)$ is continuous at origin.

Solution: First calculate the limit of the function:
 I.  

$$
\lim_{y \to 0} \frac{x^3y}{x^2 + y^2} = \lim_{y \to 0} 0 = 0
$$

 II.  

$$
\lim_{x \to 0} \frac{x^3y}{x^2 + y^2} = \lim_{x \to 0} 0 = 0
$$

III.  

$$
\lim_{x \to 0} \lim_{y \to 0} \frac{mx^3y}{\left(1 + m^2x^2\right)^2} = \lim_{x \to 0} \frac{mx^3}{\left(1 + m^2x^2\right)^2} = 0
$$

Since the limit along any path is the same, the limit exists and equal to zero which is the value of the function $f(x, y)$ at the origin. Hence the function $f$ is continuous at the origin.

Example 5: Discuss the continuity of the function $f(x, y) = \frac{x^3y}{x^2 + y^2}$ when $x \neq 0, y \neq 0$ and $f(x, y) = 2$ when $x = 0, y = 0$.

Solution: At first, evaluate the limit

I.  

$$
\lim_{y \to 0} \frac{x}{\sqrt{x^2 + y^2}} = 0
$$

II.

$$
\lim_{x \to 0} \frac{x}{\sqrt{x^2 + y^2}} = \lim_{y \to 0} \frac{x}{\sqrt{x^2}} = \lim_{y \to 0} \frac{x}{|x|} = 1 = 1
$$

Since the limits along paths I and II are different, the limit itself does not exist. Therefore the function is discontinuous at the origin.

##### Example 6:
Examine for continuity at origin of the function defined by

$$
f(x, y) = \frac{x^2}{\sqrt{x^2 + y^2}}, \quad \text{for } (x \neq 0, y \neq 0)
$$

$$
= 3, \quad \text{for } (x = 0, y = 0)
$$

Redefine the function to make it continuous.

###### Solution:
Initially, find the limit

$$
\lim_{(x, y) \to (0, 0)} \frac{x^2}{\sqrt{x^2 + y^2}}
$$

I. $\lim_{y \to 0} \frac{x^2}{\sqrt{x^2 + y^2}} = \lim_{y \to 0} \frac{x^2}{|x|} = \lim_{y \to 0} x = 0$

II. $\lim_{x \to 0} \frac{x^2}{\sqrt{x^2 + y^2}} = \lim_{x \to 0} \frac{x^2}{|y|} = 0$

III. $\lim_{x \to 0} \frac{x^2}{\sqrt{x^2 + y^2}} = \lim_{x \to 0} \frac{x^2}{\sqrt{1 + m^2}} = \lim_{x \to 0} \frac{x^2}{1 + m^2} = 0$

IV. $\lim_{y \to 0} \frac{x^2}{\sqrt{x^2 + y^2}} = \lim_{y \to 0} \frac{x^2}{\sqrt{(1 + mx^2m^2)}} = 0$

Thus the limit along any path exists and is the same and the common value equals to zero i.e.,

$$
\lim_{(x, y) \to (0, 0)} \frac{x^2}{\sqrt{x^2 + y^2}} = 0
$$

However the value of the functions at origin is 3 i.e.,

$$
f(0, 0) = 3
$$

Therefore $f$ is discontinuous at origin because

$$
\lim_{(x, y) \to (0, 0)} \frac{x^2}{\sqrt{x^2 + y^2}} \neq 3 = f(0, 0)
$$

The function can be *made* continuous at origin by redefining the function as $f(0, 0) = 0$, since in this case

$$
\lim_{(x, y) \to (0, 0)} \frac{x^2}{\sqrt{x^2 + y^2}} = 0 = f(0, 0).
$$

### EXERCISE

#### Limits
Evaluate the following limits:

1. $\lim_{(x, y) \to (0, 0)} \frac{x^2 + y^3}{2x^2y}$
Ans. $\frac{31}{24}$

2. $\lim_{(x, y) \to (0, 0)} \frac{2x^2y}{3x + y^2}$
Ans. $\frac{2}{3}$

3. $\lim_{(x, y) \to (0, 0)} \frac{3xy + y}{x + y}$
Ans. does not exist

Hint: Along path $y = mx$, limit is $\frac{m}{m + 1}$ which is different for different values of $m$.

4. $\lim_{(x, y) \to (0, 0)} \frac{2x^2 + y^2}{2x^2 + y^2}$
Ans. $\frac{1}{2}$

5. $\lim_{(x, y) \to (0, 0)} \frac{x}{|y|}$
Ans. does not exist

6. $\lim_{(x, y) \to (0, 0)} \frac{x}{\sqrt{x^2 + y^2}}$
Ans. does not exist

7. $\lim_{(x, y) \to (0, 0)} \frac{x^2 + y^2}{xy}$
Ans. does not exist

8. $\lim_{(x, y) \to (0, 0)} \frac{2xy - 3}{xy + 2}$
Ans. 0

Show that 

$$
\lim_{x \to 0} \left[ \lim_{y \to 0} f(x, y) \right] \neq \lim_{y \to 0} \left[ \lim_{x \to 0} f(x, y) \right]
$$

if

9. $f(x, y) = \frac{x^2 - y}{x + y}$ Ans. $\frac{1}{1} \neq -1$

10. $f(x, y) = \frac{xy}{x + y}$ Ans. $\frac{1}{1} \neq -1$

#### Continuity
11. If 

$$
f(x, y) = \frac{(x^2 - y^2)}{\sqrt{x^2 + y^2}}, \quad \text{when } x \neq 0, y \neq 0
$$

$$
= 0, \quad \text{when } (x = 0, y = 0)
$$
show that $f$ is discontinuous at origin.


II. $\lim_{x \to 0} \frac{x}{\sqrt{x^2 + y^2}} = \lim_{y \to 0} \frac{x}{\sqrt{x^2}} = \lim_{x \to 0} \frac{x}{|x|} = 1 = 1$

Since the limits along paths I and II are different, the limit itself does not exist. Therefore the function is discontinuous at the origin.

12. (a) Is the function $f(x, y) = \frac{xy^2}{x^2+y^2}$ when $(x, y) \neq (0, 0)$ and $f(0, 0) = 4$ continuous at origin, O? Redefine if necessary to make it continuous at O.

Ans. a. not continuous; $\lim = 0 \neq 4 = f(0, 0)$
b. continuous if $f(0, 0) = 0$

13. If $f(x, y) = x^2 + y^2$ determine where the function is continuous.

Ans. continuous for every x and y i.e., everywhere

14. If $f(x, y) = \frac{xy^2}{x^2+y^4}$, for $(x, y) \neq (0, 0)$

    $\quad \quad \quad \quad = 15$, at $(0, 0)$

    show that $f$ is discontinuous at origin.

    Ans. $f$ discontinuous at origin.

15. Find whether $f(x, y) = \frac{x^2y}{x^2+y^2}$ is continuous at $(0, 0)$ when $f(a) = 0$; $f(b) = 15$; $f(0, 0) = 0$.

Ans. a. not continuous; $\lim = 0 \neq 15 = f(0, 0)$
b. continuous since $\lim = 0 = 0 = f(0, 0)$

16. Given $f(x, y) = x^3 + 3y^2 + 2x + y$ for every $(x, y)$ except $(2, 3)$ where $f(2, 3) = 10$. Examine whether $f$ is continuous at (a) point (2, 3) (b) at any other points (c) can the function be made continuous at (2, 3) by redefining $f$ at (2, 3).

    Ans. a. discontinuous at (2, 3)
           b. continuous for every x and y i.e., everywhere except at (2, 3)
           c. $f$ becomes continuous by redefining $f$ at (2, 3) as $f(2, 3) = 42$

17. a. Prove that $f(x, y) = \frac{x - y}{x + y}$, $x \neq y$ is discontinuous at origin when $f(0, 0) = 0$

    Ans. a. discontinuous at origin when $f(0, 0) = 0$
           b. $f$ can be made continuous by redefining $f$ at (0, 0) i.e., for any other value of $f(0, 0)$, then the limit at (0, 0) does not exist.

18. Prove that $f(x, y) = \frac{xy}{x^2+y^2}$ when $(x, y) \neq (0, 0)$ and $f(0, 0) = 0$ is discontinuous at origin.

    Ans. $f$ is discontinuous at origin.

19. $\frac{y}{\sqrt{x^2+y^2}}$

    Ans. discontinuous

20. $\frac{x}{1+\sqrt{x^2+y^2}}$

    Ans. continuous

21. $\frac{xy}{(x^2+y^2)}$

    Ans. continuous

22. $\frac{(x^2-y^2)}{\sqrt{x^2+y^2}}$

    Hint: continuous.

we can have $\frac{\partial u}{\partial y} = f_y = \frac{\partial f}{\partial y}$, etc. The value of a partial derivative at a point $(a, b, c)$ is denoted by

$$
\frac{\partial u}{\partial x}\bigg|_{x=a, y=b, z=c} = \frac{\partial u}{\partial x}(a, b, c) = f_x(a, b, c)
$$

### Geometrical interpretation of a partial derivative of a function of two variables: $z = f(x, y)$ represents the equation of a surface in $xyz$-coordinate system. Let APB the curve, which a plane through any point P on the surface parallel to the $xz$-plane, cuts. As point P moves along this curve APB, its coordinates $z$ and $x$ vary while $y$ remains constant. The slope of the tangent line at P to APB represents the rate at which $z$ changes w.r.t. $x$.

Thus

$$
\frac{\partial z}{\partial x} = \tan \alpha = \text{slope of the curve } APB \text{ at the point } P
$$

Similarly,

$$
\frac{\partial z}{\partial y} = \tan \beta = \text{slope of the curve } CPD \text{ at } P.
$$

### Higher Order Partial Derivatives

Partial derivatives of higher order, of a function $f(x, y, z)$, are calculated by successive differentiation. Thus if $u = f(x, y, z)$ then

$$
\frac{\partial^2 u}{\partial y \partial x} = \frac{\partial}{\partial y}\left(\frac{\partial u}{\partial x}\right) = f_{xy} = f_{12}
$$

$$
\frac{\partial^2 u}{\partial x^2} = \frac{\partial}{\partial x}\left(\frac{\partial u}{\partial x}\right) = f_{xx} = f_{11}
$$

$$
\frac{\partial^2 u}{\partial x \partial y} = \frac{\partial}{\partial x}\left(\frac{\partial u}{\partial y}\right) = f_{yx} = f_{21}
$$

$$
\frac{\partial^2 u}{\partial y^2} = \frac{\partial}{\partial y}\left(\frac{\partial u}{\partial y}\right) = f_{yy} = f_{22}
$$

$$
\frac{\partial^3 u}{\partial x \partial y \partial z} = \frac{\partial}{\partial z}\left(\frac{\partial^2 u}{\partial y \partial x}\right) = f_{xyz} = f_{123}
$$

$$
\frac{\partial^4 u}{\partial x \partial y \partial z^2} = \frac{\partial}{\partial z^2}\left(\frac{\partial^3 u}{\partial y \partial x \partial z}\right) = f_{xyz2} = f_{1232}
$$

The partial derivative $\frac{\partial u}{\partial x}$ obtained by differentiating once is known as first-order partial derivative, while $\frac{\partial^2 u}{\partial y \partial x}, \frac{\partial^2 u}{\partial y^2}, \frac{\partial^3 u}{\partial y \partial x \partial z}$ which are obtained by differentiating twice are known as second-order derivatives. 3rd order, 4th order derivatives involve 3, 4 times differentiation respectively.

Note 1: The crossed or mixed partial derivatives $\frac{\partial^2 f}{\partial y \partial x}$ and $\frac{\partial^2 f}{\partial x \partial y}$ are in general, equal

$$
\frac{\partial^2 f}{\partial y \partial x} = \frac{\partial^2 f}{\partial x \partial y}
$$

i.e., the order of differentiation is immaterial if the derivatives involved are continuous.

Note 2: In the subscript notation, the subscripts are written in the same order in which differentiation is carried out, while in the '∂' notation the order is opposite, for example,

$$
\frac{\partial^2 u}{\partial y \partial x} = \frac{\partial}{\partial y}\left(\frac{\partial u}{\partial x}\right) = f_{xy}
$$

Note 3: A function of 2 variables has two first-order derivatives, four second-order derivatives and $2^n$ of nth-order derivatives. A function of m independent variables will have $m^n$ derivatives of order n.

### WORKED OUT EXAMPLES

Example 1: Find the first order partial derivatives $\frac{\partial u}{\partial x}$ and $\frac{\partial u}{\partial y}$ when:

a) $u = e^{x \cos y}$ 
b) $u = \tan^{-1}\left(\frac{y}{x}\right)$ 
c) $u = \ln \left(\sqrt{x^2 + y^2}\right)$
## 3.2 PARTIAL DIFFERENTIATION

A partial derivative of a function of several variables is the ordinary derivative with respect to one of the variables when all the remaining variables are held constant. Partial differentiation is the process of finding partial derivatives. All the rules of differentiation applicable to functions of a single independent variable are also applicable in partial differentiation with the only difference that when the function is partially with respect to one variable, all the other variables are treated (temporarily) as constants.

Consider a function $f(x, y, z)$ of the three independent variables $x, y, z$ (refer Fig. 3.1).

1. Keeping $y$ and $z$ constant and varying only \( x \), the partial derivative of $f$ with respect to $x$ is denoted by

$$
f_x = \frac{\partial f}{\partial x} = \lim_{\Delta x \to 0} \frac{f(x+\Delta x, y, z) - f(x, y, z)}{\Delta x}
$$

and is called the partial derivative of $f$ with respect to $x$.

Partial derivatives of $f$ with respect to $y$ and $z$ can be defined similarly and are denoted by $f_y$ and $f_z$.
Notation: The partial derivative is also denoted by $D_1f$, $D_2f$, $D_3f$, or $D_xf$, $D_yf$, $D_zf$ where the subscripts $x, y, z$ indicate the variable w.r.t. which the partial differentiation is carried out. Thus
   

#### Solution:

a.

$$
\frac{\partial w}{\partial x} = \cos y \frac{\partial}{\partial x}(e^x) = e^x \cos y
$$

$$
\frac{\partial w}{\partial y} = e^x \frac{\partial}{\partial y}(\cos y) = -e^x \sin y
$$

b.

$$
\frac{\partial w}{\partial x} = \frac{1}{1 + \left(\frac{x}{y}\right)^2} \cdot \frac{\partial}{\partial x} \left(\frac{y}{x}\right) = \frac{-y}{x^2 + y^2}
$$

$$
\frac{\partial w}{\partial y} = \frac{1}{1 + \left(\frac{x}{y}\right)^2} \cdot \frac{\partial}{\partial y} \left(\frac{x}{y}\right) = \frac{x}{x^2 + y^2}
$$

c.

$$
\frac{\partial w}{\partial x} = \frac{1}{\sqrt{x^2 + y^2}} \cdot \frac{1}{2 \sqrt{x^2 + y^2}} \cdot \frac{\partial}{\partial x} \left( x^2 + y^2 \right) = \frac{x}{\sqrt{x^2 + y^2}}
$$

$$
\frac{\partial w}{\partial y} = \frac{1}{\sqrt{x^2 + y^2}} \cdot \frac{1}{2 \sqrt{x^2 + y^2}} \cdot \frac{\partial}{\partial y} \left( x^2 + y^2 \right) = \frac{y}{\sqrt{x^2 + y^2}}
$$

### Example 2:

Find the partial derivative of $f$ with respect to each of the independent variables:

a.

$$
f(x, y, z, w) = x^2e^{2y+3z} \cos(4w)
$$

$$
f_x = \frac{\partial f}{\partial x} = 2x e^{2y+3z} \cos(4w)
$$

$$
f_y = 2x^2 e^{2y+3z} \cos(4w) \cdot 2
$$

$$
f_z = 2x^2 e^{2y+3z} \cos(4w) \cdot 3
$$

$$
f_w = 2x^2 e^{2y+3z} \cdot -\sin(4w) \cdot 4
$$

b.

$$
f(r, \theta, z) = r(2 - \cos 2\theta) / (r^2 + z^2)
$$

$$
\frac{\partial f}{\partial r} = \frac{(r^2 - r^2)(2 - \cos 2\theta) - r(2 - \cos 2\theta) \cdot 2r}{(r^2 + z^2)^2}
$$


### Example 3:

Find $\frac{\partial^3 u}{\partial x \partial y \partial z}$ if $u = e^{x^2 + y^2 + z^2}$

Solution:

$$
\frac{\partial u}{\partial x} = 2xe^{x^2 + y^2 + z^2}
$$

$$
\frac{\partial^2 u}{\partial y \partial x} = 4xy e^{x^2 + y^2 + z^2}
$$

$$
\frac{\partial^3 u}{\partial z \partial y \partial x} = 8xyz e^{x^2 + y^2 + z^2}
$$

Thus

$$
\frac{\partial^3 u}{\partial x \partial y \partial z} = 8xyz e^{x^2 + y^2 + z^2}
$$

### Example 4:

Show that $V(x, y, z) = \cos 3x \cos 4y \sinh 5z$ satisfies Laplace's equation

$$
\frac{\partial^2 V}{\partial x^2} + \frac{\partial^2 V}{\partial y^2} + \frac{\partial^2 V}{\partial z^2} = 0
$$

Solution:

$$
V_{xx} = -3 \sin 3x \cdot \cos 4y \cdot \sinh 5z
$$

$$
V_{yy} = -16 \cos 3x \cdot \sin 4y \cdot \sinh 5z
$$

$$
V_{zz} = 25 \cos 3x \cdot \cos 4y \cdot \sinh 5z
$$

Adding (1), (2), and (3), we get

$$
V_{xx} + V_{yy} + V_{zz} = 0
$$



### Example 5:

If $u = e^{\alpha t} \cos(a \ln r)$, show that

$$
\frac{\partial^2 u}{\partial r^2} + \frac{1}{r} \frac{\partial u}{\partial r} + \frac{1}{r^2} \frac{\partial^2 u}{\partial \theta^2} = 0
$$

## Solution:

$$
u = e^{\alpha t} (\text{cos }a \ln r) \quad (1)
$$

$$
u_{rr} = e^{\alpha t} \left[ \frac{-1}{r^2} \sin(a \ln r) + \frac{\cos(a \ln r)}{r^2} \right] \quad (2)
$$

$$
u_{\theta\theta} = -ae^{\alpha t} \sin(a \ln r) \quad (3)
$$

$$
u_{t} = \alpha e^{\alpha t} \cos(a \ln r) \quad (4)
$$

using (1), (2), and (3)

$$
u_{rr} + \frac{1}{r^2}u_{\theta\theta} = e^{\alpha t} \left[\frac{ae^{\alpha t}}{r^2} \sin(a \ln r) - \frac{a^2}{r^2} \right] + \left(- \frac{ae^{\alpha t}}{r^2} \sin(a \ln r)\right) + \left(\frac{\alpha^2 e^{\alpha t}}{r^2}\right) = 0
$$

#### Example 6: 

If $u = \ln(x^3 + y^3 - \frac{x^2y - xy^2}{x^2+y^2})$, then show that $u_{xx} + 2u_{xy} + u_{yy} = 0$

Solution:

$$
u_x = \frac{3x^2 - 2xy - y^2}{(x^3 + y^3 - x^2y - xy^2) - \frac{xy(x+y)}{(x^2 + y^2)}} \quad (1)
$$

$$
u_y = \frac{3y^2 - 2xy - x^2}{(x^3 + y^3 - x^2y - xy^2) - \frac{xy(x+y)}{(x^2 + y^2)}} \quad (2)
$$

Adding (1) and (2), we get

$$
u_x + u_y = \frac{(3x^2 - 2xy - y^2) + (3y^2 - 2xy - x^2)}{(x^3 + y^3 - x^2y - xy^2)} = \frac{2(x+y)(x-y)}{x^2 + y^2} + 2xy \quad (3)
$$

Now

$$
u_{xx} + 2u_{xy} + u_{yy} = \frac{\partial^2 u}{\partial x^2} + 2 \frac{\partial^2 u}{\partial x \partial y} + \frac{\partial^2 u}{\partial y^2} = 0
$$



### EXERCISE

1. Find the first order partial derivatives of:
    - a. $u = x+y$
    - b. $u = \ln(x + \sqrt{x^2 - y^2})$
    - c. $u = \sin y$
    - d. $u = x^y$

Ans.
- a. $u_x = 1$, $u_y = 1$
- b. $u_x = \frac{1}{x + \sqrt{x^2 - y^2}} \times \left(1 + \frac{x}{\sqrt{x^2 - y^2}}\right)$, $u_y = \frac{-y}{(x + \sqrt{x^2 - y^2}) \sqrt{x^2 - y^2}}$
- c. $u_x = 0 \), \( u_y = \cos y$
- d. $u_x = yx^{y-1} \log x$, $u_y = x^y \log x$

2. Find the partial derivative of the given function w.r.t. each variable:
    - a. $f(x, y, z) = \sin^{-1}(y/z)$
    - b. $f(x, y, u, w) = (u^2 - w^2)\sin^{-1}(y/x)$
    - c. $f(x, y, r, s) = \sin 2x \sin 3y \cos 4s$
    - d. $f(x, y, r, s) = 4\sin 3y \sin 4s$

Ans.
- a. $f_x = 0$, $f_y = \frac{1}{z}$, $f_z = \frac{-y}{z^2 \sqrt{1 - y^2/z^2}}$
- b. $f_u = 2u \sin^{-1}(y/x)$, $f_w = -2w \sin^{-1}(y/x)$
- c. $f_r = 2 \cos 2x \cos 3r$, $f_s = 3 \cos 3y \cos 4s$
- d. $f_r = 3 \sin 2r \sin 3r$, $f_s = 4\sin 3y \sin 4s$

3. If $w = \ln(2x + 2y) \text{ and } u = 2x(y - 2y)$, prove that 

$$
\frac{\partial^2 w}{\partial x \partial y} = \frac{\partial^2 w}{\partial y^2}
$$

4. Verify that $w_{xy} = w_{yx}$ when 
   a. $u = \ln(2x + 3y)$
   b. $w = x^3y^2 + 3x^2y^4$
   c. $w = \tan^{-1} \frac{y}{x}$
   d. $w = \ln(x \sin x + \sin y)$

5. Show that $u_x + u_y = u$ if $u = e^{x+y}/(e^x + e^y)$.

6. Prove that $w = f(x + ct) + g(x - ct)$ satisfies the wave equation $\frac{\partial^2 w}{\partial t^2} = c^2 \frac{\partial^2 w}{\partial x^2}$ where c is a constant. Verify this when $w = 7\sin(3x + 5ct) + 9\cosh(5x - 5ct)$.

7. Show that $w_{xx} + w_{tt} = 0$ if $w = \sin(2x - 3ct)$.

8. If $w = x^4 + y^4 + z^4 + 2xyz$, prove that $w_{xx} + w_{yy} + w_{zz} = 6(x + y + z)$.

10. Verify that V satisfies Laplace's equation

$$
\frac{\partial^2 V}{\partial x^2} + \frac{\partial^2 V}{\partial y^2} + \frac{\partial^2 V}{\partial z^2} = 0
$$

   if (a) $V = x^2 + y^2 - 2z^2$, (b) $V = e^{x^2 + 4y} \cos 5z$, 
   (c) $V = \ln(x^2 + y^2 + z^2)$.

11. Find $\frac{\partial^3 u}{\partial x \partial y \partial z}$ if $u = e^{xyz}$.

12. Show that $w_{xx} + w_{yy} + w_{zz} = 0$ when

$$
w = \frac{y}{x} + \frac{z}{x} + \frac{x}{y} + \frac{z}{y} + \frac{x}{z} + \frac{y}{z}
$$

13. If $u = r^m$ prove that
  
  $$
    u_{xx} + u_{yy} + u_{zz} = m(m + 1)r^{m - 2}
   $$

where $r^2 = x^2 + y^2 + z^2$.

14. For $m = 2$ or $3$ show that $u = r^m(3 \cos^2 \theta - 1)$ satisfies the differential equation

$$
\frac{\partial}{\partial r} \left( r^2 \frac{\partial u}{\partial r} \right) + \frac{1}{\sin \theta} \frac{\partial}{\partial \theta} \left( \sin \theta \frac{\partial u}{\partial \theta} \right) = 0
$$

15. Prove that $\left( \frac{\partial^2 u}{\partial r^2} + \frac{1}{r} \frac{\partial u}{\partial r} + \frac{1}{r^2} \frac{\partial^2 u}{\partial \theta^2} \right) = 0$ if

$$
    u = \ln(x^2 + y^2) + \left( x + \frac{1}{x^2 + y^2} \right)
$$

   Hint: Prove and use the result $u_x + u_y + u_z = \left( \frac{1}{x + y + z} \right)$.

16. Prove (the Cauchy-Riemann equations in polar coordinates) $r u_r = v_{\theta}, r v_r = -u_{\theta}$ when

$$
u = r \cos (\cos r), \quad v = r \sin (\sin \theta)
$$

17. Show that $v_{xx} + v_{yy} - x^2 - y^2$.

18. Hint: Solve for $z = (y^2 - x^2) \ln (x - y)$.
    If $u = (x^2 + y^2) \ln (x - y)$.

19. Prove that $f(x, t) = a \sin bx \cdot \cos bt$ satisfies

$$
\frac{\partial^2 f}{\partial t^2} = c^2 \frac{\partial^2 f}{\partial x^2}
 $$

where $c = b$.

20. Show that $u_x + u_y = 0$ if $u = x - y$.
