
### 3.7 EULER'S THEOREM

#### Homogeneous Function

A polynomial in \( x \) and \( y \) is said to be homogeneous if all its terms are of the same degree. Generalizing this property to include non-polynomials, a function \( f(x, y) \) in two variables \( x \) and \( y \) is said to be a homogeneous function of degree \( n \) if for any positive number \( \lambda \),

\[
f(\lambda x, \lambda y) = \lambda^n f(x, y)
\]

This definition can be further enlarged to include transcendental functions also as follows. A function \( f(x, y) \) is said to be homogeneous of degree \( n \) if it can be expressed as

\[
x^n \phi \left(\frac{y}{x}\right) \quad \text{or} \quad y^n \psi \left(\frac{x}{y}\right)
\]

Here \( n \) need not be an integer, \( n \) could be positive, negative or zero.



#### Example:
1. \( 3x^2 - 2xy + \frac{15}{2}y^2 \) is homogeneous of degree 2
2. \( \frac{\sqrt{5}x + \sqrt{5}y}{y - x} \) is homogeneous of degree \( -\frac{1}{2} \)
3. \( \sin\left(\frac{x}{y}\right) + \tan^{-1}\left(\frac{x}{y}\right) \) is homogeneous of degree zero
4. \( \left(\frac{x+y}{xy + \frac{3}{2}e^y}\right)y^{-\frac{3}{5}} \) is not homogeneous
5. \( x^{\frac{1}{3}}y^{-\frac{3}{2}} + x^{\frac{2}{3}}y^{-\frac{1}{3}} \) is not homogeneous

Homogeneous function \( f \) of three variables \( x \), \( y \), \( z \) of degree \( n \) can be expressed as

\[
f = x^n \phi \left(\frac{y}{x}, \frac{z}{x}\right) \quad \text{or} \quad y^n \psi \left(\frac{x}{y}, \frac{z}{y}\right) \quad \text{or} \quad z^n \chi \left(\frac{x}{z}, \frac{y}{z}\right)
\]

### Euler’s Theorem on Homogeneous Functions

#### Theorem:
If \( f \) is a homogeneous function of \( x \), \( y \) of degree \( n \) then

\[
x \frac{\partial f}{\partial x} + y \frac{\partial f}{\partial y} = n f \quad \text{(1)}
\]

#### Proof:
Since \( f \) is a homogeneous function



Here is the markdown version of the provided content:

---

## Worked Out Examples

**Example 1:** Find the degree of the following homogeneous functions:

a. \( x^2 - 2xy + y^2 \)

b. \( \log y - \log x \)

c. \( (\sqrt{x^2 + y^2})^3 \)

d. \( x^{\frac{1}{3}} y^{-\frac{4}{3}} \tan^{-1}(y/x) \)

e. \( 3x^2 y^2 + 5x^2 y^2 + 4x^4 \)

f. \( [x^2/(x^2+y^2)]^{\frac{1}{3}} \)

**Ans:**

a. 2

b. \( \log y - \log x = \ln \left( \frac{y}{x} \right) = x^0 \ln \left( \frac{y}{x} \right) \) degree zero

c. \( (\sqrt{x^2+y^2})^3 = x^3 \sqrt{1 + \left(\frac{y}{x}\right)^2} \)

d. \( x^{\frac{1}{3}} y^{-\frac{4}{3}} \tan^{-1}(y/x) = x^{-1} \cdot x^{1-\frac{1}{3}} \cdot \tan^{-1} \frac{y}{x} = -x^{-1} y^{-\frac{4}{3}} \tan^{-1} x^{-1} \)

   degree: -1

e. degree 4

f. \[ \left[ \frac{x^2}{x^2+y^2} \right]^{\frac{1}{3}} = x^{-\frac{4}{3}} \left[ 1 + \left(\frac{y}{x}\right)^2 \right] \]

   degree = -2/3.

**Example 2:** Verify Euler’s theorem for the following functions by computing both sides of Euler’s Equation (1) directly:

i. \( (ax+by)^{\frac{1}{3}} \)

ii. \( x^{\frac{1}{3}} y^{-\frac{4}{3}} \tan^{-1}(y/x) \)

**Solution:**

i. \( f = (ax+by)^{\frac{1}{3}} \) is a homogeneous function of degree \( \frac{1}{3} \)

Differentiating \( f \) partially w.r.t. \( x \) and \( y \), we get

\[ f_x = \frac{\partial f}{\partial x} = \frac{1}{3} (ax+by)^{-\frac{2}{3}} \cdot a \]

\[ f_y = \frac{\partial f}{\partial y} = \frac{1}{3} (ax+by)^{-\frac{2}{3}} \cdot b \]

Multiplying by \( x \) and \( y \) and adding, we get the L.H.S. of (1)

\[ x f_x + y f_y = \frac{1}{3} (ax+by)^{-\frac{2}{3}} ax + \frac{1}{3} (ax+by)^{-\frac{2}{3}} by \]

\[ = \frac{1}{3} (ax+by)^{-\frac{2}{3}} (ax+by) \]

\[ = \frac{1}{3} (ax+by)^{\frac{1}{3}} = \frac{1}{3} f \]

Since \( f \) is a homogeneous function of degree \( \frac{1}{3} \), the R.H.S. of (1) is \( nf = \frac{1}{3} f \).

Thus

\[ x f_x + y f_y = L.H.S. = \frac{1}{3} f = R.H.S. \]

ii. \( f = x^{\frac{1}{3}} y^{-\frac{4}{3}} \tan^{-1}(y/x) \) is homogeneous function of degree \(-1\)

\[ f_x = \frac{1}{3} x^{-\frac{2}{3}} y^{-\frac{4}{3}} \tan^{-1}\left(\frac{y}{x}\right) + x^{\frac{1}{3}} y^{-\frac{7}{3}} \cdot \frac{-y}{x^2} \]

\[ f_y = x^{\frac{1}{3}} \left( \frac{4}{3} \right) y^{-\frac{7}{3}} \tan^{-1} \left( \frac{y}{x} \right) + x^{\frac{1}{3}} y^{-\frac{4}{3}} \frac{1}{x^2} \]

\[ f_y x + f_x y = \frac{1}{3} x^{-\frac{2}{3}} y^{-\frac{4}{3}} \tan^{-1}(y/x) + x^{\frac{1}{3}} y^{-\frac{4}{3}} \cdot \frac{1}{x^2} \]

\[ -x^{\frac{1}{3}} y^{-\frac{4}{3}} \tan^{-1} \left( \frac{y}{x} \right) - x f_x \]

**Example 3:** If \( u = \log \frac{x^2+y^2}{x+y} \), prove that

\[ xu_x + yu_y = 1 \]

**Solution:**

Let

\[ f = e^u = \frac{x^2+y^2}{x+y} = \frac{x^2}{1+\left(\frac{y}{x}\right)^2} \]

\[ x f_p \left( \frac{y}{x} \right) \]

f is a homogeneous function of degree 1.

Applying Euler’s theorem for the function \( f \), we get

\[ x f_x + y f_y = nf = f \]

Since \( f = e^u \), \( f_x = e^u u_x, f_y = e^u u_y \)

\[ e^u u_x + ye^u u_y = f e^u \]

since \( e^u \neq 0 \), \( xu_x + yu_y = 1 \).

**Example 4:** Show that \( xu_x + yu_y + zu_z = -2 \cot u \) when

\[ u = \cos^{-1} \left( \frac{x^3+y^3+z^3}{ax+by+cz} \right) \]

**Solution:**

Let

\[ f = \cos u = \frac{x^3+y^3+z^3}{ax+by+cz} \]

Here \( f \) is a homogeneous function of degree 2 in the three variables \( x, y, z \). By Euler’s theorems 

Here is the markdown version of the provided content:

---

\[x f_x + y f_y + z f_z = 2 f.\]

