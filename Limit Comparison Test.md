This test is when you find another series that is either larger or smaller than the target series and with the information you get from the second series, make conclusions about the first series.

Imagine you have series $\sum a_{n}$ and series $\sum b_{n}$. If $\lim_{n\to\infty} \frac{a_{n}}{b_{n}} = c$ and $c$ is both finite and positive, then $\sum a_{n}$ and $\sum b_{n}$ are either both convergent or both divergent.

**Ex:** Is this series converging or diverging $$\sum^{\infty}_{n=1}\frac{1}{2^{n} - 1}$$

$\sum b_{n}$ would be equal to $\sum \frac{1}{2^{n}}$ because $2^{n} > 2^{n} - 1$ which means that $\sum b_{n}$ is smaller than $\sum a_{n}$. With these series we would then:  

$$\begin{align}
\lim_{n\to\infty}&\frac{\frac{1}{2^{n}-1}}{\frac{1}{2^{n}}} \\
\lim_{n\to\infty}&\frac{2^{n}}{2^{n}-1}
\end{align}$$

which all equals 1. 1 is finite and positive, so $\sum a_{n}$ and $\sum b_{n}$ are either both convergent or both divergent. 
We can say that $\sum b_{n}$ is convergent because it is a geometric series with a $r = \frac{1}{2}$. So $\sum a_{n}$ is also **convergent**!
