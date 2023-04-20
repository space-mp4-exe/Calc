For this class we will use Maclaurin and Taylor series to find the series representation of certain functions.

Taylors series:

$$\sum^{\infty}_{n = 0}\frac{f^{n}(a)}{n!}(x-a)^{n}$$  
The difference between Taylor and Maclaurin series is that Maclaurin series are "centered at 0", which means that a in the equation equals 0.
We could use a Maclaurin series to find the series representation of $sin(x)$.
You can see in the definition of $M$ that $f(x)$ is being taken to the *nth* derivative, so we should first find a pattern in the derivatives of $f(x)$ to find a value of $M$.

The derivatives of $sin(x)$ are:

$$
\begin{aligned} 
f(x) &= sin(x) \\ 
f'(x) &= cos(x) \\
f''(x) &= -sin(x) \\
f'''(x)& = -cos(x) \\
f^{(4)}(x) &= sin(x)
\end{aligned}
$$

the values of those derivatives at zero (because this is a Maclaurin series) are:
$$\begin{aligned} 
f(0) &= 0 \\ 
f'(0) &= 1 \\
f''(0) &= 0 \\
f'''(0)& = -1 \\
f^{(4)}() &= 0
\end{aligned}$$ you can see a pattern that all the even derivatives of $f(x)$ are equal to zero, so we can just focus on the odd derivatives, which are either equal to 1 or -1 which means that it's alternating.
if we write out the series it will be equal to:
$$f(0) + \frac{f'(0)}{1!}x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!}x^3+...$$ if we plug in the numbers it is also equal to $$0 + \frac{x}{1!}+0-\frac{x^3}{3!}+...$$ 
if continue to simplfy the equation we get:
$$\frac{x}{1!}-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+... $$ There are two things that we can see from this series
1. The odd terms are negative
2. The numerator are odd powers
3. the denominator are ! of odd numbers
With this information we can write out the series to be 
$$\sum^{\infty}_{n=0} (-1)^n\frac{x^{2n+1}}{(2n+1)!} $$ 
$$|R_{n}| \leq \frac{M}{(n + 1)!} |x - a|^{n+1}$$
 $$ M \leq |f^{n+1}(x)|$$