Now differentiating \(f\) with respect to \(x, y, z\) respectively, we get

\[f_x = - \sin u \cdot u_x, f_y = -\sin u \cdot u_y, f_z = - \sin u \cdot u_z.\]

Substituting

\[x f_x + y f_y + z f_z = -\sin u (x u_x + y u_y + z u_z) = 2f\]

\[= 2 \cos u\]

or

\[x u_x + y u_y + z u_z = \frac{-2 \cos u}{\sin u} = -2 \cot u\]

**Example 5:** Prove that \(x u_x + y u_y = \frac{5}{2} \tan u\) if

\[u = \sin^{-1} \left(\frac{x^3 + y^3}{\sqrt{x + y^5}}\right)\]

**Solution:** Let

\[f = \sin u = \frac{x^3 + y^3}{\sqrt{x + y^5}}\]

then \(f\) is a homogeneous function of degree \(\frac{5}{2}\) since

\[f = \frac{x^3}{\sqrt{x}} \left(\frac{1+y/x^3}{1+(y/x)^5}\right) = x^{\frac{5}{2}} \phi(y/x).\]

Applying Euler’s theorem for \(f\), we have

\[x f_x + y f_y = nf = \frac{5}{2} f.\]

Since \(f = \sin u, f_x = \cos u \cdot u_x, f_y = \cos u \cdot u_y\) so that

\[x \cdot \cos u u_x + y \cos u u_y = \frac{5}{2} f = \frac{5}{2} \sin u\]

\[x u_x + y u_y = \frac{5}{2} \cdot \frac{\sin u}{\cos u} = \frac{5}{2} \tan u\]

**Example 6:** If \(u = x^3 y^2 \sin^{-1}(y/x)\) show that

\[x u_x + y u_y = 5u\]

and

\[x^2 u_{xx} + 2x y u_{xy} + y^2 u_{yy} = 20u\]

**Solution:** Rewriting

\[u = \frac{x^2}{x} \cdot x^3 y^2 \sin^{-1} \left(\frac{y}{x}\right) = x^5 \left(\frac{y}{x}\right)^2 \sin^{-1} \left(\frac{y}{x}\right)\]

\[u = x^5 \phi(y/x)\]

so \(u\) is a homogeneous function of degree 5.

Applying Euler’s theorem to \(u\), we get

\[x u_x + y u_y = nu = 5u\]

Differentiating the above equation partially w.r.t. \(x\) and \(y\), we have

\[x u_{xx} + y u_{xy} + y u_{yx} = 5u_x\]

\[x u_{xy} + y u_{yy} = 5u_y\]

Multiplying by \(x\) and \(y\) and adding, we get

\[(x^2 u_{xx} + xu_x + xy u_{xy}) + (x y u_{xy} + y u_y + y^2 u_{yy})\]

\[= 5(x u_x + y u_y)\]

or

\[x^2 u_{xx} + 2x y u_{xy} + y^2 u_{yy} = (5-1)(x u_x + y u_y)\]

\[= (5-1) \cdot 5 u = 20 u\]

Here we replaced \(x u_x + y u_y\) by \(5u\) (from Euler’s theorem) and assumed \(u_{yx} = u_{xy}\).

---

### Exercise

1. Determine the degree of the following homogeneous functions:

   a. \(\sqrt{x^2-xy}\)

   b. \(\sin^{-1} \left(\frac{y}{x}\right)\)

   c. \(\frac{x^3-y^3}{x+y}\)

   d. \(\frac{ax+by+cz}{A x^6 + B y^6 + C z^6}\)

   e. \(x^2 (x^2-y^2)^{\frac{1}{3}} (x^2+y^2)^{\frac{2}{3}}\)

   f. \(2x^3 y^2 + 3x^2 y^3 + 6xy^4 - 8y^5\)

**Ans.:**

   a. 1

   b. 0

   c. 2

   d. 4

   e. 4/3

   f. 5

2. Verify Euler’s theorem

   a. \(\sqrt{x^2+y^2}\)

   b. \(\cos^{-1} \left(\frac{y}{x}\right)\)

   c. \((ax+by)^{\frac{2}{3}}\)

   d. \(x^2(x^2-y^2)^{\frac{1}{3}} (x^2+y^2)^3\)

   e. \(x^2 y^2/(x+y)\)

   f. \(\cos^{-1} \left(\frac{y}{x}\right) + \cot^{-1} \left(\frac{y}{x}\right)\)

   g. \((x^3 + y^3)/(x^{\frac{1}{4}}-y^{\frac{1}{4}})\)

   h. \(xy/(x+y)\)

   i. \((x^2+y^2)^{-1}\)

   j. \(\frac{1}{x}+\frac{1}{y} + \frac{\log x - \log y}{x^2+y^2}\)

   k. \(\log \frac{x^4+y^4}{x+y}\)

--- 

Let me know if you need any other help!


3. If \( f(x, y) = \sec^{-1} \left( \frac{x^3 + y^3}{x - y} \right) \) show that \( x f_x + y f_y = 2 \cot f \).

4. If \( u = \sin^{-1} \left( \frac{x}{y} \right) + \tan^{-1} \left( \frac{y}{x} \right) \) show that \( x u_x + y u_y = 0 \).

5. If \( u = \ln \left( \frac{x^4 + y^4}{x + y} \right) \) then \( x f_x + y f_y = 3 \).

6. If \( u = \sin^{-1} \left( \frac{x^2 + y^2}{x + y} \right) \) show that \( x u_x + y u_y = \tan u \) and \( x^2 u_{xx} + 2xy u_{xy} + y^2 u_{yy} = \tan^3 u \).

7. If \( u = \sin^{-1} \left( \frac{x^2}{\sqrt{x+y}} \right) \) then \( x u_x + y u_y = 3 \tan u \).

8. If \( f = x g \left( \frac{y}{x} \right) + h \left( \frac{x}{y} \right) \) show that \( x^2 f_{xy} + 2xy f_{yy} + y^2 f_{yy} = 0 \).

9. If \( u = y e^{\frac{x}{y}} + x^2 \tan^{-1} \left( \frac{x}{y} \right) \) show that
   \[
   x u_x + y u_y = 2u
   \]
   and
   \[
   x^2 u_{xx} + 2xy u_{xy} + y^2 u_{yy} = 2u.
   \]

10. If \( u = \tan u = \frac{x^3 + y^3}{x - y} \) show that \( x u_x + y u_y = \sin 2u \) and \( x^2 u_{xx} + 2xy u_{xy} + y^2 u_{yy} = 2 \cos 3u \cdot \sin u \).

11. If \( u = \cos u = \frac{x^2 + y^2}{\sqrt{x+y}} \) then \( x u_x + y u_y = -\frac{3}{2} \cot u \).

12. If \( u = \frac{x^2 y^2}{(x + y)} \) then show that \( x u_x + y u_y = 3u \ln u \).

13. If \( u = 3x^4 \cot^{-1} \left( \frac{y}{x} \right) + 16y^4 \cos^{-1} \left( \frac{x}{y} \right) \) then prove that \( x u_{xx} + 2xy u_{xy} + y^2 u_{yy} = 12u \).

14. Show that
    \[
    \tan \frac{u}{12} \left( \frac{13}{12} u + \frac{\tan^2 u}{12} \right) + \left( \sqrt{x} + \sqrt{y} \right) \sin^2 u = x^3 + y^3.
    \]

15. Verify Euler’s theorem for
    \[
    f = \frac{z}{x+y} + \frac{y}{z+x} + \frac{x}{y+z}.
    \]

16. If \( u = \cos^{-1} \left( \frac{x^5 - 2y^5 + 6x^5}{\sqrt{x^3 + y^3 + z^3}} \right) \) then show that \( x u_x + y u_y + z u_z = -\frac{7}{2} \cot u \).

