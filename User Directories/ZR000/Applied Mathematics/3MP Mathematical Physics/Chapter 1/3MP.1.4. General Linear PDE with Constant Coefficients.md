Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.3. Fourier Transform of PDEs on the line]]

Next: [[3MP.1.5. The Shr&ouml;dinger Equation & Parseval's Identity]]

---
Take a general linear PDE of the form
$$\mathcal{L}(\partial_t,\partial_x)u(x,t)=0$$

Write $$u(x,t)=\int U(k,t)e^{-ikx}dk$$ and apply to both sides the operator $\mathcal{L}$, then $$\mathcal{L}u=0=\mathcal{L(\partial_t,\partial_x)}\int U(k,t)e^{-ikx}dk$$ so $$\int \underbrace{\mathcal{L}(\partial_t,-ik)U(k,t)}_0e^{-ikx}dk$$ Note that the $\partial_x\to-ik$ within $\mathcal{L}$ due to that fact that $U$ is independent of $x$ and so the differentiations fall on the exponential. 

Hence, we have the linear ODE $$\mathcal{L}(\partial_t,-ik)U(k,t)=0$$ and we know that the solutions of linear ODEs are of course exponentials $$U(k,t)=F(k)e^{i\omega t}$$

The ODE is then $$\mathcal{L}(i\omega.-ik)=0$$ which is nothing more than the dispersion relation, and mostly solveable for $\omega_n(k)$.

Substituting the form for $U(k,t)$ we now have, we can rewrite $u(x,t)$ as
$$u(x,t)=\int F(k)e^{i(\omega t-kx)}dk$$
so while $\omega$ is a root of the dispersion relation, the above form is still as general, just not in different terms. 

If we were now to stipulate an IC $u(x,0)=f(x)$, then
$$f(x)=\int F(k)e^{-ikx}dk$$ so $F(k)$ is the fourier integral of $f(x)$.

We might find we have a total of $N$ dispersion branches. In this case, as is usual with linear DEs, the most general solution is any linear combination of the linearly independent solutions, and thus we would write
$$u(x,t)=\sum_{n=1}^N\int F_n(k)e^{i(\omega_n(k) t-kx)}dk$$

# Worked Example: Shr&ouml;dinger (31)
...
# Worked Example: D'Alembert and his Formula (35)
...
---
Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.3. Fourier Transform of PDEs on the line]]

Next: [[3MP.1.5. The Shr&ouml;dinger Equation & Parseval's Identity]]