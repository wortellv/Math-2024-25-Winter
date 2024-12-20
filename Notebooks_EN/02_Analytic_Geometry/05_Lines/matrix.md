1)  The general equation of a sphere with center \((h, k, l)\) and radius \(r\) is:

$$
(x - h)^2 + (y - k)^2 + (z - l)^2 = r^2
$$

Given:
- Center \(P = (1, 2, 3)\), so \(h = 1\), \(k = 2\), and \(l = 3\),
- Radius \(r = 3\),

Substituting these values into the formula, we get:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 3^2
$$

Simplifying:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$


2)  To determine if the two spheres with equations 

$$
x^2 + y^2 + z^2 = 1
$$

and 

$$
x^2 + y^2 + z^2 = 2
$$

have any common points, we analyze whether there exist any points \((x, y, z)\) that satisfy both equations simultaneously.

 Combine the equations: Subtract the first equation from the second:

$$
(x^2 + y^2 + z^2) - (x^2 + y^2 + z^2) = 2 - 1
$$

This simplifies to:

$$
0 = 1
$$

which is a contradiction.



3)  To find the curve of intersection between the two spheres:

1. Equations of the spheres:
   - Sphere 1: $x^2 + y^2 + z^2 = 1$
   - Sphere 2: $(x-1)^2 + y^2 + z^2 = 1$

2. Expand the second equation:
   $$
   (x-1)^2 + y^2 + z^2 = x^2 - 2x + 1 + y^2 + z^2 = 1
   $$
   Simplifying:
   $$
   x^2 + y^2 + z^2 - 2x + 1 = 1
   $$
   $$
   x^2 + y^2 + z^2 - 2x = 0
   $$

3. Substitute Sphere 1 into the simplified Sphere 2:
   From Sphere 1, $x^2 + y^2 + z^2 = 1$. Substitute this into the equation $x^2 + y^2 + z^2 - 2x = 0$:
   $$
   1 - 2x = 0
   $$
   Solving for $x$:
   $$
   x = \frac{1}{2}
   $$

4. Equation of the curve:
   The curve of intersection lies in the plane $x = \frac{1}{2}$, and the points on this curve also satisfy the equation of Sphere 1, $x^2 + y^2 + z^2 = 1$. Substituting $x = \frac{1}{2}$ into Sphere 1:
   $$
   \left(\frac{1}{2}\right)^2 + y^2 + z^2 = 1
   $$
   Simplifying:
   $$
   \frac{1}{4} + y^2 + z^2 = 1
   $$
   $$
   y^2 + z^2 = \frac{3}{4}
   $$

   This represents a circle in the plane $x = \frac{1}{2}$ with radius $\frac{\sqrt{3}}{2}$ centered at $\left(\frac{1}{2}, 0, 0\right)$.

5. Final equation of the curve:
   The curve is given by:
   $$
   x = \frac{1}{2}, \quad y^2 + z^2 = \frac{3}{4}.
   $$


4) To find the equation of the tangent plane to the paraboloid 

$$
z = (x-1)^2 + y^2 + 1
$$

at the point \(P(1, 0, 1)\), we proceed as follows:

### Step 1: Compute partial derivatives
The general equation of the paraboloid is:

$$
z = (x-1)^2 + y^2 + 1.
$$

The partial derivatives with respect to \(x\) and \(y\) are:

$$
\frac{\partial z}{\partial x} = 2(x-1),
$$

$$
\frac{\partial z}{\partial y} = 2y.
$$

### Step 2: Evaluate partial derivatives at \(P(1, 0, 1)\)
At the point \(P(1, 0, 1)\):

$$
\frac{\partial z}{\partial x} = 2(1-1) = 0,
$$

$$
\frac{\partial z}{\partial y} = 2(0) = 0.
$$

### Step 3: Tangent plane equation
The equation of the tangent plane to a surface \(z = f(x, y)\) at a point \((x_0, y_0, z_0)\) is:

$$
z - z_0 = \frac{\partial z}{\partial x}(x_0, y_0)(x - x_0) + \frac{\partial z}{\partial y}(x_0, y_0)(y - y_0).
$$

Substitute \((x_0, y_0, z_0) = (1, 0, 1)\) and the partial derivatives:

$$
z - 1 = 0(x - 1) + 0(y - 0).
$$

This simplifies to:

$$
z = 1.
$$

### Final Answer:
The equation of the tangent plane is:

$$
z = 1.
$$