17. Prove that
    \[
    \left( x \frac{\partial}{\partial x} + y \frac{\partial}{\partial y} \right)^3 f = x^3 f_{xxx} + 3x^2 y f_{xxy} + 3xy^2 f_{xyy} + y^3 f_{yyy} = n(n-1)(n-2)f
    \]
    if \( f(x, y) \) is a homogeneous function of degree \( n \).

18. Prove that \( 4x f_x + 4y f_y + \sin 2f = 0 \) if \( \left( \sqrt{x} + \sqrt{y} \right) \cot f = x - y = 0 \).

19. Show that \( x u_x + y u_y + z u_z = 0 \) when \( u = \frac{y}{z} + \frac{z}{x} \).

**Hint:** \( u \) is a homogeneous function of degree zero.

## 3.8 Jacobian

Jacobian\(^*\) is a functional determinant (whose elements are functions) which is very useful in the transformation of variables from Cartesian to polar, cylindrical, and spherical coordinates in multiple integrals (Chapter 7). Let \( u(x, y) \) and \( v(x, y) \) be two given functions of two independent variables \( x \) and \( y \).

The **Jacobian** of \( u, v \) with respect to \( x, y \), denoted by \( J \left( \frac{u, v}{x, y} \right) \) or \( \frac{\partial (u,v)}{\partial (x,y)} \) is a second-order functional determinant defined as
\[
J \left( \frac{u, v}{x, y} \right) = \frac{\partial(u, v)}{\partial(x, y)} = 
\begin{vmatrix}
\frac{\partial u}{\partial x} & \frac{\partial u}{\partial y} \\
\frac{\partial v}{\partial x} & \frac{\partial v}{\partial y}
\end{vmatrix}.
\]
**Note:** Obviously \( J \left( \frac{u,v}{x,y} \right) = \frac{\partial(u,v)}{\partial(w,u)} = 1 \).

Similarly, the Jacobian of three functions \( u, v, w \) of three independent variables \( x, y, z \) is defined as
\[
J \left( \frac{u, v, w}{x, y, z} \right) = \frac{\partial (u, v, w)}{\partial (x, y, z)} = 
\begin{vmatrix}
\frac{\partial u}{\partial x} & \frac{\partial u}{\partial y} & \frac{\partial u}{\partial z} \\
\frac{\partial v}{\partial x} & \frac{\partial v}{\partial y} & \frac{\partial v}{\partial z} \\
\frac{\partial w}{\partial x} & \frac{\partial w}{\partial y} & \frac{\partial w}{\partial z}
\end{vmatrix}.
\]

\(^*\)Carl Gustav Jacob Jacobi (1804–1851), German mathematician.

In a similar way, Jacobian of \( n \) functions in \( n \) variables can be defined.

## Two Important Properties of Jacobians

**Book Work I.** If \( J = \frac{\partial(u, v)}{\partial(x, y)} \) and \( J^* = \frac{\partial(x, y)}{\partial(u, v)} \) then \( J \cdot J^* = 1 \).

i.e., \( J = \frac{\partial(u, v)}{\partial(x, y)} = \frac{1}{J^*} = \frac{1}{\frac{\partial(x, y)}{\partial(u, v)}} \).

### Proof:
Let 
\[
u = f(x, y) \quad \text{and} \quad v = g(x, y) \tag{1}
\]
be two given functions in terms of \( x \) and \( y \), which are transformations from \( u, v \) to \( x, y \). Solving (1) for \( x \) and \( y \), we get \( x \) and \( y \) as functions in terms of the two independent variables \( u \) and \( v \):
\[
x = \phi(u, v) \quad \text{and} \quad y = \psi(u, v) \tag{2}
\]
known as inverse transformations from \( x, y \) to \( u, v \). Differentiating partially with respect to \( u \) and \( v \), we get:
\[
1 = \frac{\partial u}{\partial u} = \frac{\partial u}{\partial x} \frac{\partial x}{\partial u} + \frac{\partial u}{\partial y} \frac{\partial y}{\partial u} = u_x x_u + u_y y_u \tag{3}
\]
\[
0 = \frac{\partial u}{\partial v} = \frac{\partial u}{\partial x} \frac{\partial x}{\partial v} + \frac{\partial u}{\partial y} \frac{\partial y}{\partial v} = u_x x_v + u_y y_v \tag{4}
\]
\[
0 = \frac{\partial v}{\partial u} = \frac{\partial v}{\partial x} \frac{\partial x}{\partial u} + \frac{\partial v}{\partial y} \frac{\partial y}{\partial u} = v_x x_u + v_y y_u \tag{5}
\]
\[
1 = \frac{\partial v}{\partial v} = \frac{\partial v}{\partial x} \frac{\partial x}{\partial v} + \frac{\partial v}{\partial y} \frac{\partial y}{\partial v} = v_x x_v + v_y y_v \tag{6}
\]

**Consider:**
\[
J \cdot J^* = 
\begin{vmatrix}
u_x & u_y \\
v_x & v_y
\end{vmatrix}
\cdot
\begin{vmatrix}
x_u & x_v \\
y_u & y_v
\end{vmatrix}
=
\begin{vmatrix}
u_x & u_y \\
v_x & v_y
\end{vmatrix}
\begin{vmatrix}
x_u & x_v \\
y_u & y_v
\end{vmatrix}
\]
By interchanging rows and columns in the second determinant.

Multiplying the determinant row-wise,
\[
J \cdot J^* = \begin{vmatrix} u_x x_u + u_y y_u & u_x x_v + u_y y_v \\ v_x x_u + v_y y_u & v_x x_v + v_y y_v \end{vmatrix}
\]

Substituting (3), (4), (5), (6) above, we get:
\[
J \cdot J^* = \begin{vmatrix} 1 & 0 \\ 0 & 1 \end{vmatrix} = 1
\]

---

## Chain Rule for Jacobians

**Book Work II.** If \( u, v \) are functions of \( r, s \) and \( r, s \) are themselves functions of \( x, y \) then
\[
\frac{\partial (u, v)}{\partial (x, y)} = \frac{\partial (u, v)}{\partial (r, s)} \cdot \frac{\partial (r, s)}{\partial (x, y)} \Rightarrow J \left( \frac{u, v}{x, y} \right) = J \left( \frac{u, v}{r, s} \right) \cdot J \left( \frac{r, s}{x, y} \right).
\]

### Proof:
Differentiating \( u, v \) partially with respect to \( x, y \):
\[
\frac{\partial u}{\partial x} = \frac{\partial u}{\partial r} \frac{\partial r}{\partial x} + \frac{\partial u}{\partial s} \frac{\partial s}{\partial x} \tag{1}
\]
\[
\frac{\partial u}{\partial y} = \frac{\partial u}{\partial r} \frac{\partial r}{\partial y} + \frac{\partial u}{\partial s} \frac{\partial s}{\partial y} \tag{2}
\]
\[
\frac{\partial v}{\partial x} = \frac{\partial v}{\partial r} \frac{\partial r}{\partial x} + \frac{\partial v}{\partial s} \frac{\partial s}{\partial x} \tag{3}
\]
\[
\frac{\partial v}{\partial y} = \frac{\partial v}{\partial r} \frac{\partial r}{\partial y} + \frac{\partial v}{\partial s} \frac{\partial s}{\partial y} \tag{4}
\]

From the definition of Jacobian:
\[
\frac{\partial(u, v)}{\partial(r, s)} \cdot \frac{\partial(r, s)}{\partial(x, y)} =
\begin{vmatrix}
u_r & u_s \\
v_r & v_s
\end{vmatrix}
\cdot
\begin{vmatrix}
r_x & r_y \\
s_x & s_y
\end{vmatrix}
\]
By interchanging the rows and columns in the second determinant.

Multiplying the determinant row-wise:
\[
= \begin{vmatrix} u_r r_x + u_s s_x & u_r r_y + u_s s_y \\ v_r r_x + v_s s_x & v_r r_y + v_s s_y \end{vmatrix}
\]

