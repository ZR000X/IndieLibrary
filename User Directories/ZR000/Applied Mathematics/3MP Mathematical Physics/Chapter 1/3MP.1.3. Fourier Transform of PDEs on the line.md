Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.2. The Fourier Transform]]

Next: [[3MP.1.4. General Linear PDE with Constant Coefficients]]

---

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
 
 We now use the [[3MP. Convolution Theorem|convolution theorem]] to write
 $$u(x,t)=f(x)*g(x,t)$$
 where
 $$g(x,t)=\int e^{-\kappa k^2 t}e^{-ikx}dk$$
 
 We can use [[3MP. Calculation of Integral from 3MP.3.|this]] to work out the integral above (using $\kappa=\alpha^2$ in there) as
 $$g(x,t)=\sqrt{\frac{\pi}{\kappa t}}\exp\left(-\frac{x^2}{4\kappa t}\right)$$
 
 So $$u(x,t)=\frac{1}{2\pi}\int f(x)g(x-x',t)dx'$$
 or using the [[3MP. Influence Function|influence function]] we can write
 $$u(x,t)=\frac{1}{2\pi}\int f(x)\mathcal{G}(x,t;x',0)dx'$$
 where
 $$\mathcal{G}(x,t;x',t')=\frac{1}{2\pi}\sqrt{\frac{\pi}{\kappa (t-t')}}\exp\left(-\frac{(x-x')^2}{4\kappa (t-t')}\right)$$
 $$=\frac{1}{\sqrt{4\pi\kappa (t-t')}}\exp\left(-\frac{(x-x')^2}{4\kappa (t-t')}\right)$$
 
 ---
 Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.2. The Fourier Transform]]

Next: [[3MP.1.4. General Linear PDE with Constant Coefficients]]
 
 