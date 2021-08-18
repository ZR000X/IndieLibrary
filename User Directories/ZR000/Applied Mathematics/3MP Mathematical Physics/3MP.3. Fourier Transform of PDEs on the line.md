Take a general Heat Equation,
$$\left\{\begin{matrix}\mathcal{L(\partial_t,\partial_x)u(x,t)=0}\\ \mathcal{L}=\partial_t-\kappa\partial_{xx} \\ u(x,0)=f(x)\end{matrix}\right.$$
where the boundaries are at the infinities.

Consider now that $u(x,t)$ is but a function of $x$ only; that is, take $t$ be a fixed parameter. We can write the function $u(x,y)$ as a Fourier integral:
$$u(x,t)=\int U(k,t)e^{-ikx}dk$$

We may then differentiate partially to obtain
$$u_{xx}=(-ik)^2\int U(k,t)e^{-ikx}dk=-k^2u$$
$$u_t=\int U_te^{-ikx}dk$$

Substituting these into the PDE gives us
$$\int e^{-ikx}\left(U_t+\kappa k^2U\right)dk=0$$
and so, since the inverse fourier transform of $0$ is $0$, we conclude
$$U_t+\kappa k^2U=0$$

This is an ODE for $U$ w.r.t. $t$ and can be solved by
$$U(k,t)=F(k)e^{-\kappa k^2 t}$$
 $$\therefore u(x,t)=\int F(k)e^{-\kappa k^2 t}e^{-ikx}dk$$
 
 Using the IC, we know that
 $$u(x,0)=f(x)=\int F(k)e^{-ikx}dk$$
 verifying that $F(k)$ is the fourier integral of $f(x)$.
 
 # The Convolution Theorem
 Suppose
 $$f(x)=\int F(k)e^{-ikx}dk$$
 $$g(x)=\int G(k)e^{-ikx}dk$$
 $$H(k)=F(k)G(k)$$
 $$h(x)=\int H(k)e^{-ikx}dk$$

What is the dependency of $h$ on $f,g$? Well,
$$h(x)=\int F(k)G(k)e^{-ikx}dk$$
$$h(x)=\int \left[\int F(k)e^{-ikx}dk\right]G(k)e^{-ikx}dk$$
$$h(x)=\int \left[\frac{1}{2\pi}\int f(x')e^{ikx'}dx'\right]G(k)e^{-ikx}dk$$
$$h(x)=\frac{1}{2\pi}\int f(x')\left[\int G(k)e^{-ik(x-x')}dk\right]dx'$$
$$h(x)=\frac{1}{2\pi}\int f(x')g(x-x')dx'$$

We call this quantity, 
$$f*g=\frac{1}{2\pi}\int f(x')g(x-x')dx'$$
the convolution of $f$ and $g$.