Using (1), (2), (3), (4):
\[
\frac{\partial(u, v)}{\partial(r, s)} \cdot \frac{\partial(r, s)}{\partial(x, y)} = 
\begin{vmatrix}
u_x & u_y \\
v_x & v_y
\end{vmatrix}
= \frac{\partial(u, v)}{\partial(x, y)}.
\]

Thus Jacobians behave in a certain way like derivatives.

**Note:** All the above results of the Jacobian of two variables can be extended similarly to \( n \) (any number of) variables.

---

### Standard Jacobians

**Jacobians for change of variables from Cartesian coordinates to:**

- **i.** Polar coordinates: \( x = r \cos \theta, \, y = r \sin \theta \)
-


- **ii.** cylindrical coordinates: \( x = r \cos \theta \), \( y = r \sin \theta \), \( z = z \)

- **iii.** spherical coordinates: \( x = r \sin \theta \cos \phi \), \( y = r \sin \theta \sin \phi \), \( z = r \cos \theta \)

---

### Example 1: Find the Jacobian \( \frac{\partial(u, v)}{\partial(x, y)} \) in each of the following:

i. \( u = x \sin y \), \( v = y \sin x \)

ii. \( u = e^x \sin y \), \( v = x + \log \sin y \)

**Solution:**

By definition:
\[
\frac{\partial(u, v)}{\partial(x, y)} = \begin{vmatrix} \frac{\partial u}{\partial x} & \frac{\partial u}{\partial y} \\ \frac{\partial v}{\partial x} & \frac{\partial v}{\partial y} \end{vmatrix}
\]

i. \( u = x \sin y \), \( v = y \sin x \):

\[
u_x = \sin y, \quad u_y = x \cos y, \quad v_x = y \cos x, \quad v_y = \sin x
\]

Jacobian:
\[
= \begin{vmatrix} \sin y & x \cos y \\ y \cos x & \sin x \end{vmatrix} = \sin x \sin y - xy \cos x \cos y
\]

ii. \( u = e^x \sin y \), \( v = x + \log \sin y \):

\[
u_x = e^x \sin y, \quad u_y = e^x \cos y, \quad v_x = 1, \quad v_y = \frac{\cos y}{\sin y}
\]

Jacobian:
\[
= \begin{vmatrix} e^x \sin y & e^x \cos y \\ 1 & \frac{\cos y}{\sin y} \end{vmatrix} = e^x \cos y - e^x \cos y = 0
\]

---

### Example 2: Calculate \( J = \frac{\partial(u, v)}{\partial(x, y)} \) and \( J^* = \frac{\partial(x, y)}{\partial(u, v)} \), and verify that \( J \cdot J^* = 1 \) is given.

i. \( u = x + \frac{y^2}{x}, v = \frac{y^2}{x} \)

ii. \( x = e^{u} \cos v, y = e^{u} \sin v \)

**Solution:**

i. \( u = x + \frac{y^2}{x}, v = \frac{y^2}{x} \)

\[
J = \frac{\partial(u, v)}{\partial(x, y)} = \begin{vmatrix} 1 - \frac{y^2}{x^2} & \frac{2y}{x} \\ -\frac{y^2}{x^2} & \frac{2y}{x} \end{vmatrix} = \frac{2y}{x} - \frac{2y^3}{x^3} + \frac{2y^3}{x^3} = \frac{2y}{x}
\]

Solving for \( x, y \) in terms of \( u, v \), we have:
\[
u = x + \frac{y^2}{x} = x + v \quad \therefore \quad x = u - v, \quad y = \frac{\sqrt{v x}}{x}
\]

---

### Continuing from the previous section...

1. \( x = r \cos \theta \), \( y = r \sin \theta \), so \( x_r = \cos \theta \), \( x_\theta = -r \sin \theta \), \( y_r = \sin \theta \), \( y_\theta = r \cos \theta \)

\[
\frac{\partial(x, y)}{\partial(r, \theta)} = \begin{vmatrix} x_r & x_\theta \\ y_r & y_\theta \end{vmatrix} = \begin{vmatrix} \cos \theta & -r \sin \theta \\ \sin \theta & r \cos \theta \end{vmatrix} = r(\cos^2 \theta + \sin^2 \theta) = r
\]

Solving for \( r, \theta \) we have:
\[
r = \sqrt{x^2 + y^2}, \quad \theta = \tan^{-1} \left(\frac{y}{x}\right)
\]

so:
\[
r_x = \frac{x}{r}, \quad r_y = \frac{y}{r}, \quad \theta_x = \frac{-y}{r^2}, \quad \theta_y = \frac{x}{r^2}
\]

\[
\frac{\partial(r, \theta)}{\partial(x, y)} = \begin{vmatrix} \frac{x}{r} & \frac{y}{r} \\ \frac{-y}{r^2} & \frac{x}{r^2} \end{vmatrix} = \frac{x^2}{r^3} + \frac{y^2}{r^3} = \frac{r^2}{r^3} = \frac{1}{r}
\]

\[
J = \frac{\partial(x, y)}{\partial(r, \theta)} = r(\cos^2 \theta + \sin^2 \theta) = r
\]

\[
J^* = \frac{\partial(r, \theta)}{\partial(x, y)} = \frac{1}{J} = \frac{1}{r}
\]

2. \( x = r \sin \theta \cos \phi \), \( y = r \sin \theta \sin \phi \), \( z = r \cos \theta \)

\[
\frac{\partial(x, y, z)}{\partial(r, \theta, \phi)} = \begin{vmatrix} \sin \theta \cos \phi & r \cos \theta \cos \phi & -r \sin \theta \sin \phi \\ \sin \theta \sin \phi & r \cos \theta \sin \phi & r \sin \theta \cos \phi \\ \cos \theta & -r \sin \theta & 0 \end{vmatrix} = r^2 \sin \theta \cos^2 \theta + r^2 \sin \theta \sin^2 \theta = r^2 \sin \theta
\]

Using property (ii):
\[
\frac{\partial(r, \theta, \phi)}{\partial(x, y, z)} = \frac{1}{\frac{\partial(x, y, z)}{\partial(r, \theta, \phi)}} = \frac{1}{r^2 \sin \theta}
\]



\[ Y^2 = u x, \, Y^2 = v(u-v) \quad \therefore \quad Y = \sqrt{u(v-v)} \]

Expanding the determinant:
\[
\begin{aligned}
&\mathcal{J}^* = \begin{vmatrix}
\frac{\partial(x, y)}{\partial(u, v)} & \frac{\partial(x, y)}{\partial(u, w)} \\
x_u y_u & x_w y_w
\end{vmatrix} = \frac{1}{\sqrt{v(u-v)}}\begin{vmatrix}
1 & -1 \\
\frac{1}{2} & -\frac{1}{2} (u-2v)
\end{vmatrix} = \frac{1}{\sqrt{v(u-v)}} \left[\frac{u-2v}{2} - v\right] = \frac{x}{2y} 
\end{aligned}
\]

Verification:
\[
\mathcal{J} \cdot \mathcal{J}^* = \frac{2y \cdot x}{x \cdot 2y} = 1
\]

### ii. \( x = e^u \cos v, y = e^u \sin v \)
\[
J = \begin{vmatrix}
\frac{\partial(x, y)}{\partial(u, v)} 
\end{vmatrix} = 
\begin{vmatrix}
e^u \cos v & -e^u \sin v \\
e^u \sin v & e^u \cos v
\end{vmatrix} = e^{2u}(\cos^2 v + \sin^2 v) = e^{2u}
\]

Solving for \( u, v \) in terms of \( x, y \):
\[
\begin{aligned}
& \tan v = \frac{e^u \sin v}{e^u \cos v} = \frac{y}{x}, \quad v = \tan^{-1} \frac{y}{x} \\
& x^2 + y^2 = e^{2u} (\cos^2 v + \sin^2 v) = e^{2u}
\end{aligned}
\]

