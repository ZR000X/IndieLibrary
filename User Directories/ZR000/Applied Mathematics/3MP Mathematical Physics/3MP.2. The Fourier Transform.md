Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1. The Dispersion Relation]]

Next: [[3MP.3. Fourier Transform of PDEs on the line]]

---

Take an arbitrary PDE
$$\left\{\begin{matrix}\mathcal{L(\partial_t,\partial_x)u(x,t)=0}\\ u(x,0)=f(x) \\ u(-L,t)=u(L,t)=0 \end{matrix}\right.$$

The solution is known by the Fourier series:
$$u(x,t)=\sum_{k=-\infty}^{\infty}F_n e^{-\kappa k_n^2 t-i k_n x},~~~k_n=\frac{\pi n}{L}$$ where $$F_n=\frac{1}{2L}\int_{-L}^L f(x)e^{ik_n x}dx$$

We wish to side-step the complications of the boundary conditions by taking the physicists' approach of sending $L\to\infty$.

# The Fourier Integral Transform
We begin with arbitrary Fourier series on the interval $[-L,L]$:
$$f(x)=\sum_{n=-\infty}^{\infty}F_n e^{-ik_n x}$$ where $$F_n=\frac{1}{2L}\int_{-L}^L f(t)e^{ik_n t}dt$$ and $k_n=\frac{\pi n}{L}$. Define $\Delta k$ to be the difference between successive discrete values of $k_n$, then clearly $$\Delta k=\frac{\pi}{n}$$ This allows us to transform an above equation to $$f(x)=\sum_{n=-\infty}^{\infty}F_n e^{-inx\Delta k}$$ where $$F_n=\frac{\Delta k}{2\pi}\int_{-L}^L f(t)e^{ik_nt}dt$$

We are trying to get an integral from this. So, define
$$F_n e^{-inx\Delta k}=\phi(k_n,x)\Delta k$$

Then $$\phi(k_n,x)=\frac{e^{-ik_nx}}{2\pi}\int_{-L}^L f(t)e^{ik_nt}dt$$ and $$f(x)=\sum_{n=-\infty}^{\infty}\phi(k_n,x)\Delta k$$

Now we can let $L\to\infty$, meaning $\Delta k\to0$, and get the [[Riemann Integral|Riemann Integral]] $$f(x)=\int_{-L}^L\psi(k,x)dk$$ where $$\phi(k,x)=\frac{e^{-ikx}}{2\pi}\int_{-L}^L f(t)e^{ikt}dt$$

We now introduce the notation $$F(k)=\frac{1}{2\pi}\int_{-\infty}^{\infty}f(x)e^{ikx}dx$$ and since $F(k)e^{-ikx}=\psi(k,x)$, we also have the accompanying $$f(x)=\int_{-\infty}^{\infty}F(k)e^{-ikx}dk$$

In these formulae, we call $F$ the **Fourier Integral** of $f$ and $f$ the **Inverse Fourier Integral** of $F$.

# Assignment Interlude
## 1.
Find the dispersion of the [[3MP. Some Differential Equations#Klein-Gordon|Klein-Gordon]] equation $u_{tt}-u_{xx}+m^2u-\beta u_{xxxx}=0$.

## 2.
Investigate the differences between the equations
$$ u_{tt}-u_{xx}-u_{xxxx}=0$$
which is the original Boussinseq equation, and
$$ u_{tt}-u_{xx}-u_{xxtt}=0$$
which is a modified version. Seek in terms of dispersion.

Compare the advantages of the forms of the dispersion you get in each.

## 3. 
Find the dispersion of the [[3MP. Some Differential Equations#Shr ouml dinger|Shr&ouml;dinger]] equation, first by substituting the ansatz $e^{i(\omega t-kx)}$ and second by decomposing the PDE variable into real and imaginary parts and solving the resulting system of linear equations. Compare each way.

## ...

## 8.
Consider the nonlinear Shr&ouml;dinger equation $$i\psi_t+\int_{-\infty}^{\infty}J(x-y)\left[\psi(y,t)-\psi(x,t)\right]dy=0$$ where $J(p)=e^{-\alpha|p|},~\alpha>0$.

Show first that the equation can be written as $$i\psi_t+\frac{2}{\alpha}\left(-\frac{\partial^2}{{\partial x}^2}+\alpha^2\right)^{-1}\psi_{xx}=0$$ and then find the dispersion law.

[[Worked Example of 3MP.2. Assignment Question|SOLUTION]]

---

Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1. The Dispersion Relation]]

Next: [[3MP.3. Fourier Transform of PDEs on the line]]