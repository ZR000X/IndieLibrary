Index: [[Index for ZR000 Quantum Complexity]]

We are interested in the integral
$$I=\int_{-\infty}^{\infty} dx\exp\left(-ax^2+bx\right)$$
for constants $a,b$.

A neat way is to complete the square of the exponent,
$$-ax^2+bx=-\left(\sqrt{a}x-\frac{b}{2\sqrt{a}}\right)^2+\frac{b^2}{4a}$$

This turns out to be extremely useful because, letting
$$u=\sqrt{a}x+\frac{b}{2\sqrt{a}}$$
we have that $u$ has the same limits as $x$ since they are the infinities and $du=\sqrt{a}dx$. 

Substituting,
$$I=\frac{1}{\sqrt{a}}\exp\left(\frac{b^2}{4a}\right)\int_{-\infty}^{\infty} du\exp\left(-u^2\right)$$

The integral that's left is just the plain [[3MP. Calculation of the Gaussian Integral|Gaussian integral]], so $I=$
$$\int_{-\infty}^{\infty} dx\exp\left(-ax^2+bx\right)=\sqrt{\frac{\pi}{a}}\exp\left(\frac{b^2}{4a}\right)$$