\[
\therefore u = \frac{1}{2} \ln (x^2 + y^2)
\]

\[
\therefore \mathcal{J}^* = \begin{vmatrix}
\frac{\partial(u, v)}{\partial(x, y)}
\end{vmatrix} = \frac{x}{x^2 + y^2}, \quad \frac{y}{x^2 + y^2}
\]

Verification:
\[
\mathcal{J} \cdot \mathcal{J}^* = \frac{1}{e^{2u}} = 1
\]

### Example 3: 
Calculate \( \frac{\partial(x, y, z)}{\partial(u, v, w)} \) if \( u = \frac{2y}{x}, v = \frac{3x}{y}, w = \frac{4y}{z} \).

**Solution:**
\[
\begin{vmatrix}
\frac{\partial(x, y, z)}{\partial(u, v, w)} 
\end{vmatrix} =
\begin{vmatrix}
\frac{-2y}{x^2} & \frac{2x}{y^2} & \frac{2y}{z^2} \\
\frac{3z}{y} & \frac{-3z}{x} & \frac{3x}{y^2} \\
\frac{4y}{z} & \frac{4x}{z} & \frac{-4xy}{z^2}
\end{vmatrix} 
\]

### Example 4: 
Calculate \( \frac{\partial(u, v)}{\partial(r, \theta)} \) if \( u = 2a xy, v = a(x^2 - y^2) \), where \( x = r \cos \theta \), \( y = r \sin \theta \).

**Solution:**
\[
\begin{aligned}
&\text{Since } u, v \text{ are functions of } x, y \text{ which are themselves functions of } r, \theta, \text{ use chain rule for Jacobians.} \\
&\frac{\partial(u, v)}{\partial(r, \theta)} = 
\begin{vmatrix}
\frac{\partial(u, v)}{\partial(x, y)} & \frac{\partial(x, y)}{\partial(r, \theta)}
\end{vmatrix} 
\end{aligned}
\]

Given \( u = 2a xy \), \( v = a(x^2 - y^2) \), \( u_x = 2ay \), \( u_y = 2ax \), \( v_x = 2ax \), \( v_y = -2ay \).

\[
\begin{aligned}
& \frac{\partial(u, v)}{\partial(x, y)} = \begin{vmatrix}
2ay & 2ax \\
2ax & -2ay
\end{vmatrix} 
\end{aligned}
\]

Since \( x^2 + y^2 = r^2 \), \( \cos^2 \theta + \sin^2 \theta = r^2 \)

\[
\therefore \quad \frac{\partial(u, v)}{\partial(r, \theta)} = 
\begin{vmatrix}
-\frac{4a^2 r^2}{r^2 + x^2}
\end{vmatrix} 
= -4a^2 r^2 
\]

### Example 5:
If \( x = \sqrt{uww} \), \( y = \sqrt{uwu} \), \( z = \sqrt{wu} \), and \( u = r \sin \theta \cdot \cos \phi \), \( v = r \sin \theta \sin \phi \), \( w = r \cos \theta \), calculate \( \frac{\partial(x, y, z)}{\partial(r, \theta, \phi)} \).

**Solution:**
\[
\begin{aligned}
&\text{Since } x, y, z \text{ are functions of } u, v, w \text{ which are in turn functions of } r, \theta, \phi, \text{ use chain rule for Jacobians.}
\end{aligned}
\]

\[
\frac{\partial(x, y, z)}{\partial(r, \theta, \phi)} = 
\frac{\partial(x, y, z)}{\partial(u, v, w)} 
\cdot 
\frac{\partial(u, v, w)}{\partial(r, \theta, \phi)}
\]

Consider:
\[
\frac{\partial(x, y, z)}{\partial(u, v, w)} = 
\begin{vmatrix}
x_u & x_v & x_w \\
y_u & y_v & y_w \\
z_u & z_v & z_w
\end{vmatrix}
\]
Here's the content from the second image converted into markdown:


\[
\begin{vmatrix}
0 & \frac{1}{2} \frac{w}{u} & \frac{1}{2} \frac{v}{w} \\
\frac{1}{2} \frac{w}{u} & 0 & \frac{1}{2} \frac{u}{v} \\
\frac{1}{2} \frac{v}{w} & \frac{1}{2} \frac{u}{v} & 0
\end{vmatrix} = \frac{1}{8}
\begin{vmatrix}
\frac{v w}{u} & \frac{v w}{u v} & \frac{v w}{u w} \\
\frac{v w}{u v} & \frac{v w}{v} & \frac{v w}{v w} \\
\frac{v w}{u w} & \frac{v w}{v w} & \frac{v w}{w}
\end{vmatrix} = \frac{2}{8} = \frac{1}{4}
\]

We know already that the Jacobian for spherical coordinates is:
\[
\frac{\partial(u, v, w)}{\partial(r, \theta, \phi)} = r^2 \sin \theta
\]

Thus:
\[
\frac{\partial(x, y, z)}{\partial(u, v, w)} \cdot \frac{\partial(u, v, w)}{\partial(r, \theta, \phi)} = \frac{1}{4} r^2 \sin \theta
\]

### Example 6:
Calculate \(\frac{\partial(u, v, w)}{\partial(x, y, z)}\) if \( u = x/\sqrt{1-r^2}, v = y/\sqrt{1-r^2}, w = z/\sqrt{1-r^2} \), where \( r^2 = x^2 + y^2 + z^2 \).

**Solution:**
Given \( r^2 = x^2 + y^2 + z^2, r = \sqrt{x^2 + y^2 + z^2}, r_x = \frac{1}{2}\frac{1}{\sqrt{x^2 + y^2 + z^2}} \cdot 2x \), Similarly \( r_y = \frac{y}{r}, r_z = \frac{z}{r} \).

Differentiating \( u = x/\sqrt{1-r^2} \) with respect to \( x \), we get:
\[
\begin{aligned}
& u_x = \frac{1}{\sqrt{1-r^2}} + x \cdot \left(-\frac{1}{2}\right) \cdot \frac{-2r}{(1-r^2)^{\frac{3}{2}}} \cdot r_x \\
& u_x = \frac{1}{\sqrt{1-r^2}} + \frac{r x}{(1-r^2)^{\frac{3}{2}}} = \frac{(1-r^2) + x^2}{(1-r^2)^{\frac{3}{2}}}
\end{aligned}
\]

Put \( e = (1-r^2)^{\frac{3}{2}}, \) so \( u_x = \frac{1-r^2 + x^2}{e} \).

By symmetry:
\[
v_y = \frac{(1-r^2) + y^2}{e}, \quad w_z = \frac{(1-r^2) + z^2}{e}
\]

Differentiating \( u \) with respect to \( y \), we get:
\[
u_y = -x \cdot \left(-\frac{1}{2}\right) \cdot \frac{-2r}{(1-r^2)^{\frac{3}{2}}} \cdot \frac{xy}{r} = \frac{xy}{e}
\]

In a similar way, we have:
\[
\begin{aligned}
& u_z = \frac{xz}{e}, \quad v_x = \frac{xy}{e}, \quad v_z = \frac{yz}{e} \\
& w_x = \frac{xz}{e}, \quad w_y = \frac{yz}{e}
\end{aligned}
\]

Thus:
\[
\frac{\partial(u, v, w)}{\partial(x, y, z)} = 
\begin{vmatrix}
\frac{(1-r^2) + x^2}{e} & \frac{xy}{e} & \frac{xz}{e} \\
\frac{xy}{e} & \frac{(1-r^2) + y^2}{e} & \frac{yz}{e} \\
\frac{xz}{e} & \frac{yz}{e} & \frac{(1-r^2) + z^2}{e}
\end{vmatrix} = \frac{1}{(1-r^2)^{\frac{3}{2}}}
\]

