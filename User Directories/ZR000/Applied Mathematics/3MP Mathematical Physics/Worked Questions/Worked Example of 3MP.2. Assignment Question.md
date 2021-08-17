	
# Solution
Let
$$
    I(x)=\int_{-\infty}^{\infty} J(x-y)\left[\psi(y)-\psi(x)\right]dy
$$

Separate the integral into the regions such that we can dissolve the absolute value signs into normal brackets.
$$
    I(x)=\int_{-\infty}^{x} e^{-\alpha(x-y)}\left[\psi(y)-\psi(x)\right]dy+\int_{x}^{\infty} e^{\alpha(x-y)}\left[\psi(y)-\psi(x)\right]dy    
$$
$$
    =e^{-\alpha x}\int_{-\infty}^{x}e^{\alpha y}\psi(y)dy-\underbrace{e^{-\alpha x}\psi(x)\int_{-\infty}^{x}e^{\alpha y}dy}_{\frac{1}{\alpha}\psi(x)}+e^{\alpha x}\int_{x}^{\infty}e^{-\alpha y}\psi(y)dy-\underbrace{e^{\alpha x}\psi(x)\int_{x}^{\infty}e^{-\alpha y}dy}_{\frac{1}{\alpha}\psi(x)}
$$
$$
    =e^{-\alpha x}\int_{-\infty}^{x}e^{\alpha y}\psi(y)dy+e^{\alpha x}\int_{x}^{\infty}e^{-\alpha y}\psi(y)dy-\frac{2}{\alpha}\psi(x)
$$

Differentiating once, we get
$$
    I_x=-\alpha e^{-\alpha x}\int_{-\infty}^{x}e^{\alpha y}\psi(y)dy+e^{-\alpha x}e^{\alpha x}\psi(x)+\alpha e^{\alpha x}\int_{x}^{\infty}e^{-\alpha y}\psi(y)dy-e^{\alpha x}e^{-\alpha x}\psi(x)-\frac{2}{\alpha}\psi_x
$$
$$
    =-\alpha e^{-\alpha x}\int_{-\infty}^{x}e^{\alpha y}\psi(y)dy+\alpha e^{\alpha x}\int_{x}^{\infty}e^{-\alpha y}\psi(y)dy-\frac{2}{\alpha}\psi_x
$$

Differentiating again (doing all the work, yes),
$$
    I_{xx}=\alpha^2 e^{-\alpha x}\int_{-\infty}^{x}e^{\alpha y}\psi(y)dy-\alpha e^{-\alpha x}e^{\alpha x}\psi(x)+\alpha^2 e^{\alpha x}\int_{x}^{\infty}e^{-\alpha y}\psi(y)dy-\alpha e^{\alpha x}e^{-\alpha x}\psi(x)-\frac{2}{\alpha}\psi_{xx}
$$
$$
    =\alpha^2 \int_{-\infty}^{\infty}J(x-y)\psi(y)dy-2\alpha \psi(x)-\frac{2}{\alpha}\psi_{xx}
$$

Note that
$$
    I=\int_{-\infty}^{\infty}J(x-y)\psi(y)dy-\frac{2}{\alpha}\psi(x)
$$
and therefore we have
$$
    I = \frac{1}{\alpha^2}\left(I_{xx}+\frac{2}{\alpha}\psi_{xx}\right)
$$
$$
    I_{xx}=\alpha^2 I-\frac{2}{\alpha}\psi_{xx}
$$

The PDE is
$$
    i\psi_t-\frac{2}{\alpha}\left(\frac{\partial^2}{{\partial x}^2}-\alpha^2\right)^{-1}\psi_{xx}
$$

Substituting $\psi=e^{i(\omega t-kx)}$ takes us to the dispersion law:
$$
    i(i\omega)-\frac{2}{\alpha}\left(\frac{\partial^2}{{\partial x}^2}-\alpha^2\right)^{-1}(-ik)^2=0
$$
$$
    \omega=\frac{2}{\alpha}\left(\frac{\partial^2}{{\partial x}^2}-\alpha^2\right)^{-1}k^2
$$
$$
    \underbrace{\frac{\partial^2\omega}{{\partial x}^2}}_{0}-\alpha^2\omega=\frac{2}{\alpha}k^2
$$
$$
    \therefore\omega(k)=-2\alpha k^2
$$