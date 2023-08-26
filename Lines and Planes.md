# Lines
We can write lines in a couple different ways the regular slope intercept form like $y = \frac{2}{3} x + 1$there is also the *vector - valued function* where it's in the form of $r(t) = <x(t), y(t)> = <0, 1> + t<3, 2>$. The slope is represented by the **velocity vector** which follows $t$. The x intercept in this is represented by the *initial point* which is the first point that the vector starts from. 
If a line had a slope of $\frac{3}{4}$ then the velocity vector would be $v = <\Delta x, \Delta y> = <4, 3>$ 

velocity vectors could show the 'slope' of lines in $\mathbb{R}^3$ space. Like the line that passes through point $P(1, 2, 3)$ and $Q(3, 0, 7)$ has a velocity vector of $v = <2, -2, 4>$ 

**Vector equation** of line $L$ going through point $P=<x_0, y_0, z_0>$ and with velocity vector $v = <a, b, c>$ 
$$r(t) = <x_0, y_0, z_0> + t<a, b, c>$$ **Parametric equation** for the same line $L$ $$\begin{equation} \begin{split} x(t) &= x_0 + at \\ y(t) &= y_0 +bt \\ z(t) &= z_0 +ct \end{split} \end{equation}$$ **Symmetric equation** of the parametric equation $$\frac{x - x_0}{a} = \frac{y - y_0}{b} = \frac{z - z_0}{c}$$ **Skew lines** - two lines that are not parallel and do not intersect. two lines are parallel if the $v$ of the first matches the $v$ of the second. If lines do intersect, then they would meet at point $(x, y, z)$ at parameter values $t$ and $s$ 

# Planes
**Planes** are defined by knowing a point on the plane and the **normal vector**, which is perpendicular to the surface of the plane. Let $r$ be a point on the plane and $r_0$ be the point where normal vector $v = <a, b, c>$  intersects the plane. This plane could be described with $(r - r_0) \perp \vec{n}$. This is equal to $\vec{n} \cdot (r-r_0) = 0$, which is all equal to $$<a, b, c> \cdot <x - x_0, y - y_0, z - z_0> = 0$$ which is equal to $$ax + by + cz + d = 0$$ 