This simplifies to:
\[
= (1-r^2)^{-2} [ (1-r^2 + x^2)((1-r^2) + y^2)((1-r^2) + z^2) - y^2z^2 ] = (1-r^2)^{-2}(1-r^2) = (1-r^2)^{-3/2}
\]

### Example 7:
Verify the chain rule for Jacobians if \( x = u, y = u \tan v, z = w \).

**Solution:**
\[
J = \frac{\partial(x, y, z)}{\partial(u, v, w)} = 
\begin{vmatrix}
1 & 0 & 0 \\
\tan v & u \sec^2 v & 0 \\
0 & 0 & 1
\end{vmatrix} = u \sec^2 v
\]

Solving for \( u, v, w \) in terms of \( x, y, z \) we have \( u = x, \tan v = \frac{y}{u}, w = z, \tan^{-1} \frac{y}{x}, u = z \).

Thus:
\[
J^* = \frac{\partial(u, v, w)}{\partial(x, y, z)} = 
\begin{vmatrix}
1 & -\frac{y}{x^2 + y^2} & 0 \\
0 & \frac{x}{x^2 + y^2} & 0 \\
0 & 0 & 1
\end{vmatrix} = \frac{1}{u \sec^2 v}
\]

Thus \( J \cdot J^* = u \sec^2 v \cdot \frac{1}{u \sec^2 v} = 1 \).


Let me know if you need anything else!

Certainly! Here's the content from the images transcribed into Markdown:

---

### Exercise

**Find the Jacobian \(\frac{\partial(u,v)}{\partial(x,y)}\) when**

1. \(u = 3x + 5y, v = 4x - 3y\)  
   **Ans.** \(-29\)

2. \(x + y = u, y = uv\)  
   **Ans.** \((x + y)^{-1}\)

   **Hint:** Solving \(u = x + y, v = y/(x + y)\)

3. \(u = (x + y)/(1 - xy), v = \tan^{-1}x + \tan^{-1}y\)  
   **Ans.** \(0\)

**Verify the chain rule for Jacobians**

i.e.,  
\[
J \cdot J^* = \frac{\partial(u,v)}{\partial(x,y)} \cdot \frac{\partial(x,y)}{\partial(u,v)} = 1 \quad \text{for the following}
\]

4. \(x = u(1 - v), y = uv\)  
   **Ans.** \(J = u, J^* = (x + y)^{-1} = u^{-1}\)

5. \(u = x + y, v = xy\)  
   **Ans.** \(J = x - y\)

6. Show that \(\frac{\partial(u,v)}{\partial(r,\theta)} = -6r^3\sin 2\theta\) given \(u = x^2 - 2y^2, v = 2x^2 - y^2\) and \(x = r\cos\theta, y = r\sin\theta\).  
   **Hint:** Use \(\frac{\partial(u,v)}{\partial(r,\theta)} = \frac{\partial(u,v)}{\partial(x,y)} \cdot \frac{\partial(x,y)}{\partial(r,\theta)}\). Also \(\frac{\partial(x,y)}{\partial(r,\theta)} = r\).

7. Calculate the Jacobian of \(u, v, w\) w.r.t. \(x, y, z\) when \(u = yz/x, v = zx/y, w = xy/z\)  
   **Ans.** \(4\)

8. Find \(\frac{\partial(u,v)}{\partial(r,\theta)}\) if \(u = 2xy, v = x^2 - y^2\) and \(x = r\cos\theta, y = r\sin\theta\).  
   **Ans.** \(4r^3\)

9. \(u = x^2 + y^2, v = y, x = r\cos\theta, y = r\sin\theta\).  
   **Ans.** \(2xr\)

10. If \(x = u^2 + y, y = u w^2\) and \(u = x^2 - y^2, v = x y\) find \(\frac{\partial(x,y)}{\partial(u,v)}\).  
   **Hint:** Use \(\frac{\partial(x,y)}{\partial(u,v)} = \frac{\partial(x,y)}{\partial(u,w)} \cdot \frac{\partial(u,w)}{\partial(u,v)}\) (chain rule).  
   **Ans.** \(6x^2y(x^2 + y^2)(x^2 - y^2)\)

11. Find \(\frac{\partial(u,v,w)}{\partial(x,y,z)}\) if \(u = x^2, v = \sin y, w = e^{-3z}\)  
   **Ans.** \(-6e^{-3z}\cos y\)

12. If \(u = x + y + z, wv = y + z, wuw = z\) find \(\frac{\partial(x,y,z)}{\partial(u,v,w)}\)  
   **Ans.** \(u^2v\)

13. \(u = xyz, v = xy + yz + zx, w = x + y + z\)  
    **Ans.** \((x - y)(y - z)(z - x)\)

14. \(u = \frac{1}{2}(u^2 - v^2), v = uv, z = w\)  
    **Ans.** \((u^2 + v^2)^{-1}\)

15. \(u = 3x + 2y - z, v = x - y + z, w = x + 2y - z\)  
    **Ans.** \(-2\)

---

### Functional Dependence

Let \(u = f(x, y)\), \(v = \phi(x, y)\) be two given differentiable functions of the two independent variables \(x\) and \(y\). Suppose these functions \(u\) and \(v\) are connected by a relation \(F(u, v) = 0\), where \(F\) is differentiable. Then these functions \(u\) and \(v\) are said to be functionally dependent on one another (i.e., one function say \(u\) is a function of the second function \(v\)) if the partial derivatives \(u_x\), \(u_y\), \(v_x\) and \(v_y\) are not all zero simultaneously.

**Necessary and sufficient condition** for functional dependence can be expressed in terms of a determinant as follows: Differentiating \(F(u, v) = 0\) partially w.r.t. \(x\) and \(y\), we get:

\[
\frac{\partial F}{\partial u} \cdot \frac{\partial u}{\partial x} + \frac{\partial F}{\partial v} \cdot \frac{\partial v}{\partial x} = 0
\]

\[
\frac{\partial F}{\partial u} \cdot \frac{\partial u}{\partial y} + \frac{\partial F}{\partial v} \cdot \frac{\partial v}{\partial y} = 0
\]

A non-trivial solution \(F_u \neq 0, F_v \neq 0\) to this system exists if the coefficient determinant is zero.

\[
\begin{vmatrix}
u_x & v_x \\
u_y & v_y \\
\end{vmatrix}
= 0
\]

**Result:** Two functions \(u\) and \(v\) are functionally dependent if their Jacobian

---

### Exercise (continued)

5. \(u = x^2 + y^2 + 2xy + 2x + 2y, v = e^x \cdot e^y\)  
   **Ans.** Dependent, \(u = (\log v)^2 + 2 \log v\)

6. \(u = x + y + z, v = x^2 + y^2 + z^2, w = x^3 + y^3 + z^3 - 3xyz\)  
   **Ans.** Dependent, \(2w = u(3v - u^2)\)

7. \(u = x \sin z, v = x^2 \cos z, w = x^2 e^{2y}\)  
   **Ans.** Dependent, \(u^2 + v^2 = w\)

8. \(u = x + y + z, v = x^3 + y^3 + z^3 - 3xyz, w = x^2 + y^2 + z^2 - xy - yz - zx\)  
   **Ans.** Dependent, \(uw = v\)

9. \(u = 4x^2 + 9y^2 + 16z^2, v = 2x + 3y + 4z, w = 12xy + 16xz + 24yz\)  
   **Ans.** Dependent, \(v^2 - u = w = 0\)

10. \(u = \frac{3x^2}{2(y+z)}, v = \frac{2(y+z)}{3(x-y)^2}, w = \frac{x-y}{x}\)  
    **Ans.** Dependent, \(uvw^2 = 1\)

11. \(u = \frac{x}{y-z}, v = \frac{y}{z-x}, w = \frac{z}{x-y}\)  
    **Ans.** Dependent, \(uv + w + uw + uv + 1 = 0\)

