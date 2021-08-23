# Infinite Sequence Convergence
Let $(X,d)$ be some metric space, $(x_n)$ a sequence in $X$ and $x\in X$. We say that the sequence $(x_n)$ converges to $x$ if 
$$\lim_{n\to\infty}d(x_n,x)=0~~\Leftrightarrow~~\forall\varepsilon>0,~\exists n_\varepsilon\in\mathbb{N}:~~n\geq n_\varepsilon~\Rightarrow~d(x,x_n)<\varepsilon$$
$$\Leftrightarrow~~\forall\varepsilon>0,~\exists n_\varepsilon\in\mathbb{N}:~~n\geq n_\varepsilon~\Rightarrow~x_n\in B(x,\varepsilon)$$

# Coordinatewise Convergence
Consider two vectors $\vec{x}=(x_1,x_2,\ldots,x_m)$ and $\vec{x}_n=(x_{n1},x_{n2},\ldots,x_{nm})$. Then we say
$$\vec{x}_n\to\vec{x}~~\Leftrightarrow~~\forall k=\{1,2,\ldots,m\},~x_{nk}\to x_k$$

