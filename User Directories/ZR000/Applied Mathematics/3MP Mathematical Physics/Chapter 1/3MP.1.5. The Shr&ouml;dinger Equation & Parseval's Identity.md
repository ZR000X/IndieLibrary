Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.4. General Linear PDE with Constant Coefficients]]

Next: [[3MP.6.]]

---
In order to demonstrate, take the Shr&ouml;dinger equation
$$i\psi_t+\psi_xx=0$$
and use it to find the local conservation law (check [[3MP.1.5. Workings of Conservation Laws#1|this]])
$$\frac{\partial}{\partial t}|\psi|^2=i\frac{\partial}{\partial x}(\psi^*\psi_x-\psi_x^*\psi)$$

Integrating on both sides,
$$\frac{dN}{dt}=i(\psi^*\psi_x-\psi_x^*\psi)|_{-\infty}^{\infty}$$
where $$N(t)=\int |\psi(x,t)|^2dx$$

The quantity $dN/dt$ is conserved, as it is independent of time. Using [[3MP. Parseval's Identity|Parseval's identity]], we obtain
 $$N=2\pi\int |\Psi|^2dk$$
 where $\Psi$ is the Fourier integral of $\psi$.
 
 There are other conserved quantities, such as [[3MP.1.5. Workings of Conservation Laws#2|this]] and [[3MP.1.5. Workings of Conservation Laws#3|this]]. Due to these two, and using similar techniques, we arrive at two other conserved quantities
 $$E=2\pi\int k^2|\Psi|^2dk$$
 $$P=2\pi \int k|\Psi|^2 dk$$
 
 We leave as exercise the reverse-engineering and working out of the fact that these two quantities are conserved within [[3MP. Some Differential Equations#Shr&ouml;dinger|Shrodinger]], similarly to how we did for $N$. But there is a simpler way. Solving Shr&ouml;dinger gives us
 $$\Psi(k,t)=F(k)e^{-ik^2t}$$
 and so $$|\Psi|=|F(k)|$$ 
 
 Hence, $|\Psi|$ is independent of $t$!

---

Index: [[Index for 3MP Mathematical Physics]]

Prev: [[3MP.1.4. General Linear PDE with Constant Coefficients]]

Next: [[3MP.6.]]