12. \(u = \sin^{-1}x + \sin^{-1}y, v = x \sqrt{1 - y^2} + y \sqrt{1 - x^2}\)  
    **Ans.** Dependent, \(v = \sin u\)

---

### Errors and Approximations

If \(z = f(x, y)\), then the total differential of \(z\), denoted by \(dz\), is given by

\[
dz = \frac{\partial f}{\partial x} dx + \frac{\partial f}{\partial y} dy
\]

If \(x\) increases by an increment \(\Delta x\) and \(y\) increases by an increment \(\Delta y\), then the total increment in \(z\), denoted by \(\Delta z\), is

\



Here's the content from the image transcribed into Markdown:

---

5. \(u = x^2 + y^2 + 2xy + 2x + 2y, v = e^x \cdot e^y\)  
   **Ans.** Dependent, \(u = (\log v)^2 + 2 \log v\)

6. \(u = x + y + z, v = x^2 + y^2 + z^2, w = x^3 + y^3 + z^3 - 3xyz\)  
   **Ans.** Dependent, \(2w = u(3v - u^2)\)

7. \(u = x \sin z, v = x^2 \cos z, w = x^2 e^{2y}\)  
   **Ans.** Dependent, \(u^2 + v^2 = w\)

8. \(u = x + y + z, v = x^3 + y^3 + z^3 - 3xyz, w = x^2 + y^2 + z^2 - xy - yz - zx\)  
   **Ans.** Dependent, \(uw = v\)

9. \(u = 4x^2 + 9y^2 + 16z^2, v = 2x + 3y + 4z, w = 12xy + 16xz + 24yz\)  
   **Ans.** Dependent, \(v^2 - u = w = 0\)

10. \(u = \frac{3x^2}{2(y+z)}, v = \frac{2(y+z)}{3(x-y)^2}, w = \frac{x-y}{x}\)  
    **Ans.** Dependent, \(uvw^2 = 1\)

11. \(u = \frac{x}{y-z}, v = \frac{y}{z-x}, w = \frac{z}{x-y}\)  
    **Ans.** Dependent, \(uv + w + uw + uv + 1 = 0\)

12. \(u = \sin^{-1}x + \sin^{-1}y, v = x \sqrt{1 - y^2} + y \sqrt{1 - x^2}\)  
    **Ans.** Dependent, \(v = \sin u\)

---

### 3.10 Errors and Approximations

If \(z = f(x, y)\), then the total differential of \(z\), denoted by \(dz\), is given by

\[
dz = \frac{\partial f}{\partial x} dx + \frac{\partial f}{\partial y} dy
\]

If \(x\) increases by an increment \(\Delta x\) and \(y\) increases by an increment \(\Delta y\), then the total increment in \(z\), denoted by \(\Delta z\), is

\[
\Delta z = f(x + \Delta x, y + \Delta y) - f(x, y)
\]

or

\[
f(x + \Delta x, y + \Delta y) = f(x, y) + \Delta z
\]

But \(\Delta z \approx dz\).

Replacing \(dz\) by (1), we have the approximate formula

\[
f(x + \Delta x, y + \Delta y) \approx f(x, y) + \frac{\partial f(x, y)}{\partial x} \Delta x + \frac{\partial f(x, y)}{\partial y} \Delta y
\]

Thus, the value of a function at a point can be obtained approximately if the value of the function and its derivatives at a neighboring point are known.

Errors in measured data will result in error in the estimated value. For example, a small error in the measurement of the radius of a sphere will introduce a corresponding error in the volume of the sphere \(V = \frac{4\pi}{3} r^3\). Absolute error, denoted by \(\Delta x\), is the error in \(x\). Error may be positive or negative. Relative or proportional error in \(x\) is \(\frac{\Delta x}{x}\) or \(\frac{dx}{x}\) since \(\Delta x = dx\). Percentage error in \(x\) is given by \(100 \frac{dx}{x}\).

**Example:** If the error is 0.05 cm in measuring a dimension of length of 2 cm, then the absolute error is 0.05 cm, the relative error is \(\frac{0.05}{2} = 0.025\) cm, and the percentage error is \(100 \times 0.025 = 2.5\).

For a function \(z = f(x, y)\), the actual error \(\Delta z\) in \(z\) can be calculated approximately by using the differential \(dz\), for given errors \(\Delta x\), \(\Delta y\) in \(x\) and \(y\) respectively.

---

### Worked Out Examples

**Example 1:** Using differentials, calculate approximately the value of \(f(0.999)\) where \(f(x) = 2x^4 + 7x^3 - 8x^2 + 3x + 1\).

**Solution:** Choose \(x = 1\) and \(\Delta x = -0.001\) so that \(x + \Delta x = 1 + (-0.001) = 0.999\). Thus to calculate

\[
f(0.999) = f(x + \Delta x) = f(x) + \Delta f
\]

\[
\approx f(x) + f'(x)\Delta x \approx f(1) + f'(1)(-0.001)
\]

Here \(f(1) = 2.1 + 7.1 - 8.1 + 3.1 + 1 = 5\) and 

\[
f'(x) = 8x^3 + 21x^2 + 16x + 3
\]

so

\[
f'(1) = 8.1 + 21.1 + 16.1 + 3 = 16
\]

Thus the approximate value of

\[
f(0.999) \approx 5 + 16(-0.001) = 5 - 0.016 = 4.984
\]

---

Certainly! Here's the content from the image written in Markdown:

---

**Example 2**: Considering the volume of a spherical shell as an increment of volume of a sphere, calculate approximately the volume of a spherical shell whose inner diameter is 8 inches and whose thickness is \(\frac{1}{16}\) inch (Fig. 3.2).

![Fig. 3.2](path/to/image.png)

**Solution**: Volume of a sphere of radius \(r\) is \(V = \frac{4}{3} \pi r^3\). Now the volume of the spherical shell \(\Delta V\) is the difference between volume \(V_o\) of outer sphere and volume \(V_i\) of inner sphere. Thus volume of the spherical shell is \(\Delta V = V_o - V_i\). Here radius of the outer sphere \(r = 4\) in (diameter is 8 inches) choose \(r = 4\) and \(dr = \frac{1}{16}\).

Then 
\[
V\left(4 + \frac{1}{16}\right) - V(4) = V(r + \Delta r) - V(r) = \Delta V \approx dV = \frac{4}{3} \cdot 3\pi r^2 dr \text{ at } r = 4 \text{ and } dr = \frac{1}{16}
\]
\[
= 4\pi (4)^2 \left(\frac{1}{16}\right) = 4\pi \text{ cubic inches.}
\]

---

**Example 3**: The time \(T\) of a complete oscillation of a simple pendulum of length \(L\) is governed by the equation \(T = 2\pi \sqrt{\frac{L}{g}}\) where \(g\) is a constant.

**i**. Find the approximate error in the calculated value of \(T\) corresponding to an error of 2% in the value of \(L\).

**ii**. By what percentage should the length be changed in order to correct a loss of 2 minutes per day?

**Solution**:

**i**. Taking log: \(\ln T = \ln 2\pi + \frac{1}{2} \ln L - \frac{1}{2} \ln g\).

Differentiating \(\frac{dT}{T} = 0 + \frac{1}{2} \cdot \frac{dL}{L} - \frac{1}{2} \cdot \frac{dg}{g}\).

Error relation: \(\frac{dT}{T} = \frac{1}{2} \frac{dL}{L}\).

Error in value of \(L\) is 2% i.e., \(\frac{dL}{L} \times 100 = 2\).

Then \(100 \times \frac{dT}{T} = \frac{1}{2} \cdot 2 \times \frac{dL}{L} \times 100 = \frac{1}{2} \times 2 = 1\). The percentage error in calculating value of \(T\) is 1.

**ii**. Loss of error in value of \(T\) is 2 minutes per day i.e., \(\frac{dT}{T} = (-2) \times \frac{1}{60} \times \frac{1}{24}\).

