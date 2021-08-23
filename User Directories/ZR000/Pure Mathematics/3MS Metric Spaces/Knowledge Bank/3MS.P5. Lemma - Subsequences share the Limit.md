In any metric space $(X,d)$, any sequence $(x_n)$ in $X$ which converges to $x$ under $d$ also has all of its subsequences converge to $x$.

PROOF: Let the subsequence of $(x_n)$ be $(y_n)$. By definition of subsequences, there exists a strictly increasing sequence of natural numbers $(n_k)$ such that $$y_n=x_{n_k}$$

Thus, by showing the definition of convergence for the fact that $$\lim_{n\to\infty}x_n=x~~\Leftrightarrow~~\forall \varepsilon>0,~\exists n_\varepsilon:~~n\geq n_\varepsilon~\Rightarrow~d(x_n,x)<\varepsilon$$
and combining this with $$\forall n,~\exists k:~~k\leq n_k,~x_{n_k}=y_n$$
means
$$\forall \varepsilon>0,~\exists n_\varepsilon:~~k\geq n_{\varepsilon}~\Rightarrow~n_k\geq n_\varepsilon ~\Rightarrow~d(x_{n_k},x)=d(y_n,x)<\varepsilon$$
$$\therefore \lim_{n\to\infty}y_n=x$$

QED.