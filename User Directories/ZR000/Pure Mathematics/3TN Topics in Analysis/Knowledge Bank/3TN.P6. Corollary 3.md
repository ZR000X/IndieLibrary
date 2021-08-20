Index: [[Index for 3TN Topics in Analysis]]

Return: [[3TN.1. Sequences]]

See: [[3TN.P5. Proposition 3]]

We now look at the case where $f$ is decreasing.

Consider the recurrent sequence defined by
$$\begin{matrix}
x_0=a\\ 
x_{n+1}=f(x_n) & \forall n\in\mathbb{N}
\end{matrix}$$
and assume that $f$ is a decreasing function. Then
* If $x_0\leq x_2$, then $(x_{2n})$ is increasing and $(x_{2n+1})$ is decreasing.
* If $x_0\geq x_2$, then $(x_{2n})$ is decreasing and $(x_{2n+1})$ is increasing.

PROOF: If we set $y_n=x_{2n}$ and $z_n=x_{2n+1}$ then $$y_{n+1}=x_{2n+2}=f^{(2)}(x_{2n})=f^{(2)}(y_n)$$ $$z_{n+1}=x_{2n+3}=f^{(2)}(x_{2n+1})=f^{(2)}(z_n)$$

So, both $(y_n)$ and $(z_n)$ are recurrent sequences defined by the function $g=f^{(2)}=f\circ f$. 