From the error relation
\[
\frac{dT}{T} \times 100 = -2 \times \frac{1}{60} \times \frac{1}{24} \times 100 = \frac{1 \cdot dL}{2 \cdot L} \times 100
\]
or \(100 \times \frac{dL}{L} = -\frac{1}{360} \times 100 = -0.2777 \approx -0.278\%\).

---

**Example 4**: The diameter and height of a right circular cylinder are measured to be 5 and 8 inches respectively. If each of these dimensions may be in error by ±0.1 inch, find the relative percentage error in volume of the cylinder.

**Solution**: Let \(x\) be the diameter and \(y\) be the height of the cylinder then
\[
V = \text{volume of cylinder} = \pi \left(\frac{x}{2}\right)^2 y = \frac{1}{4} \pi x^2 y. \quad \left(\text{radius} = \frac{x}{2}\right)
\]
Differential:
\[
dV = \frac{1}{4} \pi \cdot 2xy \cdot dx + \frac{1}{4} \pi x^2 dy
\]
\[
100 \times \frac{dV}{V} = \frac{2dx}{x} \times 100 + \frac{dy}{y} \times 100
\]

Given \(x = \text{diameter} = 5\) inches, \(y = \text{height} = 8\) inches, error \(dx = dy = \pm 0.1\). So
\[
100 \times \frac{dV}{V} = \pm \left(2 \cdot \frac{0.1}{5} + \frac{0.1}{8}\right) = \pm 0.0525
\]
Thus the percentage error in volume is \(\pm 0.0525\).

---

**Exercise**

1. Using differential, calculate approximately:

    (a) \((2.98)^3\) (b) \(\sqrt[4]{4.05}\) (c) \(\left(1 + \frac{2.1}{3}\right)^{4}\) (d) \((83.7)^{1/4}\) (e) \(\sqrt{(1.997)}\) where \(y(x) = x^4 - 2x^3 + 9x + 7\)

    **Hint**: Choose \(y = f(x)\), \(x\), and \(\Delta x\) as follows
    
    a. \(x^3\), \(x = 3\), \(\Delta x = -0.02\)
    
    b. \(y = \sqrt{x}\), \(x = 4\), \(\Delta x = 0.5\)
    
    c. \(y = \left(1 + \frac{x}{2}\right)^2\), \(x = 0.1\)
    
    d. \(y = x^{1/4}\), \(x = 81\), \(\Delta x = 2.7\)

---

This content has been transcribed in markdown format, including equations, examples, and exercises.


Certainly! Here is the content from the image written in Markdown:

---

**Answers**:

1. **(a)** 26.46, **(b)** 2.13, **(c)** 0.475, **(d)** 3.025, **(e)** 24.949

2. If the radius of a sphere is measured as 5 inches with a possible error of 0.02 inches, find approximately the greatest possible error and percentage error in the computed value of the volume.

   **Hint**: 
   \[
   V = \frac{4}{3}\pi r^3, \ dV = 4\pi r^2 dr, \ r = 5, \ dr = 0.02, \ dV = \pm 2\pi, \ V = \frac{500\pi}{3}
   \]

   **Answer**: 
   \[
   \pm 0.012, \ \pm 1.2\%
   \]

3. The quantity \(Q\) of water flowing over a V-notch is given by the formula \(Q = cH^{5/2}\) where \(H\) is the head of water and \(c\) is a constant. Find the error in \(Q\) if the error in \(H\) is 1.5%.

   **Hint**: 
   \[
   \frac{dQ}{Q} = \frac{5}{2} \frac{dH}{H} = \frac{5}{2} (1.5)
   \]

   **Answer**: 
   \[
   3.75\%
   \]

4. Calculate the percentage increase in the pressure \(p\) corresponding to a reduction of \(\frac{1}{2}\%\) in the volume \(V\), if the \(p\) and \(V\) are related by \(pV^{1.4} = c\) where \(c\) is a constant.

   **Hint**: 
   \[
   \text{Hint:} \ 100 \times \frac{dp}{p} = -1.4 \frac{dV}{V} \times 100 = (-1.4) \times \left(-\frac{1}{2}\right)
   \]

   **Answer**: 
   \[
   0.7
   \]

5. Find the possible error in (a) surface area (b) volume of a sphere of radius \(r\) if \(r\) is measured as 18.5 inches with a possible error of 0.1 inch.

   **Answer**: 
   \[
   \text{(a)} \ 14.8\pi \ \text{sq. in} \quad \text{(b)} \ 136.97\pi \ \text{cubic inch}
   \]

6. Show that the relative error in \(c\) due to a given error in \(\theta\) is minimum when \(\theta = 45^\circ\) if \(c = k \tan \theta\).

   **Hint**: 
   \[
   \frac{dc}{c} = \frac{2d\theta}{\sin 2\theta} \quad \text{minimum when} \ \sin 2\theta \ \text{is greatest i.e.,} \ 2\theta = 90.
   \]

7. Considering the area of a circular ring as an increment of area of a circle, find approximately the area of a ring whose inner and outer radii are 3 and 3.02 respectively.

   **Hint**: 
   \[
   A = \pi r^2, \quad \text{Area of circular ring} = A(3.02) - A(3) = 2\pi r \ dr \ \text{with} \ r = 3, \ dr = 0.02
   \]

   **Answer**: 
   \[
   0.12\pi
   \]

8. Find the percentage error in calculated value of volume of a right circular cone whose altitude is the same as the base radius and is measured as 5 inches with a possible error of 0.02 inches.

   **Hint**: 
   \[
   V = \frac{1}{3}\pi r^2 h = \frac{1}{3}\pi r^3 \ \text{(as} \ r = h), \ \frac{dV}{V} = \frac{3dr}{r}, \ r = 5, \ dr = 0.02
   \]

   **Answer**: 
   \[
   1.2\%
   \]

9. Calculate the error in \(R\) if \(R = E/l\) and possible errors in \(E\) and \(l\) are 20% and 10% respectively.

   **Hint**: 
   \[
   \frac{dR}{R} \times 100 = \left(\frac{dE}{E} - \frac{dl}{l}\right) \times 100 = 20 - 10 = 10
   \]

   **Answer**: 
   \[
   10\%
   \]

10. The diameter and the height of a right circular cylinder are measured as 4 cm and 6 cm respectively, with a possible error of 0.1 cm. Find approximately the maximum possible error in the computed value of the volume and surface area.

   **Hint**: 
   \[
   V = \pi r^2 h = \frac{\pi D^2 H}{4}, \ dV = \frac{\pi}{4} [2D HdD + D^2 dH], \ S = 2\pi rh = \pi DH, \ dS = \pi [HdD + DdH].
   \]

   **Answer**: 
   \[
   1.6\pi \ \text{cu. cm}; \ \pi \ \text{sq. cm}
   \]

---

### **3.11 DIFFERENTIATION UNDER INTEGRAL SIGN: LEIBNITZ'S RULE**

We know from the fundamental theorem on integral calculus that if \(f(x)\) is a continuous function and
\[
\phi(x) = \int_a^x f(t)dt, \text{then}
\]
\[
\frac{d\phi}{dx} = f(x) = \frac{d}{dx} \int_a^x f(t)dt = f(x)
\]
i.e., the derivative of a definite integral w.r.t. the upper limit is equal to the integrand in which the variable of integration \(t\) is replaced by the upper limit \(x\).

**Example 1**: 
\[
(i) \ \frac{d}{dx} \int_1^x \frac{1}{t} dt = \frac{1}{x}, \quad x > 0
\]
Now if \(F(x)\) is some antiderivative of a continuous function \(f(x)\), then the Newton-Leibnitz formula \(\int_a^b f(x)dx = F(b) - F(a)\) yields a practical and convenient method of computing definite integrals in cases where the anti-derivative of the integrand is known. This general method has extended.

---

This content has been transcribed in markdown format, including equations, examples, and answers.
